# VS CODE SETTINGS

My personal settings for VS Code

### THEMES

- Cobalt2 <a href="https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2">Official Extension Page</a>
- Debri Next <a href="https://marketplace.visualstudio.com/items?itemName=sldobri.bunker">Official Extension Page</a>
- Gruvbox <a href="https://marketplace.visualstudio.com/items?itemName=jdinhlife.gruvbox">Official Extension Page</a>
- Just Black <a href="https://marketplace.visualstudio.com/items?itemName=nur.just-black">Official Extension Page</a>
- Signed Dark Pro <a href="https://marketplace.visualstudio.com/items?itemName=51gn3d.signed-dark-pro">Official Extension Page</a>
- Spotify Color Theme <a href="https://marketplace.visualstudio.com/items?itemName=oguhpereira.spotify-color-theme">Official Extension Page</a>
- GitHub Theme <a href="https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme">Official Extension Page</a>

### EXTENSIONS

- advanced-new-file <a href="https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file">Official Extension Page</a>
- Auto Rename Tag <a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag">Official Extension Page</a>
- Bracket Pair Colorizer <a href="https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer">Official Extension Page</a>
- C/C++ <a href="https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools">Official Extension Page</a>
- EsLint <a href="https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint">Official Extension Page</a>
- GitLens <a href="https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens">Official Extension Page</a>
- Jupyter <a href="https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter">Official Extension Page</a>
- Live Server <a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer">Offcial Extension Page</a>
- Prettier <a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode">Official Extension Page</a>
- Python <a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python">Official Extension Page</a>
- Quokka.js <a href="https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode">Official Extension Page</a>
- Spanish Language Pack <a href="https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-es">Official Extension Page</a>
- TODO HightLight <a href="https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight">Official Extension Page</a>

### FONT AND ICONS

- Cascadia Code <a href="https://github.com/microsoft/cascadia-code">Official Github Repo</a>
  - Font Ligatures: true
  - Font Size: 14
- Material Icon Theme <a href="https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme">Official Extension Page</a>

### OTHER

- Cursor Style: line
- Cursor Blinking: expand

### JSON FILE

<code>
{
  "terminal.integrated.rendererType": "dom",
  "workbench.statusBar.visible": true,
  "workbench.iconTheme": "material-icon-theme",
  "explorer.confirmDelete": false,
  "window.zoomLevel": 1,
  "editor.wordWrap": "on",
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "C_Cpp.updateChannel": "Insiders",
  "liveServer.settings.donotVerifyTags": true,
  "workbench.startupEditor": "none",
  "liveServer.settings.donotShowInfoMsg": true,
  "editor.linkedEditing": true,
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "eslint.alwaysShowStatus": true,
  "window.autoDetectColorScheme": true,
  "workbench.colorTheme": "GitHub Dark",
  "editor.fontFamily": "'cascadia code'",
  "window.menuBarVisibility": "toggle",
  "editor.accessibilitySupport": "off",
  "tabnine.experimentalAutoImports": true,
  "editor.formatOnSave": true,
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
  "python.showStartPage": false,
  "editor.fontLigatures": true,
  "window.title": "${dirty}${activeEditorShort}${separator}${rootName}",
  "window.newWindowDimensions": "maximized",
  "editor.cursorBlinking": "expand",
  "workbench.preferredDarkColorTheme": "Spotify",
  "editor.minimap.enabled": false
}
</code>

#### KEY BINDINGS

<code>
[
  {
    "key": "ctrl+n",
    "command": "extension.advancedNewFile"
  },
  {
    "key": "ctrl+alt+n",
    "command": "-extension.advancedNewFile"
  },
  {
    "key": "ctrl+shift+o",
    "command": "workbench.action.files.openFolder"
  },
  {
    "key": "ctrl+k ctrl+o",
    "command": "-workbench.action.files.openFolder"
  },
  {
    "key": "ctrl+alt+s",
    "command": "workbench.action.gotoSymbol"
  },
  {
    "key": "ctrl+shift+o",
    "command": "-workbench.action.gotoSymbol"
  }
]
</code>
