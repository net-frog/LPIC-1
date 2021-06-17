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
```console
1. ls -l /bin/sh
2. readlink /bin/sh 
3. echo $SHELL
```
#### Shell Version:
```
1. echo $BASH_VERSION
2. bash --version
```
### Working with Directories:

##### Print Current working directory: 
- ```pwd```

##### Create Directory in current Directory:
- ```mkdir parent_dir```

##### Create Directory sub-directory in parent_dir:
- ```mkdir parent_dir/child_dir```

##### Create Parent and Child Directory together 
- ```mkdir -p parent_dir/child_dir```

##### Change Directory 
- Change to /etc directory: ```` cd /etc ```` 
- Change to home directory, tilda (~) is used as home: ``` cd ~ ```

