# My nodejs dev env vimrc for Mac and Win

## Install jshint
	
	npm install jshint -g

## Mac

	cd ~/
	git clone git://github.com/shichao/vimrc_nodejs.git
	ln -s vimrc_nodejs .vim
	ln -s vimrc_nodejs/vimrc .vimrc
	ln -s vimrc_nodejs/jslintrc .jslintrc
	ln -s vimrc_nodejs/jshintrc .jshintrc
	cd vimrc_nodejs
	git submodule init
	git submodule update
