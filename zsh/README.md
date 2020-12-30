# ZSH

Oh My ZSH:

sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

For Zsh (using Oh My Zsh) add the following plugins for a great prompt:

```
plugins=(
	docker
	git-prompt
	zsh-navigation-tools
	zsh-autosuggestions
	zsh-syntax-highlighting
	zsh-z
)
```

Some of these plugins are located in: https://github.com/zsh-users and must be
installed separately.

```
git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

# Oh My ZSH

Run `export ZSH_COMPDUMP="$ZSH/cache/.zcompdump"` before Oh My ZSH to change cache file directory.

Powerlevel10k ZSH Theme

```
brew install romkatv/powerlevel10k/powerlevel10k
echo 'source /usr/local/opt/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```

Z

```
git clone https://github.com/agkozak/zsh-z "${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-z"
```
