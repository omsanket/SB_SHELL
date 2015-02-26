# SB_SHELL

	Project 1 features:

	1)Supports execution of  cd command.
	Test Cases:	cd ..
			cd ~
			cd ~/path
			cd path
			cd ../..
			cd /

	2)Supports  execution of binaries interactively.
	Test Cases:	ls
			date
			gdb
			pwd

	3)Supports  execution of scripts with ".sh" extension. An example of script file is kept in rootfs directory.
	Test Case:	path/filename.sh
			./filename.sh

	4)Supports execution of pipelines of binaries.
	Test Cases:	/bin/ls|/bin/grep filename

	5)Support for Set and use PATH and PS1 variables. PS1 output  displays the  input string along with current directory.
	You can set PATH by PATH=PATH:pathname and the PATH gets displayed thereafter.
	Test Case: 	PATH=PATH:/path
	
	6)Implemented all functions from include/stdlib.h .
	7)Implemented system calls using x86-64 Calling Conventions.
	8)Implemented all functions required for string manipulation .
	9)Implemented printf and scanf with basic support for %d,%s,%x,%c.
	10)Implemented case sensitive "exit" command to come out of shell.
	11)mallo.c file contains malloc and free functions.
	12)dir.c file contains opendir,readdir,and  closedir functions.

	REFERENCES:
	1) Brain W. Kernighan and Dennis M. Ritchie (The C prgramming language).
	2) LINUX MAN Pages (www.kernel.org/doc/man-pages).
