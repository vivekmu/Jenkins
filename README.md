--------------------------------------------
create a new repository on the command line
--------------------------------------------
echo "# git-push--u-origin-main" >> README.md
git init
git add README.md
git commit -m "first commit"

-------------------------------------------------
push an existing repository from the command line
-------------------------------------------------
git remote add origin https://github.com/vivekmu/Jenkins.git
git branch -M main
git push -u origin main
