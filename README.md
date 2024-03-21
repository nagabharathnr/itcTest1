# itcTest1

Git Assignment - Nagabharath

	•	How do you initialize a new Git repository named "project1" on your local machine?
	•		change directory to the folder where reppsoitory is copied and git init
	•	How do you add a new file named "index.html" to the "project1" repository?
			using touch command - touch index.html
			git add index.html (or) git add .
			
	•	How do you stage the changes made to "index.html" for committing?
			git commit -m “<commit message>”
	•	How do you commit the changes made to "index.html" with a commit message of "Add index.html"?
			git commit -m “<commit message>”
	•	How do you view the commit history of the "project1" repository?
	•	How do you create a new branch named "feature-branch" in the "project1" repository?
			git branch feature-branch
	•	How do you switch to the "feature-branch" in the "project1" repository?
			git checkout feature-branch
	•	How do you make changes to "index.html" in the "feature-branch"?
			git merge main
			vi index.html
	•	How do you stage and commit the changes made in the "feature-branch" with a commit message of "Update index.html in feature branch"?
			git add .
			git commit -m “udate index.html în feature branch”
	•	How do you switch back to the main branch in the "project1" repository?
			git checkout main
	•	How do you merge the changes from the "feature-branch" into the main branch?
			git merge feature-branch
	•	How do you resolve any merge conflicts that occur during the merge process?
			in gitHub, we can resolve the comments
	•	How do you view the changes introduced by the merge commit?
	•	How do you create a new tag named "v1.0" for the current commit in the "project1" repository?
			git tag v1.0
			git show (to see the tag)
	•	How do you push the "project1" repository to a remote repository named "origin"?
			
	•	How do you clone the "project1" repository from a remote repository to another machine?
	•	How do you fetch the latest changes from the remote repository to your local "project1" repository?
			cd <location>/project1
			git clone <remote_repository>
	•	How do you pull the latest changes from the remote repository into your current branch in the "project1" repository?
			git pull origin 
	•	How do you create a new branch named "bug-fix" in the "project1" repository based on a specific commit?
			cd <repo_location>/project1
			git branch bug-fix
	•	How do you revert the last commit made in the "project1" repository?

