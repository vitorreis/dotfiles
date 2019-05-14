# dotfiles
.bashrc
```
. ~/dotfiles/bashrc
```

.bash_profile
```
if [ -f ~/.bashrc ];
then
	source ~/.bashrc
fi
```

Or if using zsh

[Install zsh and oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
[Install powerline font](https://github.com/powerline/fonts)
````
vi ~/.zshrc


ZSH_THEME="agnoster"
...
# at the end of the file source the zshrc from the repo
. ~/workspace/dotfiles/zshrc
# and optionally your secrets
. ~/workspace/dotfiles/secret
```

Iterm2 config:
Font: Meslo LG M DZ Regular
Color Preset: solarized dark

Restore the git config
````
cp git/.gitconfig ~
```