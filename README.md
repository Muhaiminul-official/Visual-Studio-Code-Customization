# Visual Studio Code Customization

## 📝 Why?
I've been a loyal user of Visual Studio Code, and it has become my preferred code editor. Its speed and flexibility make it a reliable choice for me, regardless of the operating system I'm using.I've made various customizations to tailor it to my preferences.

I've tweaked its appearance, added and modified features, installed extensions, and even created a personalized theme because I haven't found a theme that's absolutely perfect for me. Each time I set up a new work environment, I find myself manually configuring these settings. To streamline this process, I've uploaded all my settings here, so I can quickly apply them. Feel free to use any of them for your convenience.

## 🛠 VS Code Settings
```bash
{
  "editor.fontFamily": "Operator Mono, Fira Code",
  "code-runner.saveAllFilesBeforeRun": true,
  "code-runner.runInTerminal": true,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "terminal.integrated.defaultLocation": "editor",
  "terminal.integrated.fontSize": 17,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.autoClosingBrackets": "always",
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 50,
  "editor.codeLensFontSize": 12,
  "editor.cursorBlinking": "expand",
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "workbench.colorCustomizations": {
    "editorGroupHeader.tabsBackground": "#2c2c54",
    "activityBar.background": "#2c2c54",
    "sideBar.background": "#141422",
    "minimap.background": "#141422",
    "tab.activeBackground": "#706fd3",
    "tab.inactiveBackground": "#191846",
    "terminal.border": "#2c2c54",
    "terminal.background": "#2c2c54",
    "statusBar.background": "#474787",
    "scrollbarSlider.background": "#474787",
    "scrollbarSlider.hoverBackground": "#706fd3"
  },
  "editor.tokenColorCustomizations": {
    "comments": "#95afc0"
  },
  "editor.linkedEditing": true,
  "editor.guides.bracketPairs": true,
  "editor.guides.bracketPairsHorizontal": true,
  "window.zoomLevel": 1.5,
  "liveServer.settings.CustomBrowser": "chrome",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/css"
    }
  ],
  "liveSassCompile.settings.generateMap": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Andromeda Bordered",
  "editor.rename.enablePreview": false,
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "security.workspace.trust.untrustedFiles": "open",
  "prettier.proseWrap": "always",
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  // Screencast mode
  "screencastMode.onlyKeyboardShortcuts": true,
  "screencastMode.mouseIndicatorColor": "#f1c40f",
  "screencastMode.verticalOffset": 0,
  "editor.fontSize": 20,
  "chatgpt.lang": "en",
  "editor.mouseWheelZoom": true,
  "terminal.integrated.mouseWheelZoom": true
}

  

```

## ⚙️ VS Code Extension
- Auto Close Tag (Jun Han)
- Auto Import - ES6, TS, JSX, TSX (Sergey Korenuk)
- Auto Rename Tag (Jun Han)
- Debugger for Chrome
- ESLint (Microsoft)
- indent-rainbow (oderwat)
- HTML CSS Support (ecmel)
- JavaScript (ES6) code snippets (charalampos karypidis)
- Live Server (Ritwick Dey)
- Live Sass Compiler (Glenn Marks)
- Material Icon Theme (Philipp Kief)
- npm Intellisense (Christian Kohler)
- Path Intellisense (Christian Kohler)
- Postman (Postman)
- Prettier - Code formatted (Prettier)
- Reactjs code snippets (charalampos karypidis)
- Simple React Snippets (Burke Holland)
- Snipped (Jefferson Licet)
- Stylelint (Stylelint)
- WordPress Snippets (wpprotools.io)
- VSCode React Refactor (planbcoding)
- Tailwind CSS IntelliSense (Tailwind Labs)

