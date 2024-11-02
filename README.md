<h1 align="center"><strong>Neptune Firefox</strong></h1>

**Instructions:** 
- This theme works for **Firefox v132+** and is compatible with both Windows and macOS.
- To enable adaptive colors, you need to install the **[Adaptive Tab Bar Color](https://addons.mozilla.org/en-US/firefox/addon/adaptive-tab-bar-colour/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)** extension. 

**Known issues:** 
- The three buttons on the right side of the toolbar cannot be moved in compact layout.

**Tips:** 
- Some elements like unnecessary context menus are removed, so it might not be ideal for everyone.

## Preview:
<img align="bottom" width="800" alt="Screen Shot 1" src="https://github.com/user-attachments/assets/bd6341eb-704c-4118-8161-869c0695ade3">

## Installation

Download the theme file and unzip the **"chrome"** folder into your **"profile"** folder.

## Browser Configuration
- `about:preferences`

    - Set appearance to automatic.

-  `about:config`

    **Important**
    - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
    - Set `svg.context-properties.content.enabled` to `true`.
    - Set `browser.newtabpage.activity-stream.newtabWallpapers.enabled` to `true`.
    - Set `browser.newtabpage.activity-stream.newtabWallpapers.v2.enabled` to `true`.
    - Set `widget.non-native-theme.scrollbar.style` to `2` （**For Windows10**. Due to the default scrollbar in Windows 10 being quite wide, it can affect the setting menu's width., this configuration is recommended.)

    **Layout switch** (Enabling or disabling them can switch between vertical tab mode and compact mode)
    - `sidebar.revamp` to `true` or `false`.
    - `sidebar.verticalTabs` to `true` or `false`.

    **Homepage search bar switch**
    - Set `browser.newtabpage.activity-stream.improvesearch.handoffToAwesomebar` to `false`.

- **Adaptive Tab Bar Color settings**

    - Turn off all `Customization` colors,
    - configure `advanced`
        - light:`rgb 246,246,246`
        - dark:`rgb 56,56,56`