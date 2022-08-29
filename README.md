# **GIT**
Practice using git + GitHub

This project consists of four separate min projects consisting:
- Learning Git

- Creating a repository.

- Configuration of Git.

- Git commands

## Learning Git

Git is a [free and open source](https://git-scm.com/about/free-and-open-source) distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
## Creating a repository.

- I learned git from scratch with this website [learn git ](https://git-scm.com/about/free-and-open-source)
- Go to [GitHub](https://github.com). 
- Sign in to GitHub.
- On the right side of the page, click on the green `New repository` button.
- Give your repository any name you like and make sure that the repository is public.
- Also make sure that the `Initialize this repository with a README ` is NOT checked.

## Configuration of GitHub
If you are on any linux distro you can use the package management tool that comes with your distribution to install it.

- Setting up your username and email

```
─$ git config --global user.name "your username"
─$ git config --global user.email "youremail@email.com"
```

- Change the default branch for Git using this command
```
─$ git config --global init.defaultBranch main
```
- To enable colorful output with git
```
─$ To enable colorful output with git, type
```

- To verify that things are working properly, enter these commands and verify whether the output matches your name and email address.

```
─$ git config --get user.name
─$ git config --get user.email
```

### Git Commands 
* repo -> repository
* `clone` -> bring a repo down from the internet (remote repository like Github) to your local machine
* `add` -> track your files and changes with Git
* `commit` -> save your changes into Git
* `push` -> push your changes to your remote repo on Github (or another website)
* `pull` -> pull changes down from the remote repo to your local machine

* `status` -> check to see which files are being tracked or need to be commited
* `init` -> use this command inside of your project to turn it into a Git repository and start using Git with that codebase

