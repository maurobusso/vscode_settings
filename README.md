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
formulahendry.auto-rename-tag
```

For Bash (on Linux/macOS)
To install all the extension create a .text file with the above list then run this command:
`cat file_name.txt | xargs -L1 code --install-extension`

### This is the list of personalized settings

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

### ZSH plugins to install

```
plugins=(
    git
    web-search
    zsh-syntax-highlighting
    zsh-autosuggestions
)
```

