# git-command

1. Delete local repo from .git version control (Windows run inside Bash) <br/>
rm -rf .git


2. Create a new repo <br/>
git init


3. Checkout repo from remote <br/>
git clone /path/to/repository


4. Add <br/>
git add .


5. Commit to local <br/>
git commit -m "Commit message"


6. Push changes to remote <br/>
git push


7. Create a new branch named "feature_x" and switch to it using <br/>
git checkout -b feature_x


8. Delete the branch <br/>
git branch -d feature_x


9. Get latest local master branch from remote <br/>
git pull


10. Merge local branch (cd to master first) <br/>
git merge <branch>


11. View git logging in summary <br/>
git log --oneline


12. Discard all local changes to all files permanently <br/>
git reset --hard


13. Add file to .gitignore and remove existing check-in <br/>
git reset file_name_x <br/>
git rm --cached file_name_x <br/>
[Stackoverflow example](https://stackoverflow.com/a/4308645/2965356) 
  

14.
