# The Ultimate Git and GitHub Developer Guide

Hello everyone! Hope you're doing well. Today we'll learn about Git and GitHub basics and try to deep dive into it. So, what are you waiting for? 😏

![start.gif](https://media.tenor.com/ql-wOB_SKrwAAAAM/lets-get-started-rosanna-pansino.gif align="center")

More or less I hope that you all have heard about Git/GitHub at least once in your lifetime after you got into tech. Let's see its origin and its basics along with use cases.

## What is Git?

Git is a version-control system by which you can track your project state/condition. It was originally authored by Linus Torvalds in 2005 for the development of the Linux kernel, with other kernel developers contributing to its initial development.

A quick story behind it is Linus Torvalds was developing Linux Kernel along with his team and at that time it was tough to track the tasks of each person at the same time and they had to face various problems. Although [BitKeeper](http://www.bitkeeper.org/) *(similar to Git)* existed at that time but it wasn't free to use and has some limitations. Linus wanted a free distributed version control system which gave birth to **Git**.

**According to [Wikipedia](https://en.wikipedia.org/wiki/Git):**

> Git is a free and open source software for distributed version control: tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.

Here some of the terms might be tricky for you which is completely fine if you are a beginner. Let me explain things one by one. 

![here for you.gif](https://media.tenor.com/3KuelwT8Q8oAAAAC/here-for-you.gif align="center")

### Open Source software

**Open Source software** in simple terms means a software/project whose source code is open and accessible to everyone on the internet no matter if the project is small, tiny, or big. These kinds of projects are uploaded on some platforms like [GitHub](https://github.com/), [GitLab](https://gitlab.com/), [Bitbucket](https://bitbucket.org/product/), etc., by the owner of the project or by the organization.

### Version Control

**Version Control** is the process of tracking your source code of a project after every commit. 

Let's say that you're painting something like the below image and committed a mistake.
![painting.gif](https://media.tenor.com/IPq0Hkpjm28AAAAC/alice-in-wonderland-alice.gif  align="center")

Now, can you revert to that version of your painting before you committed the mistake?<br /> You obviously cannot do that. But using Git while developing a project, it's possible. Here comes, Git commands in handy. We'll learn about those commands later on in this article.

Still, having confusion about ***version control***? 🤔 <br />
Check out the following video.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xQujH0ElTUg" title="YouTube video player" align="center" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## What is GitHub?

GitHub is a cloud-based hosting service that lets you manage Git repositories. Either way, you may call it a platform that hosts thousands and thousands of Open Source Projects/Repositories where every repository has lots of files and folders in it required that particular project. You may think of a repository as a folder containing all other files in it. 

You get to know a lot of developers around the world and collaborate with them, connecting on their socials via contributing to each others' open-source projects.

---

## Git Workflow 🎃

A basic git workflow looks like this:
1. Fork repository
2. Clone repository
3. Create a new branch
4. Make Changes
5. Fetch for Incoming Changes
6. Stage and Commit New Changes
7. Create a Pull Request

We often follow these simple steps to make a contribution to Open Source projects on GitHub. ***Hold on, we'll get to know all about them sooner.***

<figure>
<img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1668364305474/9F-m3vMf9.png" alt="git-flow" />
<figcaption align="center">Fig: Git Workflow Diagram &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Source: Google</figcaption>
</figure>

---

## Heads Up to Open Source 🙌

By now we have got through lots of learnings just by reading. I know you're feeling bored now. So, let's do something hands-on and get our energy back.

<img src="https://media.tenor.com/1PbqRCr1QXEAAAAC/duracell-bunny.gif" width="50" height="30" />

We'll start from the basics like setting up Git and forking a repository*(repo in short)* and then making a simple contribution to that particular repo.

### Prerequisities:

1. You must have downloaded and installed [Git](https://git-scm.com/downloads) according to your system(Windows, Linux or Mac)
2. You must have a [GitHub](https://github.com/) account.
3. You should have a code editor like [Visual Studio Code](https://code.visualstudio.com/download) installed on your system.

Next, we'll set up Git locally by logging in within the Git Bash by using the following commands.

- Setup Git username
```bash
git config --global user.name "Susmita-Dey"
```
- Setup Git email
```bash
git config --global user.email "test@gmail.com"
```
- Cache the login credentials in Git Bash
```bash
git config --global credential.helper cache
```

Now first thing first, you should have a repo with your GitHub username on your GitHub account. This will be known as a special repository that will represent your GitHub profile. 

As an example, check out my GitHub profile repo with my username [Susmita-Dey](https://github.com/Susmita-Dey/Susmita-Dey).

If you want to customize your GitHub profile like me, then you make check this course of [Eddie Jaoude](https://www.eddiejaoude.io/) on ["How to customize your GitHub Profile"](https://www.eddiejaoude.io/portal) 

So, now let's move on to searching for some good first repositories to start with. 

### Resources to Find Good First Issues/Beginner-Friendly Repos 📃

1. https://goodfirstissue.dev/
2. https://finder.eddiehub.io/
3. https://up-for-grabs.net/#/
4. https://githubindia.com/
5. https://goodfirstissues.com/
6. https://github.com/topics/good-first-issue
7. https://firstcontributions.github.io/ 

You'll come across a lot of beginner-friendly open-source projects on the above websites and choose one by one among them to start making your contribution.

### Making Contribution To an Open Source Project 🤝

As an example, I'm taking up one of my organization's repositories to show you how to contribute to an open-source project. 

Repository link:- https://github.com/opensourcecommunity-hub/Contribute-To-This-Project-First 

> Note: Before moving on to further steps, for other than this kind of getting-started repositories, kindly find issues/features/bugs in that project which you could improve by making contributions. 

1. **Forking Repository**

Now head over to the repository and first of all, we'll fork them to our account. Here forking repository means creating a copy of the original repository on my account. 

We can do it after going to the repository and then clicking on the fork symbol at the top right corner.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668365060907/uB4ekuTIM.png align="center")

2. **Cloning Repository**

Click on the Code button and a window will open up as in the following image.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668365312310/3P7baAzpm.png align="center")

Here I prefer using an HTTPS link but you may go with SSH or GitHub CLI tools. Now copy the link using the copy icon and it's time to open up Git bash on your local system. 
Put the following command in your Git bash. You may also use any other terminal window *(Command Prompt, Powershell, Terminal, Bash, ZSH)* alternatively to do the same work.
```bash
  git clone https://github.com/YOUR_GITHUB_USERNAME/Contribute-To-This-Project-First.git
```
Here in the place of `YOUR_GITHUB_USERNAME` put your GitHub username and then hit Enter on your keyboard. Wait for some time and you'll see something like the image below.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668403063674/AhbvmhQLK.png align="center")

3. **Create a new branch**

Now before creating a new branch we have to enter that folder and add upstream. Now in your terminal, type this command and hit enter.

```bash
  cd Contribute-To-This-Project-First
git remote add upstream https://github.com/Susmita-Dey/Contribute-To-This-Project-First.git
```

Here the `upstream` command is required to pull in changes from the main repo directly into our local repository. 

Now use the following command to create a new branch.

```bash
  git checkout -b <name-of-new-branch>
```

Here instead of `<name-of-new-branch>` you may give any name of your choice such as `typo-fix`, `Name-patch-1`, etc.  Your username would make a good branch because it's unique.

As an example, I have done this.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668405230626/b4JXFd597.png align="center")

>💡**Important**: I guess many of you are thinking that why creating a new branch is required as we can work on the *default* `main` branch itself. So, here's why. Branches isolate your development work from other branches in the repository. For example, you could use a branch to develop a new feature or fix a bug. You always create a branch from an existing branch. Typically, you might create a branch from the default branch of your repository. You can track your changes while developing using various branches.

If you want to know more about this topic, then you should learn about Git Branching Strategies. Take this [tutorial guide](https://www.atlassian.com/git/tutorials/using-branches) as a reference. 

4. **Make Changes**

Now we have switched to a new branch from the main branch, we'll make some changes. Before this one important task is to be done i.e., fetching upstream to keep track of the incoming changes and merge them into our repository. The following command will help you to do so.

```bash
git fetch upstream
git merge upstream/main
```

Alternatively method:

```bash
git pull
```

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668405311092/CIzmgwHgV.png align="center")

As you can see, here a change has been made in the original repository and we have pulled and merged those changes locally.

<iframe src="https://giphy.com/embed/cFkiFMDg3iFoI" width="480" height="269" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/git-merge-cFkiFMDg3iFoI">via GIPHY</a></p>

Now without closing your terminal, open up this folder in your favorite code editor or IDE. I'll be using Visual Studio Code here. Now, this is my current folder structure.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668405507921/VFZ97Dyuq.png align="center")

Inside the `public/data` folder, I'll be creating a new file as `Susmita.yml` and you'll be putting your name instead of mine. Now, in this file just copy the following syntax and make the changes and save the file.

```bash
name: Martin Developers
bio: Software Developer
skills:
- Python
- Perl
- pascal
location: India
interest: Web Development
```

I have done something like this:

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668405779408/uHA_HEnIG.png align="center")

5. **Fetch for Incoming Changes** 

Before committing and updating our forked repository, we should always fetch for incoming changes to avoid merge conflicts. 

```bash
git fetch upstream
git merge upstream/main
```

You might be thinking what the hell is this merge conflict now? 🤔
<iframe src="https://giphy.com/embed/tzNyMk9OxjDVu" align="center" width="270" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/cute-bear-fighting-tzNyMk9OxjDVu">via GIPHY</a></p>

You could think of a fight between incoming changes and the changes you made as if both are fighting to get the first place in the repository.

This [article by freecodecamp](https://www.freecodecamp.org/news/resolve-merge-conflicts-in-git-a-practical-guide/) will help you to learn about merge conflicts and the ways to face them if any happen in the near future.
<iframe src="https://giphy.com/embed/VePtB3roynxfLYicuV" align="center" width="270" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/MeeshoTech-code-pull-github-VePtB3roynxfLYicuV">via GIPHY</a></p>

6. **Stage and Commit New Changes**

Let's go back to our terminal and run the following commands.

```bash
   git add  public/data/Susmita.yml
``` 

*Note that I'm adding my file with my name and you should use your file name instead of `Susmita.yml`*

Let's commit our changes.

```bash
  git commit -m "Add <your-github-username>"
``` 

Here give your username instead of `<your-github-username>`. 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668407754364/C0iMqbhEy.png align="center")

Now, check the status of your repository.

```bash
  git status
``` 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668407824587/Y76QTQs-G.png align="center")

It's time to push our changes to our forked GitHub repository.

```bash
  git push origin <name-of-your-branch>
``` 

Here instead of `<name-of-your-branch>`, you'll give the branch name you're working on till now. For my reference, I've used `git-tut` and you can see the output as in the following image.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668407943816/d7Nfjq4xF.png align="center")

7. **Create a Pull Request**

Now head over to your forked repository and you may something like the following image. For mine, it's showing my branch name `git-tut`. It could be something else for you.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668408079754/I54d1Fp7C.png align="center")

Now click on the **Compare & Pull Request button** and you may see something like this.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668408256245/v0QStuIJ6.png align="center")

Here, add your commit message at the top and write some comments in the larger box about the changes you made and click on the **Create Pull Request button**.  You should wait for some days to get your PR reviewed by the project maintainer and merged. 

Here's a complete guide on "[How to write Good Commit messages and Pull Requests Best Practices](https://www.freecodecamp.org/news/git-best-practices-commits-and-code-reviews/)". This will help you to learn the perfect way of writing good commits and code reviews.

> Note: The maintainer might ask you to make some required changes in your PR. In that case, you have to make those changes first and make your PR ready to be reviewed again and merged.

After it gets merged, it will show up like this:

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668408711078/gn7Y6Prgo.png align="center")

Let's have party 🥳🎈🎉🎊 Congratulations on getting your first PR merged.

![dance.gif](https://media.tenor.com/bI99D4EN9WcAAAAC/merged-pull-request.gif  align="center" )

---

## Git cheatsheet 🗒️

A cheat sheet full of git commands always comes in handy. So, here I have shared an image with you. Alternatively, you may download the [PDF version of the Git cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf).

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668353437970/QGrnKkm3H.png align="center")

You may also check out this [article from FreeCodeCamp](https://www.freecodecamp.org/news/git-cheat-sheet/).

---

## Hands-on resources 📒

Following are some hands-on resources that will help you make your git and GitHub skills stronger.

1. GitHub's interactive courses that are designed for beginners and experts:- https://skills.github.com/

2. @[Kunal Kushwaha](@kunalk) Git Tutorial :- https://youtu.be/apGV9Kg7ics 

3. GitHub Actions Tutorial:- https://youtu.be/R8_veQiYBjI 

4. Git For Professionals:- https://youtu.be/Uszj_k0DGsg 

---

## Do's ✅ & Dont's ❎ While Making Contributions

I'd love to share some tips and hacks with you that helped me personally to level up my Open Source journey.

- Before contributing to the project, you should first go through the `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md` files. Both of these files contain contributing guidelines and code of conduct rules for the project which you should follow.
- Find a new feature/bug/docs fixes first and during this process, you should take a look at the existing *Issues* and *Pull Requests* once. In this way, you may find some issues that have not been fixed/taken up by someone which you may take up to solve it.
- Always create issues and let the maintainers know about the feature or bug fix you wanna make in the project and get assigned first before making any pull request(PRs).
- You should behold your patience. If you have made an issue today morning, then wait for 2-3 more days to get assigned by the maintainers of the project. If you have created a PR today then you should have at least wait for 10 days to get reviewed and merged.
- If the project you're contributing to, doesn't have active maintainers for more than a week after you created an issue, then I'd recommend not contributing to that project and moving to a new one.
- It's always better to get in touch with the maintainers of the project you're contributing to via their socials. This will help your contribution to get reviewed and merged faster in that project and this also shows that you're eager to help the maintainer of the project in improving it.
- While you can always ask for help, you should not disturb the maintainers by messaging them repeatedly at once. I believe all have their respective work in their personal lives or they might be ill. So, you have to work on keeping things in mind.

- A famous quote by me: 
> "More green squares 🟩 = More Open Source = More GitHub contributions"

This is okay but don't go crazy behind it because apart from these you might also be having your work and studies and you need to focus on them too. 😊

---

## Benefits of Contributing To Open Source Projects

- You come across various developers all over the world.
- Helps you make your profile stronger
- Creates an eagerness to learn a new tech stack or a programming language and contribute to a new project.
- Gives you exposure to the tech world and leverages your profile.

---

## Open Source Programs

Open Source Programs are the best practices to join in and connect with various folks and project maintainers while contributing to different projects and leveraging up the GitHub contribution graph. Some open source program offers swags to the top contributors and certificates for all. There are also some Open Source programs like **Google Summer of Code(GSoC)** that provides stipend. 

Some of them are listed below.
- [Google Summer of Code(GSoC)](https://summerofcode.withgoogle.com/)
- [GirlScript Summer of Code(GSSoC)](https://gssoc.girlscript.tech/)
- [GirlScript Winter of Code(GWoC)](https://gwoc.girlscript.tech/)
- [Hacktoberfest](https://hacktoberfest.com/)
- [Social Summer of Code(SSoC)](https://ssoc.devfolio.co/)
- [Social Winter of Code(SWoC)](https://swoc.getsocialnow.co/#)

Alternatively you may check out this blog on "[25+ Paid Open Source Programs and Internships](https://blog.commclassroom.org/25-paid-open-source-programs-and-internships)" by @[Karuna Tata](@starlightknown).

![open-source.gif](https://media.tenor.com/LOCixsaRx5MAAAAd/freakandy.gif align="center")

---

## Open Source Communities

Communities are a great way to get into Open Source, collaborate and learn with each other. Following are some of the list of Open Source communities on Discord that will help you level up your Open Source journey and career.

1. [EddieHub Community](http://discord.eddiehub.org/)
2. [Community Classroom](https://discord.gg/commclassroom)
3. [4C Community](https://discord.gg/SntDwJgMfS)
4. [Tech With Susmita](https://discord.gg/g7FmxB9uZp)
5. [Major League Hacking](https://discord.gg/mlh)

---

That's all for today. Hope all went well and you enjoyed the article.

Don't forget that **each and every contribution matters neither less of being small or big, code or low-code or documentation fixes**. More powers to you. 💪 

<iframe src="https://giphy.com/embed/287U9qQH5vrKg7KYSH" align="center" width="390" height="390" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/jackiejameswhiskey-good-luck-crossing-fingers-cross-287U9qQH5vrKg7KYSH">via GIPHY</a></p>

---

## Hope this helps you. Thank you for reading, and let's connect!
Thank you for reading my blog. Feel free to subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCsuzc8lqAbgUYo4yzpjtfSw) and connect on [LinkedIn](https://www.linkedin.com/in/susmita-dey-15a15a210/) or [Twitter](https://twitter.com/its_SusmitaDey).
Also, feel free to [support](https://www.buymeacoffee.com/susmitadey) my work.😊
