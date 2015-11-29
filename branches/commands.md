$ git status
$ cd patchwork
$ git branch add-ackuser
$ git checkout add-ackuser
$ touch add-ackuser
$ echo ackuser > add-ackuser.txt
$ git status
$ git add add-ackuser.txt
$ git commit -m "adding ackuser"
$ mv add-ackuser.txt contributors
$ git add -A
$ git commit -m "move file into contributors folder"
$ git push origin add-ackuser 
