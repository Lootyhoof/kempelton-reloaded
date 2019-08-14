# Changelog

### 5.6.0
- update Reader View styling to reflect changes in Pale Moon 28.6.0+
- macOS: improve tab audio indicator visibility

### 5.5.0
- add tab audio indicators for Pale Moon 28.3.0+
- update in-browser developer tools
- experimental: add support for Ambassador IRC client (standalone/extension)

### 5.4.0
- sync global stylings with Pale Moon 28
- remove redundant devtools styling
- mark as compatible with Pale Moon 28 only
- use non-prefixed -inline syntax
- update media controls
- improve menubar appearance on Linux

### 5.3.0
- add PM28 newtab styling
- add tabbrowser findbar styling
- improve about:permissions sizing
- fix disappearing titlebar in private and lwtheme modes on macOS
- fix favicon sizes in password manager

### 5.2.0
- add initial Pale Moon 28 support
- don't use background image on standalone image viewer

### 5.1.4
- show navigator-toolbox bottom border when tabs bar disabled

### 5.1.3
- style fullscreen warning message

### 5.1.2
- set minimum supported version to Pale Moon 27.5.0
- fix statusbar progressmeter custom colors
- don't use filters on extension icons
- re-implement back-forward dropmarker in icons+text and text modes
- improve titlebar styling on non-compositor Windows when tabs are in titlebar
- fix new tab icon mapping when not in tab bar
- Windows: only apply inactive appmenu styling to Aero Glass
- Win10: use white window backgrounds on active windows with no accent color applied
- Linux: redesign appmenu button
- minor cleanup

### 5.1.1
- improve downloads indicator appearance
- use larger private browsing indicator in menu bar
- restore native toolbarbutton styling
- Linux: add private browsing indicator to tab bar

### 5.1.0
- improve downloads panel appearance
- use new icon for "switch to tab" in address bar
- add basic OS X styling
- PM27.5: draw a background on Windows 10 for improved accent color detection
- add private browsing indicator in menubar
- fix caption button/appmenu margins for tabsintitlebar mode

### 5.0.0
- redesign appmenu on Windows and Linux
- add HiDPI-capable toolbar images
- add new hover/click/disabled states for all icons (including most extension icons)
- make sure back/forward dropmarker shows as disabled when disabled
- refactor tab styling
- improve tabsintitlebar styling for tabs
- improve platform stylings for Windows and Linux
- add basic CSS variable support for increased customisation
- fix navigation button padding in about:addons to match the places window
- sync devtools styling with default
- cleanup of redundant code

### 4.11.0
- sync about:support styling with default
- sync about:permissions styling with default
- add image document favicon when viewing standalone images
- fix "learn more" links in notification popups
- add about:home styling for Home Styler

### 4.10.1
- sync devtools styling with default
- allow extensions to style their own toolbarbutton-badge
- remove redundant social API components
- provide new icons for updater
- sync updater styling with default
- improve tabpanels appearance

### 4.10.0
- support PM27's devtools
- drop PM26 support
- use correct margins for all downloads view

### 4.9.0
- PM27: add statusbar styling
- PM27: add styling for downloads panel components
- PM27: style devtools
- improve appearance of about:

### 4.8.0
- titlebar colorisation for Windows 10
- use dark window frame detection on Windows 8/10
- refactor media controls for Pale Moon 26.3
- use unified close button icons
- use dark toolbar detection in Pale Moon 26.3 to detect dark system themes

### 4.7.1
- (PM26) add download location styling

### 4.7.0
- (PM26) add history menu button
- show more icons in history/bookmarks menus
- stability improvements
- correctly style alert box
- fix media controls
- improve alltabs button's appearance when not in the tab bar
- add unified back/forward menu icons
- improve presentation of alltabs' close buttons
- make tab bar's alltabs button more FF3-like

### 4.6.2
- (Win10) shade window background on Pale Moon 26 builds later than b2

### 4.6.1
- fix vertical toolbar borders

### 4.6.0
- Pale Moon v26 compatibility
- fix window borders on Windows 10
- don't animate popups on non-Windows

### 4.5.2
- add back/forward dropmarker
- ensure bottom border is present if tab bar disabled

### 4.5.1
- fix menu button orientation
- Linux rough visual parity with Windows version
- Linux: style appmenu
- navigator-toolbox border fix
- several notification style fixes
- about:addons: make header be consistent with toolbar in places

### 4.5.0
- replace deprecated attributes (-moz-border-radius, etc) with current standards
- fix tabs
- curve identity box
- fix notification icon alignment
- fix Status4Evar download status icon padding
- redesigned addon manager
- use larger appmenu-button backgrounds
- replace media toolbar stylings to enable cross-platform compatibility

### 4.4.6
- disable persona-based text colouring on WinXP

### 4.4.5
- theme titlebar when maximized using a persona

### 4.4.4
- implement doorhanger notifications
- add bright close button for dark personas

### 4.4.3
- fix notification box padding

### 4.4.2
- add mixed padlock state
- improve persona compatibility

### 4.4.1
- provide Pale Moon 24 version
- fix menu bar colours
- improve persona compatibility

### 4.4.0
- Pale Moon v25-only; DO NOT USE ON PALE MOON 24, it won't work!
- added Pale Moon's GUID, removed Firefox's
- fix alltabs button's clicked behaviour
- add background to all of tabs toolbar

### 4.3.1pm
- temporary(?) findbar "not found" fix
- add "visited" icon for live bookmarks

### 4.3.0pm
- new appmenu button
- new zoom icons
- urlbar feed icon
- urlbar security padlock icons
- download manager icon
- download buttons (for download manager)
- fix urlbar favicon padding
- redesigned add-on manager
- various fixes