## Bash auto completion script for Liberty Profile `server` command

### Installation

1. Download the *server* Bash auto completion script.
2. Move the script into */etc/bash_completion.d/* directory.

### Usage

To list all supported *server* command actions:
* `$ ./bin/server [TAB][TAB]` (list all actions)
* `$ ./bin/server c[TAB][TAB]` (complete to 'create')
 
 
To list all server instances (for all actions except 'create', 'version', and 'help'):
* `$ ./bin/server start[TAB][TAB]` (lists all available server instances)
* `$ ./bin/server start de[TAB][TAB]` (complete to 'defaultServer' instance)
 
