# 这是什么?
简单来说，2017年搞的触动精灵加密脚本还原。
具体点来讲，触动精灵的脚本加密大概分为三种。
从逆向角度来讲，都是修改了lua解释器，在装载的时候根据文件头进行的解密还原，区别是解密的方式不同。  
这里是根据调试结果，模拟的解密过程。  
两年没试过了，也不再更新，如果能看懂代码的，相信再更新也不难。