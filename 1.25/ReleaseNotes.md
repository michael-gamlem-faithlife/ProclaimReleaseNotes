---
title: Proclaim 1.25 Release Notes
---

# Proclaim Version 1.25

### 1.25.0.0413 Wednesday, December 17, 2014 (Mac only)
* Fixed bug where background audio playlist could not be to set to end at the end of the section.
* Fixed bug where uploading files and audio from the account menu did not work.

### 1.25.0.0410 Tuesday, November 11, 2014 (Mac only)
* Fixed various memory leaks that improve performance on machines running Yosemite (OS X 10.10).

### 1.25.0.0406 Monday, November 3, 2014
* Fixed bug where audio in pre-service loop would play when viewing a blank quick screen.
* Fixed the way custom verse tags for song items are rendered on the confidence monitor.
* Fixed bug where 'Include words of Christ in red' was not working correctly.
* Fixed crash related to Logos 6 and 'Send to Proclaim'.
* Fixed bug related to going off-air with a quick screen showing; a quick screen service item will no longer show in the edit view when going off air.
* Pattern Fills now remember the 'Blend Mode' setting when saved w/ a style.
* Pattern Fills now render correctly in the 'Styles' menu.

### 1.25.0.0399 Tuesday, October 28, 2014
* Fixed issue with reszing Faithlife Panel (Mac only).
* Fixed crash that could occur when searching for songs.
* Force sync when current group changes.

### 1.25.0.0397 Monday, October 27, 2014 (Mac only)
* Fixed input event issue which could result in lost keystrokes and mouse clicks.
* Fixed crash in Send to Proclaim when sending images from Logos 6.

### 1.25.0.0393 Monday, October 27, 2014
* Send to Proclaim enhancements for [Logos 6](http://logos.com).
* Added support to media browser for editing group upload media title, description, video loop setting, and tags.
* Save Bible and Song service item settings in synced user preference and use saved values when creating new items.
* Tags and service item kind are now clickable for searching in Media Browser.
* Added new UI to "Link your accounts..." menu for [linking user licensed content](https://community.logos.com/forums/t/92805.aspx). 
* Added Highway Media search facet.
* Added Alt+M keyboard shortcut for opening Media Browser to last viewed state.
* Added quick screen keyboard shortcuts on Mac, now matching Windows.
* Performance improvements on Mac when navigating video backgrounds while on air.
* Added account menu button to invite group members.
* Added button to create a group when a user cannot find a group.
* Added button to link SongSelect account in song entry helper search results.
* Changed default Blank Presentation titling to use the upcoming Sunday’s date.
* Added button to create a group when a user cannot find a group.
* Always show fade transition when hiding/showing foreground text via quick screen.
* Use presentation default transition when showing blank quick screen.
* Fixed minor presentation issue when purchasing Pro Media in app.
* Memory usage improvements when uploading files.
* Handling sign in after password change scenario more gracefully.
* Added startup option to disable hardware acceleration for Windows machines with video driver issues (Windows only).
* Add support for Hindi, Burmese, Nepalese system font fallbacks.
* Added new Greek and Hebrew fonts for Send to Proclaim support.
* Updated [getting started video](http://fast.wistia.net/embed/iframe/5wif3me9vy).
* Fixing bug causing unnecessary calls to try and hide duplicate media.
* Fixed video player preview distortion (Windows only).
* Moved analytics web call to thread pool thread which could have previously caused a hang when resolving DNS.
* Supporting drag and drop from Media Browser to Image Slideshow service item.
* Fixed a few issues in On Screen Bible related to certain reference ranges.