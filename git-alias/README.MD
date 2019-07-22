### Git Alias

In this directory I put my own git alias that I use it every day, it's really simplified my git uses.

### How to use
1. MacOS
	Just like Linux, open the file: `~/.bash_profile`(touch it if not exist!), and copy the alias to it, then run: `source ~/.bash_profile`, then you can try it instantly.
	
	FYI, git for Mac version already provide many useful alias in the .gitconfig, for example:
```
git l => 
	log --graph --all --pretty=format:'%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset'
```
so combined with built-in alias, you can build your own alias.

2. Windows
	Run the Git Bash, and open file:  `~/.bashrc`(as the always, touch it if not exist), then copy the alais to it, at the last, run `source ~/.bashrc`.
	
	Git for Windows dose not provide built-in alias in .gitconfig like Mac, but you can also build it by your own.
