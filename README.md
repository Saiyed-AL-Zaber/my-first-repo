GIT START UP COMMAND FOR NEW REPO

echo "# deleted-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Saiyed-AL-Zaber/deleted-repo.git
git push -u origin main
