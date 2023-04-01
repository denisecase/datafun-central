---
title: "Git: Branches"
---

In Git, we are always working on a **branch** of code,
which is like a separate "timeline" for the code.

## Default Branch

The default branch is employed automatically when we first create a repository,
and it is typically and by default named **main**. On older repos,
you may see a _master_ branch instead, but the old terminology is
discouraged and easy to update.

## Working Alone

For independent projects, we may work directly on the main default branch.

Individual developers may choose to use branches to work on
new features or fixes without affecting their main codebase.

## Working Together

In a professional environment, it's generally recommended to create
new branches for new features or changes to avoid conflicts with other
developers and to make it easier to manage and review changes.

Individual developers can also use branches to experiment with new features
or make changes without affecting the main codebase.

We can make changes, commit them to our branch, and then merge our
branch back into the default branch when appropriate.
Multiple branches allow a team to work on different features or changes
at once without worrying about conflicts or breaking the main codebase.

Once we're satisfied with our changes on a branch, we can create
a **pull request** to request that the changes be reviewed and
merged into the default branch. Team leads can then review and merge
the changes as needed. The default branch is typically set to "main"
and is the primary branch for the project.

You can create a new branch with the `git branch` command,
and switch to that branch with the `git checkout` command.
Once you're on the new branch, any changes you make and commit
will only affect that branch.

To merge a branch back into the main codebase, you can use
the `git merge` command. This will bring any changes from the
branch into the main codebase,
and you can resolve any conflicts that arise during the merge.

Git branches are an important tool for managing complex
projects with multiple contributors,
and they allow for efficient collaboration and code review.
