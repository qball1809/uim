# ![Logo](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Logos/WebTools-48x48.png) Find Media

Upon entering the FindMedia tool module you will be presented with a similar view to that shown below. All of your Plex libraries will be displayed and you can choose any library to scan for missing media or unmatched media.

![](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/FindMedia/FM-image01.png)

## The Results

![](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/FindMedia/FM-image03.png)

After clicking on a library name, FindMedia will scan the Plex database and your associated media folder for any missing media in this library and for any files in your library that have not been matched by Plex.

With any luck, FindMedia will not find anything missing, but if it does, it will display the results in a similar manner to what is shown above, and you also have an option to download the result as a text file.

You may then go to your media folders and if the file is present, the most likely cause of the file not being found is file or ownership permissions. Correct the permissions, scan your library in Plex and hopefully all will be well.
Or it could be caused by not naming your media according to the [guide](https://support.plex.tv/hc/en-us/categories/200028098-Media-Preparation)

Similarly, files that have not been matched within Plex are also caused by incorrect file naming and/or file permissions. However, your network conditions and those at the various databases and too many requests (from everyone) may sometimes see limits imposed by the databases and that may also play a part in non-matched files in your Plex library. 

If any of the above does not help to correct the problem, then visit the [Plex Forums](https://forums.plex.tv/).

## The Settings 

Clicking on the Show Settings button on the right of screen will display the following panel:

![](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/FindMedia/FM-image02.png)

**The available settings include:**

1. Ignore Hidden. This will ignore any hidden folders found in your media folder.
2. Ignore Extras. This will ignore any '[extras](https://support.plex.tv/hc/en-us/articles/200220677-Local-Media-Assets-Movies)' that may be included in your media folder.
3. Ignore Folders. This will ignore any system or other folders within your media folder.

**Add or remove ignored folders:**

To remove an ignored folder, click on the `-` button to the left of the named folder.

To add an ignored folder, click on the `+` button below the list of ignored folders and then type in the name of the folder you wish to ignore in the appropriate text box.

**Valid Extensions:**

In the Valid Extensions text box you may add or remove extensions that FindMedia will search for. You should only use extensions that are recognised by your Plex Media Server.

**Reset Settings** will reset the FindMedia settings to the default settings that come with WebTools for the FindMedia tool module.

**Save settings** will of course save your current settings.

***

[[Home|Home]] | [[Back|UAS]] | [[Next|Playlists]]