
![LZIJ6471](https://user-images.githubusercontent.com/71068380/227551971-bd598483-6a5c-48c9-8324-8d2ec9817215.JPG)


to download the file 
$ git clone git@github.com:maryammohamed198/maryam_mohamed.git
to creat branch1
$ git branch dev
to creat branch2
$ git branch test

to be in dev branch
$ git checkout dev
to creat file in dev 
$touch dev.txt
to be local
$ git add dev.txt
$git commit -m "dev tet"
to be global
$ git push origin dev
  
to be in test branch
$ git checkout test
to creat file in test 
$touch test.txt
to be local
$ git add test.txt
$git commit -m "test tet"
to be global
$ git push origin test

to merge 

  $ git checkout main
  $ git merge dev
  $ git merge test
  $ git push origin main
  
 2- to delete branch
$ git branch -d dev (local)
$git push origin --delete dev (global)

task 2
$ git tag v1.0
$ git push origin v1.0
$ touch README.md file
$ git add README.md file
$ git commit -m "read me file"
$ git push origin main

click on readme file , issue,new issue,copy img , paste img in readme file 

 2- to delete tag
$ git tag -d v1.0 (local)
$git push origin --delete v1.0 (global)