## 🛠 VS Code Other Settings
```bash
{
  // Editor Font Settings
  "editor.fontFamily": "Operator Mono, Fira Code", // Sets the font family for the editor

  // Code Runner Settings
  "code-runner.saveAllFilesBeforeRun": true, // Automatically save all files before running the code
  "code-runner.runInTerminal": true, // Runs code in the terminal instead of the output pane

  // Editor Preferences
  "editor.tabSize": 2, // Sets the tab size to 2 spaces
  "editor.wordWrap": "on", // Enables word wrap in the editor
  "terminal.integrated.defaultLocation": "editor", // Places terminal at the bottom of the editor
  "editor.cursorSmoothCaretAnimation": "on", // Enables smooth caret animation
  "editor.autoClosingBrackets": "always", // Automatically closes brackets
  "files.autoSave": "afterDelay", // Automatically saves files after a delay
  "files.autoSaveDelay": 500, // Delay before auto-saving (in ms)
  "editor.codeLensFontSize": 12, // Font size for code lens
  "editor.cursorBlinking": "expand", // Sets the cursor blinking style to expand
  "editor.formatOnSave": true, // Automatically formats code on save
  "editor.formatOnPaste": true, // Automatically formats code when pasting
  "editor.formatOnType": true, // Automatically formats code while typing

  // Custom Theme and Color Settings
  "workbench.colorCustomizations": {
    "editorGroupHeader.tabsBackground": "#2c2c54", // Background color for editor tabs
    "activityBar.background": "#2c2c54", // Background color for the activity bar
    "sideBar.background": "#000000", // Background color for the sidebar
    "sideBar.foreground": "#ffffff", // Foreground color for the sidebar
    "activityBar.foreground": "#1bde42", // Foreground color for the activity bar
    "activityBar.inactiveForeground": "#FFFFFF", // Inactive foreground color for the activity bar
    "editor.selectionHighlightBorder": "#ffffff", // Border color for highlighted selections
    "editor.lineHighlightBackground": "#aa9e9e20", // Background color for the current line
    "editor.background": "#000000", // Editor background color
    "minimap.background": "#141422", // Minimap background color
    "menu.background": "#283350", // Background color for menus
    "menu.foreground": "#ffffff", // Foreground color for menus
    "tab.activeBackground": "#000000", // Background color for active tabs
    "tab.inactiveBackground": "#191846", // Background color for inactive tabs
    "terminal.border": "#2c2c54", // Terminal border color
    "terminal.background": "#06061e", // Terminal background color
    "statusBar.background": "#474787", // Status bar background color
    "statusBar.foreground": "#f8f8f8", // Status bar foreground color
    "scrollbarSlider.background": "#474787", // Scrollbar background color
    "scrollbarSlider.hoverBackground": "#706fd3" // Scrollbar hover background color
  },

  // Editor Token Color Customizations
  "editor.tokenColorCustomizations": {
    "comments": "#c8c8e9" // Custom color for comments
  },

  // Linked Editing Settings
  "editor.linkedEditing": true, // Enables linked editing
  "editor.guides.bracketPairs": true, // Displays guides for bracket pairs
  "editor.guides.bracketPairsHorizontal": true, // Displays horizontal guides for bracket pairs

  // Window Zoom Level
  "window.zoomLevel": 0.8, // Sets the zoom level for the window

  // Live Server Settings
  "liveServer.settings.CustomBrowser": "chrome", // Sets Chrome as the custom browser for Live Server
  "liveServer.settings.donotShowInfoMsg": true, // Disables info messages in Live Server
  "liveServer.settings.donotVerifyTags": true, // Disables tag verification in Live Server

  // Live Sass Compile Settings
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed", // Compresses the output CSS file
      "extensionName": ".min.css", // Sets the extension for the compressed file
      "savePath": "/css" // Specifies the save path for the output file
    }
  ],
  "liveSassCompile.settings.generateMap": false, // Disables generation of source maps

  // Icon Theme Settings
  "workbench.iconTheme": "material-icon-theme", // Sets the icon theme to Material Icon Theme

  // Editor Rename Preview
  "editor.rename.enablePreview": false, // Disables rename preview in the editor

  // Terminal Settings
  "terminal.integrated.defaultProfile.windows": "PowerShell", // Sets PowerShell as the default terminal profile in Windows
  "security.workspace.trust.untrustedFiles": "open", // Opens untrusted files without warning

  // Prettier Settings
  "prettier.proseWrap": "always", // Forces Prettier to wrap prose
  "prettier.singleQuote": true, // Uses single quotes in Prettier
  "prettier.arrowParens": "avoid", // Avoids parentheses for single-parameter arrow functions
  "editor.defaultFormatter": "esbenp.prettier-vscode", // Sets Prettier as the default formatter

  // Screencast Mode Settings
  "screencastMode.onlyKeyboardShortcuts": true, // Shows only keyboard shortcuts in Screencast Mode
  "screencastMode.mouseIndicatorColor": "#f1c40f", // Sets the color for the mouse indicator in Screencast Mode
  "screencastMode.verticalOffset": 0, // Sets the vertical offset for Screencast Mode

  // Font Size Settings
  "editor.fontSize": 20, // Sets the font size in the editor
  "chatgpt.lang": "en", // Sets the language to English for the ChatGPT extension
  "editor.mouseWheelZoom": true, // Enables zooming with the mouse wheel in the editor
  "terminal.integrated.mouseWheelZoom": true, // Enables zooming with the mouse wheel in the terminal
  "terminal.integrated.fontSize": 17, // Sets the font size for the terminal

  // CSS Linting Settings
  "css.lint.unknownAtRules": "ignore", // Ignores unknown at-rules in CSS linting

  // Editor Suggestions
  "editor.quickSuggestions": {
    "strings": "on", // Enables quick suggestions for strings
    "comments": "on" // Enables quick suggestions for comments
  },

  // Language-Specific Formatter Settings
  "[cpp]": {
    "editor.defaultFormatter": "ms-vscode.cpptools" // Sets the default formatter for C++ to MS VSCode C++ Tools
  },

  // Workbench Theme Settings
  "workbench.colorTheme": "Dark Chai", // Sets the workbench color theme to Dark Chai
  "workbench.quickOpen.preserveInput": true, // Preserves input in Quick Open
  "workbench.editor.enablePreviewFromQuickOpen": true, // Enables preview when opening files from Quick Open

  // Emmet Settings
  "emmet.useInlineCompletions": true, // Enables inline completions for Emmet

  // Quick Open Settings
  "workbench.quickOpen.closeOnFocusLost": false, // Keeps Quick Open open when it loses focus

  // Inline Suggestions
  "editor.inlineSuggest.enabled": true, // Enables inline suggestions in the editor
  "editor.suggest.showInlineDetails": true, // Shows inline details in suggestions
  "editor.minimap.autohide": true // Automatically hides the minimap when not in use
}



```

