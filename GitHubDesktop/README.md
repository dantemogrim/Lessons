<img src="https://media.giphy.com/media/349qKnoIBHK1i/giphy.gif?cid=ecf05e47sywxajbr0z13sxg3ovtcj2f2idcaw3qmy5et08k2&rid=giphy.gif&ct=g" width="100%">

# 00 - GitHub + GitHub Desktop

**GitHub** is a platform where developers can store, manage, track, collaborate and control changes to their coding projects.
It also has social qualities in a sense as you can take part of and contribute to what other developers are working with around the world.
GitHub is mainly referred to as a "Git repository hosting service" - meaning that the logic behind what makes this all work is system is called [Git](https://git-scm.com/).

**GitHub Desktop** is an app that lets you interact with GitHub directly without having to use your command line or Web Browser.

**Git** is the tool/language/behind-the-scenes-wizardry that we use when interacting with GitHub for example. Alot of the terms we are using today are based off if it. _We'll explain more about this in a future lesson._

- :books: Documentation

  - [Git](https://git-scm.com/docs)

- :link: Links

  - [GitHub courses](https://lab.github.com/)
  - [First day on GitHub](https://lab.github.com/githubtraining/first-day-on-github)
  - [Learn about Git](https://git-scm.com/about/)
  - [GitHub flow chart](https://guides.github.com/introduction/flow/)
  - [Forking and pull requests](https://guides.github.com/activities/forking/)
  - [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

- :headphones: Screencasts

  - [GitHub Desktop](https://www.youtube.com/watch?v=iv8rSLsi1xo)
  - [Version control](https://git-scm.com/video/what-is-version-control)
  - [Markdown tutorial with examples](https://www.youtube.com/watch?v=bpdvNwvEeSE)

- [GitHub + GitHub Desktop Basics](https://www.youtube.com/watch?v=GqNAD4XoZ6k)

> If you happen to get stuck the best thing is to ask a study buddy or your teachers for [help](https://www.youtube.com/watch?v=zkTf0LmDqKI)!

<details>
<summary> ⚡️ Buzz Words</summary>

- `.gitignore` - A file containing information about all the folders and files you _don't_ want Git to keep track of and that you _don't_ want to publish on GitHub.
- [`Clone`](https://giphy.com/gifs/iFkHQLzYA09Zm) - "To clone" means to make a quick copy of someones project and downloading it to your local computer. It's rather detached from the original creator.
- `Commit` - Saving (commiting) your changes to Git. Similar to taking a snapshot of your repository and adding a title to that snapshot. _This will become clearer once you start looking through commits in future projects._
- `Fork` - "To fork" means to copy a remote repository to your GitHub account. You can then use it to propose changes or as a starting point for a project of your own. Good for collaborations. [_(In ways similar to a clone but you can read about their differences here)_](https://github.community/t/the-difference-between-forking-and-cloning-a-repository/10189).
- `Merge` - Simply but, it's when two repositories become one. Let's say you make a project and a friend of yours makes a fork and continues to build on it. That friend will be able to make a pull request to you. You as the original creator can then choose to create a merge by accepting these changes. This means that the friend's added work now is a part of the original creation.
- `Pull request` - 'Asking' the original creator of a repo to merge/add changes proposed in your forked version of said repository.
- `Push` - 'Upload' changes to a remote repository (on GitHub, for instance).
- `Repository/Repo/Directory` - Simply put it's your 'folder' containing all the files that your coding project holds.
- `Remote (or remote repository)` - A copy of your repository that exists on a server somewhere far away from you (in this case, GitHub's!). Think of the definition of "remote" and that it means something that is away or distant from you and (in this case) your own computer.

</details>

---

## Exercises

1. If you haven't already, download the GitHub Desktop software through [this link](https://desktop.github.com/). _If you're a homebrew-user you can also use this homebrew-cask command and do the installation straight through your terminal by typing:_
   `$ brew install --cask github`

2. Create a new public repository on GitHub. Initialize the repo with a `README.md` file. Don't fill in `.gitignore` or `License` - skip these for now!

3. Clone down the repository you've just made to your local computer. :dancers:

4. Now that it's on your computer - try opening up your repo in VSCode and go to your README.md file. Give your repository a fun title using [Markdown](https://guides.github.com/features/mastering-markdown/).

5. Commit your changes and push them to your remote repository. Now try reloading the GitHub page in your browser and see if your local changes made it to the internet!

6. Wouldn't it be nice to add a `.gif` to our `README.md`? Go to [Giphy](https://giphy.com/) (or your gif-dealer of choice), and find something fun. Paste it on top of your heading you just wrote. Let's try something new this time: instead of writing this in VSCode, try doing this by editing your file [directly on GitHub](https://docs.github.com/en/github/managing-files-in-a-repository/managing-files-on-github/editing-files-in-your-repository).

7. Can you see your new `.gif` if you go back to VSCode? No? Too see changes that have been made away from our local machine (remotely), we need to use something called **fetch origin** and then **pull** in GitHub Desktop. Make it happen, captain! :mage:

8. In VSCode create a so called [.gitignore](https://git-scm.com/docs/gitignore) to your repository folder. Create a second file named `confidential.md` and write a fun fact about yourself in it. List your `confidential.md` within your `.gitignore`.

9. Let's take our updates and publish them up to cyberspace! Third time's a charm! :four_leaf_clover: In GitHub Desktop you should know have some visual information about the changes that have been made in your project folder. Let's commit and push them up to GitHub!

   > Uh, oh! Didn't we just write a fun fact about ourselves that now is public for anyone to see? That's where the magic with `.gitignore` comes in. If we have sensitive or unnecessary data in our projects we can "hide" this information from others by listing it in our `.gitignore` file. The sensitive/unnecessary data will only be accessible locally in your local repo.

10. **Extra:** Look up one of your classmates new repositories they've made today and [fork](https://duckduckgo.com/?q=fork&t=hy&va=g&ia=web) it.

11. **Extra:** Update their `README.md` file by writing something nice about their chosen `.gif` and make a [pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests). Last but not least the original creator can [merge](https://docs.github.com/en/github/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request) the pull request _(P.S. If the merger hasn't recieved any notifications about your pull request, ask them to double check their e-mail.)_. Great job!
