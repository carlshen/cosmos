cosmos
======
桃李不言，下自成蹊。

尽自己一份力，让c++的世界变得更美好！

C++开源社区：http://purecpp.org/

深入应用C++11学习总结-代码优化与工程级应用，这本书深刻剖析C++11中最常用的新特性，我边学习边做了一些总结。

请参考博客：https://blog.csdn.net/carlshen/article/details/90755183

感谢原作者，我为了学习，把有些例子重新整理了一下，放在了test_c11目录下面，请参考。

下面是我的一些总结：

改进单例模式，C++11之前，泛型单例的构造函数参数个数和类型是个问题，C++11的可变参数模板正好可以消除这种重复；

改进观察者模式，C++11改进：被通知接口的参数化和std::function来代替继承；通过可变参数模板和完美转发来消除接口变化产生的影响；

改进访问者模式，C++11改进：通过可变参数模板就可以实现一个稳定的接口层；

改进命令模式，要解决命令模式类爆炸问题，关键是如何定义通用的泛化的命令类；C++11改进了；

改进对象池模式，问题：对象用完之后需要手动回收；构造函数参数个数和类型；C++11改进：智能指针；可变参数模板；

