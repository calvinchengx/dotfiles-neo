# dotfiles

Easy-to-setup and properly documented dotfiles

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

ln -s ~/dotfiles-neo/.zprofile ~/.zprofile
ln -s ~/dotfiles-neo/.zshrc ~/.zshrc
```