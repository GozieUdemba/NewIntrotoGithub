# **Introduction to GitHub**

## **Table of contents**

1. Introduction

2. What is GitHub

3. Why GitHub

4. Git vs GitHub

5. Clone : How to do cloning

6. Pull request : How to do pull request

7. Commit : How to do a commit

8. GitHub Desktop vs GitHub CLI

9. Conclusion

### **Introduction**

GitHub has become an indispensable tool for software developers. The purpose of this article is to provide some descriptions of GitHub and how to use it. Some definitions and graphic illustrations of GitHub actions such as cloning, commit and pull request will also be presented.

### **What is GitHub**

GitHub is a cloud platform with version control capabilities, for hosting code projects. It allows individuals to collaborate on the same project remotely. GitHub serves as a social network for people to collaborate on the most complex technological projects in the world.

### **Why GitHub**

GitHub has superior version control attributes. Software developers can branch a project, work on it independently online or offline and merge the project. Changes to a project can also be tracked. GitHub has a user friendly interface and makes it easy for even new coders and more experienced ones to use [Git](https://git-scm.com/) for version control and collaboration.

### **Git vs GitHub**

Git is a version control tool that allows the users to modify their work and to track the modifications. GitHub is a cloud platform that allows hosting and management of Git repositories. Both Git and GitHub provide software programmers with version control capabilities which allow the programmers to work on a project at the same time without botching the entire project. GitHub takes it a step further by also providing storage capacity for the projects being worked on. It is also a platform for developers to showcase their work.

| S.No | Git | GitHub |
| --- | --- | --- |
| 1 | Git is a software | GitHub is a service |
| 2 | Git is a command-line tool | GitHub is a graphical user interface |
| 3 | Git is installed locally on the system | GitHub is hosted on the web |
| 4 | Git is maintained by linux | GitHub is maintained by Microsoft |
| 5 | Git is focused on version control and code sharing | GitHub is focused on centralized source code hosting |
| 6 | Git is a version control system to manage source code history | Github is a hosting service for Git repositories |
| 7 | Git was released in 2005 | GitHub was launched in 2008 |
| 8 | Git has no user management feature | GitHub has a built-in user management feature |
| 9 | Git is open-source licensed | GitHub includes a free-tier and pay-for-use tier |
| 10 | Git has minimal external tool configuration | GitHub has an active marketplace for tool integration |
| 11 | Git provides a Desktop interface named Git GUI | GitHub provides a desktop interface named GitHub Desktop |
| 12 | Git competes with CVS, Azure Devops Server, Subversion, Mercurial, etc | GitHub competes with GitLab, GitBucket, AWS Code Commit, etc |

Reference: https://www.geeksforgeeks.org/difference-between-git-and-github/

# **GitHub Actions**

## **Clone**

A clone is a copy. In GitHub a clone is a copy of a repository that is made from GitHub to the local system.

### **How to clone a repository**

1. On GitHub.com, navigate to the main page of the repository.
2. Above the list of files, click  Code.
![Image](https://github.com/GozieUdemba/NewIntrotoGithub/blob/main/annotely_image1.png)

 Reference: https://docs.github.com/assets/cb-20363/images/help/repository/code-button.png

3. Copy the URL for the repository.

     a) To clone the repository using HTTPS, under "HTTPS", click.
     
     b) To clone the repository using an SSH key, including a certificate issued by your organization's  SSH certificate authority, click SSH, then click
     
     c) To clone a repository using GitHub CLI, click GitHub CLI, then click .
