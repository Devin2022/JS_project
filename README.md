# JS_project

Please  find this doc.

//check project status
git log ---> to check commmit in local
1. git status ---> check if files are changed on my local

// Add new created file in git, that does not exist in the system.
2. git add <FILE_NAME>
// Add all files - caution
2. git add .

// TO commit and save the changes do this. 
3. git commit -m "My message"   (eg :  git commit -m "Add login form")
// check if any files are left to commit ---> git status

// Fetch latest changes from server(origin); in case if some other dev has updated some code meanwhile. 
4. git pull origin <BRANCH_NAME>   (eg: git pull origin main)

// Saved the changes in the git server (origin)
5. git push origin <BRNACH_NAME>   (eg: git push origin main)