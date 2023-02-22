# MyWebClass collaboration and brainstorming activity to identify required content for mywebclass

### Learning Objectives:

1.  You will be able to create an issue
2.  You will learn to fork a github repo
3.  You will be able to to create a project and a task
4.  You will be able to create a branch and check the branch out for development
5.  You will learn to create a pull request 
6.  You will learn to generate an SSH key and add it to GitHub
7.  You will learn to merge pull requests and resolve merge conflicts
8.  You will learn to manage a basic project using GitHub Project.

## Overview

The purpose of this assignment is to practice collaborating using GIT/GitHub.  To accomplish this task we are going to create three lists(What I Know, What I Don't Know, and What I Want To Learn) that consolidate the items from everyone in the class.  You need at least 3 items for each list and you should plan that these items are going to be used for project 1 as the basis for the possible topics that people can choose to build online tutorials about.   In project one each person will need to create 3 tutorial (one item from each list).  You should develop your issue templates to collect the information from someone filing an issue that you might want to know to develop the correct tutorial article.

## We will accomplish this project in 5 phases:

1.  Each person will follow the instructions below to create issues -> project task -> issue branch -> fetch -> checkout issue branch -> resolve issue -> commit -> push branch -> pull request -> merge & close issue-> update master locally -> repeat

2.  Find a person in class and then make a pull request for each item on your list to THEIR repository. Create an issue using the template "Submitting Assignment List" and reference the pull request that you make in the comment.

This person should then merge the pull requests and resolve the merge conflict to add new items to their list and increment the count on dupilicate items.  We want to know how many people said the same thing, so that we can prioritize the requirement, when we decide on what tutorials to make in project 1.  

3.  Once you have merged the pull requests from someone in class, you need to find someone new in class to submit a pull request called "merge my list".  that asks to merge your master into their master, so that they can add new items to their list and increment the duplicate issue count for each item in the list.  Create an issue using the template "Submitting Assignment List" and reference the pull request that you make in the comment.

4. The person that receives the pull request from #3 needs to resolve merge conflics and merge, so that the new issues are added and duplicate counts are incrimented as necessary.

5. Once you have merged someone else's list into your project make a pull request on this repository that asks to merge your list into the branch "complete_list".  Submit this pull request to canvas to finish the assignment.  Create an issue using the template "Submitting Assignment List" and reference the pull request that you make in the comment.

### You are done when you have completed the following:
 
1.  Added your issues individually and resolved them
2.  Made pull requests to another person for each item that contains the branch you want to merge 
3.  Made a pull request to another person with your master branch that contains the consolidated list 
4.  Merged the pull request of someone with a compiled list
5.  Submmited a pull request to this repository to have your complete list merged and create an issue using the template "Submitting Assignment List" and attach the pull request to the issue.

### Submission instructions

To submit this assignment you need to submit the result of step #4 to canvas.  When you look at the commits for your project you should see at least 3 different users have contributed items to the list.  If you don't have at least 3 different people's commits on the. project you will lose 33 points for each person not found.

### Each list should look like this:

### Things I know
1. Creating an SSH public key[2]. <-count of duplicated issues should be in brackets
2. Setting up a Traefik 

## Prerequisite
Add your ssh public key to github

## Instructions
Collaborating on GitHub:

1. Fork the repository: Each person should fork the repository to their own GitHub account. To do this, click the "Fork" button in the top-right corner of the repository page.
2. Enable issues: If you don't see the "Issues" tab in the main menu, you should enable it in the repository settings. Go to the "Issues" tab, and click "Milestones" to add a 0.1.0 milestone and describe it as a consolidated list of issues from your team.  On the issues tab you should also create labels for "I Know", "Want to Know", and "Don't Understand".  Once you create these labels then go to settings and look for the "Issues Template" and create 3 issue templates that will provide the starting text for each issue filed of that type.  At the bottom of each issue you will see that you can automaticly assign a label to that issue type, so connect the respective labels you created with the 3 issue types.
3. Create one issue per item in your list and assign it to the correct issue template.  
4. Create a new project tab and create a new project (you have to click the down arrow next to "link project" to change it to new project). When you create a project you need to select "board" and name it "Documentation Tasks".
5.  Go back to your issues, click on each issue, and assign the issue to the following: assignee i.e. you, miletone i.e. the one you created 0.1.0, project documentation (set the status to todo) and create the branch for the issue.
4. Go to the "Project" board, and if you see any tasks without a status move them to the todo column.  
5. Pick one task and move it to the in progress column to indicate you are going to work on it.
6. If you have not done so already clone the repository to your local and type "git fetch" to see the branch(s) for the issues you created. 
7.  Do a "git checkout <name of branch>" i.e. "git checkout 1-some-issue".
8.  Complete the issue by adding one item to one of the 3 categories.  Do a git status and make sure that only the readme is changed.  If the readme just has the change then you can do a git commit -a -m "PUT A DESCRIPTIVE MESSAGE HERE".  git commit with the -a flag adds all the new and modified files to the commit.
9. Push the branch back by doing a git push origin head or use the push command from the drop down in Pycharm.  
10.  Make a pull request (MAKE SURE YOU DO IT FOR YOUR OWN IT WILL DEFAULT TO MAKING A PULL REQUEST TO THE UPSTREAM REPOSITORY" for the branch and when you come to the part where you have to need the commit message you have to add "closes #?"  the ? is whatever issue number that the pull request resolves.
11.  Check the documentation board and you should see that the task has moved from in progress to done.
12.  Once you have resolved an issue you should go to your partners' fork and make a pull request that to merge your issue branch.  
13.  Your partner will then need to create an issue to merge the pull request.  You first need to save an issue and after you save it will make the right side controls active and you can select the repository / pull request you want to link and fill out the other fields like assigning the task to the milestone, assigning a developer, assiginging it to the right project with the todo status.
14. Once your partner creates the issue they need to merge the pull request and close it with the "closes #?" in the merge message.
15. On your own fork, you will want to make a pull request to yourself to merge their updated master into yours.


# Complete the Assignment By adding your issues to these 3 lists.

## Put your items here
### Things you understand so far
1. How to containesise a docker image
2. How to collaborate with the team using version control
3. How to fork and pull request on git 
### Things you don't understand about what we are doing / web development.
1. How to configures docker images for various applications
2. How to create a test case to validate the integrity of the code
3. How to write test cases to for web pages
### Things you want to know next
1. How to create new VMs and configure them in AWS 
