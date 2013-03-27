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
	
	