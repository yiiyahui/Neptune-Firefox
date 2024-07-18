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
- To display wallpapers in the preview, remove the comments from lines 326 to 332 in **"userContent.css"**.

## Preview:

<img align="bottom" width="696" alt="Screen Shot 1" src="https://github.com/user-attachments/assets/ef7261d7-ff9b-4524-a930-44fae9660ef2">
<img align="bottom" width="696" alt="Screen Shot 2" src="https://github.com/user-attachments/assets/b3a18714-69bc-4715-8b2f-9d9c4b0df060">
<img align="bottom" width="696" alt="Screen Shot 3" src="https://github.com/user-attachments/assets/11fc5856-8711-4bfd-91ec-c7dfb5ec1919">
<img align="bottom" width="696" alt="Screen Shot 4" src="https://github.com/user-attachments/assets/02c77bd1-ab2c-42e5-b95f-e9cbdfe4d400">

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

    **Optional**
    - Set `browser.newtabpage.activity-stream.improvesearch.handoffToAwesomebar` to `false`.

- **Adaptive Tab Bar Color settings**

    - Turn off all `Customization` colors,
    - configure `advanced`
        - light:`rgb 246,246,246`
        - dark:`rgb 56,56,56`