## 🎨 VS Code Themes
- Andromeda 👈
- Dracula Official
- Night Owl
- Shades of Purple
- SynthWave '84
- Ayu (Theme)

## 🔑 VS Code Keyboard Shortcuts 

| Keyboard Shortcuts | Windows / Linux     | Mac   |
| :-------- | :------- | :-------------------------------- |
|  HTML boilerplate  |  ! + TAB | ! + TAB |
|  Open the palette to search for a file  | Ctrl + P | cmd + P |
|  Add cursors to all matching selections  | Ctrl + Shift + L  | cmd + Shift + L |
|  Undo  |  Ctrl + U | cmd + U |
|  Select Current Line  | Ctrl + L | cmd + L |
|  Zen Mode  | Ctrl + K Z | cmd + K Z |
|  Toggle Sidebar  | Ctrl + B | cmd + B |
|  Search Global Files  | Ctrl + Shift + F | Ctrl + Shift + F |
|  Search on file  | Ctrl + F | cmd + F |
|  Find and Replace  | Ctrl + H | cmd + H |
|  Delete the previous Word  | Ctrl + Backspace | cmd + Backspace |
|  Move line up/Down  | Alt + up/down arrow | option + up/down arrow |
|  Add multiple cursors  | Ctrl + Alt +up/down arrow | cmd + option + up/down arrow |
|  Comment Line  | Ctrl + / | cmd + / |
|  Comment Line  | Ctrl + K + Ctrl + C | cmd + K + cmd + C |
|  Split View  | Ctrl + \  | cmd + \ |
|  Switch Between views |  Ctrl +1, Ctrl + 2 .. | cmd + 1, cmd + 2 |
|  Duplicate Line  | Alt + Shift + up/down | option + Shift + up/down |
|  Navigate to a specific line  | Ctrl + g | cmd + G |
|  Open Terminal | Ctrl + ` | cmd + ` |
|  To Show suggestion | Ctrl + Space | cmd + space |
|  To Close a TAB | Ctrl + W | cmd + W |
|  To Close all TAB | Ctrl + Shift + W | cmd + Shift + W |


## 🔑 VS Code Keybindings
```
// Place your key bindings in this file to override the defaultsauto[]
[
  {
    "key": "f1 f2",
    "command": "code-runner.run"
  },
  {
    "key": "ctrl+alt+n",
    "command": "-code-runner.run"
  },
  {
    "key": "ctrl+e",
    "command": "editor.action.commentLine",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "f3 f4",
    "command": "workbench.action.terminal.clear"
  },
  {
    "key": "f2 f3",
    "command": "extension.liveServer.goOnline",
    "when": "editorTextFocus"
  },
  {
    "key": "f5 f6",
    "command": "workbench.action.terminal.moveToTerminalPanel"
  },
  {
    "key": "shift+up",
    "command": "editor.action.insertCursorAbove",
    "when": "editorTextFocus"
  },
  {
    "key": "shift+down",
    "command": "editor.action.insertCursorBelow",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+alt+win+n",
    "command": "-welcome.showNewFileEntries"
  },
  {
    "key": "ctrl+n",
    "command": "explorer.newFile"
  }
]

```


## ✒ Font Info
- [Fira Code](https://fonts.google.com/specimen/Fira+Code)
- [Operator Mono](https://www.typography.com/fonts/operator/styles)

## 🧑‍💻 Contributor
 [Muhaiminul Islam]
