### Install Visual Studio Code

[https://code.visualstudio.com](https://code.visualstudio.com/)

### Install Extensions

- VSCodeVim
- Prettier - Code formatter

### Copy User Settings

```bash
mkdir -p ~/Library/Application\ Support/Code/User
cp settings.json ~/Library/Application\ Support/Code/User
```

### Enable Vim Key Repeat

```bash
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```
