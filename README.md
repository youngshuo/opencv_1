# opencv_1
Linux 下用命令行编译显示图片   
gcc Test.c -o Test `pkg-config --cflags --libs opencv`     
 ./ xxx.jpg  
 选项--cflags 它是用来指定程序在编译时所需要头文件所在的目录,选项 --libs则是指定程序在链接时所需要的动态链接库的目录  
 

