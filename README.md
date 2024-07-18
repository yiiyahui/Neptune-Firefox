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
<img align="bottom" width="696" alt="Screen Shot 1" src="https://github.com/user-attachments/assets/2102162f-123c-4c19-9e2c-151d32d6333a">

<img align="bottom" width="696" alt="Screen Shot 2" src="https://github.com/user-attachments/assets/4f348395-758c-4d65-91ff-fefdfb001b99">

<img align="bottom" width="696" alt="Screen Shot 3" src="https://github.com/user-attachments/assets/6768664c-9a5a-470f-840c-ffe6a6512a73">

<img align="bottom" width="696" alt="Screen Shot 4" src="https://github.com/user-attachments/assets/4e1a32ba-d19c-47dd-8322-5f402f4bef85">

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
