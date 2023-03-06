+++
title = "Remotes"
+++

In Git, the term "origin" refers to the default remote repository that a local repository is linked to. 
When you clone a repository from a remote server to your local machine, 
Git automatically sets up the "origin" remote for you. This allows you to push changes from your local repository to the remote repository, 
and pull changes from the remote repository to your local repository.

When you clone a repository, 
Git sets up the origin remote by default, 
pointing to the repository you cloned from. 
This means that when you push changes to the remote repository, 
they will be added to the branch on the remote repository that you cloned from.

Using the "origin" remote allows you to collaborate with others by sharing changes to the same repository. 
When someone else pushes changes to the remote repository, 
you can pull those changes down to your local repository 
and merge them with your own changes.

However, if you edit the same file in 
both your local repository and the remote repository, 
conflicts can arise. 
To avoid conflicts, 
it's important to always pull down changes 
from the remote repository 
before making your own changes, 
and to carefully review any merge conflicts that arise.
