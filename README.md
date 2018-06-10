### Install Visual Studio Code

[https://code.visualstudio.com](https://code.visualstudio.com/)

### Add To Path

```bash
echo "source ~/GitHub/rkiel/vscode-setup/vs-code.bash" >> ~/GitHub/rkiel/osx-setup/dotfiles/bash_profile
```

### Install Extensions

Prettier

```bash
code --install-extension esbenp.prettier-vscode
```

Vim

```bash
code --install-extension vscodevim.vim
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
