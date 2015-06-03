npm-g_nosudo
============

A shell script which will fix the problem where you want to stop using sudo for npm -g on Ubuntu.

Inspired by a day trying to sort various machines out on our system to run code nicely.

and this [Stackoverflow answer](http://stackoverflow.com/a/13021677)

Tested on Ubuntu 14.04 and Mac OS 10.10.3 with Bash

##Usage:

Download the script, run it:

./npm-g-nosudo.sh 

It will give you the option to fix your .bashrc .zshrc .profile file(s) automatically to use the settings from [Sindre Sorhus' Guide](https://github.com/sindresorhus/guides/blob/master/npm-global-without-sudo.md)

If you say "n", it will print the variables you need to enable you to fix manually.

If you say "y", you will need to source your corresponding file for your current environment vars to be updated.

## License

MIT © [Glen Pike](http://glenpike.co.uk)
