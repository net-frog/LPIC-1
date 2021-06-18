## Linux Shells
> Shell is an interactive interface that allows users to interactive with Linux Operating system. 
- Bash
	- Default Shell
	- First release in 1989
 
- Dash
- Korn
- Zsh
- tcsh
#### Shell in use: 

```
foo@bar:~$ ls -l /bin/sh 
```

``` 
foo@bar:~$ readlink /bin/sh  
```

``` 
foo@bar:~$ echo $SHELL 
```

#### Shell Version:
``` 
foo@bar:~$ echo $BASH_VERSION 
```

```
foo@bar:~$ bash --version 
```
### Working with Directories:

##### Print Present Working Directory: 
```
foo@bar:~$ pwd
```

##### Create Directory in current Directory:
```
foo@bar:~$ mkdir parent_dir
```

##### Create Directory sub-directory in parent_dir:
```
foo@bar:~$ mkdir parent_dir/child_dir
```

##### Create Parent and Child Directory together 
```
foo@bar:~$ mkdir -p parent_dir/child_dir
```
### Directory Path types:
- Absolute Path: Path that start from root '/' e.g.
  - /var/log
- Relative Path: Path relative to current or some directory e.g.
  - ~/ for /home/user_home_dir
  - ../ for parent directory
  - ./ for current directory
  
##### Change Directory 
Change to /etc directory: 
``` 
cd /etc 
``` 
Change to home directory, tilda (~) is used as /home/user_home_dir: 
``` 
cd ~ 
```
```
cd -
```
### Command types
- Internal: Commands that built-in shell
- External: Commands that provide by external utility.
> Some commands might be available as both.


