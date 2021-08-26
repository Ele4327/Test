![](https://github.com/Ele4327/Test/blob/main/Recourses/Shell.png)

👋 Hello Devs
# Simple Shell

Hello and Welcome to our Holberton Simple Shell project.
In this repository you will find our own simple shell, developed by software developers in progress.

For those who dont know a shell is a program that presents a command line interface which allows you to control your computer using commands entered with a keyboard instead of controlling graphical user interfaces (GUIs) with a mouse/keyboard combination.

For a more specific explanation, we invite you to see our manual: man_1_simple_shell

# Features

- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- Your shell should not have any memory leaks
- No more than 5 functions per file
- All your header files should be include guarded
- Use system calls only when you need to

List of allowed functions and system calls:

- [ ] access
- [ ] chdir
- [ ] close
- [ ] closedir
- [ ] execve
- [ ] exit
- [ ] _exit
- [ ] fflush
- [ ] fork
- [ ] free
- [ ] getcwd
- [ ] getline
- [ ] getpid
- [ ] isatty
- [ ] kill
- [ ] malloc
- [ ] open
- [ ] opendir
- [ ] perror
- [ ] read
- [ ] readdir
- [ ] signal
- [ ] stat (__xstat)
- [ ] lstat (__lxstat)
- [ ] fstat (__fxstat)
- [ ] strtok
- [ ] wait
- [ ] waitpid
- [ ] wait3
- [ ] wait4
- [ ] write



## Output

Your program must have the exact same output as sh (/bin/sh) as well as the exact same error output.
The only difference is when you print an error, the name of the program must be equivalent to your argv[0] (See below)

Example SH:
```
Example of error with sh:

$ echo "qwerty" | /bin/sh
/bin/sh: 1: qwerty: not found
$ echo "qwerty" | /bin/../bin/sh
/bin/../bin/sh: 1: qwerty: not found
$
```

Same error with your program hsh:
```
$ echo "qwerty" | ./hsh
./hsh: 1: qwerty: not found
$ echo "qwerty" | ./././hsh
./././hsh: 1: qwerty: not found
$
```
## Installation:

There is two ways: Compilation and Execution and Make

## Compilation and Execution




# How this works:

## Main Functions

## Subfunctions

## FlowChart:

![](https://github.com/Ele4327/simple_shell/blob/main/RECURSES/Basic_Shell_Flowchart.png)

## Tests

Your shell should work like this in interactive mode:

```
$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
```

But also in non-interactive mode:

```
$ echo "/bin/ls" | ./hsh
hsh main.c shell.c test_ls_2
$
$ cat test_ls_2
/bin/ls
/bin/ls
$
$ cat test_ls_2 | ./hsh
hsh main.c shell.c test_ls_2
hsh main.c shell.c test_ls_2
$
```
<h3 align="left">Contribuitors</h3>
<p align="left">
<a href="https://twitter.com/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="" height="30" width="40" />Juan Esteban Duque</a>
</p>
<p align="left">
<a href="https://twitter.com/@CanelitaCadavid" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="" height="30" width="40" />Laura Alejandra Cadavid</a>
</p>
<p align="left">
<a href="https://twitter.com/@ele5438" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="" height="30" width="40" />Sebastian Garzón</a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.gnu.org/software/bash/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> </p>


##### Thanks for your attention, feel free to contribute to the project or contact us if you need something

![](https://github.com/Ele4327/printf/blob/main/img/holb_logo.png)

### End
