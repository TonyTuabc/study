#If not first time and changed
git add readme.txt
git commit -m readme.txt
git push origin master

#If the first time
git init
git remote add origin https://github.com/tugenhua0707/testgit.git #http relies on repository in Github
git add readme.txt
git commit -m readme.txt
git push -u origin master
