#lesson10笔记

###在github上上传文件夹
    akaedu@akaedu-desktop:~/work$ git commit -a -m "lesson10_2"
    akaedu@akaedu-desktop:~/work$ git push //注意前面路劲
###上传一个文件夹里面有两个文件
    akaedu@akaedu-desktop:~/work$ git add ./lesson10/lesson10_1.md
    akaedu@akaedu-desktop:~/work$ git commit -a -m "lesson10_5"
    akaedu@akaedu-desktop:~/work$ git push

###软件卸载
    sudo apt-get remove --purge packagename(软件名)
    sudo apt-get purge packagename(软件名)

###vimtutor vim学习文档
    akaedu@akaedu-desktop:~$ vimtutor

###接口函数
    man 3 printf(scanf)  或者在函数名上按“K”

###查看工程历史
    akaedu@akaedu-desktop:~$ psjicfh gource  //装软件
    akaedu@akaedu-desktop:~/work/lesson7/lesson7-project$ gource  //注意路径

###给master作备份
    akaedu@akaedu-desktop:~/work/lesson7/lesson7-project$ git branch
    * master
      one_file_stare
    akaedu@akaedu-desktop:~/work/lesson7/lesson7-project$ git checkout -b tmp //注：此处可省略40位版本号
    Switched to a new branch 'tmp'
    akaedu@akaedu-desktop:~/work/lesson7/lesson7-project$ git branch
      master
      one_file_stare
    * tmp
    akaedu@akaedu-desktop:~/work/lesson7/lesson7-project$ git checkout master 
    Switched to branch 'master'
    akaedu@akaedu-desktop:~/work/lesson7/lesson7-project$ git branch
    * master
      one_file_stare
      tmp

###学习书籍
http://billie66.github.com/TLCL/book/    vim的

http://progit.org/book/zh/               git的
