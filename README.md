

2. Enable issues: If you don't see the "Issues" tab in the main menu, you should enable it in the repository settings. 
3. Go to the "Issues" tab, and click "Milestones" to add a 0.1.0 milestone and describe it as a consolidated list of issues from your team.  
4. Go to the issues tab you should also create labels for "I Know", "Want to Know", "Don't Understand", and "Master List".  
5. Once you create these labels then go to settings and look for the "Issues Template" and create/edit 4 issue templates that will provide the starting text for each issue filed of that type.  At the bottom of each issue you will see that you can automaticly assign a label to that issue type, so connect the respective labels you created with the 4 issue types.  You need an issue for "I Know", "Want to Know", "Don't Understand", and "Master List".
4. Goto the project tab and create a new project (you have to click the down arrow next to "link project" to change it to new project). When you create a project you need to select "board" and name it "Documentation Tasks".
5. Once this is completed then clone this to your computer using the SSH link **NOT THE HTTP LINK** you need the ssh link to use the key you added to your account, so you don't get an error when pushing.


### Project management and Collaboration workflow Steps
1. create an issue
2. assign issue to project task
*  Assign to yourself
*  Assign to correct project board
*  Assign to "todo" project status
*  Assign to the correct milestone
* create issue branch 
3.  Go to the project board and move the task you created to in progress
4. git fetch origin to see new branch
5. checkout issue branch locally
6. git status to make sure you don't have any changed files in the branch before you work
7. Resolve the issue by adding the list item or incrementing the count of the item
8. commit -a -m "message text" to do the commit 
9. git push origin head <- pushes current branch to github
10. Do a pull request for the branch and make sure you pick the correct source and destination.  Click compare forks because by default it will go to the upstream repository i.e. mine
11.  merge the pull request and add "closes #<issue number> i.e. closes #4 to close the issue
12.  Check that your task is moved from in progress to done
13.  update your local main branch with the changes from the merge by doing git pull origin main
14. Repeat again, and again, and again
=======
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

Things we understand**
1. Python Print[1]
2. Linux Directory listing[2]
3. Docker Installation[1]
 
Things we don't understand**
1. Git Stash[1]
2. GIt pull[2]
3. GIT status[1]
  
 
Things we want to know next**
1. Elastic Search Indexing [1]
2. Cloud deployment with Kubernetes[2]
3. Teraform[1]

