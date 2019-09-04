(1) Steps of connecting to github 
(2) push an entire directory(ie. folder) to github
(3) push all things inside the directory to github
(4) disconnect from github 

(1) --------------------------------------------------

1. Makesure git is downloaded  
2. create a directory in terminal
    $vi dir
3. $git init
4. create a readme.txt file 
5. $git add readme.txt
6. $git commit -m "message"
7. git remote add origin git@github.com:HJNVR/game.git (after origin vary)
8. git push -u origin master
9. after -u push , we can just use $git push origin master


(2) --------------------------------------------------
1. just do $git add folder

(3)--------------------------------------------------
$git add --all

(4) --------------------------------------------------
$git remote rm origin 

