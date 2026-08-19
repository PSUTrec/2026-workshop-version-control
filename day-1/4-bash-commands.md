# Introductory `bash` Commands

whenever we run a command, we are doing so from a specific folder on your computer, on windows there is a separate sandbox area set up for git bash, on macOS and linux it's your home directory, usually your prompt will show the directory but if not it's pwd time

* mkdir
* head <file>
* tail <file>
* touch

### Navigation

```bash
# Prints a list of the files in the current folder
ls
# Prints a list of all files in the current folder, including hidden ones
ls -a
# Prints the name of the current folder
pwd
# Moves to the given folder
cd my-folder/sub-folder
# . means the current folder
ls .
# .. means the parent folder of the current folder
cd ..
```

### File inspection

```bash
# Prints the contents of the given file
cat foo.txt
# Prints the given string
echo "hello"
# Prints the value of the variable VAR
echo $VAR
```

### File manipulation

> DANGER!!! It is relatively easy to **permanently** overwrite or delete files using these commands. Approach with care, and don't be afraid to ask for help.

```bash
# Copies the given file to the given folder or destination file 
cp file1 my-folder/
cp file1 my-folder/copied-file
# Moves the given file to the given folder or destination file
mv file1 my-folder/
mv file1 my-folder/renamed-file
# Deletes the given file
rm file1
```

> If a destination file that already exists is provided to `cp` or `mv`, it will be overwritten. Files overwritten by `cp` or `mv` or deleted by `rm` are not sent to the Trash, but instead fully erased.

### Next Module: [Introductory `git` Commands](/day-1/5-git.md)
