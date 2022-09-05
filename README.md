# Git-Github tutorial

Description :-
* Git tutorial
[link of git_config](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)

## infomation :-

	* Initialize the git --  git init
	* Config-global-git -- 
	    git config --global user.name "Sagar Guttal"
        git config --global user.email saguguttal220@example.com
	        From <https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration> 
	* Git status gives the information of tracking of files or not -- git status 
	* Add file to track -- git add "file name" or git add . (Dot means add all files in the folder)
	* Commit the changes -- git commit -m "commit msg" -m "Description of commit'
	* Branch of git -- git branch
	* Changing the master branch to main -- git branch -m main
	* Which repo of GitHub my files to be push/send specifying the repo -- git remote add origin "Copy of repo link"
	* Staging environment where I am pushing and fetching files/code -- git remote  -v 
    * Finally sending all files from local to github repo -- git push -u origin main
    * Restore the files for untracking from github to stage -- git restore --staged "file name" 
                                                            -- git reset "file name"
    

## Branch and Merge
    * finding the staging branch or active branch -- git branch
    * create a new branch at the current commit -- git branch [branch name]
    * Switching the branches -- git checkout [switching branch name] # After that what ever commit you made this will goes to switched branch
    * merge the specified branch's history into the current one -- git merge [branch name] # after that you can push your code to merged branch
    * list out commit history for currently active branch -- git log
                                                          -- git log -p -3 # last three commit history
