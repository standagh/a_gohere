# a_gohere
Tool to bookmark locations in linux cmd line

Set alias:

`alias a='. /usr/local/bin/a'`

Export env variable:

`export A_CONFIG=/etc/a.config`

File /etc/a.config has to be readable.

## Usage

`a xa name`

add local directory to $A_CONFIG file with key `name`.

`a name`

jump to location saved in $A_CONFIG file with key `name`
