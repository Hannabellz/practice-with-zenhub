# practice-with-zenhub
practicing this fun stuff in a private repo

maybe updating with commands to keep handy?

->First things first, to make sure you are not committing and pushing straight to main or development from the get-go, you'll want to make sure...
    1) The command "git branch branchName" will make a new branch branchName (if it doesn't already exist. If it does exist, it will give you a warning)
    2) The command "git checkout branchName" will make it so you are now in the branch branchName, since the previous step keeps you in whatever branch you were in.
    3) If you ever forget which branch you're in prior to starting to type/code/make any changes, you can just run "git branch" which will show you (at least some of) the list of branches, and highlights which one you are in.
    **You'll want to make sure you are in the correct branch before making any changes. Speaking from experience, it's a real pain to be making edits in the development branch, find out later, and have to find the neatest way to copy all of what you did somewhere else, undo all the changes you had done, switch to the branch you wanted to be in, and put all the changes there. Obviously not impossible, but definitely a pain.

->If I wanted to merge present1 into merging (I want to update merging with what I have in present1), how would I do it?
    1) Make sure that you are in the merging branch (run "git checkout merging")
    2) Run the command "git merge present1"
