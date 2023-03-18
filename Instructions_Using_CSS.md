This example list the steps to create website usign CSS template.

STEPS:
(1) Create your domain using your username in Github.
  (1.1) Click on Repository --> Crreate New Repository
  (1.2) Repository name: username.github.io
  (1.3) Create Repository
 
 (2) Download wesite template. You can download free templates from [here](https://www.free-css.com/ "text")
 
 (3) Upload the html and CSS files. 
    (3.1) You can modify the files directly on github and commit the changes. Actions tab can be checked to see the upload progress.
    
    (3.2) Another way is to use command line / terminal from your computer.
      (3.2.1) Copy the github repository path.
      (3.2.2) Open the terminal or command prompt. type 'git clone repostoryPath'
         - repostoryPath is the path copied from github.
      (3.2.3) It would create a folder in your current path. Type 'cd usernameFolder' to go inside the folder.
      (3.2.4) Make changes in the .html file as per your choise, using any test editor and sabe the file.
        (3.2.4.1) To comment any line in.html use '<!-- This is a comment -->'
      (3.2.5) type 'git add .' in the termnial to ammend all the files.
      (3.2.6) Type 'git commit -m "First commit"'
      (3.2.6) Tpye 'git push origin main'
    (3.3) To track changes and difference in file
      (3.3.1) Type 'git status' to check status of the file.
      (3.3.2) Type 'git diff' to track changes in the file.
