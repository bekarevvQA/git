# 💎 git

I would like to share some Git commands I used to create my GitHub portfolio.

## Navigation

- [Creating, cloning, pushing and pulling repositories](#task-1)
- [Creating, adding remote repositories](#task-2)

## Task 1

##### Creating, cloning, pushing and pulling repositories
```git
git init bekarevvQA                                           # Create a repository with a name identical to your username 
git clone git@github.com:bekarevvQA/bekarevvQA.git            # Copy your repository from GitHub to your computer by cloning it into a separate folder
git clone git@github.com:bekarevvtest/bekarevvtest.git        # Clone github.com/bekarevvtest/bekarevvtest on your computer to a separate folder
cd bekarevvtest                                               # Push data from bekarevvtest repository to your own 
git push git@github.com:bekarevvQA/bekarevvtest.git main:main
git commit -m "changing description"                          # Open the README.md file and make each block a separate commit
git push

```
## Task 2

##### Creating, adding remote repositories
```git
git init proxyman                                                   # Create a dedicated repository for each portfolio item
git remote add proxyman https://github.com/bekarevvQA/proxyman.git  # Declarie repository remotely
README.md edited manually                                           # Add links to your README.md file
git commit -m "changing description"                                # Push changes to remote repository
git push                                                     
