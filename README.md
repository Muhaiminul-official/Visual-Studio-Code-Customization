# Visual Studio Code Customization

## 📝 Why?
I've been a loyal user of Visual Studio Code, and it has become my preferred code editor. Its speed and flexibility make it a reliable choice for me, regardless of the operating system I'm using.I've made various customizations to tailor it to my preferences.

I've tweaked its appearance, added and modified features, installed extensions, and even created a personalized theme because I haven't found a theme that's absolutely perfect for me. Each time I set up a new work environment, I find myself manually configuring these settings. To streamline this process, I've uploaded all my settings here, so I can quickly apply them. Feel free to use any of them for your convenience.

## 🛠 VS Code Settings
```bash
{
  // ============================
  // Editor & Font Settings
  // ============================
  "editor.fontFamily": "Operator Mono Lig, Fira code",
  "editor.fontSize": 20,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "expand",
  "editor.mouseWheelZoom": true,
  "editor.autoClosingBrackets": "always",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeLensFontSize": 12,
  "editor.rename.enablePreview": false,
  "editor.quickSuggestions": {
    "strings": "on",
    "comments": "on"
  },
  "editor.inlineSuggest.enabled": true,
  "editor.suggest.showInlineDetails": true,
  "editor.guides.bracketPairs": true,
  "editor.guides.bracketPairsHorizontal": true,
  "editor.minimap.autohide": "mouseover",
  "editor.minimap.sectionHeaderFontSize": 15,

  // ============================
  // Formatting & Code Style
  // ============================
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "prettier.proseWrap": "always",
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",

  // Language-Specific Formatting
  "[cpp]": { "editor.defaultFormatter": "ms-vscode.cpptools" },
  "[java]": { "editor.defaultFormatter": "redhat.java" },
  "[c]": { "editor.defaultFormatter": "ms-vscode.cpptools" },

  // ============================
  // Code Runner Settings
  // ============================
  "code-runner.saveAllFilesBeforeRun": true,
  "code-runner.runInTerminal": true,

  // ============================
  // Terminal Settings
  // ============================
  "terminal.integrated.defaultLocation": "editor",
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.mouseWheelZoom": true,
  "terminal.integrated.fontSize": 20,

  // ============================
  // Auto Save Settings
  // ============================
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 500,

  // ============================
  // UI Customization
  // ============================
  "workbench.colorCustomizations": {
    "editorGroupHeader.tabsBackground": "#0a0a1b",
    "activityBar.background": "#0b0b12",
    "activityBar.foreground": "#3df5ae",
    "activityBar.inactiveForeground": "#637067",
    "sideBar.background": "#0b0b0b",

    "sideBar.foreground": "#ffffff",
    "editor.selectionHighlightBorder": "#ffffff",
    "editor.lineHighlightBackground": "#ffffff20",
    "editor.background": "#0c0c0c",
    "minimap.background": "#131315",
    "menu.background": "#0d1732",
    "menu.foreground": "#ffffff",
    "tab.activeBackground": "#312656",
    "tab.inactiveBackground": "#070712",
    "terminal.border": "#2c2c54",
    "terminal.background": "#0d0d0e",
    "statusBar.background": "#151518",
    "statusBar.foreground": "#f8f8f8",
    "scrollbarSlider.background": "#3e3e45",
    "scrollbarSlider.hoverBackground": "#a4a4b6"
  },
  "editor.tokenColorCustomizations": {
    "comments": "#94909d"
  },
  "workbench.iconTheme": "material-icon-theme",
  "window.zoomLevel": 0.3,

  // ============================
  // Git & Version Control
  // ============================
  "git.autofetch": true,

  // ============================
  // Extensions Settings
  // ============================

  // Codeium AI Settings
  "codeium.enableConfig": {
    "*": true,
    "markdown": true,
    "properties": true
  },
  "codeium.aggressiveShutdown": true,
  "codeium.enableAutoTrigger": true,
  "codeium.enableSupercomplete": true,
  "codeium.enableSupercompleteCommit": true,
  "codeium.enableSupercompletePreview": true,
  "codeium.enableSupercompleteSuggest": true,
  "codeium.enableSupercompleteTrigger": true,
  "codeium.enableTrigger": true,
  "codeium.enableTriggerSuggest": true,
  "codeium.showStatusBarItem": true,
  "codeium.disableSupercomplete": true,

  // GitHub Copilot Settings
  "github.copilot.enable": {
    "*": false,
    "plaintext": false,
    "markdown": false,
    "scminput": false
  },

  // Codegeex AI Settings
  "Codegeex.Privacy": true,
  "Codegeex.CompletionDelay": 0.3,
  "Codegeex.SidebarUI.LanguagePreference": "English",
  "Codegeex.GenerationPreference": "automatic",
  "Codegeex.DisabledFor": { "": true },
  "Codegeex.EnableExtension": false,

  // Live Server & Sass Compiler
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

  // ============================
  // Miscellaneous Settings
  // ============================
  "security.workspace.trust.untrustedFiles": "open",
  "redhat.telemetry.enabled": true,
  "php.validate.executablePath": "",
  "cmake.options.statusBarVisibility": "visible",
  "editor.linkedEditing": true,

  // Screencast Mode (For Recording Tutorials)
  "screencastMode.onlyKeyboardShortcuts": true,
  "screencastMode.mouseIndicatorColor": "#139616",
  "screencastMode.verticalOffset": 0,

  // Quick Open Settings
  "workbench.quickOpen.preserveInput": true,
  "workbench.editor.enablePreviewFromQuickOpen": true,
  "workbench.quickOpen.closeOnFocusLost": false,

  // Emmet & Code Editing
  "emmet.useInlineCompletions": true,

  // CSS & Linting
  "css.lint.unknownAtRules": "ignore",

  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "codeium.enableCodeLens": false,
  "terminal.integrated.fontFamily": "Operator Mono Lig, Fira Code"
}


```

