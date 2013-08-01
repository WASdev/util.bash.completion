## Bash auto completion scripts for Liberty profile server

###Auto completion script for *server* command

#### Installation

1. Download the *[server](https://raw.github.com/WASdev/util.bash.completion/master/server)* Bash auto completion script.
2. On Ubuntu/Debian, move the script into */etc/bash_completion.d/* directory. On Windows/Cygwin, ensure the `bash-completion` package is installed first.


#### Usage

To list all supported *server* command actions:
* `$ ./bin/server [TAB][TAB]` - list all actions
* `$ ./bin/server c[TAB][TAB]` - complete to 'create' action
 
 
To list all server instances (for all actions except 'create', 'version', and 'help'):
* `$ ./bin/server start[TAB][TAB]` - list all available server instances
* `$ ./bin/server start de[TAB][TAB]` - complete to 'defaultServer' instance (if it is there)

