# fluffy-happiness


to install:
https://github.com/git-guides/install-git

to verify installation:
on the command line: `Git --version`

make a directory:
`mkdir Git`

navigate to the directory:
`cd Git`

make another directory for you project:
`mkdir firstProject`

to initialize the directory as a "Git Repository" :

cd (change directory) into firstProject/ and type `git init`

to transfer your project to GitHub you should first create a repository with a ".git" extension on the GitHub website.

I created a repository called "potential-enigma" with a url of https://github.com/erateran/potential-enigma.git

then copy the url and combine it with this commands: `git remote add origin https://github.com/erateran/potential-enigma.git`

create your file:

on macOS or Linux: `touch test.py`

on Windows: `type nul > test.py`

Now you can open your project with your favourite text editor and include your code.

in order to "add" your project to the repository (locally) use: `git add` 

or if you have several projects and you want to add all of them: `git add.`

to publish your project (locally): `git commit -m "your message"`

now it's time to "push" the file into GitHub remotely using: `git push --set-upstream origin 'name of the branch'`

the `--set-upstream` flag is only needed once in each branch. after that you only use: `git push` 

some other usefull Git commands:

`git branch` to view the branches (current branch is indicated with an asterisk)

`git branch 'name'` to create a new branch

`git checkout 'name of the branch'` to switch to a different branch

What if you want to remove a file remotely?

`git rm --cached 'file name'`

`git commit -m'message'`

`git push`




