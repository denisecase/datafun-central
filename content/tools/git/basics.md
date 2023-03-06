---
title: "Basics"
---


Git is a widely-used version control system that helps you track changes to your code and collaborate with others.
With Git, you can create a complete history of your work, from the initial commit to the latest changes. This makes it easy to work on a project with others, keep track of your progress, and recover from mistakes.

## Creating a Repository

To get started with Git, you need to create a repository.
This is where you'll store your code and track changes to it.
There are several ways to create a repository:

- **Clone an existing repository**: If you want to work on code that's already been created and shared by someone else, you can clone their repository to your local machine. To do this, you'll need the repository's URL and you can use the `git clone` command to create a local copy of the code.

- **Fork an existing repository**: If you want to make changes to someone else's code and contribute those changes back to their repository, you can fork their repository. This creates a copy of their repository in your GitHub account, which you can then clone to your local machine and work on.

- **Create a new repository**: If you want to start a new project from scratch, you can create a new repository by clicking the "+" sign in the top right corner of your GitHub account.

## Getting Code onto Your Machine

Once you have a repository set up, you'll want to get the code onto your local machine so you can work on it.
To do this, clone the repository using the `git clone sourceurl` command. Change sourceurl to the address shown in the browser when viewing the root folder of the repository. This will create a local copy of the repository on your machine that you can work with.

## Saving Changes with Git

Once you have a copy of the repository on your machine, you can make changes to the code and save those changes to the repository using Git. The basic workflow for this is:

1. **Add changes**: Use the `git add .` command to add the changes you've made to the code to the staging area. It's said "git add dot" - see the dot at the end - that means add all the newly created files into source control.

2. **Commit changes**: Use the `git commit -m "add feature n` command to save the changes to the local repository with a descriptive commit message.

3. **Push changes**: Use the `git push origin main` command to push the changes from your local repository back up to the remote repository on GitHub.

This sequence of commands is very common:

```
git add .
git commit -m "tell us what you did"
git push origin main
```

## Editing on your Machine

We typically like to edit files on our machine using editors
like VS Code or IDEs like PyCharm and Spyder.
These local tools provide advanced features including syntax highlighting,
code completion, and debugging, which can make our work more efficient.

## Editing in the Cloud

However, the power of our local editors and IDEs is increasingly
becoming available in the cloud, and we can make many updates to
our repositories right from the GitHub web interface.
For example, you can use the github.dev web-based editor to
edit files and commit your changes.

It's important to note that if we edit files both on our machine
and in the cloud, we can end up with conflicts when trying to merge our changes.
Therefore, it's important to ensure that we always pull down the latest
changes from the cloud before making any local edits, and that we
push our changes back up to the cloud as soon as we're finished with them.

Using the git pull command will bring any changes made directly
in your GitHub (or other cloud) repository down to your machine.

```
git pull
```

Read more about the github.dev editor at:

- <https://docs.github.com/en/codespaces/the-githubdev-web-based-editor>

## [Remotes](remotes.md)

In Git, "origin" is a shorthand name that refers to the remote repository where your code is stored.
When you clone a repository,
Git automatically creates an "origin" remote that points to the original repository on the server.
You can use this remote to pull changes from the server or push your local changes back to it.

You can add more than one remote to a repository.

## [Branches](branches.md)

Git branches are separate lines of development that allow multiple
contributors to work on different features or versions of a project simultaneously.

The default branch in Git is now called "main", but "master" was previously used,
so you may still see it.

## Pull and Push

When we use `git pull`,
Git already knows the source and destination of the changes (i.e.,
the remote and local repositories)
because it's been configured using the git clone command.

When we use `git push`, we need to specify both the remote repository
(the source) and the branch we want to push the changes to (the destination).
The origin in `git push origin main` refers to the remote repository we want
to push the changes to,
and main refers to the branch on the remote repository that we want to
update with our changes.
