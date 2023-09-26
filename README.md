# Lecture note on Shell Command

## Shell command

### pwd
shows the current path in a hierarchical directory

---

### cd
change directory

### ls
The **ls** command is used to list the contents of a directory.
It is probably the most commonly used Linux command.
It can be used in a number of different ways.

- ls: list files and directories
- ls /bin: list the files in the /bin directory
- ls -l: list the files in the working directory in long format
- ls -l /etc /bin: list the files in the /bin directory and the /etc directory in long format
- ls -la ..: list all files in the parent of the working directory in long format

#### argunents
- [directory name]/: root
- [directory name].: current directory
- [directory name]..: upper-level directory
- [directory name]~: home of current user
- /[directory name]: absolute path
- ./[directory name]: relative path
- ../[directory name]: relative path

#### options
- -l: show detailed information (long format)
- -lh: same as above, but size in units

---

###  clear

```
$ ls
README.md
$ clear
```

```
$

```


## Manipulation
### cp
copy files and directories
```
$ cp file1(copied) file2
```

### mv
move files and directories or rename them
```
$ mv file1 file2(file1 -> file2)
```

### rm
delete files and directories **permantely and irreversevely**
```
$ rm file1(removed)
$ rm file1 and file2(removed both)
```

### mkdir
make a new directory
```
$ mkdir new_directory
```

---

## Help command

### help
```
$ help cd
```

### man
```
$ man cp
```

---

## Exiting terminal

### exit
```
$ exit
```

























