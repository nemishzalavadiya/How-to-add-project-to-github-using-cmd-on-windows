# How-to-add-project-to-github-using-cmd-on-windows
give knowledge of uploading project to github using cmd on windows

1. install git on windows.

2. press : win + r => write cmd (enter)
  
    git -Version (If works fine then ....,)

   $ git config --global user.name "<name>"
  
   $ git config --global user.email "<email id>"
  
cd/your project directory

 1) git init
 
    - create and initiate the .git folder
  
 2) git add . or git add ['filename']
 
    - add the data to the .git folder
  
 3) git commit -m "My first File"
    
    - add data to the local folder for upload on push cmd
 
 4) git remote add origin https://github.com/yourusername/your-repo-name.git
 
     - link the push/pull request to the .git folder
 
 5) git pull origin master
 
    - remove the restraning the temp push datas
 
 6) git push origin master
 
    - finally, upload it to the resitory.
