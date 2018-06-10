### Install Visual Studio Code

[https://code.visualstudio.com](https://code.visualstudio.com/)

### Add To Path

```bash
echo "source ~/GitHub/rkiel/vscode-starter/vs-code.bash" >> ~/GitHub/rkiel/osx-setup/dotfiles/bash_profile
```

### Install Extensions

```bash
code --install-extensions esbenp.prettier-vscode
code --install-extensions vscodevim.vim
```

### Copy User Settings

```bash
mkdir -p ~/Library/Application\ Support/Code/User
cp settings.json ~/Library/Application\ Support/Code/User
```

### Enable Vim Key Repeat

```bash
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```
