---
layout: default
---

# Github & Version Control
Version control is very important as it is allows for the mistakes you make to be reversible. Having multiple versions of a work, in this context we are taking about a website, can really help.
For example, you wrote an article about a specific topic. Later on you found out that the article you wrote was invaild. And so with version control, we can simply revert back to the previous version without the article with a click of a button. Instead of having to go back into your code and deleting the article from there. It will be too time consuming.

## Github
Github is a free and open-sourced distributed version control system which will allow you revisions for your code. Git allows for multiple people to work on a single project. This project will be pushed onto a remote repository that can be accessed on their website. Git also allows your to retrieve the repository from their website and edit it locally on your personal computer.

This can be achieved by a series of commands:

|Commands |Usage |
|-------|-------|
|git clone|Copies and downloads a repository to your folder. Fast method to copy existing work.|
|git add|Add any file to your repository in your staging area.|
|git commit|Commits and cofirms the changes made to the local repository, not limited to adding or removing files.|
|git push|Copies the files into the remote repository from the local one.|
|git pull|Bring down the current version of the repository so it can be worked on.|

[GitHub Desktop](https://desktop.github.com/) was used to edit the repository locally.

Github desktop allows you to see the changes made to the repository and will notify the user if any changes were made, when and by who.
(changes.jpeg)

You can select the change your will like to keep or discard by using the checkboxes by the side, right clicking it and click discard changes. If you are satisfied with the changes made, you can click "commit to main" in the bottom left hand corner to upload the changes into the local repository.
(push.jpeg)

Going back to the staging area, when you are ready to copy the changes to the remote repository at git, click push origin to copy the changes over. The changes will be reflected in the history section of Github Desktop.
(history.jpeg)

If you will like to take back some changes that you have already pushed. You can simply right click the changes made and click *Revert this commit*. This return the previous version before the changes is made. Make sure to push to the orign again to confirm the revert.
(revert.jpeg)
