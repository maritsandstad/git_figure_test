# git_figure_test
Figure sharing test repository

This repository contains figures of formaldehyde and other miscalleneous figures

## How did I set up this repository?

### In your web browser:

* Go to [github](https://github.com/) and log in (if you don't have user there, do make one)
* Click the green button that says New to create a new repository
* Make up a name for your repository to put in the repository name field (this repository is called git_figure_test)
* Make the repository private if you just want to share with a few people (for now), or public if you want it to be available for anyone from the very beginning
* Click the green Create repository button

### In your terminal

* Navigate to the folder with what you want to share, or make a new one. Having it have the same name as the repository is nice, but not necessary
* Type and run the following commands:

`git init`
`git add name-or-regexp-of-files-in-folder-to-add`
`git commit -m "First commit"`
`git -M main`
`git remote add origin git@github.com:yourusername/the-repository-name-you-choose`
`git push -u origin main`

## For later workflow in terminal:

* To check status in your terminal:

`git status`

Will tell you which files have changed, which are untracked and which are staged for commit.

* To stage one or more files for commit:

`git add filname-or-regexp`

* To commit changes:

`git commit -m "A commit message"`

* To push changes to github:

`git push`

If you have a new branch, you may need to tweak this, but if you run this you will get a recommendation for how to do so.

* To pull changes from github. (If someone else has changed the code, or you've changed it in the web interface or from a different machine.)

`git pull`

* To make a new branch to switch to:

`git checkout -b name-of-new-branch`

If you omit the -b part of the command, you change to an existing branch of that name.

For more info search the web, or try this [link](https://letmegooglethat.com/?q=git+for+dummies)
