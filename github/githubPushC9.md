Add a git remote in the Cloud9 console. Should look like this (replace the git url with your repo url): 

    git remote add origin git@github.com:C9Support/testPush.git 

Add files and commit them:

    git add . 
    git commit -m "First commit"

Push to github: 

    git push -u origin master