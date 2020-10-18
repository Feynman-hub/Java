# Java
Java实验

#程序阅读

##实验目的
用类描述计算机中CPU的速度和硬盘容量,要求Java应用程序有四个类，分别为PC，CPU，HardDisk和Test，其中Test是主类。

##实验方法
1.按照教材例子7--9，用eclipse按照实验要求进行实验编写，在完成基本要求的同时，可增加附属要求，完善代码，使程序更加完美。
2.完成程序编写任务后，见文件上传至Github网站中，同时按照实验过程编写Readme，将实验过程记录下来。
3.将Github中Readme的链接上传到云班课，等待老师检查。

##实验过程
实验要求：
① main方法中创建一个CPU对象cpu，cpu将自己的speed设置为2200，
② main方法中创建一个HardDisk对象disk，disk将自己的amount设置为200，
③ main方法中创建一个PC对象pc，
④ pc调用setCUP(CPU c)方法，调用时实参是cpu，
⑤ pc调用setHardDisk (HardDisk h)方法，调用时实参是disk，
⑥ pc调用show()方法。

CPU类要求getSpeed()返回speed的值，要求setSpeed(int m)方法将参数m的值赋值给speed。 
HardDisk类要求getAmount()返回amount的值，要求setAmount(int m)方法将参数m的值赋值 amount。
PC类要求setCPU(CPU c)将参数c的值赋值给cpu要求setHardDisk(HardDisk h)方法将参数h的值赋值给HD，要求show()方法能显示cpu的速度和硬盘的容量。


运行结果：
电脑中CPU的速度为：2200
电脑中的硬盘容量为：200


实验感想：
通过这次实验，让我对于引用类型参数的传值有了进一步的理解。对于包，类的使用方法也更加明确。
明确了对象与类的关系，学习到了许多编程方法，如show（），setSpeed(),setAmount()等方法。
