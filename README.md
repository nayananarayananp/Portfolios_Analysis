# Portfolio_Analysis Documentation
## JupyterLab files
- risk_return_analysis.ipynb
This file demonstrates how to calculate and analyse the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas using JupyterLab.
- Resources/whale_navs.csv
This file contains data of 4 fund portfolios and S&P 500. 


## Git and terminal commands
nayan@NayanaWork MINGW64 ~
$ cd Fintech-Workspace/Challenge/
(base)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ conda activate dev
(dev)
### Create Repo

Created a repo via Github UI and clone to local
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ git clone https://github.com/nayananarayananp/Portfolios_Analysis.git
Cloning into 'Portfolios_Analysis'...
warning: You appear to have cloned an empty repository.
(dev)

```
### Switch to local git repo called Crypto_Arbitrage
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ ls
Challenge2/  Challenge3/  Challenge4/  Crypto_Analysis/  Loan_Analyzer/  Loan_Qualifier/  Portfolios_Analysis/
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ cd Portfolios_Analysis/
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ ls
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ ls
README.md  Resources/  risk_return_analysis.ipynb
(dev)

```

### Organize folders in starter code
Checked git status showing the organized starter code
```
$ git status
On branch master

```

### Add starter code files to git
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        README.md
        Resources/
        risk_return_analysis.ipynb

nothing added to commit but untracked files present (use "git add" to track)
(dev)
```

### Check the files got added
```
git add *
(dev)

nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   Resources/whale_navs.csv
        new file:   risk_return_analysis.ipynb

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git add .gitignore
warning: CRLF will be replaced by LF in .gitignore.
The file will have its original line endings in your working directory
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   README.md
        new file:   Resources/whale_navs.csv
        new file:   risk_return_analysis.ipynb

(dev)


nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(dev)

### Git commit
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git commit -m "Created Jupyter Notebook for portfolio analysis"
[main (root-commit) 2b10257] Created Jupyter Notebook for portfolio analysis
 4 files changed, 3848 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 Resources/whale_navs.csv
 create mode 100644 risk_return_analysis.ipynb
(dev)
```
## Git push
Try pushing to github 
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 503.08 KiB | 16.23 MiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nayananarayananp/Portfolios_Analysis.git
 * [new branch]      main -> main
(dev)
```
### Run program


Running the program with code completed
```
```



### Final commit and push
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   risk_return_analysis.ipynb

no changes added to commit (use "git add" and/or "git commit -a")
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ git add *
(dev)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        modified:   risk_return_analysis.ipynb

(dev)

$ git commit -m "Final commit"
[main 04228e6] Final commit
 2 files changed, 380 insertions(+), 210 deletions(-)
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 2.75 KiB | 351.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/nayananarayananp/Portfolios_Analysis.git
   2b10257..04228e6  main -> main
(dev)
    

### Capture terminal history
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ history 50 > terminal_history.txt
(dev)
```
Attached to [](./terminal_history.txt)

### Updated the code and added to git
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   risk_return_analysis.ipynb

no changes added to commit (use "git add" and/or "git commit -a")
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git add *
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   risk_return_analysis.ipynb

(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git commit -m "Updated Code"
[main d6c0e31] Updated Code
 1 file changed, 134 insertions(+), 150 deletions(-)
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 203.89 KiB | 8.50 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/nayananarayananp/Portfolios_Analysis.git
   7c8f147..d6c0e31  main -> main
(dev)

### Final changes made
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   risk_return_analysis.ipynb
        deleted:    terminal_history.txt

no changes added to commit (use "git add" and/or "git commit -a")
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git add *
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git commit -m "Final changes made"
[main e6b5ea7] Final changes made
 1 file changed, 104 insertions(+), 110 deletions(-)
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 94.04 KiB | 6.72 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/nayananarayananp/Portfolios_Analysis.git
   daa8987..e6b5ea7  main -> main
(dev)
    
    
    
    
    