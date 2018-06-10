### Install Visual Studio Code

[https://code.visualstudio.com](https://code.visualstudio.com/)

### Clone Repository

```bash
mkdir -p ~/GitHub/rkiel && $_
git clone https://github.com/rkiel/vscode-setup.git
```

### Add To Path

```bash
echo "source ~/GitHub/rkiel/vscode-setup/vs-code.bash" >> ~/GitHub/rkiel/osx-setup/dotfiles/bash_profile
```

Test the update. You may have to open a new shell window.

```bash
code --help
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
cd ~/Library/Application\ Support/Code/User
ln -nfs ~/GitHub/rkiel/vscode-setup/settings.json .
```

### Enable Vim Key Repeat

```bash
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```
