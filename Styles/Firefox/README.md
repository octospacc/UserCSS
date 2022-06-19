Note: Download your desired CSS file from this repo and rename it as `userChrome.css` (important).

## How to use a userChrome.css theme

1. Type `about:config` into your URL bar. Click on the **I accept the risk** button if you're shown a warning.
2. Seach for the following values and set them to **`true`**:  
    - **`toolkit.legacyUserProfileCustomizations.stylesheets`**
    - **`layers.acceleration.force-enabled`**
    - **`gfx.webrender.all`**
    - **`svg.context-properties.content.enabled`**
    - **`browser.compactmode.show`**
3. Go to your profile folder:
    - Linux: `$HOME/.mozilla/firefox/######.default-release/`
    - MacOS: `Users/[USERNAME]/Library/Application Support/Firefox/Profiles/######.default-release`
    - Windows: `C:\Users\[USERNAME]\AppData\Roaming\Mozilla\Firefox\Profiles\######.default-release`
4. If it doesn't exist already create a folder called `chrome`.
5. Copy your desired `userChrome.css` into that folder.

_This guide is borrowed from the Cascade repo. Credits: [github.com/andreasgrafen/cascade](https://github.com/andreasgrafen/cascade/blob/main/README.md#how-to-use-a-userchromecss-theme)_
