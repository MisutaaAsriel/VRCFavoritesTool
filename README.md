# VRCFavoritesTool
## Based on the [Community-Driven VRChat API Docs](https://vrchatapi.github.io/)
A simple utility for reading your favorites list from VRChat to a JSON file.

### Why would I need this?
Avatar worlds, more or less. This gives a graphical way of exploring your favorites, and lets you export selected avatars to a JSON file on disk, which contains the name, creator, ID, & thumbnail URL, with which to create a pedestal.

### Could this be used for theft?
Not to my knowledge. Private avatars don't show up on pedestals in my experience, so anything you could use this for is public already. You're also not sharing the avatar or accessing its data at all — You just get the information necessary to add a pedestal for it to your own world.

### Why can't I chose where the file is saved?
Why can't Unity support file dialogs? *Who knows?*

### How do I log out?
You'll have to delete its preferences file. Not sure where its stored at the moment. I tried writing a log-out function but it was having a bit of issue. Don't worry, cookies expire, so you should get logged out within a couple weeks.

### How do I run this on Mac?
If you are getting a security error due to the package being unsigned/unnotarized, right click the program, hold down shift, and click open. It should give you the option to run the program now in the dialog that appears.

Apple prevents unsigned and unofficially signed code from running, to slow the spread of malware and ensure all software has been validated by them. This doesn't mean that all software like this is malicious, just that it's meant to protect the weakest of users, who are more than willing to run software they know they shouldn't. However, if there is a need to run this software, for more experienced users, Apple has left a shortcut in the operating system which enables you to run applications on a case by case basis.

This also beats disabling SIP. *lmao, why do so many people say to do that?*

### It isn't working!
Open an issue, I guess? Idunno, the API is unofficial and Unity makes some things harder than it should be.
