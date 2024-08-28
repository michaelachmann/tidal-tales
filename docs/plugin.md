---
title: Tidal Tales Plugin
hide:
    - navigation
---

![Tidal Tales Plugin Logo](../assets/logo-plugin.png){ align=right style="height:125px;width:125px" }

The **Tidal Tales Plugin** is a modified version of the original [Zeeschuimer project](https://github.com/digitalmethodsinitiative/zeeschuimer) designed to capture Instagram Stories. It is based on the research and work by Stijn Peeters for the [Digital Methods Initiative](https://digitalmethods.net). This plugin allows researchers to collect Instagram Stories in real-time, directly onto their local machines, without relying on any third-party servers.

<br/>

!!! note
    This documentation is currently work in progress!

--- 

## Installation

[Download the latest version of the Tidal Tales Plugin](https://github.com/michaelachmann/tidal-tales-plugin/releases/latest) and install the extension using [Firefox](https://www.mozilla.org/en-GB/firefox/). The plugin can be easily installed by following the standard Firefox extension installation process.

## Use

Once the plugin is installed, start browsing Instagram Stories. The plugin works in the background to download the media files (images and videos) and metadata as you browse. All files are stored in your downloads location. When you have finished collecting data, you can export the metadata by opening the plugin's pop-up menu and clicking *Export as CSV*. This will save a CSV file containing all metadata, including the relative file paths for the downloaded media files.

<p align="center"><img alt="A screenshot of Tidal Tales Plugin Pop Up" width="50%" src="https://github.com/michaelachmann/tidal-tales-plugin/raw/master/images/example_screenshot.png"></p>

## Data

The data collected by the Tidal Tales Plugin is stored locally on your machine. This includes:

- **Media Files**: Images and videos from Instagram Stories.
- **Metadata**: Information about each story, such as timestamps, user handles, and any other relevant details.

The CSV export functionality includes the relative file paths to the downloaded media, allowing for easy organization and analysis of your data.

## More Information
For additional details, including source code, issue tracking, and contribution guidelines, please visit the [Tidal Tales Plugin GitHub Repository](https://github.com/michaelachmann/tidal-tales-plugin).