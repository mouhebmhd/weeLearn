    Git Workflow 

1. Working Directory => 2. Staging Area => 3.local repo (pc/laptop) => 4.remote repo (github)

1. Working Directory (les modifs lkoll) => 2. Staging Area (li bech yetsajlou) : Git add 
2. Staging Area =>  3.local repo (pc/laptop) : git commit -m "message" (les modifs msajlin fel local)
3.local repo (pc/laptop) => remote repo(github) git push 

git add index.html
git add .  current directory
git add * just files in current directory(no sub-directory)

Git Stash is used to hide local changes 
1. Working Directory : najem na5ter anahom les fichiers li yatl3ou  : We can Select 
2. Staging Area : when commiting , all changes will be transfered to the local repo We cannot Select 

git restore => any modification (not saved) in the working directory  will be removed 
git restore --staged => any modification in the staging area will be restored to the wroking directory


Main                                     testingBranch
C5                                            
C4                                            
C3            git branch testingBranch        C3
C2                                            C2
C1                                            C1
C0                                            C0

git commit -a -m "message" = git add + git commit  
git commit  -m "message" 

Working Directory  ==> Staging Area ==> Local Repo  ==> Remote Repo     
    git add 
                        git commit
                                        git push   


modification 
    git add + git commit + git push (One commit added local + One commit added)
git reset Cancel One or More  Commit (Cancel +1 Commit + Local but not in the remote )