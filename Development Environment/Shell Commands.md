>> The terminal

● terminology

> GUI = graphical user interface
> CLI = command line interface - command line
		
>> terminal = text input/output environment; console = physical terminal
	
> unix / linux / mac
		○ shell / bash / terminal
	
> windows
		○ command prompt / windows command / cmd / dos prompt

>> Shell / bash commands I

● shell / bash commands\
	> pwd\
	> ls\
	> ls -la\
	>> permissions\
		● owner, group, world\
		● r, w, x\
		● 4, 2, 1\
d = directory\
rwxrwxrwx = owner, group, world\
	> cd\
	> cd ../\
	> mkdir\
	> touch\
		■ touch temp.txt\
	> nano temp.txt\
	> cat temp.txt\
	> clear\
		■ command + k\
		■ clear\
	> chmod\
		■ chmod options permissions filename\
		■ chmod 777 temp.txt\
	> env\
	> rm <file or folder name>\
		■ rm -rf <file or folder name>\
	> .bash_profile & .bashrc\
		■ .bash_profile is executed for login shells, while .bashrc is executed for interactive non-login shells. When you login (type username and password) via console, either sitting at the machine, or remotely via ssh: .bash_profile is executed to configure your shell before the initial command prompt.\
	> grep\
		■ cat temp2.txt | grep enter\
		■ ls | grep -i documents\
