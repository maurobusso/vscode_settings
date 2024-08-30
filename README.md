
### This is a list of the extensions I use on my IDE.

```
esbenp.prettier-vscode
streetsidesoftware.code-spell-checker
vscode-icons-team.vscode-icons
bradlc.vscode-tailwindcss
styled-components.vscode-styled-components
dbaeumer.vscode-eslint
ms-python.python
ms-python.debugpy
```

For Bash (on Linux/macOS)
run `xargs -I % code --install-extension % < extensions_list_file`

### These is the list of personazied settings 

```
{
  "breadcrumbs.enabled": false,
  "editor.formatOnSave": true,
  "workbench.preferredHighContrastColorTheme": "Default High Contrast",
  "workbench.iconTheme": "vs-seti",
  "editor.linkedEditing": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.wordWrap": "on",
  "editor.minimap.enabled": false,
  "explorer.confirmDelete": false,
  "explorer.compactFolders": false,
  "editor.codeActionsOnSave": {
    "source.organizeImports": "explicit"
  },
  "workbench.colorCustomizations": {
    "titleBar.activeBackground": "#64570b"
  },
  "files.trimTrailingWhitespace": true,
  "terminal.integrated.fontSize": 12,
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.fontWeight": "normal",
  "terminal.integrated.drawBoldTextInBrightColors": false,
  "workbench.sideBar.location": "left"
}
```