![Image](https://github.com/GozieUdemba/NewIntrotoGithub/blob/main/annotely_image2.png)

 Reference: https://docs.github.com/assets/cb-33207/images/help/repository/https-url-clone-cli.png

4. Open [Git Bash](https://www.atlassian.com/git/tutorials/git-bash).
5. Change the current working directory to the location where you want the cloned directory.
6. Type git clone, and then paste the URL you copied earlier.
7. Press Enter to create your local clone.

 Reference: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository


## **Pull request**

A pull request is an occassion where a software developer seeks to add the changes made in a code project, from the local system of the developer to the main repository in GitHub. 

### **How to create a pull request**

1. On GitHub.com, navigate to the main page of the repository.
2. In the "Branch" menu, choose the branch that contains your commits.
![Image](https://github.com/GozieUdemba/NewIntrotoGithub/blob/main/annotely_image3.png)

 Reference: https://docs.github.com/assets/cb-29841/images/help/pull_requests/branch-dropdown.png

3. Above the list of files, click  Pull request.
![Image](https://github.com/GozieUdemba/NewIntrotoGithub/blob/main/annotely_image4.png)

Reference: https://docs.github.com/assets/cb-26570/images/help/pull_requests/pull-request-start-review-button.png

4. Use the base branch dropdown menu to select the branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose the topic branch you made your changes in.
![Image](https://github.com/GozieUdemba/NewIntrotoGithub/blob/main/annotely_image5.png)

Reference: https://docs.github.com/assets/cb-34915/images/help/pull_requests/choose-base-and-compare-branches.png

5. Type a title and description for your pull request.
![Image](https://docs.github.com/assets/cb-28826/images/help/pull_requests/pullrequest-description.png)

Reference: https://docs.github.com/assets/cb-28826/images/help/pull_requests/pullrequest-description.png

6. To create a pull request that is ready for review, click Create Pull Request. To create a draft pull request, use the drop-down and select Create Draft Pull Request, then click Draft Pull Request

![Image](https://docs.github.com/assets/cb-26223/images/help/pull_requests/pullrequest-send.png)

Reference: https://docs.github.com/assets/cb-26223/images/help/pull_requests/pullrequest-send.png



## **Commit**

A commit is a change that is effected to the contents of the file/project.

### **How to do a commit**

1. On GitHub.com, navigate to the main page of the repository.
2. Above the list of files, using the Add file drop-down, click Upload files.

![Image](https://docs.github.com/assets/cb-26342/images/help/repository/upload-files-button.png)

Reference: https://docs.github.com/assets/cb-26342/images/help/repository/upload-files-button.png

3. Drag and drop the file or folder you'd like to upload to your repository onto the file tree.
   
![Image](https://docs.github.com/assets/cb-10159/images/help/repository/upload-files-drag-and-drop.png)

Reference: https://docs.github.com/assets/cb-10159/images/help/repository/upload-files-drag-and-drop.png

4. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file. You can attribute the commit to more than one author in the commit message.

![Image](https://docs.github.com/assets/cb-9378/images/help/repository/write-commit-message-quick-pull.png)

Reference: https://docs.github.com/assets/cb-9378/images/help/repository/write-commit-message-quick-pull.png

5. Below the commit message fields, decide whether to add your commit to the current branch or to a new branch. If your current branch is the default branch, you should choose to create a new branch for your commit and then create a pull request.
   
![Image](https://docs.github.com/assets/cb-32137/images/help/repository/choose-commit-branch.png)

Reference: https://docs.github.com/assets/cb-32137/images/help/repository/choose-commit-branch.png

6. Click Commit changes.

![Image](https://docs.github.com/assets/cb-19765/images/help/repository/commit-changes-button.png)

Reference: https://docs.github.com/assets/cb-19765/images/help/repository/commit-changes-button.png


### **GitHub Desktop vs GitHub CLI**


  * #### **Using GitHub Desktop**
  
  * With GitHub Desktop, you can interact with GitHub using a Graphic User Interface, instead of the command line or a web browser. You can use GitHub Desktop to complete most Git commands from your desktop, such as pushing to, pulling from, and cloning remote repositories, attributing commits, and creating pull requests, with visual confirmation of changes.
  
Reference: https://docs.github.com/en/desktop
  
   1. Click "commit to master"
   2. Click "Push origin" button twice
   3. Done
   
  * #### **Using Git Command line**
  
  * GitHub CLI is a command-line tool that brings pull requests, issues, GitHub Actions, and other GitHub features to your terminal, so you can do all your work in one place. Reference: https://docs.github.com/en/get-started/using-github/github-cli
  
   1. git add filename
   2. git commit
   3. git push origin master
   
### **Conclusion**

GitHub is used by almost all large or remote software development groups because of it's awesome capabilites to facilitate collaboration. 







