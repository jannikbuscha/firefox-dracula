# Firefox Dracula

This Firefox userChrome.css and userContent.css theme is a fork of [Edge-Frfox](https://github.com/bmFtZQ/edge-frfox) that aims to recreate the look and feel of the Chromium version of [Microsoft Edge](https://www.microsoft.com/edge) in the style of [Dracula](https://draculatheme.com/).

**[Extra Features](#-extra-features) • [Installation](#-installation) • [JSON Viewer](#-json-viewer) • [Tweaks](#-tweaks)** • [License](#-license)**

![thumbnail](screenshots/thumbnail.png)

## 💫 Extra Features

- Custom DevTools
- Custom [JSON Viewer](#-json-viewer)

## ⚙️ Installation

1. Go to `about:support` and click the "Open Folder/Show in Finder" button for the root directory of your browser profile/s.
2. Download and copy the `chrome` folder into the profile folder.
3. Go to `about:config` and change these preferences:

   ### For all operating systems:
   1. `toolkit.legacyUserProfileCustomizations.stylesheets` = `true`
   2. `svg.context-properties.content.enabled` = `true`
   3. `layout.css.color-mix.enabled` = `true`

   ### On macOS:
   1. To use the Edge style context menu on macOS then set `widget.macos.native-context-menus` = `false`

   ### Recommended:
   1. `browser.tabs.tabMinWidth` = `66`
   2. `browser.tabs.tabClipWidth` = `86`
   3. `browser.tabs.tabmanager.enabled` = `false`

## 📜 JSON Viewer

| Preview                       | Settings                                        |
|-------------------------------|-------------------------------------------------|
| ![json](screenshots/json.png) | ![json-settings](screenshots/json-settings.png) |

### Installation

1. Go to `about:config` page and set `devtools.jsonview.enabled` = `false`.
2. Install the JSON Lite extension from [here](https://addons.mozilla.org/en-US/firefox/addon/json-lite/).
3. Set the values as shown in the screenshot above, you can find the values to copy below.

   ```yaml
   Font: 13px JetBrains Mono,monospace
   Text color: #f8f8f2
   Background color: #282A36
   Info color: #6272a4
   Info hover color: #6272a4
   Line numbers color: #6272a4
   Line numbers background: #1D2128
   String color: #f1fa8c
   Number color: #bd93f9
   Boolean color: #bd93f9
   Null color: #bd93f9
   Propertie name color: #8be9fd
   Error color: #ed2655
   ```

## 🎨 Tweaks

Certain customizations like hiding the Firefox logo on the newtab page or switching to floating tabs can be done on the theme. More information on how to do this can be found in the original [repository](https://github.com/bmFtZQ/edge-frfox#tweaks).

You can also check out [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) themes (e.g. [StackOverflow](https://draculatheme.com/stackoverflow) or [GitHub](https://draculatheme.com/github)).

## 📝 License

[MIT](./LICENSE)
