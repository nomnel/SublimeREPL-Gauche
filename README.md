# Scheme REPL with SublimeREPL
This config file adds Scheme(Gauche, MIT-Scheme) REPL to SublimeREPL. And also, you can add other Scheme Implementations.

## Installation
**In advance**, you have to install [SublimeREPL](https://github.com/wuub/SublimeREPL).

1. Clone git repo into your SublimeREPL/config folder (in ST2, see menu(Sublime Text 2 -> Preferences -> Browse Packages…) to find SublimeREPL folder)
2. Rename SublimeREPL-Scheme to Scheme

that is,

	# at /PATH/TO/Package/SublimeREPL/config/
	$ git clone https://github.com/nomnel/SublimeREPL-Scheme Scheme

## Add other Scheme Implementations
See `Main.sublime-menu` and append preference list. Regularly, copy&paste MIT-Scheme's and fix caption, id, and cmd preferences.