---
title: "Learning Git"
date: 2023-04-14T18:42:44+05:30
authors: ["Aryan Mehesare"]
description: ""
tags: ["Git", "Github", "FOSS", "learning"]
categories: [""]
series: [""]
url: ""
slug: ""
externalLink: ""
featuredImage: "/images/git_github.jpg"
disableComments: true
draft: true
---

Git is a very important software that every software developer should now. It simplifies tasks and helps people to contribute and collaborate with others on projects. I have been using Github for a year now but I didn't have a lot of knowledge about git so i decided to learn it this week.

<h2>Index</h2>

- [What is Git?](#what-is-git)
- [Installing Git](#installing-git)
- [Getting Started](#getting-started)
- [Staging and Committing](#staging-and-committing)
- [Linking the repo to a hosting service](#linking-the-repo-to-a-hosting-service)
- [Pushing the changes to Github](#pushing-the-changes-to-github)
- [Pulling changes to the repo](#pulling-changes-to-the-repo)
- [Branching](#branching)
- [Pull Requests](#pull-requests)
- [Cloning Repositories](#cloning-repositories)
- [Forking Repositories](#forking-repositories)

## What is Git?

Git is a version control software that was developed by Linus Torvalds (also the developer of the linux kernel) in 2005. It is an amazing piece of software that helps multiple people to work on projects faster and more efficiently. As of today Git is the most widely used version control software worldwide.

## Installing Git

Git is a multiplatform tool that is available on all major operating systems including windows, Mac and Linux. I have been using Windows 11 ever since I bought a new laptop in August last year so i downloaded the exe file and downloaded it. I also use Microsoft's Visual Studio Code as my primary editor and refer to use vim in the terminal. Git has been integrated very weel with vscode and its functionality as been increade with additional software like GitLens from the Gitkraken team. (You can use the premium versions of both these software if you are a member of Github's student program)

## Getting Started

I created a new folder and used `git init` to initialise it as a git repository. I followed the tutorial from W3Schools and later referred to some tutorials on youtube to get a deeper understanding of how git works.

## Staging and Committing

I created a README.md file in the repository and used the `git add .` command to add it to the staging area, after doing this gits starts tracking the file for any changes. Next comes the commiting part which can be done using the `git commit` command. It is important to write precise commit messages so that other people can know what has been changed. This is very important especially ehile working on large projects to keep track of changes or while working with multiple people on a project.
Changes can also be unstaged using `git rm --cache file_name`.

## Linking the repo to a hosting service

Github is one of the most popular code hosting services and that is what ill be using for my my tutorial. You can create a github repository and use the `git remote add origin link_to_repo` to link it to your local repository created earlier. This will allow us to save our files on the cloud so that we can refer to it later or allow others to collaborate eith us.

NOTE: Before pushing the changes over to Github you will be asked for verification via email, a security code or SSH key.

## Pushing the changes to Github

To push the changes to github we can use the `git push` command. This will upload our files to the cloud and we can check them by going to our github repository.

## Pulling changes to the repo

If someone makes changes to the files on the github repo then we need to import those changes into our local repository on our device. We can use the `git pull` command to trasfer the changes. The pull command is actually the combination of the `fetch` and `merge` commands. You can also check the status of your repositry by using the `git status` command

## Branching

This is avery useful and important feature of git. Branching allows you to work on multiple instances of the same repository. It is useful while trying out new features before making them mainstrea. Doing this allows u to keep the main code untouched while simultaneously gives you the freedom to work on your project.

We can create new or switch branches using the `git checkout` command.

## Pull Requests

Suppose you have created some changes in the _test_ branch of your repository and now want to include them into your main repo. To do this you can create a pull request which when approved will bring over all or some of the changes to the main branch from the test branch. You can easily create pull requests and also link them to issues on Github.

## Cloning Repositories

Git gives you the ability to clone any remote repo to ur system to work on it in your local machine or to run the software with the `git clone link_to_repo`

## Forking Repositories

Github allows you to fork repositories from other people on the platform. This is very useful if u want to contribute to it as it gives us the freedom to play around with the code and open a pull request for merging into the main repositry.

---

This is just thr basics of git and what i have learned so far. I'll update it in the future when in learn things such as revert, ammend, reset etc.

Millions of people use git everyday and it has transformed the software industry. Git has many commands but it is not recommended to learn them. Many commands get memorised over time and you always have access to the documentation locally.

<h4> You can use the <i>git help command_name</i> command to check out the detailed documentation for each command. <h4>
