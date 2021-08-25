---
layout: post
title:  "Blog 0 - Git Basics"
date:   2021-08-24 12:06:20 -0700
categories: git blog 
---

# What is Git?
Git is an Open Source Distributed Version Control System. Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

# What is Github?
[GitHub](http://github.com) is designed as a Git repository hosting service. It's an online database that allows you to keep track of and share your Git version control projects outside of your local computer/server. In addition, Github provides many of it's own features.

**Git Commands**

`git status` command is used to see a summary of which files have changes that are staged or unstaged for a commit. Untracked files are also listed with the git status command. 

`git checkout` command switches between branches or restores working tree files.

```
# Checkout an existing branch named main
git checkout main

# Checkout a new branch named update-package
git checkout -b update-package
```


`git add` adds new or changed files into your  
```
# Add a single file
git add <FILE NAME>

# Add multiple files
git add <FILE NAME 1> <FILE NAME 2> ....

# Add all tracked and untracked files
git add .
```

`git commit` save changes to local repository
```
# Commit with message
git commit -m "Commit message goes here"

# Stage and commit tracked files
git commit -am "Commit message goes here"
```

`git push` command sends (or push) the commits from your local branch in your local Git repository to the remote repository. In our case Github.
```
git push
```

