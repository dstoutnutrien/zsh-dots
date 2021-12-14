# Just 2 dotfiles

if you want a prompt in the zshrc, add one. You can append a 

```shell
eval $(starship init zsh)


```

and use the starship.toml if that's something you'd like. It looks like this:

```┌╼ ZSH dots   main 
┌╼ ZSH dots   main 
└──╼ >>> 
```

You'll need to install 

- zsh-syntax-highlighting
- zsh-history-substring-search
- zsh-autosuggestions

Note: the starship prompt requires nerd-fonts... and starship. https://starship.rs/guide/#%F0%9F%9A%80-installation


to install all dependencies, run ```brew install font-blex-mono-nerd-font font-fira-mono-nerd-font font-hack-nerd-font starship zsh-autosuggestions zsh-history-substring-search zsh-syntax-highlighting fzf exa```