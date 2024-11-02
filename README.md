<h1 align="center"><strong>Neptune Firefox</strong></h1>

**Instructions:** 
- This theme works for **Firefox v128+** and is compatible with both Windows and macOS.
- In shades of blue.
- To enable adaptive colors, you need to install the **[Adaptive Tab Bar Color](https://addons.mozilla.org/en-US/firefox/addon/adaptive-tab-bar-colour/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)** extension. 

**Known issues:** 
- The buttons on the right cannot be dragged. however, they can be moved to the far left or hidden.
- Due to changes in the Picture-in-Picture player's style, it cannot be resized.

**Tips:** 
- Some elements like unnecessary context menus are removed, so it might not be ideal for everyone.
- The default new tab wallpaper of the theme uses Firefox's wallpaper feature. However, it cannot be customized. Therefore, to display the wallpaper shown in the preview, search for and modify **"userContent.css"** by removing the `/*` and `*/` symbols from this line:

```css
/*body {
  background: url("neptune/image/Orange.png") center/cover no-repeat fixed !important;

  @media (prefers-color-scheme: dark) {
    background: url("neptune/image/Blue.png") center/cover no-repeat fixed !important;
  }
}*/
```
## Preview:

<img align="bottom" width="696" alt="Screen Shot 1" src="https://github.com/user-attachments/assets/ef7261d7-ff9b-4524-a930-44fae9660ef2">
<img align="bottom" width="696" alt="Screen Shot 2" src="https://github.com/user-attachments/assets/b3a18714-69bc-4715-8b2f-9d9c4b0df060">
<img align="bottom" width="696" alt="Screen Shot 3" src="https://github.com/user-attachments/assets/11fc5856-8711-4bfd-91ec-c7dfb5ec1919">
<img align="bottom" width="696" alt="Screen Shot 4" src="https://github.com/user-attachments/assets/02c77bd1-ab2c-42e5-b95f-e9cbdfe4d400">
<img align="bottom" width="696" alt="Screen Shot AM" src="https://github.com/user-attachments/assets/d6140223-3989-4416-a9bd-3ced1d8a14a3">

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

    **Optional**
    - Set `browser.newtabpage.activity-stream.improvesearch.handoffToAwesomebar` to `false`.

- **Adaptive Tab Bar Color settings**

    - Turn off all `Customization` colors,
    - configure `advanced`
        - light:`rgb 246,246,246`
        - dark:`rgb 56,56,56`
