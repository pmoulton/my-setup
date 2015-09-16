### My OS X Terminal Setup
### Version
1.0

**Install iTerm2.**

[Download here](https://www.iterm2.com/downloads.html)

**Add shortcuts for skipping words**

Press option arrow to skip by word in terminal.
```
Keyboard Shortcut: ⌥←
Action: Send Escape Sequence
Esc+: b
```
```
Keyboard Shortcut: ⌥→
Action: Send Escape Sequence
Esc+: f
```

**Install Sublime Text**

Download from [here](https://www.sublimetext.com/3).


**Setup st command**
```
ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/sublime
```
Now you can open files with the sublime command in a terminal.

**Setup Git Aliases**
```
[alias]
	st = status
	co = checkout
	cob = checkout -b
	lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
```

**Install oh-my-zsh**

Download oh-my-zsh from [here](https://github.com/robbyrussell/oh-my-zsh) and set it as your default shell.

Choose the agnoster theme.

edit ~/.zshrc and add the line:
```
ZSH_THEME='agnoster'
```

**Install the patched monaco powerline font**

Download it from [here](https://gist.github.com/baopham/1838072).

**Install a color scheme**
Choose solarized light or solarized dark.


