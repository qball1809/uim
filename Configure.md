# ![Logo](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Logos/WebTools-48x48.png) Configure WebTools

In order to configure WebTools, open the Plex home page in your Web Browser and then click on Channels [Now named Plugins] (See: * [[Locating WebTools|Locate-WT]]) and locate the WebTools poster. Now move your mouse over the poster until you see the icons as shown below. Click on the Gear icon (shown in the red box).

![](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Configuration/CWT-image01.png)

You will then be presented with the following dialogue:

![](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Configuration/CWT-image02.png)

In the WebTools Settings dialogue you are able to set the port number on which to communicate with WebTools. Normally, you would add this port number to the end of your Plex Media Server's IP Address in your Web Browser, like so:

http://Your-PMS-Server-IP-Address:33400 (or you would use the port number you have configured in the upper text box)

**Note:** Remember to open your PMS servers firewall for the selected ports, if a firewall is present!

If you access your Plex Media Server in a secure environment, you must first 'tick' the 'Select to force https' check box and then enter your desired port number in the text box above. You would then enter your Plex Media Server's IP Address followed by your configured port number in your Web Browser, like so:

https://Your-PMS-Server-IP-Address:33443 (or you would use the port number you have configured in the lower text box)

***

The Base URL text box is used to enter the url required if you are using a proxy server. If you do not use a proxy server, then leave this text box blank.

EG: Your base URL may be something like: `/WebTools`

If using mod_proxy from Apache something like this should do it:

`AllowEncodedSlashes NoDecode`

`ProxyPass /WebTools http://localhost:33400/WebTools nocanon`

`ProxyPassReverse /WebTools http://localhost:33400/WebTools nocanon`

***

If you use custom certificates then the certificate name and the certificate key file names can be entered into the appropriate text boxes.

The certificate and it's key should be stored in the `/Plex Media Server/Plug-ins/WebTools.bundle/Contents/Code/Certificate` folder.

The default certificate name is WebTools.crt and the default key name is WebTools.key.

Please do not overwrite the default certificate files. Instead, rename your custom certificate files and place them into the correct folder alongside the default certificate files.

That will allow you to quickly switch the certificate files should you encounter any problems with your custom certificates.

> **Note:** After any changes to the certificates or the base URL, you may need to stop and then restart your Plex Media Server and please, do not forget to click on 'Save' after making any changes to the settings.

***

[[Home|Home]] | [[Back|Install]] | [[Next|Locate-WT]]