#Git and Githup

###Git is the program that allow to push your code to this website called Githup it also allow you to take other people codes into your computer.this way you can share your code with others.

...
$ Repository is a folder.
$ how to make a Repository
$ cd ..
$ mkdir foldername.
$ ls - empty
$ cd foldername
$ ls- empty
$ mkdir firstRepository
$ cd firstRepository
$ touch README.md
...

###create account from github.com,and then create repository

###this code will be appear
...
$ git init
$ git add README.md
$ git commit -m "first commit"
###when you are here it will ask you email and username like this
...
$ git config --global user.email "you@example.com"
$ git config --global user.name "your Name"
$ git remote add origin https://github.com/hashim2/FristRepository.git//paste it to the $ gitbush is-shift + insert
$ git push -u origin master
...
###local computer----staging---remote###(https://github.com/hashim2/FristRepository.git)



###...
###when adding your repository online with changes

$ git add
$ git commit -m "we have changed something"
$ git push

### working together from perspective of some who does not have main repo
for repo you want to work with