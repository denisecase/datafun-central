+++
title = "Git: Conflicts"
+++

We can edit project files in at least two places:

- locally, on our machine
- in the cloud, e.g., by using the editing features in GitHub

## Bad Practices

We want to keep our local version and cloud version in sync at all times.

Some of the worst things we can do are:

1. Forget to pull before we start our work.
1. Pull code and leave it for a long time, then start working on old, stale code.
1. Make huge, expansive contributions that take a long time (unless we know how to branch - an intermediate Git skill.)
1. Wait to push our completed changes to the cloud.

## Good Practices

To minimize the chance of conflits:

1. Always pull code before you start working locally. Never work on stale code!
2. Make small, incremental changes.
3. As soon as you finish a useful contribution, git add, commit, and push up to the cloud.  

Keep your local and cloud repositories synchronized. Use these for each session.

Before you start:

```shell
git pull
```

After you finish a set of edits:

```shell
git add .
git commit -m "add title"
git push
```

When working collaboratively, communicate with team members and establish a clear workflow.
Ensure the team knows who is working on which files and when changes are being made.
You might create different small,
focused branches that don't overlap much in terms of the files they modify.

## Merge Conflicts

Merge conflicts can occur when:

- two people edit the same file simultaneously
- changes are made to a file both locally and in the cloud at the same time.
- two branches with different changes are merged.

For example, we might use the GitHub cloud editor to make a quick
fix to our README.md - forgetting that we're also in the process of updating installation instructions on the local README.md.

Merge conflicts can be frustrating,
but they are an inevitable part of collaborative work.

If you do run into a merge conflict,
don't worry - it's not the end of
the world.
Git provides tools to help you resolve conflicts and merge
changes together.
The first step is to understand which files have
conflicts by running git status.
The files with conflicts will be
marked as "unmerged".

To resolve the conflict,
open the conflicted file and look for the conflicting sections
marked with <<<<<<< HEAD, =======, and >>>>>>>.
Manually edit the file to remove the conflicting sections
and keep the changes you want.
Once you've resolved the conflict,
fstage the changes with git add and commit them with git commit.

If you're still unsure how to resolve the conflict,
ask for help from your team members or consult Git documentation.
Stay calm and take your time to carefully resolve the conflict.

Experience managing merge conflicts can be very valuable.
