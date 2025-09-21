# Body by Dayoung
My updated custom userChrome.css for Firefox 143.0.1 to make it dark and minimalist.

## Installation
1. Open `about:config` in Firefox. <br>
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and change it to **True**. <br>
3. Open `about:profiles`, find your profile and click **Open Folder**. <br>
4. Create a new folder named `chrome`.
5. Place the `userChrome.css` file inside.
6. Restart Firefox.

### Fonts
+ Download and Install [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono)

### Optional
Improve the color change in audio playing tabs:
+ Open `about:config`
+ Search for `browser.tabs.delayHidingAudioPlayingIconMS` and change the value to something like `50`

Using system colors for text highlights:
+ Open `about:config`
+ Seach for `widget.windows.uwp-system-colors.highlight-accent` and change it to **True**

## Preview
![firefox](https://github.com/user-attachments/assets/3d27efb1-1f9c-409d-9b26-82de5c689de7)

## Credits
* [r/FirefoxCss](https://www.reddit.com/r/FirefoxCSS/) - where i found mostly of the styling rules.
