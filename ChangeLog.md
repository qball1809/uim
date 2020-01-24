# ![Logo](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Logos/WebTools-48x48.png) This is the changelog for WebTools

## Versions:

* [V3.0.0](ChangeLog#v300)   (2017-12-10)
* [V2.4.1](ChangeLog#v241)   (2017-02-19)
* [V2.4](ChangeLog#v24)   (2017-02-14)
* [V2.3](ChangeLog#v23)   (2016-10-23)
* [V2.2](ChangeLog#v22)   (2016-04-25)
* [V2.1](ChangeLog#v21)   (2016-01-14)
* [V2.0](ChangeLog#v20)   (2016-01-14)
* [V1.1](ChangeLog#v11)   (2016-10-25)
* [V1.0](ChangeLog#v10)   (2016-10-11)
* [V0.0.0.18](ChangeLog#v00018)
* [V0.0.0.17](ChangeLog#v00017)
* [V0.0.0.16](ChangeLog#v00016)
* [V0.0.0.15](ChangeLog#v00015)
* [V0.0.0.14](ChangeLog#v00014)
* [V0.0.0.13](ChangeLog#v00013)
* [V0.0.0.12](ChangeLog#v00012)
* [V0.0.0.11](ChangeLog#v00011)
* [V0.0.0.10](ChangeLog#v00010)
* [V0.0.0.9](ChangeLog#v0009) ...First public release...
* [V0.0.0.8](ChangeLog#v0008)
* [V0.0.0.7](ChangeLog#v0007)
* [V0.0.0.6](ChangeLog#v0006)
* [V0.0.0.5](ChangeLog#v0005)
* [V0.0.0.4](ChangeLog#v0004)
* [V0.0.0.3](ChangeLog#v0003)
* [V0.0.0.2](ChangeLog#v0002)
* [V0.0.0.1](ChangeLog#v0001)


***

### V3.0.0:

* **New**:
  * Brand new backend API V3
  * GUI completely redesigned, using [Angular](https://angular.io/)
  * [Multilingual](https://github.com/ukdtom/WebTools.bundle/wiki/Language)
  * New module to manipulate [Playlists](https://github.com/ukdtom/WebTools.bundle/wiki/Playlists)
  * New module to show [Technical Information](https://github.com/ukdtom/WebTools.bundle/wiki/TechInfo)
  * Support for [BaseURL](https://github.com/ukdtom/WebTools.bundle/wiki/Configure) (Proxy)
  * Support for [custom certificates](https://github.com/ukdtom/WebTools.bundle/wiki/Configure)
  * [FindMedia](https://github.com/ukdtom/WebTools.bundle/wiki/FindMedia) can now detect, if a media is missing MetaData
  * Lots of [fixes](https://github.com/ukdtom/WebTools.bundle/issues?utf8=%E2%9C%93&q=is%3Aissue%20milestone%3AV3.0.0%20) 

[Jump to top of page](ChangeLog#top)

### V2.4.1:

* **Fix**:
  * [#264](https://github.com/ukdtom/WebTools.bundle/issues/264) UAS: v2.4 of WebTools UnsupportedAppStore Error
  * [#265](https://github.com/ukdtom/WebTools.bundle/issues/265) SUB: No paging by letter, for TV-Shows

[Jump to top of page](ChangeLog#top)

### V2.4:

* **Fix**:
  * [#166](../issues/166) WT: Themes - v2.2 release - Default theme error
  * [#197](../issues/197) SUB: Error while deleting any subtitle (Sub-Zero, and file stored within metadata)
  * [#202](../issues/202) WT: Added word-wrap to dialogbox
  * [#203](../issues/203) UAS: Non UAS 2 UAS
  * [#209](../issues/209) WT: WT Autoupdate broke
  * [#212](../issues/212) WT: Problems with browser caching
  * [#213](../issues/213) WT: Need a Misc function to Unicodize a filepath
  * [#214](../issues/214) UAS: Channel Update from manual app installer broken
  * [#215](../issues/215) WT: Fixed removal of "Library" menu when leaving module
  * [#216](../issues/216) WT: WebTools and ports used
  * [#218](../issues/218) FM: Extradirs
  * [#219](../issues/219) WT: Improve detection of bad installation path
  * [#221](../issues/221) WT: Fixed sorting
  * [#227](../issues/227) FM: FindMedia failing
  * [#232](../issues/232) WT: New line in VERSION on git pull
  * [#233](../issues/233) WT: Hardcoded strings to const/var
  * [#235](../issues/235) FM: FM Module and Extra dirs
  * [#237](../issues/237) FM: FM and initialize defaults
  * [#239](../issues/239) WT: http/credits.txt
  * [#240](../issues/240) UAS: UAS main screen
  * [#241](../issues/241) WT: Update Wiki Page
  * [#243](../issues/243) SUB: Module navigator broken
  * [#244](../issues/244) WT: Editing the update window
  * [#245](../issues/245) SUB: Subs identified as Sidecar, when agent based
  * [#248](../issues/248) WT: Debug mode force uas repo to test branch
* **New**:
  * [#168](../issues/168) WT: Error message
  * [#171](../issues/171) SUB: Add search function to SUB module for movies
  * [#174](../issues/174) WT: Notifies if there is a new version upon logon
  * [#177](../issues/177) UAS: Added force update of repo button/functionality
  * [#181](../issues/181) SUB: Add a download button for sidecar subtitles
  * [#205](../issues/205) SUB: Add an option to shorten the list to only items with 'unfiltered' subtitles
  * [#206](../issues/206) WT: Add setting of locale to the log
  * [#230](../issues/230) UAS: Add ability to search plugins
  * [#231](../issues/231) UAS: Add possibility to show a msg when a plugin is installed
  * [#234](../issues/234) UAS: New key to UAS json
  * [#238](../issues/238) FM: FM and Extras

[Jump to top of page](ChangeLog#top)

### V2.3:

* **Fix**:
  * [#110](../issues/110) UAS: Allow it to fetch from release info as well
  * [#134](../issues/134) UAS: Wrong time for Latest Update on Github
  * [#165](../issues/165) LOGS: Fixed issue with spaces in filenames
  * [#166](../issues/166) UAS: Removed highlight of All after selecting category
  * [#172](../issues/172) WT: Fixed issue with Factory reset
  * [#176](../issues/176) UAS: Critical error in updateInstallDict
  * [#178](../issues/178) WT: Fixed issue with intruder detection
  * [#184](../issues/184) WT: Logging can fail on Mac OS
  * [#187](../issues/187) UAS: Fix for correct sorting. Now sorts alphabetical without concerning about capital/lower case letters
  * [#188](../issues/188) UAS: New way with consts and debug broken on Windows
  * [#189](../issues/189) WT: Fix for startup issue if on Windows and lang is set to CP1251
  * [#190](../issues/190) LOGS: Fix for issue with cyrilian characters, when not running UTF-8
  * [#197](../issues/197) SUB: Error while deleting any subtitle (Sub-Zero, and file stored within metadata)
* **New**:
  * [#170](../issues/170) WT: Added a user guide from Trumpy81. URL is /manual/WebTools-User-Manual.pdf
  * [#171](../issues/171) PMS: Added Search to the backend
  * [#175](../issues/175) PMS: Autodownload Repo if json is missing
  * [#185](../issues/185) WT: Enhance developer/debug mode
  * [#191](../issues/191) WT: Version numbering moved to VERSION file in the root of the bundle
  * [#204](../issues/204) FM: New Modul: FindMedia

[Jump to top of page](ChangeLog#top)

### V2.2:

* **Fix**:
  * [#115](../issues/115) UAS: Migration fails, if plugin directory contains hidden folder
  * [#116](../issues/116) UAS: Make UAS work, even if a git is dir levels too low
  * [#117](../issues/117) UAS: Uninstall unknown bundle
  * [#121](../issues/121) UAS: Cleanup old files/folders when updating
  * [#122](../issues/122) UAS: bundle migration
  * [#131](../issues/131) UAS: After changing category, focus is no longer set on inputbox
  * [#138](../issues/138) UAS: getAllBundleInfo is reset when UASRepo is updated
  * [#139](../issues/139) UAS: Unknown bundles without url won't be able to be uninstalled or re-installed
  * [#140](../issues/140) UAS: Migrate now always goes back to showing ALL available bundles
  * [#145](../issues/145) SUB: Fixed display of undefined when deleting sidecars
  * [#159](../issues/159) LOGS: Fix for incorrect highlights when searching for "Warn"
  * [#161](../issues/161) THEMES: Partial fix, now retains correct coloring
  * [#161](../issues/161) THEMES: Request for element isolation
  * [---] SUB: Added more logging for uploads
* **New**:
  * [#93](../issues/93) WT: Now has support for custom themes! First out is a draft of @trumpy81 that needs to be finetuned by trumpy81
  * [#112](../issues/112) SUBS: Allow delete/view of subs
  * [#126](../issues/126) UAS: Allow WebTools to autoupdate
  * [#129](../issues/129) UAS: Allow 3.Party devs to clear their stuff
  * [#133](../issues/133) SUBS: Added GUI for uploading subtitles
  * [#135](../issues/135) WT: Tell users, if wrong install path is used
  * [#137](../issues/137) WT: Add new decorator for auth
  * [#142](../issues/142) LOGS: Search for keywords, highlighting of the same. Jump to top
  * [#149](../issues/149) SUBS: Implemented letters instead of straight up numbers for paging
  * [#160](../issues/160) WT: Implemented Factory Reset functionality. Available through the Options menu
  * [---] WT: Added a language module for devs
  * [---] WT: Added a reset function, that will reset to factory settings
  * [---] SUBS: Now uses the new Language Module
  * [---] WT: Removed LogFiles from top menu, redirecting users to LogViewer instead
		
[Jump to top of page](ChangeLog#top)

### V2.1:

Sadly lost info about what changed in that version

[Jump to top of page](ChangeLog#top)

### V2.0:

* **New**:
  * [---] UAS: Added UAS module
  * [---] LOGS: Added Logs module
* **Fix**:
  * [---] WT: Speed increase

[Jump to top of page](ChangeLog#top)

### V1.1:

* **Fix**:
  * [---] WT: Fix for languagecodes. Not using flags anymore.

[Jump to top of page](ChangeLog#top)

### V1.0:

* **New**:
  * [---] WT: Release of the brand new interface. It holds a ton of new and refined looks and some under the hood improvements. Completly rewritten.
  * [---] WT: Now use the PMS build-in Tornado WebServer

[Jump to top of page](ChangeLog#top)

### V0.0.0.18:

* **Fix**:
  * [---] WT: Moved Token handling to the end of queries

[Jump to top of page](ChangeLog#top)

### V0.0.0.17:

* **Fix**:
  * [---] WT: Modified Token handling to make sure it's only appended if it's actually there
  * [---] SUBS: Modified loading screens when loading sections and movies
  * [---] SUBS: Corrected an issue with autoselecting duplicates that caused all subtitles to be selected

[Jump to top of page](ChangeLog#top)

### V0.0.0.16:

* **New**:
  * [---] WT: Added Token handling.
* **Fix**:
  * [---] SUBS: Changed viewing of subtitles to be handled by Modal instead
  * [---] LOGS: Changed viewing of logs to be handled by Modal instead
  * [---] WT: Corrected text on welcome page

[Jump to top of page](ChangeLog#top)

### V0.0.0.15:

* **New**:
  * [---] API: Added Token authentication, if needed
  * [---] WT: Added new setting to the settings file, to be used by the http part
  * [---] WT: Added a restart function to the bundle part, to be used by the devs only
* **Fix**:
  * [---] WT: Removed old changelog file from the http part
  * [---] WT: Changed the Windows Symblink file into creating a hardlink instead of a junction
  * [---] WT: Moved creation of symblink, tokens and secret to the validateprefs function from the start function

[Jump to top of page](ChangeLog#top)

### V0.0.0.14:

* **Fix**:
  * [---] SUBS: Corrected viewing of Subtitles. Functioncall was wrong.

[Jump to top of page](ChangeLog#top)

### V0.0.0.13:

* **Fix**:
  * [---] WT: Attempted to fix caching issues.

[Jump to top of page](ChangeLog#top)

### V0.0.0.12:

* **New**:
  * [---] WT: Added icon

[Jump to top of page](ChangeLog#top)

### V0.0.0.11:

* **New**:
  * [---] WT: WT will now warn Windows users, if they forgot to run the cmd file

[Jump to top of page](ChangeLog#top)

### V0.0.0.10:

* **New**:
  * [---] WT: Moved version number to settings.py. Version number is now a shared number between the webpart and the bundle part

[Jump to top of page](ChangeLog#top)

### V0.0.0.9:

**First public release**

* **Fix**:
  * [---] API: Fixed GetXML function
  * [---] API: Made sure that settings set are with forward slash when entered with back-slash
  * [---] API: Fixed auth error.....Again.....SIGH.....

[Jump to top of page](ChangeLog#top)

### V0.0.0.8:

Internal version, never released

* **New**:
  * [---] API: Hopefully fixed auth error

[Jump to top of page](ChangeLog#top)

### V0.0.0.7:

Internal version, never released

* **New**:
  * [---] API: Added randomizer to the secret

[Jump to top of page](ChangeLog#top)

### V0.0.0.6:

Internal version, never released

* **New**:
  * [---] API: Removed PathToLib function. PathToLib variable will now be stamped during startup to settings.js

[Jump to top of page](ChangeLog#top)

### V0.0.0.5:

Internal version, never released

* **New**:
  * [---] API: Added SetPref - Call like http://PMS:32400/utils/webtools?Func=SetPref&Secret=MySecret&Pref=myVar&Value=Value1

[Jump to top of page](ChangeLog#top)

### V0.0.0.4:

Internal version, never released

* **New**:
  * [---] API: Added GetLibPath
  * [---] WT: Switched from putting the prefs in functions.js to settings.js

[Jump to top of page](ChangeLog#top)

### V0.0.0.3:

Internal version, never released

* **New**:
  * [---] API: Added PathExists
  * [---] API: Added ShowSRT
  * [---] API: Added DelSub

[Jump to top of page](ChangeLog#top)

### V0.0.0.2:

Internal version, never released

* **Fix**:
  * [---] WT: Will now update functions.js based on prefs
* **New**:
  * [---] WT: Added channel menu
  * [---] WT: Added prefs

[Jump to top of page](ChangeLog#top)

### V0.0.0.1:

Internal version, never released

* **New**:
  * [---] SUBS: Can now view subtitles via the view link
  * [---] SUBS: Can list movies and seasons
  * [---] SUBS: Can list subtitles
  * [---] SUBS: Can show if subtitle is sidecar or not, and hide check boxes accordingly
  * [---] WT: Can change items-per-page
  * [---] WT: Only refreshes display if sections_contents is not empty
  * [---] WT: Hide local subtitles is now working correctly
  * [---] SUBS: Hide integrated subtitles is now working correctly
  * [---] SUBS: Hide videos without subtitles is now working correctly
  * [---] SUBS: Show only multiple/language works
  * [---] LOGS: Limited display on page to 5 log entries
  * [---] LOGS: Enabled a "View Logs" function that opens a new window, displaying all logs

[Jump to top of page](ChangeLog#top)