# cybensis-zsh-theme
<p align="center">
    <img src="./theme.gif" height="300px">
</p>

An oh-my-zsh theme based on the standard af-magic theme but with a pastel colour scheme. Plugins include git, autosuggestions and syntax highlighting.

&nbsp;

## How to install
1. Install zsh with your OS's package manager
```sh
sudo apt-get install zsh
```
2. Install oh-my-zsh
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
3. Download the required plugins
```sh
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```
4. Download this repo and move the files into their required places
```sh
git clone https://github.com/cybensis/cybensis-zsh-theme
cd cybensis-zsh-theme
mv .zshrc ~/.zshrc
mv ./cybensis.zsh-theme ~/.oh-my-zsh/themes/cybensis.zsh-theme
```
  
