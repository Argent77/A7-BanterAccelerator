[![GitHub release (latest by date)](https://img.shields.io/github/v/release/Argent77/A7-BanterAccelerator?color=darkred&include_prereleases&label=latest%20release)](https://GitHub.com/Argent77/A7-BanterAccelerator/releases/latest)
[![GitHub release date (latest by date)](https://img.shields.io/github/release-date/Argent77/A7-BanterAccelerator?color=gold)](https://GitHub.com/Argent77/A7-BanterAccelerator/releases/latest)
[![Github downloads (all releases)](https://img.shields.io/github/downloads/Argent77/A7-BanterAccelerator/total.svg?color=blueviolet)](https://GitHub.com/Argent77/A7-BanterAccelerator/releases)
[![Platform](https://img.shields.io/static/v1?label=platform&message=Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Project%20Infinity&color=informational)](https://GitHub.com/Argent77/A7-BanterAccelerator/releases/latest)
[![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20%7C%20German&color=limegreen)]()

# Banter Accelerator for Enhanced Edition games
*A WeiDU mod for Enhanced Edition games that can be used to modify the party banter behavior*

[![Beamdog Forums](https://img.shields.io/static/v1?label=Discussion&message=Beamdog%20Forums&color=444&labelColor=eee&style=flat)](https://forums.beamdog.com/discussion/64551)

## Overview

This mod allows you to define how often party members will banter with each other. You can either choose from a list of presets or specify the desired values yourself.

*All Enhanced Edition games are supported.*


## Installation

This is a WeiDU mod, that means it is very easy to install. Simply unpack the downloaded archive into your game directory and run `setup-A7-BanterAccelerator.exe`.

Alternatively, you can simply copy a premade banter timing file into the game without running the installer at all. They can be found in `A7-BanterAccelerator/override`. You can choose between many variants with different interval and/or probability values. Each one is located in a subfolder that indicates both interval in ticks (1/15th seconds) and probability (in percent) of banters. For example "450_25" indicates a banter timing of 450 ticks interval and 25% probability. Copy the file into the game's `override` folder. Create the folder manually if it doesn't exist yet.

*You don't have to start a new game for the changes to take effect.*


## Components

There is only one component "Banter Accelerator" with several different timing variants selectable as subcomponents. You can also define your own timings by selecting "User-defined" instead.
