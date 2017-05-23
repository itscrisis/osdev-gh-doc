# Introduction to Git and Github

## What is Git?

Git is a so-called revision control system.

## What is Github?

Github is a web-based collaborative software development platform built around
Git

## Conecpts

### Repository

TBD

### Fork

TBD

## First steps

### Creating your account

TBD

### Creating and uploading your public key

## Workflows within osdev-gh

TODO: make this section more friendly. Add lots of images.

### Getting a personal copy of a repository

1. Go to http://github.com/osdev-gh. Make sure the repository tab is selected.
1. Click on the project you want to contribute to, for example osdev-gh-doc.
1. At the top right of the screen you will see a button with the text "Fork". Click this button.
1. Within a few seconds you will have your own fork.
1. From within your own fork click on clone or download. Select the URL and copy it.
1. Open up a terminal and type git clone followed by the URL you copied
1. Once the repo has finished downloading you are ready to contribute.

### Pushing code up

You have done some work and want it reviewed and hopefully merged into the
main tree.

1. In your terminal, make sure you are in the project directory.
1. Type git push. This will push your local code to your github repo.
1. Now go to your personal fork on github and click on the new pull request button. This will offer up your changes to the master repository.
1. The project admins will study your changes. If they are good, they will be merged in, otherwise the merge will be rejected with an explanation so that you can go and fix and push again.
