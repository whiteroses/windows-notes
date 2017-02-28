# Windows notes wiki

## To do
* cmd/?
* cmd.exe environment variable substitution? `%%`?
* cmd.exe quotes and escapes?
* SET /A and /P?
* FTYPE?
* SC?
* TASKLIST?
* Command extensions?
* https://ss64.com/
	Command-line and PowerShell reference?


## Command prompt

`HELP`

* List of commands


`HELP [COMMAND]`
`[COMMAND] /?`

* Help


`echo [{on|off}] [message]`

* Display messages, or turn command-echoing on or off.
* Use command without parameters to display current echo setting.
* To prevent echoing of a line in batch program: `@` in front of a command.
* To echo a blank line: `echo.`
* To display pipe `|` or redirection `<` `>` characters with echo, use caret
  `^` to escape. Two carets to escape caret.


`SET [variable=[string]]`

* Display, set, or remove cmd.exe environment variables.
* Without parameters: display the current environment variables.


## Services

* Windows Administrative Tools
* Services
* Task Scheduler
* Task Manager (with Services tab)
* Credential Manager?


### sc

Command line program for communicating with the Service Control Manager and
services.


### Development

[Development](development.md)


### Hosts file

c:\Windows\System32\Drivers\etc\hosts
