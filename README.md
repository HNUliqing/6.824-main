#源仓库链接：https://github.com/tjumcw/6.824/tree/main/src/kvRaft

# 6.824
- MIT 6.824 distributed system C++VersionC++版本的6.824分布式系统实现
- 因为没有go的骨架代码以及官方底层代码的支持，很多地方处理起来比较复杂
- 请先看各个LAB的说明文档，若有需要可参考src下的源码
- 整个项目所有LAB都涉及RPC，我个人用的RPC库在LAB1中有详细说明，包括安装方式以及所需的依赖
- 官方只有go的测试程序，我是自己根据各种情况模拟bug进行测试，我自己的想法可能会有漏洞
- 用到了一些测试脚本以及makefile，编译方法都写里面了请自行阅读，MapReduce有一部分写在编译.txt中
- 若要进行测试可以自己写测试代码，若按我的main函数的话，参数要按我给的形式传
- 我自己制造的一些人为bug对参数有特定要求，请仔细阅读源码
- 有问题可以留言，谢谢，有错误也烦请指正
