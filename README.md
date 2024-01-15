## Installation extensions

Two different extensions to choose from:

- extensions-light (lighter verion more suitable for work env)
- extensions-full (all extensions, more suitable for private env)

### PowerShell

`Get-Content extensions-light.txt | ForEach-Object { code --install-extension $_ }`
or
`Get-Content extensions-full.txt | ForEach-Object { code --install-extension $_ }`

### Bash

`cat extensions-light.txt | xargs -L 1 code --install-extension`
or
`cat extensions-full.txt | xargs -L 1 code --install-extension`

## Installation settings and keybindings

Copy settings.json and keybindings.json and place in the user directory of vscode
