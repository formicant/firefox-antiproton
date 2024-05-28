# firefox-antiproton

My personal style sheet for the Firefox UI

![screenshot](screenshot.png)

## How to install

- `about:config`:
  - `browser.compactmode.show`: **true**
  - `toolkit.legacyUserProfileCustomizations.stylesheets`: **true**
- Customize → Density: **Compact (not supported)**
- `about:support` → Profile Folder → Open Folder
  - in this folder, create a new folder named `chrome`
  - copy the contents of the `Linux-KDE` or `Windows-10` folder into it
- Restart Firefox

## Debugging with live preview

- DevTools (<kbd>F12</kbd>) → Settings (<kbd>F1</kbd>) → Advanced settings →
  - enable browser chrome and add-on debugging toolboxes
  - enable remote debugging
- Remote debugging (<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd>)
  - OK
- Style Editor tab → `userChrome.css` file
- To debug popup menu: `…` button → Disable Popup Auto-Hide
