# Git-commands start up
Some Useful Git commands for developers

# Creating a new Repo from command line
echo "# git-commands" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/RohitK0608/git-commands.git

git push -u origin master

# Listing all the configurations for a repository

Open Terminal

Change the current working directory to the local repository where you want to configure the name that is associated with your Git commits.

$ git config --list

# Setting your Git username & email for every repository on your computer
Open Terminal

$ git config --global user.name "myusername"

$ git config --global user.email "myemail@example.com"


Verify

$ git config --global user.name

$ git config --global user.email


# Setting your Git username for a single repository
Open Terminal

Change the current working directory to the local repository where you want to configure the name that is associated with your Git commits.

$ git config user.name "myusername"

$ git config user.email "myemail@example.com"



# Creating a local branch
git checkout -b feature/feature-one
