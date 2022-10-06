---
layout: default
title: How to Create a PR
nav_order: 7
---

<!-- Edit the content below for the workshop in question. Once you're ready to publish, remove the comment characters e.g. "<!--" at the start and end -->

## Understanding the GitHub flow

**Click here to for [An interactive review of the GitHub Workflow](https://guides.github.com/introduction/flow/)**
  
![GitHub Workflow](./docs/gifs/Gitflow.gif)

**GitHub Steps**
1. [Create Branch](https://seanmcilroy29.github.io/github-training/github_flow.html#2-create-branch) 
2. [Commit Changes](https://seanmcilroy29.github.io/github-training/github_flow.html#3-add-commits)
3. [Open Pull Request](https://seanmcilroy29.github.io/github-training/github_flow.html#4-open-pull-request)
4. [Discuss and review your code](https://seanmcilroy29.github.io/github-training/github_flow.html#5-discuss-and-review-your-code)
5. [Deploy/test changes](https://seanmcilroy29.github.io/github-training/github_flow.html#6-deploy)
6. [Merge branch](https://seanmcilroy29.github.io/github-training/github_flow.html#7-merge)

## 1. The Essential GitHub Workflow
The GitHub flow is a lightweight workflow that allows you to experiment with new ideas safely, without fear of compromising a project.

## 2. Create Branch
When you're working on a project, you're going to have a bunch of different features or ideas in progress at any given time – some of which are ready to go, and others which are not. Branching exists to help you manage this workflow.


> Top Tip - Branching is a core concept in Git, and the entire GitHub flow is based upon it. There's only one rule: anything in the main branch is always deployable. Because of this, it's extremely important that your new branch is created off of main when working on a feature or a fix. Your branch name should be descriptive (e.g., refactor-authentication, user-content-cache-key, make-retina-avatars), so that others can see what is being worked on.


## 3. Add Commits
Once your branch has been created, it's time to start making changes. Whenever you add, edit, or delete a file, you're making a commit, and adding them to your branch. This process of adding commits keeps track of your progress as you work on a feature branch.

Commits also create a transparent history of your work that others can follow to understand what you've done and why. Each commit has an associated commit message, which is a description explaining why a particular change was made. Furthermore, each commit is considered a separate unit of change. This lets you roll back changes if a bug is found, or if you decide to head in a different direction

## 4. Open Pull Request
Pull Requests initiate discussion about your commits. Because they're tightly integrated with the underlying Git repository, anyone can see exactly what changes would be merged if they accept your request.

You can open a Pull Request at any point during the development process: when you have little or no code but want to share some screenshots or general ideas, when you're stuck and need help or advice, or when you're ready for someone to review your work. By using GitHub's @mention system in your Pull Request message, you can ask for feedback from specific people or teams, whether they're down the hall or ten time zones away.

## 5. Discuss and review your code
Once a Pull Request has been opened, the person or team reviewing your changes may have questions or comments. Perhaps the coding style doesn't match project guidelines, the change is missing unit tests, or maybe everything looks great and props are in order. Pull Requests are designed to encourage and capture this type of conversation.

You can also continue to push to your branch in light of discussion and feedback about your commits. If someone comments that you forgot to do something or if there is a bug in the code, you can fix it in your branch and push up the change. GitHub will show your new commits and any additional feedback you may receive in the unified Pull Request view.

## 6. Deploy
With GitHub, you can deploy from a branch for final testing in production before merging to main.

Once your pull request has been reviewed and the branch passes your tests, you can deploy your changes to verify them in production. If your branch causes issues, you can roll it back by deploying the existing main branch into production.

Different teams may have different deployment strategies. For some, it may be best to deploy to a specially provisioned testing environment. For others, deploying directly to production may be the better choice based on the other elements in their workflow.

## 7. Merge
Now that your changes have been verified in production, it is time to merge your code into the main branch.

Once merged, Pull Requests preserve a record of the historical changes to your code. Because they're searchable, they let anyone go back in time to understand why and how a decision was made.

<!--

## Workshop recording

<iframe height="480" width="853" allowfullscreen frameborder=0 src="https://echo360.ca/media/4378b2ec-7d0c-4632-a1e4-5a8076a494da/public?autoplay=false&automute=false"></iframe>

View the original [here](https://echo360.ca/media/4378b2ec-7d0c-4632-a1e4-5a8076a494da/public).


## Workshop slides

<div style="position:relative;padding-top:66.25%;">
<iframe src="//docs.google.com/viewer?url=https://github.com/scds/intro-tableau/raw/main/assets/docs/tableau_20201118.pdf?dl=0&hl=en_US&embedded=true" class="gde-frame" style="position:absolute;top:0;left:0;width:100%;height:100%;border:none;" scrolling="no"></iframe>
</div>
[Download as a PDF](https://github.com/scds/intro-tableau/raw/main/assets/docs/tableau_20201118.pdf)
<br>

## Worksheets
**Coming soon!**

-->
