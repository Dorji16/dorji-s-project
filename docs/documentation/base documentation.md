# My Journey Through Gitlab.
## Introduction.

I am using GitLab for the first time, and at the beginning, it was quite difficult to understand all the different features and concepts. However, with regular practice and by learning from my mistakes, I have gradually improved my understanding and become more comfortable using GitLab.

This document explains my journey of learning GitLab and how I started using it for my project. It covers the basic steps I followed, the challenges I faced, especially with pipeline errors, and some of the difficulties I experienced while writing and organizing project documentation.

## 2. Getting Started with GitLab

To start using GitLab, you first need to create a GitLab account. If you already have an account, you can simply visit the GitLab website and sign in.

GitLab

After signing in, you will be taken to your personal dashboard. From there, you can view your projects, create new projects, manage repositories, and access other GitLab features.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1WA5ystUbvIuZcg9MEcte8i9O-08gXHIm&sz=w400" alt="Profile Photo">
From here, you can start creating your projects, repositories, and designs.

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