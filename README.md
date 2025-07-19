<h1 align="center"><strong>Neptune Firefox</strong></h1>

**Instructions:** 
- This theme is compatible with the latest release of Firefox and works on both Windows and macOS.
- To enable adaptive colors, you need to install the **[Adaptive Tab Bar Color](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour)** extension. If not, the tabs will appear transparent.

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

- **about:config**
    - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
    - Set `svg.context-properties.content.enabled` to `true`.
    - Set `widget.non-native-theme.use-theme-accent` to `true`.

- **Required settings**
    - Move all toolbar buttons to the top, and the tab bar does not display any buttons.
    - If extension (Adaptive Tab Bar Color) is enabled, set all colors in the Options (theme builder) to `0%`.

ENJOY!