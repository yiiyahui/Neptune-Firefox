<h1 align="center"><strong>Neptune Firefox</strong></h1>

**Instructions:** 
- This theme is compatible with the latest release of Firefox and works on both Windows and macOS.
- To enable adaptive colors, you need to install the **[Adaptive Tab Bar Color](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour)** extension. 

<img src="info/preview.png" alt="Preview Image" width="800px">

## Installation

- Download the theme file and unzip the `chrome` folder into your `profile` folder.
- You can modify the wallpaper in the `userContent.css`, and edit the file names for the light and dark modes

```css
body {
	background: url("neptune/image/RainbowLight.png") center/cover no-repeat fixed;

	@media (prefers-color-scheme: dark) {
		background: url("neptune/image/RainbowDark.png") center/cover no-repeat fixed;
	}
}
```

## Configuration

- **about:preferences**
    - Set `appearance` to `automatic`.

- **about:config**
    - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
    - Set `svg.context-properties.content.enabled` to `true`.
    - Set `widget.non-native-theme.use-theme-accent` to `true`.

- **Adaptive Tab Bar Color settings**
    - Set all values in the `Theme builder` to `0%`.
    - Home page color light:`#f6f6f6`
    - Home page color dark:`#383838`

ENJOY!