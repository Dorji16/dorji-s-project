# My Journey Through Gitlab.
## Introduction.

I am using GitHub for the first time, and at the beginning, it was difficult for me to understand all the different features and commands. However, with regular practice and by learning from my mistakes, I have gradually improved my understanding and become more comfortable using GitHub.

This document explains my journey of learning GitHub and how I started using it for my project. It covers the basic steps I followed, the challenges I faced while working with Git and GitHub, and some of the difficulties I experienced when writing and organizing my project documentation.

## 2. Getting Started with GitLab
To start using GitHub, I first needed to create a GitHub account. If you already have an account, you can simply sign in to GitHub.

After signing in, I could access my GitHub dashboard, where I can view my repositories, create new repositories, manage my projects, and access other GitHub features.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1WA5ystUbvIuZcg9MEcte8i9O-08gXHIm&sz=w400" alt="Profile Photo">
From here, you can start creating your projects, repositories, and designs.

## 3. Understanding Git and GitLab

Before working with GitLab, it is important to understand the difference between Git and GitLab.

Git is a version control system that allows you to track changes in your files and code. It helps you keep a history of your work and allows you to return to previous versions when necessary.

GitLab is a platform that uses Git repositories and provides additional tools for collaboration, project management, code review, and automation through features such as Merge Requests, Issues, and CI/CD pipelines.

Understanding this difference helped me understand why I was using Git commands together with the GitLab website.

## 4. Creating a Repository

The next step was creating a repository on GitHub. A repository is where my project files, code, documentation, and the history of changes are stored.

When creating a repository, I needed to choose a name and decide whether it should be public or private.

After creating the repository, I could connect it to my local project and start uploading my files.

## 5. Basic Git Workflow

One of the first things I learned was the basic workflow for sending my local project to GitHub:
Create or edit files → Stage changes → Commit changes → Push changes to GitHub

## Some of the basic Git commands I learned include:
1.git status — checks the current state of my repository.
2.git add — stages changes before committing them.
3.git commit — records the changes in Git history.
4.git push — uploads my commits to GitHub.

Learning these commands was an important step because they allowed me to manage my project and keep my local files synchronized with GitHub.

## Challenges and solutions.

## 1.Commit Failures:

One of the main challenges I faced was when commits failure. This failure prevented me from pushing my code to the repository, which is compulsary for saving changes.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1uefDPRyiJNgQixqrTtSrZ64cqXAjYzrO&sz=w400" alt="Profile Photo">

## How I overcame it?

Branch Issues: Check you are on the correct branch (e.g., main) before pushing the messages. 

When facing pipelines error which could effect the pushing accepting commits, we have to check pipelines status and sometimes you have to check .gitlab-ci.yml mistakes.


## 2.Deployment Issues of pages:

Another challenge was deploying my GitLab Pages. Sometimes, the deployment didn’t show immediately in the deploy page and the “Pages” option wasn’t visible in the page.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=13zS4mCygeoUiQXYu_NIrqiTwpF34jSD1&sz=w400" alt="Profile Photo">

## How I overcame it?

I once again checked my .gitlab-ci.yml file to make sure that the pipeline was correctly set.
Sometimes you just need to wait while the system is deploying their deployment of pages. 
Once the pages are deployed, I can get access my site directly through the Pages URL provided by GitLab.
 
 ## Documentation Site
 These pictures are some of the photo of my documentation site. Allthe things that I write in gitlab will be linked here which means all the things that I have done will be reflected here without manually copying codes.
 
 <img class="profile-photo" src="https://drive.google.com/thumbnail?id=1WNX4euaAglyGNYLQp50Q4Dy61x2W-f_9&sz=w400" alt="Profile Photo">

 
 <img class="profile-photo" src="https://drive.google.com/thumbnail?id=15jO4qJKOfl7D1CTfyw774btAiEvKU3ls&sz=w400" alt="Profile Photo">
 
 Whatever I write in web IDE, everything will show up in my documentation cite. However, to ensure this, I edited the mkdocs.yml file to link my project directly to the documentation site:
 
 <img class="profile-photo" src="https://drive.google.com/thumbnail?id=1_CYnzEpJYg094m2ZIZNhQg-lb-yCdJRC&sz=w400" alt="Profile Photo"> 

## My Takeaways...

1. You have to practice time to time to get comfortable with GitLab.

2. You really need to be patient since deployments may take a quite a few times. 

3. Always double check your branches, commits, and gitlab-ci.yml to prevent errors of pipelines and commits.

4. Use screenshots and notes to track your learnings so that when you write base documentation, it would be easy to find access to informations. 

5. Don't forget to push the commits whenever you change or add some new information in your site. 

## Some Reminders..

1. Commit often: You need to commit frequently since it save changes regularly.

2. Check pipelines: You need to make sure everything runs correctly by constantly checking pipelines because pipelines error happens a lot.