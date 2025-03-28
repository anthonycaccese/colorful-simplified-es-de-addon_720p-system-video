# Colorful (Simplified) ES-DE Add-On: 720p System Video

This is an add-on for the [Colorful (Simplified)](https://github.com/anthonycaccese/colorful-simplified-es-de) theme for ES-DE. 

It adds video playback to the system view with videos from the Colorful platform video set (originally created by [Viking](https://forums.launchbox-app.com/profile/70421-viking/) for Launchbox)

The original source for the videos in this repo can be found [here](https://forums.launchbox-app.com/files/file/1958-colorful-platform-video-set/).

This repo simply made the following changes:

- Changed the names to map to ES-DE's system naming convention
- Converted the 4k source to 720p using HandBrake's default "Fast 720p" profile and changing framerate to match the source
- Added hooks to allow this set to be used as an add-on for the [Colorful (Simplified)](https://github.com/anthonycaccese/colorful-simplified-es-de) theme for ES-DE

## Usage:

> [!NOTE] 
You will need ES-DE version 3.2.0 (or later) plus the latest version of the Colorful Simplified theme already downloaded to use this add-on. 

To install:
1. Download the `system-video-720p.zip` file from the latest release [here](https://github.com/anthonycaccese/colorful-simplified-es-de-addon_720p-system-video/releases/latest)
2. Unzip it into your existing Colorful Simplified theme directory located at: `ES-DE/themes/colorful-simplified-es-de`.  
    - After unzip you should have a new folder called `/theme-addons/system-video/` and that folder will contain the assets needed for this add-on to function (e.g. addon.xml, videos and images)
3. Then open Menu > UI Settings and set your Theme Color Scheme to: `Add-on (See Readme)`

## Credits:

- All credit for the creation of the system videos goes to [Viking](https://forums.launchbox-app.com/profile/70421-viking/) and others for their work on the original Launchbox theme [[Source](https://forums.launchbox-app.com/files/file/1958-colorful-platform-video-set/)]
- Zip prep: `zip -r system-video-720p.zip theme-addons -x "*.DS_Store"`
