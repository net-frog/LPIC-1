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
```foo@bar:~$ ls -l /bin/sh ```

```foo@bar:~$ readlink /bin/sh  ```

```foo@bar:~$ echo $SHELL ```

#### Shell Version:
```foo@bar:~$ echo $BASH_VERSION```

```foo@bar:~$ bash --version ```
### Working with Directories:

##### Print Current working directory: 
```foo@bar:~$ pwd```

##### Create Directory in current Directory:
```foo@bar:~$ mkdir parent_dir```

##### Create Directory sub-directory in parent_dir:
```foo@bar:~$ mkdir parent_dir/child_dir```

##### Create Parent and Child Directory together 
```foo@bar:~$ mkdir -p parent_dir/child_dir```

##### Change Directory 
- Change to /etc directory: ```` cd /etc ```` 
- Change to home directory, tilda (~) is used as home: ``` cd ~ ```

