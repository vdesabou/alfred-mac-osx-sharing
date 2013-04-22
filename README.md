alfred-mountain-lion-builtin-sharing
==========================

This is "Spotify Mini Player", like the alfred built-in iTunes Mini Player, but for Spotify!

## Description

Use built-in sharing introduced in Mac OS X 10.8 Mountain Lion directly from Alfred!
 
This workflow is using the amazing command line [*terminal-share*](https://github.com/mattt/terminal-share)
 
You can call directly *share* command (or use a hotkey) if you just want to share a message.
If you want to share a file (image, video or any other kind), you can select it using a File Action, or set a hotkey.
 
It currently supports all services except sinaweibo,youku and tudou (I can add them in a future release).
 
Based on the type of the selected file, services proposed will change.
 
Here are some examples:


## Screenshots

![Screenshot](http://i48.tinypic.com/4tab60.png)


## Download the workflow

Download the workflow below and open in Alfred.

[Download Workflow](https://raw.github.com/vdesabou/alfred-mountain-lion-builtin-sharing/master/MountainLionBuilt-inSharing.alfredworkflow)


## History

1.11:

* Move to [GitHub](https://github.com/vdesabou/alfred-mountain-lion-builtin-sharing)

1.10:

* fix AllayOop version

1.9:

* Added hotkeys to call built-in facebook, twitter, imessage and email

![Screenshot](http://d.pr/i/i0SR+.png)

1.8:

* Fix problem introduced in version 1.7 with files names with spaces

1.7:

* Fixed a bug where image was not displayed in the sharing window

1.6:

* Start Droplr if needed before trying to upload

1.5:

* Added support of droplr (using cmd modifier). It will upload selected file to Droplr, and then paste at the end of the message the url. It only works with facebook, twitter, imessage and email (other services don't use message).

1.4:

* Improve handling of special characters

1.3:

* The terminal-share is now included is the workflow
* Twitter issue is fixed
* Minor fixes

1.2:

* Added abilitity to cancel file sharing by selecting the Selected file entry

1.1:

* Support of Alleyoop

1.0:

* Initial Version

## Credits

* [*terminal-share*](https://github.com/mattt/terminal-share)
