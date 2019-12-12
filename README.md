# metalmajor-zsh-theme

## Features

- Show the time next to every command
- After a command was run, shows the exit code if it was not 0
- Shows the full directory in the prompt so you can easily copy-paste it
- If inside a git repo, shows the branch name, and status
- Keeps the info on one line, and on the left side, because that is where I am always looking


## Preview

![Alt text](/metalmajor-zsh-theme-screenshot.png?raw=true "metalmajor-zsh-screenshot")

A screen recording you can download: https://drive.google.com/open?id=1uBJv8QZ_MnhEgxFM130kwaxKDYUVjKaP


## How to install

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
- For command argument completion, press TAB twice and then using the arrows you can select an entry.
- To cd into a previous directory, type "cd -" and then TAB.  


## License

MIT License
