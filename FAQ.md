# ![Logo](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Logos/WebTools-48x48.png) Frequently Asked Questions

**Note:** This page is constantly updated, and is based on the feedback from the [Plex Forums support thread:](https://forums.plex.tv/discussion/288191)

## FAQ (Frequently Asked Questions):

<a name="Q1"></a>
* Q1: I manually installed Webtools, but when PMS is restarted, the WebTools.bundle directory is removed?
  * Most likely, you also installed WebTools under the `Resource/Plug-ins-XXXX`directory as well. You must delete it from that location, and then manually reinstall WebTools in the [`Library/Plug-Ins`](https://support.plex.tv/hc/en-us/articles/201106098) directory
<a name="Q2"></a>
* Q2: When I browse to `http://IP_OF_PMS:33400` nothing happens
  * Make sure that you opened your PMS server's firewall to port 33400 and 33443
<a name="Q3"></a>
* Q3: WebTools is not working, and you asked me for the WebTools logs. Where are they located
  * Make a zip file of the [entire logs](https://support.plex.tv/hc/en-us/articles/200250417-Plex-Media-Server-Log-Files) directory, including sub-directories, and **do not** use the PMS built in "Download logs" functionality
<a name="Q4"></a>
* Q4: When I click on the link in the Channels View, nothing happens
  * You should not click on it, type the URL in to your browser
<a name="Q5"></a>
* Q5: I see untranslated strings for my language, but when clicking on the Language tab, it does say 100% for my language
  * Most likely, the translation was done after the version of WebTools was released. Simply click on the button named [["Force Language Translation Update"|Language]]
<a name="Q6"></a>
* Q6: I deleted an agent based subtitles, but within minutes, it shows again
  * Most likely, your agent is still enabled, and when we delete the sub, PMS will trigger a refresh, causing the agent to redownload it
<a name="Q7"></a>
* Q7: Why doesn't the UAS automatically check for updates to the bundles I've installed?
  * When the original UAS was created, it did do that.
  * However, due to it's popularity, the impact on GitHub was huge, since every PMS running UAS, would check once every 24 hours.
  * As such, GitHub was forced to shutdown the old UAS :(
  * So to protect both GitHub, as well as the new UAS from been banned, it now requires the user of WebTools to press the button.
<a name="Q8"></a>
* Q8: When using Google as Authenticator towards Plex, WebTools fails to logon
  * To fix this, set password under [my account in Plex's user profile](https://app.plex.tv/desktop#!/account)
    * Thanks goes towards [Asafb26](https://github.com/Asafb26) for this

***

[[Home|Home]] | [[Back|Known Issues]] | [[Next|Credits]]