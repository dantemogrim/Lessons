<img src="./matrix-git-fixed.gif" width="100%">

# 05 - Git

Git is type of Version Control System (VCS). _"What's a version control system?"_ Glad you asked! It's a term used to describe a system that helps us keep track of all our saves, all our edits and much more to our projects. Git has been in use since 2005 and was created by [Linus Thorvalds](https://en.wikipedia.org/wiki/Linus_Torvalds), the mind behind Linux.

- :books: Documentation

  - [Documentation](https://git-scm.com/)

- :link: Links

  - [Learn Git Branching](https://learngitbranching.js.org/)

  - [GitHub Guides](https://guides.github.com/)

  - [GitHub Learning Lab](https://lab.github.com/)

  - [CS Visualized: Useful Git Commands](https://dev.to/lydiahallie/cs-visualized-useful-git-commands-37p1)

- :headphones: Videos

  - [Git and GitHub for Poets](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)

  - [Git Tutorial for Beginners: Command-Line Fundamentals](https://youtu.be/HVsySz-h9r4)

## Basic Commands

| Command                                           | What it does                                                                                                                                                                   |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [`git init`](https://tldr.ostera.io/git-init)     | Will initialize a new git-repository in your current directory. Can also be used like this `git init -b main` to init with a branch named 'main'.                              |
| [`git remote`](https://tldr.ostera.io/git-remote) | Command for dealing with your remote repositories, for instance: `git remote add origin https://github/user/repository.git`.                                                   |
| [`git add`](https://tldr.ostera.io/git-add)       | Will add all unstaged files to be [staged](https://git-scm.com/about/staging-area) in a commit, use with either `-A` flag for all files or the name of your file or directory. |
| [`git commit`](https://tldr.ostera.io/git-commit) | Will commit your staged files, used with an `-m` flag for including a message like this: `git commit -m 'descriptive text about commit here`.                                  |
| [`git push`](https://tldr.ostera.io/git-push)     | Will push your commits to the specified remote repository.                                                                                                                     |
| [`git fetch`](https://tldr.ostera.io/git-fetch)   | Will download the latest changes from a remote repository without merging them with your local version.                                                                        |
| [`git pull`](https://tldr.ostera.io/git-pull)     | Will download and merge the latest changes from a remote repository with your current version.                                                                                 |
| [`git status`](https://tldr.ostera.io/git-status) | Will print out the current status of your changed files. You will probably use this a lot!                                                                                     |

## Branch commands

| Command                                           | What it does                                                                                              |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| [`git branch`](https://tldr.ostera.io/git-branch) | Your main command for dealing with branches, writing it like this will print out a list of your branches. |
| `git branch 'branch-name'`                        | Will create a new branch based on your latest commit and give it the specified name.                      |
| [`git switch`](https://tldr.ostera.io/git-switch) | Used for switching from your current branch to a new one.                                                 |
| `git branch -d 'branch-name'`                     | Will delete the named branch. It cannot be the branch your currently have 'checked out'.                  |
| [`git merge`](https://tldr.ostera.io/git-merge)   | Used to merge to branches together.                                                                       |

## Other neat commands

| Command                                           | What it does                                               |
| ------------------------------------------------- | ---------------------------------------------------------- |
| [`git stash`](https://tldr.ostera.io/git-stash)   | Will 'stash' your unstaged changes locally.                |
| [`git log`](https://tldr.ostera.io/git-log)       | Will print out a list of your commits.                     |
| [`git reflog`](https://tldr.ostera.io/git-reflog) | Will print out a list of your changes to local references. |
| [`git diff`](https://tldr.ostera.io/git-diff)     | Will print out changes to tracked files.                   |
| [`git config`](https://tldr.ostera.io/git-config) | Used to manage your git configurations                     |

> If you happened to miss the lesson on GitHub Desktop and perhaps feel slightly overwhelmed by some of the terminology being used - read up on the [Buzz Words](https://github.com/dantemogrim/Lessons/tree/main/GitHubDesktop) mentioned there.

:rotating_light: Feeling overwhelmed? That is **OK**! This is a learning by repeating part of your education. You'll figure it out soon enough. [You got this](https://media.giphy.com/media/SxhDfgXq4nAYoKkvbR/giphy.gif?cid=ecf05e47as9fu87hgkcihgybpy0nd3cg7kz948m48xkga9d8&rid=giphy.gif&ct=g)! If you want more of a warm up approach to this lesson we highly recommend looking at [Daniel Shiffman's Git & GitHub for Poets](https://www.youtube.com/watch?v=BCQHnlnPusY).

## Exercises

- **Firstly** open your Terminal application. First we need to make sure that Git is installed on your computer. If you're unsure whether it's installed or not, try this command in your terminal window: `$ git --version` + `Return/Enter`. If you recieve some kind of information that means it's installed. If it's not installed then try these following commands:

  - For Homebrew users - `$ brew install git`
  - Windows users - [try this download link](https://gitforwindows.org/).

- **Secondly** Add your [GitHub username and e-mail](https://youtu.be/HVsySz-h9r4?t=281) to Git by typing `git config --global user.name 'your user name'` and `git config --global user.email 'your github email'`.

_Tip! Check the commands above for guidance!_ :sunglasses:

1. Use your terminal application of choice to create a new directory in an appropriate location. Once you're inside, create a `README.md` and maybe some other files. Don't forget your `.gitignore`!

<details><summary>Hint #1</summary>

1. First:

- To create a new directory/folder use: `mkdir <folder-name>`.
- To create new files use: `touch <file-name>`.

</details>

2. Initialize a Git repository in your new folder.

<details>
<summary>Hint #2</summary>

- To create a git repository use: `git init`.

> If your CLI outputs a text hinting you about "master" versus "main" branch, we'll explain this in a later exercise. Disregard it for now.

</details>

3. During this exercise, try running `git status` between your commands and observe the difference.
   Let’s save our files locally through Git by adding them and committing them.

<details>
<summary>Hint #3</summary>

- To stage/prepare your files for committing try: `git add <file-name>`.
- To commit your files, check out the command `git commit` (also important, don't forget to add a `-m` message to your commit!).
  > _Ex: git commit -m "My initial commit!"_

</details>

4. Great job! Let's add some content to this empty looking `README.md`. :spider_web: Open up your repository in VSCode and add the following "original Matrix quote" to your file using [Markdown Blockquotes](https://guides.github.com/features/mastering-markdown/): `"No one can be told what Git is. You'll have to see it for yourself."` and save.

5. Before we go any further, let's head to GitHub's website and open up a new **empty** repository (if you don't remember, check out the lesson on [GitHub Desktop](https://github.com/dantemogrim/Lessons/tree/main/GitHubDesktop). This time don't check any of the boxes when it comes to `README.md`, `.gitignore` or `License` options. Let it be set as 'Public' and not 'Private'. Simply give your repository a title and press `Create repository`.

> Hot tip: Once you've create a new repository on GitHub - you will be sent to page with instructions on how to set up a new repository using the command line. :fire:

6. Now it's time to couple these two creations together! Connect your local repository to the remote one you just created on GitHub.

<details>
<summary>Hint #6</summary>

1. To add a remote repository, use the command: `git remote add origin https://github.com/<username>/<repository-name>.git`. This step only needs to be done once.

2. When loading things up to GitHub, it's standard practice to rename the 'master' branch to 'main' by typing: `git branch -M main`.

   > _Git initiation in the Terminal defaults to a "master" branch and GitHub has a default expectation of our repositories having corresponding "main" branch. "Why though?" [Here's an article on the subject you can read after class](https://www.makeuseof.com/how-to-rename-the-default-git-branch-and-why-youd-want-to/)_. This article also shows how you can easily configure Git to change its default to "main" instead. We can recommend doing this as it'll spare you from unnecessary headaches in the future. :brain: :100:

</details>

7. Let's test to see that everything is working by pushing our local files to GitHub!

<details>
<summary>Hint #7</summary>

When you want to push to your remote repository, you also need to specify this **once** by typing `git push --set-upstream origin main`. After these steps you can simply use `git push` to upload your future commits.

</details>

8.  **Extra:** Try creating a new branch in your repository and use it to make some changes to your code, and then merge your changes to your 'main' branch.

<details>
<summary>Hint #8</summary>

- To create a new branch use: `git branch <new-branch-name>`
- To change your location to another branch: `git switch <branch-name>`
- Add som content. Maybe a file. Commit it. _In order for your new branch to be visible on GitHub, make sure to use:_ `git push --set-upstream origin <new-branch-name>`
- To merge a new branch into main, first switch back to the main branch and then use: `git merge <branch-name>`

> Unsure whether your new branch was created or not? `git branch` will list all created branches. :deciduous_tree:

</details>

9.  **Extra:** Fork your one your classmates repositories on GitHub. Add one of your own favorite quotes to their `README.md` in a new branch and create a pull request. Ask the your classmate to merge your pull request.

> :point_up: **Note:** The process of making a fork/pull request/merge is the same as during our GitHub Desktop lesson (not done through the command line).
