## Bash auto completion scripts for Liberty profile server

###Auto completion script for *server* command

#### Installation

1. Download the *[server](https://raw.github.com/WASdev/util.bash.completion/master/server)* Bash auto completion script.
2. On Ubuntu/Debian, move the script into */etc/bash_completion.d/* directory. On Windows with Cygwin, ensure the `bash-completion` package is installed first.
3. Open a new terminal (or Cygwin) window for the new auto completion script to be loaded.

#### Usage

To list all supported *server* command actions:
* `$ ./bin/server [TAB][TAB]` - list all actions
* `$ ./bin/server c[TAB][TAB]` - complete to 'create' action
 
 
To list all server instances (for all actions except 'create', 'version', and 'help'):
* `$ ./bin/server start[TAB][TAB]` - list all available server instances
* `$ ./bin/server start de[TAB][TAB]` - complete to 'defaultServer' instance (if it is there)

###Auto completion script for *batchManager* command

#### Installation

1. Download the *[batchManager](https://raw.github.com/WASdev/util.bash.completion/master/batchManager)* Bash auto completion script.
2. Follow previous installation instructions

#### Usage

To list all supported *batchManager* command actions:
* `$ ./bin/batchManager [TAB][TAB]` - list all actions
* `$ ./bin/batchManager su[TAB][TAB]` - complete to 'submit' action
 
 
To list help for all batchManager commands:
* `$ ./bin/batchManager help [TAB][TAB]` - list all actions
* `$ ./bin/batchManager help su[TAB][TAB]` - list help for 'submit' action

