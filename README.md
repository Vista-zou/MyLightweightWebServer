#### 1、编译准备工作

post.html 以及 post.cgi需要一定的权限才可以执行。

1、cd  httpdocs

2、sudo chmod 600 test.html

sudo chmod 600 post.html

sudo chmod +X post.cgi

![image](https://user-images.githubusercontent.com/74163396/110725577-ca6cf700-8252-11eb-96af-cdb60cb9442e.png)



3、cd  ../

4、make

5、 ./myhttp



#### 2、资源

默认端口号是6379，默认是test.html界面，同一路径下还有 post.html资源

#### 3、整体过程图

![image](https://user-images.githubusercontent.com/74163396/110725704-fe481c80-8252-11eb-8824-25fce31407ca.png)


![image](https://user-images.githubusercontent.com/74163396/110725757-128c1980-8253-11eb-9547-3ea67aeddef6.png)


![image](https://user-images.githubusercontent.com/74163396/110725785-20da3580-8253-11eb-941b-7913d35fc006.png)


#### 4、整体框架图

![image](https://user-images.githubusercontent.com/74163396/110725836-39e2e680-8253-11eb-824f-23db267cc667.png)

#### 5、参考

非常感谢

<TCPIP网络编程>-韩-尹圣雨

https://www.cnblogs.com/qiyeboy/p/6296387.html

https://www.jianshu.com/p/18cfd6019296
