Banter Accelerator for Enhanced Edition games
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Version:    1.6
Author:     Argent77

Download:   https://github.com/Argent77/A7-BanterAccelerator/releases/latest
Discussion: https://forums.beamdog.com/discussion/64551/mod-banter-accelerator-for-enhanced-edition-games


Overview
~~~~~~~~

This mod allows you to define how often party members will banter with each other. You can either 
choose from a list of presets or specify the desired values yourself.

All Enhanced Edition games are supported.


Installation
~~~~~~~~~~~~

This is a WeiDU mod, that means it is very easy to install. Simply unpack the downloaded archive 
into your game directory and run "setup-A7-BanterAccelerator.exe".

Alternatively, you can simply copy a premade banter timing file into the game without running the 
installer at all. They can be found in "A7-BanterAccelerator/override". You can choose between many 
variants with different interval and/or probability values. Each one is located in a subfolder 
that indicates both interval in ticks (1/15th seconds) and probability (in percent) of banters. 
For example "450_25" indicates a banter timing of 450 ticks interval and 25% probability.
Copy the file into the game's "override" folder. Create the folder manually if it doesn't exist yet.

You don't have to start a new game for the changes to take effect.


Components
~~~~~~~~~~

There is only one component "Banter Accelerator" with several different timing variants selectable 
as subcomponents. You can also define your own timings by selecting "User-defined" instead.


Credits
~~~~~~~

Coding and testing: Argent77

French translation: Gwendolyne

Brazilian Portuguese translation: Felipe


Copyright Notice
~~~~~~~~~~~~~~~~

The mod "Banter Accelerator for Enhanced Edition games" is licensed under the "Creative Commons 
Attribution-ShareAlike 4.0 International License" (http://creativecommons.org/licenses/by-sa/4.0/).


History
~~~~~~~

1.6
- Added Simplified Chinese translation (thanks MephistoSatanDevil)

1.5
- Added Brazilian Portuguese translation (thanks Felipe)
- Added component labels for Project Infinity

1.4
- Added Project Infinity metadata
- Added German translation for WeiDU prompts
- Added WeiDU SUPPORT information
- Fixed potential display issues with component names in WeiDU.log and Project Infinity

1.3
- Made install options more user-friendly by replacing ticks with seconds

1.2
- Added French translation (thanks Gwendolyne)
- Added German translation

1.1
- Changed "seconds" to "ticks"
- Redesigned available presets

1.0
- Initial release
