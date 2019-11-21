# metalmajor-zsh-theme

# How to install

Install on linux or macos zsh with `brew install zsh` or `apt install zsh`

Change your default shell:
```
chsh -s $(which zsh)
```

Then install this for the full experience, and select Y for all:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

Download this theme:
```
git clone https://github.com/deblauwetom/metalmajor-zsh-theme ~/.oh-my-zsh/custom/themes/metalmajor
```

Edit the config file to select this awesome theme:
```
ZSH_THEME=“metalmajor/metalmajor” in $HOME/.zshrc
```

Re-login or type zsh to see it in action.

Things to try:
- CTRL-R to see awesome reverse search. 
- CTRL-T will find a file in the current directory and below.
- cd <TAB><TAB> and using arrows you can select an entry
  
