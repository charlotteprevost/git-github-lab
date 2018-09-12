<!-- What command do you use to setup a git repository inside of your folder? -->
git init
<!-- What command do you use to ask git to start tracking a file? -->
git add <fileName>
<!-- What command do you use to ask git to move your file from the staging area to the repository? -->
<!-- Commit changes in local repo (prepare them to be sent to GitHub remote repo)  -->
git commit -m "relevant commit message"
<!-- Push changes from local repo to GitHub repo -->
git push <gitHubRemote> <branchName>

🔴 **Commit your work.** 
The commit message should read: 
"Commit 1 - The 1st set of GIT homework answers are complete".

<!-- What command do you use to pull any changes from the master repository into your local repository? -->
git pull <masterRepo:RemoteName> <branchName>
<!-- What command do you use to unstage a file? -->
git reset -- <fileName>
<!-- What command do you use to change your files back to how they were after a commit? -->
git reset HEAD^ --hard
<!-- Why is it important to use -- when changing files back to a previous state? -->
Changing a file back to a previous state requires the use of flags, -- happens to be the syntax required for the reset command flags (according to $ man git-reset)
<!-- Why might you want to reset your files back to a previous commit? -->
Maybe I've realized I haven't modified the files as I wanted.
Maybe I want to add/remove a file to the stage before I commit.
Maybe I want to change the name of the commit.

🔴 ** Commit your work.** 
The commit message should read: 
"Commit 2 - The 2nd set of GIT homework answers are complete".

<!-- What command do you use to create a branch? -->
git branch <branchName>
<!-- What command do you use to use a different branch? -->
git checkout <branchName>
<!-- Why would you want to use a branch other than the default master? -->
To reduce any risks of modifying files (local or remote) that will be later committed. 
A branch is like a harmless sandbox!

🔴 ** Commit your work.** 
The commit message should read: 
"Commit 3 - The 3rd set of GIT homework answers are complete".

<!-- Give an example for when you would use git merge and give an example for when it would be better to submit a pull request to have your branch merged -->
When working alone one can use git merge. When working with other people it might be best to consult with them about the changes that might be made, hence a pull request for a branch merge (don't want to start rearranging the house before talking to the housemates).

<!-- What command do you use to send all of the work that you've done locally to your remote repository? -->
git push <gitHubRemote> <branchName>

🔴 ** Commit your work.** 
The commit message should read: 
"Commit 4 - The 4th set of GIT homework answers are complete".




