What learned:
Expansions:
	arithmetic expansions $((exp)), can do multiple expressions, ** is ^
	{1..5} prints digits 1 through 5
	Parameter expansion echo $USER
	command substitution echo $(ls)
double quotes: show everything except $, \, and double quotes
single quotes have no exceptions
/etc/profile contains settings, sets variables
/etc/profile.d dir that contains settings for various programs
/etc/bashrc contains settings for various shells
~/.bashrc where you put those settings, which run when you launch terminal
backticks are used to complete a command before

Shell Variables
Local variables and global variables
printenv shows global and set shows local
4 types of those variables integers, strings. arrays, constant
varname="value"
export used to update or export
unset used to remove
Reserved shell variables
HOME shows current users home directory
PATH list of directories that shell looks for commands
PS1 shows name and other stuff you see when you type in terminal
special parameters $? shows last pipeline output

printenv
set
unset
alias
unalias
printf
export
source
change
