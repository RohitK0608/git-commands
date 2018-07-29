# git-commands
Some Useful Git commands for developers

# Creating a new Repo from command line
echo "# git-commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/RohitK0608/git-commands.git
git push -u origin master

# Creating a local branch
git checkout -b feature/feature-one
