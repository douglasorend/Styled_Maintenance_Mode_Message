-------

# STYLED MAINTENANCE MODE MESSAGE v1.4

[**By Dougiefresh**](http://www.simplemachines.org/community/index.php?action=profile;u=253913) -> [Link to Mod](http://custom.simplemachines.org/mods/index.php?mod=3952)

-------

## Introduction
SMF has **TWO** maintenance modes, as defined in **Settings.php** by the variable **$maintenance** in your forum folder.  Setting this variable to **1** allows the adminstrators access to perform any necessary actions that don't require taking the database offline.  Setting this variable to **2** (hardcore maintenance mode) makes the forum itself unaccessable for **EVERYBODY**.  Not even adminstrators can log into the forum.

## What This Mod Changes
When any Simple Machines forum is in maintenance mode (where *$maintenance* in **Settings.php** is set to 2), there is absolutely no CSS style to make the maintenance message look consistent with the rest of the site.  This mod attempts to resolves this issue, using the default theme CSS, to style the maintenance mode message shown to the user.  

[Arantor](https://www.simplemachines.org/community/index.php?action=profile;u=318771) stated in [this post](https://www.simplemachines.org/community/index.php?topic=528839.msg3755027#msg3755027):
[quote]
There are two levels of maintenance mode. General maintenance mode - which shows the theme like it should, and hardcore maintenance mode, which shows a basic page.

Considering that the ONLY time the white screen should be applicable is during upgrades - in which state even the default theme is by definition in flux and not necessarily reliable to be used
[/quote]
(Yes, there are several more lines in the post which are omitted!)

## Restrictions
Since theme support has not been loaded as of this point, other themes cannot be selected within the UI at this point.  This may change in future versions, but I doubt it.

## Admin Settings
There are none.  You must uninstall this mod to remove it.

## Compatibility Notes
This mod was tested on SMF 2.0.9, but should work on SMF 2.1 Beta 1, as well as SMF 2.0 and up.  SMF 1.x is not and will not be supported.

## Changelog
The changelog can be viewed at [XPtsp.com](http://www.xptsp.com/board/free-modifications/styled-maintenance-mode-message/?tab=1).

## License
Copyright (c) 2015 - 2018, Douglas Orend

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.