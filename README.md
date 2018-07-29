# git-commands
Some Useful Git commands for developers

# Creating a new Repo from command line
echo "# git-commands" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/RohitK0608/git-commands.git

git push -u origin master

# Setting your Git username for every repository on your computer
Open Terminal

$ git config --global user.name "<username>"

Verify

$ git config --global user.name


# Setting your Git username for a single repository
Open Terminal

Change the current working directory to the local repository where you want to configure the name that is associated with your Git commits.

Set a Git Username

$ git config user.name "<username>"


# Creating a local branch
git checkout -b feature/feature-one