## ⚙️ VS Code Extension

-   Auto Close Tag (Jun Han)
-   Auto Import - ES6, TS, JSX, TSX (Sergey Korenuk)
-   Auto Rename Tag (Jun Han)
-   Bootstrap 5 Snippets (HansUXdev)
-   C/C++ (Microsoft)
-   C/C++ Compile Run (danielpinto8zz6)
-   C/C++ Runner (franneck94)
-   CMake Tools (Microsoft)
-   Code Runner (Jun Han/formulahendry)
-   Codeium (Codeium)
-   Debugger for Chrome
-   Debugpy (Microsoft)
-   ES7 React/JS Snippets (rodrigovallades, dsznajder, woodreamz, naqvi)
-   ESLint (Microsoft)
-   Express Snippets (Express Snippets)
-   Gradle (Microsoft)
-   HTML CSS Support (ecmel)
-   indent-rainbow (oderwat)
-   IntelliCode API Usage Examples (Microsoft)
-   Java Debugger (Microsoft)
-   Java Dependency (Microsoft)
-   Java Test (Microsoft)
-   JavaScript (ES6) code snippets (charalampos karypidis/xabikos)
-   JS Debug Nightly (Microsoft)
-   JS/JSX Snippets (skyran)
-   JS Snippets (runningcoder)
-   Live Sass Compiler (Glenn Marks)
-   Live Server (Ritwick Dey)
-   Material Icon Theme (Philipp Kief)
-   Maven (Microsoft)
-   MongoDB for VS Code (MongoDB)
-   Node.js Snippets (Chris Noring)
-   npm Intellisense (Christian Kohler)
-   Path Intellisense (Christian Kohler)
-   PDF (tomoki1207)
-   PHP Debug (Xdebug)
-   Postman (Postman)
-   Prettier - Code formatter (Prettier)
-   Python (Microsoft)
-   React Native/React Redux snippets (EQuimper)
-   Reactjs code snippets (charalampos karypidis)
-   Simple React Snippets (Burke Holland)
-   Snipped (Jefferson Licet)
-   Socket.IO VSCode (litleleprikon)
-   Stylelint (Stylelint)
-   Tailwind CSS IntelliSense (Tailwind Labs)
-   VS Code IntelliCode (Microsoft)
-   VS Code Java Pack (Microsoft)
-   VSCode Express (Compulim)
-   VSCode React Refactor (planbcoding)
-   vscode-lldb (Vadim Chugunov)
-   WordPress Snippets (wpprotools.io)


