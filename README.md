# personal-finance-notebook

This is a personal project to get familiar with collaboration through github and introduce my dad to python. I'll be working with my dad (_Hi Dad!_) to set up a jupyter notebook that reads from a local csv where he tracks expenses and compare these expenses to a monthly budget. 



## To pull remote changes from this master after forking repo
```bash
# Navigate to local repository
cd into/cloned/fork-repo 

# Add this repo as an upstream remote repository
git remote add upstream git://github.com/TifMoe/personal-finance-notebook.git

# Fetch down the changes
git fetch upstream
```

Now your local repository should be up-to-date with any changes made to my remote repo (yay!) but your remote forked repo still won't be up-to-date until you push your changes. In future, I believe you can just enter the following command from your local repository to fetch down changes made to this remote repo:
```bash
git pull upstream master
``` 



## Some helpful commands to reference as you add, commit and push changes to your remote forked repo from a new branch
```bash
# Checkout status to see what files need to be added or committed
git status 

# Create a new branch
git checkout -b BRANCHNAME

# Make sure you're on the branch you want to be on
git branch

# Add files to be committed
git add FILENAME

# Commit files that have been added
git commit -m 'SOME MESSAGE ABOUT THE CHANGES YOU'RE COMMITTING'

# Push local changes you've committed to your remote repository
git push origin BRANCHNAME
```

Then you can navigate to your github page on the web and see your new branch to make a pull request

Other resources for learning git and github:
- [Github Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [CodeAcademy Interactive Github Tutorial](https://www.codecademy.com/learn/learn-git)
- [Github Guides](https://guides.github.com/)
- [Syncing a forked local repo to the original remote repository from command line](https://help.github.com/articles/syncing-a-fork/)

Some resources for python and jupyter notebooks:
- [Jupyter Notebook Tips and Tricks](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)

