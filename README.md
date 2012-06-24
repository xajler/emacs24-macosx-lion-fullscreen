## Emacs 24.1.50 (9.0) for Mac OS X Lion and Mountain Lion
* Implemented ns-toggle-fullscreen patch. (Better for those with  multiple monitors, no empty gray area on non-main monitors).
* Implemented my Mission Control fullscreen patch. (Better for those with one monitor to swipe out through full screen apps).

## For Mac OS X Lion
* [Download it](https://github.com/downloads/xajler/emacs24-macosx-lion-fullscreen/emacs24.1.5-fullscreen-Lion.tar.bz2).
* Untar it and copy/move to Applications folder.

## For Mac OS X Mountain Lion
* [Download it](https://github.com/downloads/xajler/emacs24-macosx-lion-fullscreen/emacs24.1.5-fullscreen-ML.tar.bz2).
* Untar it and copy/move to Applications folder.
* It (Gatekeeper) will complain that is from unidentified developer
  * Go to "System Preferences" -> "Security & Privacy" -> General.
  * "Click lock to make changes" fill the password.
  * Click "Anywhere" in "Allow applications downloaded from:"

Both binaries compiled with this configurations:
> ./configure --without-dbus --with-ns --disable-ns-self-contained

Screenshots:
*Emacs 24 on Mac OS X Mountain Lion:*

![](https://github.com/xajler/emacs24-macosx-lion-fullscreen/raw/master/screenshots/emacs24-MountainLion.png)

*Emacs 24 in Mac OS X Mountain Lion Mission Control Full Screen:*

![](https://github.com/xajler/emacs24-macosx-lion-fullscreen/raw/master/screenshots/emacs24-MountainLion-MissionControl-Fullscreen.png)

*Emacs 24 in Mac OS X Mountain Lion Mission Control as item:*

![](https://github.com/xajler/emacs24-macosx-lion-fullscreen/raw/master/screenshots/emacs24-MissionControl-item.png)

*Emacs 24 M-x ns-toggle-fullscreen:*

![](https://github.com/xajler/emacs24-macosx-lion-fullscreen/raw/master/screenshots/emacs24-mx-ns-toggle-fullscreen.png)

*Emacs 24 ns-toggle-fullscreen in action:*

![](https://github.com/xajler/emacs24-macosx-lion-fullscreen/raw/master/screenshots/emacs24-ns-toggle-fullscreen.png)

*Emacs 24 ns-toggle-fullscreen in Mission Control as Desktop item:*

![](https://github.com/xajler/emacs24-macosx-lion-fullscreen/raw/master/screenshots/emacs24-ns-toggle-fullscrein-NoItemInMissionControl.png)
