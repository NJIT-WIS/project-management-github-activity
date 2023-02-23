# MyWebClass Collaboration and Brainstorming Assignment

## Overview

The purpose of this assignment is to practice collaborating using GIT/GitHub and develop the requirements for the mywebclass.org website's tutorials and courses.  To accomplish this task we are going to create three lists(What I Know, What I Don't Know, and What I Want To Learn) and consolidate the items from everyone in the class into a master list that counts the number of repeated issues.  You need at least **3 items for each list for a total of 9 items** and you should plan that these items are going to be used for project 1 as the basis for the possible topics that people can choose to build online tutorials about.   

## Learning Objectives:
1.  You will learn to collaborate online using GIT
2.  You will learn to merge pull requests and resolve merge conflicts
3.  You will learn to manage a basic project using GitHub Project.

### Complete the Assignment By adding your issues to these 3 lists and count how many times each issue is mentioned.  The number in the bracket next to each issue is the count, you should set your count at 1 for your issue.  We need the count of how many times the issue is mentioned, so that we can prioritze each issue.

### Your list should look like this:
#### Things we understand**
1.  Git Commands[1]
2.  Using Docker[2] 
3.  Using GitHub[1]
4.  Oracle Cloud Instances [1]
5.  Flask [1]
#### Things we don't understand
1. What is Webpack and why do we use it?[1]
2. What are docker images, and why are they used?[1]
3. GitHub Workflows[1]
4. Docker vs Kubernetes [1]
#### Things we want to know next**
1.  Cloud Computing [1]
2.  CI/CD[1]
3.  Git Rebasing[1]
4. Nodejs [1]
5. More Frameworks [1]

## Prerequisite - YOU. MUST SETUP PRIVATE PUBLIC KEY AUTH WITH GITHUB OR YOU WILL GET ACCESS DENIED ERRORS WHEN YOU PUSH FROM THE TERMINAL
Add your ssh public key to github - See video
**open powershell or terminal and run "ssh-keygen -b 4096" and hit enter through the prompts and then open the file **your home directory/.ssh/id_rsa.pub** and copy that text into your github account settings under SSH/GPG keys -> add key.  in one of the prompts it will tell you where it is going to save the key.  If you already have a key reusue the one you have and cancel out of the process with control c **.  I do it on my mac with the command vi ~/.ssh/id_rsa.pub" and then i press shift colon : and q to quit

### [Assignment Video](https://youtu.be/UFLKojO3OtM)

## You will accomplish this assignment in 5 phases:

1.  Each person will follow the instructions below to create one issue per list item i.e. 9 issues.
  **You need one issue per item in your list for a total of 9 issues.**.  Resolve each issue to add each of your items to the appropriate list.

2.  Find a person in class and then make a pull request for each item on your list to **THEIR** repository.  **You make 9 pull requests to someone else**

This person should then merge the pull requests and resolve the merge conflict to add new items to their list and increment the count on dupilicate items.  We want to know how many people said the same thing, so that we can prioritize the requirement, when we decide on what to make in project 1.  

3.  **Once you have merged the pull requests from someone else in class**, you need to find someone new in class to submit a pull request called "merge my list".  that asks to merge your master into their master, so that they can add new items to their list and increment the duplicate issue count for each item in the list.  Create an issue using the template "Assignment Master List" and reference the pull request that you make in the issue.  Make sure you make a issue template to accept this issue on your own repository and provide these instructions.

4. The person that receives the pull request from #3 needs to resolve merge conflics and merge, so that the new issues are added and duplicate counts are incrimented as necessary.

5. Once you have merged someone else's combined list into your project make an issue and a pull request to the "complete_list" branch on the upstream repository i.e. the one you forked from. Use the issue "Complete List" and put a link to the pull request.  Submit a link to the **issue** to Canvas to finish the assignment.  In your pull request include your UCID,  course number, and section.  

### You are done when you have completed the following:
 
1.  Added your issues individually and resolved them
2.  Made 9 pull requests to another person for each item that contains the branch you want to merge 
3.  Merged 9 pull requests from someone else
3.  Made a pull request to another person with your master branch that contains the consolidated list 
4.  Merged the pull request of someone elsesa compiled list
5.  Submmited a pull request to this repository to have your complete list merged

### Canvas Submission instructions

To submit this assignment you need to submit the result of step #5 to canvas.  When you look at the commits for your project you should see a total of 3 different users have contributed items to the list **including yourself** .  If you don't have at least 3  people's commits on the project you will lose 33 points for each person not found.

## Project Setup Instructions
Collaborating on GitHub:

1. Fork the repository: Each person should fork the repository to their own GitHub account. To do this, click the "Fork" button in the top-right corner of the repository page.
