# Getting an Existing Project into `git`

If you have an existing project you would like to put under version control, you will need to:

1. Put all your files in one folder
2. Open the command line (e.g. Git Bash)
3. Run the command `cd /path/to/folder`, replacing "`/path/to/folder`" with the path from the current directory to the folder
4. Run the command `git init`
5. Run the command `git status` to see if there are files in the list that you **don't** want to track with `git`
   1. If there are, create a `.gitignore` file and add them to it
7. Run the commands `git add .` and `git commit -m "Initial commit"`

Now you have a local `git` repository with your project files in it! If you would like to put it on GitHub, you can follow the instructions [here](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github?platform=windows).
