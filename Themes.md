# ![Logo](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Logos/WebTools-48x48.png) Theme

Clicking on the Theme menu button will present you with a number of buttons. Each button represents a set, or theme, of colours to be used by WebTools.

By default there are a number of pre-defined Themes for you to choose from.

However, if you wish to create your own custom theme you may start by copying an existing theme file in the `/WebTools.bundle/http/custom_themes` folder and rename the file to mycustomtheme.css or any descriptive name you desire. You must ensure that the file extension, .css remains.

Once you have done that, you may open the file in a text editor and proceed to change the colour definitions for the various elements.

Note: you should be careful not to alter the format of the file in any other way. You are only allowed to edit the rgba color values (255,255,255,1).

Example:  
body {
    background-color: rgba(0, 0, 0, 1);
    color: rgba(255, 255, 255, 1);
}

The colours are defined by the 3 decimal numbers which represent the Red, Green and Blue values followed by the alpha or opacity value. The alpha value controls how much transparency the colour will have on the page. An alpha value of 1 = solid and a fractional value of 0.01 will be almost invisible.

In the line above, the background colour is set to a Red, Green, Blue value of (0,0,0,1) which is black in colour and is solid (not transparent at all).

The text colour is set to (255,255,255,1) which is white in colour and is also solid (not transparent at all). By adjusting the alpha value (1) you can change the original white colour to appear more grey as it lets the black background colour show through, the lower the alpha number is, the more black that will show through.

By changing the number values, you are able to change the various elements to any colour you desire and set it's transparency or opacity to any level.

Note: when editing your custom style sheet, you should refresh your browser page often, otherwise, you may not see the changes you have made to your custom style sheet/theme. Also, if you use an RGB value and forget to add the alpha value, then browsers such as Chrome and Edge will not show your changes as the value will be invalid.

Also note that the css value uses the American spelling for 'color' and not the English spelling which is 'colour'.

To give you some idea of the colours to use and to find their respective colour number values, then visit this page: http://www.w3schools.com/colors/colors_picker.asp

***

[[Home|Home]] | [[Back|About Us]] | [[Next|Change-Log]]