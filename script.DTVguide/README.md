#### script.DTVguide
---

### Manual for the DynamicTVGuide `DTVguide`


## DynamicTVGuide (DTVguide)

### Introduction

DynamicTVGuide, now known as DTVguide, elevates your TV viewing experience by integrating live TV plugins with a fully functional electronic program guide (EPG). Originally developed by FXB78, Bluezed, Tommy Winther, Dixie, Ray Wilson, and IVUE, the guide has been reskinned and improved by Sully Greene, who has forked and updated the project.

### Acknowledgements

All credits for the foundational work go to the original developers: FXB78, Bluezed, Tommy Winther, Dixie, Ray Wilson, and IVUE. Special thanks to Sully Greene for the latest updates and enhancements.

### Features

- **New Additions:** The script has been optimized for faster performance and cleanliness. It automatically generates `Dexter.ini` and `aPVR.ini` if Dexter or A PVR is enabled.
- **Plugin Compatibility:** Improved compatibility with various plugins.
- **Auto Features:** Added automatic favorites and PVR detection.
- **Enhanced Selection:** Broadened the selection with auto link features.
- **Resource Management:** Added a PNG folder to resources for better organization.
- **Configuration Options:** Allows the use of a second `.ini` file from a custom selection which will automatically merge.

### What's New in v0.0.1

- **Time Zone Adjustments:** Change time zones for individual channels within settings.
- **Performance:** Faster loading times and guide auto-scrolling at half-hour intervals.
- **Stream Selection:** Ability to pick streams from 'super faves'.
- **Planner Management:** Options to remove or play reminders from the planner.
- **Navigation Enhancements:** Direct navigation to the first channel in a selected category.
- **Customization:** Custom exit menu for skins, with the option to turn it off in settings. Override colours with default skin colours.
- **Additional Information:** IMDB info available for selected programs and on-demand availability for finished programs.
- **Visual Enhancements:** Progress bars for current programs, HD and SD channel tags, and different colour textures for ongoing and finished programs, all available in select skins like WhiteVue.

### Script Integration

To integrate the script into your plugin settings, add the following line to your `settings.xml`:

```xml
<setting label="Add PVR and INI" type="action" action="RunScript($CWD/add.py)" />
```

### Collaboration

Under the stewardship of Sully Greene, the DTVguide continues to evolve with contributions from both the JDM Team and the former IVUE team, ensuring that your TV guide experience is as dynamic and user-friendly as possible.

---
