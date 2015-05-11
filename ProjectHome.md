**Important Notice:**
Since Google Code announced to stop creating new downloads starting January 15th, 2014, I decided to entirely move this project to Microsoft's CodePlex server. Hence any further progress in developping "MioPocket Mini 4.0 FV" - especially all its revisions / patches - you now will find [HERE](https://miopocketmini40fv.codeplex.com). Sorry for your inconvenience.



|Abstract:|
|:--------|

This modification of [MioPocket Mini 4.0](http://www.gpspassion.com/forumsen/topic.asp?TOPIC_ID=137719) is designed to be used on lower-memory GPS SatNav devices: it decreases noticeably usage of RAM and/or Video-RAM. Due to fact applications and their icon are thematically arranged in folders, not dozens of icons have to be loaded at once and kept in RAM and/or Video-RAM, but only a handfull per folder-page. "MioPocket Mini 4.0 FV" only consumes ~ 250KB RAM (plus RAM used by the applications launched from within "MioPocket Mini 4.0 FV"). "MioPocket Mini 4.0 FV" only adds the follwing functions: Music Play, Video Play, Game, Flash,  Alarm, Notepad, Dictionary, Scheduler, Calculator, Photo Album, E-book, Volume Setting, Date & Time, etc. Note that "MioPocket Mini 4.0 FV" does not provide a so-called dual zone functionality (listening to the radio/cd while GPS works). If such feature is wanted/needed, one must extend the navigation software by an extra button by him/herself.
"MioPocket Mini 4.0 FV" is Windows Embedded CE 6.0 ready. Also it's prepared to run well in Device Emulator.


Two skins are available: MetroUI Style and iOS7 Style (both are modern, clean, light and open design with no shadows, glows or gradients)

|Screenshots:|
|:-----------|

http://www.gpspassion.com/upload2/MioPocket-Mini-4.0-Folder-Version-Demo-Screen.PNG

( For all who are turned backwards: iPhone4 Style icons are provided, too. )




|Video|
|:----|


|Modifications Log:|
|:-----------------|

1. "MioPocket Mini 4.0 FV" no longer is startet via HKLM\init\Launch9999 thus device's registry is left untouched so far


2. Removed all programs that definitly don't work under CE 6.0


3. Removed all programs that require Microsoft .NET CF


4. Removed a lot of other programs too; my goal hereby was "reduce to optimum"


5. Added freeware navigation software mapFactor's NavigatorFree (only Andorra map included)


6. All .INI files created/used now in UTF8 format instead of ANSI


7. Some hard-coded values moved from scripts to MioPocket.ini thus they can be changed many more simply


8. Added Microsoft's FakeGPS thus if run in Device Emulator navigation software starts (requires .NET CF 2.0 or higher included in CE image used)


Remark: All files modified/added contain in file header "This file is part of MioPocket Mini 4.0 Folder Version" notice


|Layout:|
|:------|

http://www.gpspassion.com/upload2/MioPocket-Mini-4.0-FV-Layout.PNG


|Legal Notice:|
|:------------|

Not only "MioPocket Mini 4.0 FV" is free software, but - unless otherwise indicated - also the softwares bundled with "MioPocket Mini 4.0 FV" are free softwares that are owned by various copyright holders and released under various free software licenses.


|Credits:|
|:-------|

[tito12](http://forum.xda-developers.com/showpost.php?p=10953917&postcount=2686)  [Osprey et.al.](http://www.gpspassion.com/forumsen/topic.asp?TOPIC_ID=137719)
[dAKirby309](http://dakirby309.deviantart.com/art/Metro-UI-Icon-Set-725-Icons-280724102)


|Disclaimer:|
|:----------|

Current state of "MioPocket Mini 4.0 FV" is 'AS IS Version' only. I haven't had the time to bring it to a stable end. It may contain bugs here and there, so be gentle. Post everything and anything you find broken (I don't expect much to be). And as always: While every care has been taken to ensure that "MioPocket Mini 4.0 FV" is safe, non-destructive and will not brick the device, you use "MioPocket Mini 4.0 FV" entirely at your own risk. I will not be held responsible or liable for any damages resulting from your use, misuse, or inability to use this product.

If you do not agree with this disclaimer, you should not use "MioPocket Mini 4.0 FV".


|Installation:|
|:------------|

_"MioPocket Mini 4.0 FV" should be used only on (portable) GPS navigation devices running Windows CE and having a touch screen. Do NOT install it on All-in-one devices._

1. If any previous version of "MioPocket Mini 4.0" installed, uninstall it

2. Download and unpack "MioPocket Mini 4.0 FV" to your desktop PC

3. Copy contents of folder "Copy To Root Of SD-Card" (not this folder itself)  to root of your mobile device's SD-card

4. Install "MioPocket Mini 4.0 FV" to your mobile device as instructed to do with [MioPocket Mini 4.0 Rel.2  ReadMe](http://www.gpspassion.com/forumsen/topic.asp?TOPIC_ID=137719)