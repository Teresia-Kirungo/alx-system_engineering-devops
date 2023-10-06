## 0x03. Shell, init files, variables and expansions
### About Bash projects
Unless stated, all your projects will be auto-corrected with Ubuntu 20.04 LTS.

Resources read or watch: <br> [Expansions](http://linuxcommand.org/lc3_lts0080.php) | [Shell Arithmetic](https://intranet.alxswe.com/rltoken/PLSUQnBcKKU5eEgRfRDlug) | [Variables](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_02.html) | [Shell initialization files](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_01.html) | [The alias Command](http://www.linfo.org/alias.html) | [Technical Writing](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/misc/2021/6/9112669886fd446a2aa3113c31319d1f468dc160.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230613%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230613T104259Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=210cc3698b867f4937799e0c94f88580aeb9acaa1dee7b8652e43a58e7be219c)

#### man or help: 
`printenv` `set` `unset` `export` `alias` `unalias` `.` `source` `printf`

Learning Objectives
-----------
At the end of this project, you are expected to be able to explain to anyone, **without the help of Google**:

General
-----------
* What happens when you type ```$ ls -l *.txt```

Shell Initialization Files
-----------
* What are the ```/etc/profile``` file and the ```/etc/profile.d``` directory
* What is the ```~/.bashrc``` file

Variables
-----------
* What is the difference between a local and a global variable
* What is a reserved variable
* How to create, update and delete shell variables
* What are the roles of the following reserved variables: `HOME, PATH, PS1`
* What are special parameters
* What is the special parameter ```$?```?

Expansions
-----------
* What is expansion and how to use them
* What is the difference between single and double quotes and how to use them properly
* How to do command substitution with `$()` and backticks

Shell Arithmetic
-----------
* How to perform arithmetic operations with the shell

The `alias` Command
-----------
* How to create an alias
* How to list aliases
* How to temporarily disable an alias

Other `help` pages
-----------
* How to execute commands from a file in the current shell

Copyright - Plagiarism
-----------
* You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
* You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
* You are not allowed to publish any content of this project.
* Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements - General
-----------
* Allowed editors: `vi, vim, emacs`
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long (`$ wc -l file should print 2`)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly `#!/bin/bash`
* A `README.md` file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use `&&, ||` or `;`
* You are not allowed to use `bc, sed` or `awk`
* All your files must be executable

More Info
-----------
Read your `/etc/profile`, `/etc/inputrc` and `~/.bashrc` files.

Look at some files in the `/etc/profile.d` directory.

Note: You do not have to learn about `awk, tar, bzip2, date, scp, ulimit, umask`, or shell scripting, yet.
