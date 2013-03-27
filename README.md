dotfiles
========

Some dot files I use regularly

Put this in your .bash_profile/.bashrc:
	
	source ~/.ps1colors
	source ~/.aliases
	source ~/.git-completion.sh
	source ~/.git-flow-completion.sh
	source ~/.bash_prompt
	
And install the excellent [vcprompt](https://github.com/djl/vcprompt "vcprompt github repo") 
tool in bin/macosx:

	sudo cp bin/macosx/vcprompt /usr/local/bin
	
	
Put it all together and you get a prompt like this:

![bash prompt screenshot](https://dl.dropbox.com/s/uunh2paq41ze7x9/bash-prompt-screenshot.png "bash prompt screenshot (iTerm2)")