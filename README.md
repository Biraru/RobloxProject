# Template For My Roblox Projects

This repository can be forked for making a new Roblox project, it contains all the development tools required for linting, syncing, etc.


## Development Setup
### Requirements

- Roblox Studio
- Git
- NPM
    - Azul Sync
- Rokit
    - Selene
    - StyLua

### Setup

1. Fork & clone the repository
2. Install Azul via NPM:
    ```ps1
    npm install azul-sync -g
    ```
3. Install tools via rokit:
    ```ps1
    rokit install
    ```
3. Open Roblox Studio
4. Connect Azul Roblox Sync in Roblox Studio with the Azul Domain:
    ```ps1
    azul
    ```
5. Start developing!

## Linting

You can run the .bat files provided to lint from either Selene or StyLua:

### Selene:
```ps1
lint-selene.bat
```

### StyLua:
```ps1
lint-stylua.bat
```

## StyLua (Check mode):
```ps1
lint-stylua-check.bat
```