## 🎨 VS Code Themes
- Chai aur Code
- Dracula Official
- Andromeda 👈
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
// Place your key bindings in this file to override the defaultsautomatically.
[
  // ============================
  // Code Runner Shortcuts
  // ============================
  {
    "key": "f1 f2",
    "command": "code-runner.run"
  },
  {
    "key": "ctrl+alt+n",
    "command": "-code-runner.run"
  },

  // ============================
  // Commenting & Editing
  // ============================
  {
    "key": "ctrl+e",
    "command": "editor.action.commentLine",
    "when": "editorTextFocus && !editorReadonly"
  },

  // ============================
  // Terminal Shortcuts
  // ============================
  {
    "key": "f3 f4",
    "command": "workbench.action.terminal.clear"
  },
  {
    "key": "f5 f6",
    "command": "workbench.action.terminal.moveToTerminalPanel"
  },

  // ============================
  // Live Server Controls
  // ============================
  {
    "key": "f2 f3",
    "command": "extension.liveServer.goOnline",
    "when": "editorTextFocus"
  },

  // ============================
  // Cursor & Navigation
  // ============================
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

  // ============================
  // File Explorer Shortcuts
  // ============================
  {
    "key": "ctrl+n",
    "command": "explorer.newFile"
  },
  {
    "key": "ctrl+alt+n",
    "command": "explorer.newFolder"
  },

  // ============================
  // Codeium AI Shortcuts
  // ============================
  {
    "key": "shift+n",
    "command": "codeium.cancelSnooze"
  },
  {
    "key": "shift+m",
    "command": "codeium.snoozeAutocomplete"
  },
  // ============================
  // Miscellaneous
  // ============================
  {
    "key": "ctrl+alt+win+n",
    "command": "-welcome.showNewFileEntries"
  }
]



```
## 🛠 VS Code Split View
To set up a split view in VS Code for handling input/output operations in Java on Windows, follow these detailed steps for better readability and structure:

### Step-by-Step Guide:

#### Step 1: Open `input.txt` and `output.txt` Files
1. In VS Code, create two files named `input.txt` and `output.txt`.
2. Add your input data in `input.txt` and leave `output.txt` empty initially (this will hold your program’s output).

#### Step 2: Split and Position the Files
1. Open `input.txt` and `output.txt` in the editor.
2. Split the view:
   - Right-click on `input.txt` tab and choose **Split Down**.
   - This will position `input.txt` at the top and `output.txt` at the bottom.
3. Adjust the split view according to your needs.

#### Step 3: Configure the Task
1. Go to the **Terminal** menu and select **Configure Tasks**.
2. Choose **Create tasks.json file from template** → **Others**.
3. Replace the contents of `tasks.json` with the following code:

```json
{
  "version": "2.0.0",
  "tasks": [
    {
      "label": "compile and run",
      "type": "shell",
      "command": "javac ${file} && java ${fileBasenameNoExtension} < input.txt > output.txt",
      "options": {
        "shell": {
          "executable": "cmd.exe",
          "args": ["/c"]
        }
      },
      "group": {
        "kind": "build",
        "isDefault": true
      }
    }
  ]
}
```

#### Step 4: Run the Code
1. Save the `tasks.json` file.
2. Open the Java file you want to compile and run.
3. Use **Ctrl + Shift + B** to run the task.
4. The program will take input from `input.txt` and write the output to `output.txt`.

### Notes:
- Make sure your Java file is in the same directory as `input.txt` and `output.txt`.
- The task will first compile the Java file and then execute it, using the input from `input.txt` and redirecting the output to `output.txt`.

This setup allows you to easily test Java programs that take input and produce output in a structured way.
## ✒ Font Info
- [Fira Code](https://fonts.google.com/specimen/Fira+Code)
- [Operator Mono](https://www.typography.com/fonts/operator/styles)

## 🧑‍💻 Contributor
 [Muhaiminul Islam](https://github.com/muhaiminul-official)
