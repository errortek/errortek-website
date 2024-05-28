---
title: UltraTextEdit UWP Plus 24H2's base build now out for Insiders!
description: The build, 26100.1, was released yesterday to all Insider Channels.
thumbnail: /blog-resources/uteuwp-plus-24h2-released/thumbnail.png
date: 2024-05-28
author: jpbandroid
---

Yesterday, I completed UTE UWP Plus build 26100.1 and released it. Nothing very significant, right?


Well, actually, *yes* it **is** significant.


Let me explain to you why...

## The build number
This release is the **base build** of UTE UWP+ 24H2. The base build in this case is simply an initial build that a version of the app is based on. In this case, all later 24H2 builds will be based on 26100.1, and so will the Beta Channel builds 26120.xxxx.
## Why May 27 specifically?
Well, I chose to release all the Insider Previews at once on the same day to not have to make many separate releases afterwards and so that they are all grouped together under one release on the app's GitHub repository.
I originally chose May 24, because then they would be released exactly one month before 26100.1's public release, but that date passed without me compiling any of the builds, so I decided on a new date, May 27.


The actual reason I chose May 27 was just that I preferred the date over later in the month and that the release still had to be in May.


Now with that explained, let's get to the best part, the **FEATURES**!!
## Features
UTE UWP+ 24H2's base build, 26100.1, will be the first ever public stable release of UTE UWP+, so there are tons of new features to explore, with the most notable ones shown and explained below.
### Ribbon
The Ribbon has to be the largest and most impactful feature UTE UWP+ introduced, as well as the ability to switch between it and the existing TabbedCommandBar.
<br>
I created a slightly adjusted version of Ivirius Text Editor Free's Ribbon (thanks to Ivirius for making that ribbon!!), with more rounded corners, and even contributed some features back to the original, such as contextual tab styles.
<br>
Exciting, right?
<br>

<figure class="margin-bottom">
    <img src="/blog-resources/uteuwp-plus-24h2-released/ute-withribbon.png" alt="A screenshot of UltraTextEdit UWP Plus, with the newly introduced Ribbon UI enabled.">
    <figcaption>UTE UWP+ with the Ribbon feature enabled.</figcaption>
</figure>

### New Home Menu
The Home Menu is equally impactful, as it blends a beautiful backgroud with a structured user interface to create a new document using new Document Templates, as well as allowing the user to carry out common file operations, such as saving, opening, or deleting a file (file deletion not available in build 26100.1).
<br>

<figure class="margin-bottom">
    <img src="/blog-resources/uteuwp-plus-24h2-released/ute-homemenu.png" alt="A screenshot of UltraTextEdit UWP Plus, with the Home Menu open.">
    <figcaption>UTE UWP+ with the new Home Menu open.</figcaption>
</figure>

### Accent color customization
Another very impactful feature, especially important for those who value personalization, is the ability to change the accent color of the app to a different one than the accent color of the OS.
<br>
In build 26100.1 (actually, ever since build 26040.1000 😅), you can switch UTE's accent color between the default accent color of the OS, Slate Green, and Lilac.
More colors will be coming soon, as I feel like this is not enough yet, but it's ok for now, I hope!

<figure class="margin-bottom">
    <img src="/blog-resources/uteuwp-plus-24h2-released/ute-accentcolors.png" alt="A screenshot of UltraTextEdit UWP Plus, with different windows, each with a different accent color open.">
    <figcaption>A showcase of UTE UWP+'s accent colors.</figcaption>
</figure>

## Changelog
Here's the entire changelog of the stable version of UTE UWP+ 24H2, which will release on June 24.

> Initial release of UTE UWP+

And the Insider Previews' changelog:

> What's New:
>
>- Fix Superscript/Subscript icons

These changelogs look quite small, but the entire, complete, list of changes in UTE UWP+ 24H2 is displayed here:

What's New:

- _Initial release_ of UTE UWP+ to the Stable Channel
- Introducing the Home Menu! It allows you to quickly create and manage documents! (not complete yet)
- Add the About Box as seen in UTE UWP Dev Channel builds
- Add the Child Windows API from UTE UWP
- Add a new Symbols Dialog and add more new symbols
- Fix font bugs in the Home menu
- Add a hash computation UI
- Add Velocity IDs!
- Allow disabling the Tabbed Window menu item (disabled by default)
- Add Templates
- Allow Templates to be opened via the Home Menu
- Add custom Mica window background for Windows 10 users
- Use TabbedCommandBar from WCT 8.1 (it comes with an updated design)
- Introduce the functionality to share text from UTE UWP+ to compatible apps!
- Dependency updates
- Fix some issues with the Mica Glass theme
- Allow user to create new blank documents via the Home Menu
- Add a dark variant of the Mica Glass theme
- Add 'Justify' text alignment
- Add a new Ribbon UI! (disabled by default)
- You can now toggle between ribbons using the new toggle in the app's top menu (Note: ribbon changes require launching a new instance/window of the app or an app restart, closing the current instance and opening a new one)
- Add Text Templates
- Fix some bugs with the new Ribbon
- Add help section to the new Ribbon
- Add a VelocityID to hide the broken "Save" menu item (option is disabled by default)
- Add more functionality to the new Ribbon
- Add Accent Color customization!!
- The colors currently included are: Lilac, the accent color chosen in Windows Settings (default option), and Slate Green
- Many bugfixes
- Add font size and font family functionality to new Ribbon
- Font color functionality in the Ribbon now works
- List styles other than Bulleted now work properly (if using the new Ribbon)
- Strikethrough now works properly (in the new Ribbon)
- Text highlighting UI bugs have been fixed (in the new Ribbon)
- Update copyright dates in About dialogs
- Icon fixes (in the new Ribbon)
- Add new Underline styles (in the new Ribbon)
- Add date and time insertion capabilities to the new Ribbon
- Replace functionality now works!
- Add the ability to access the Find/Replace pane (in the new Ribbon)
- Fix icons in the Home Menu
- Add Symbols Menu and hash/Base64 generation functionalities to the new Ribbon
- Fix bugs and crashes with the "Save" menu item
- Remove a VelocityID allowing users to hide the "Save" menu item, as the menu item is now properly functional
- Small UI fixes to the new Ribbon
- Introduce Contextual Tabs to the new Ribbon
- Add the ability to close the Comments UI to the new Ribbon via a new Comments Contextual Tab
- Update GitHub repository link
- Fix Superscript/Subscript icons

Yes, I know. This changelog is absolutely massive. Well, I guess this just tells you that UTE UWP+ 24H2 is a massive release, almost as massive as UTE UWP 22H2's publlic release on September 20, 2022, nearly two years ago as of the time of writing of this post!

You can get 26100.1 before June 24 by going here, and downloading one of the Insider Preview compiles: https://github.com/jpbandroid/UTE-UWP-Plus/releases/tag/10.0.26100.1


(It was released 20 hours ago as of the time of writing)