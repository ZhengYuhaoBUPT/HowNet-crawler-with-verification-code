# 通过关键词爬虫
键入关键字进行知网爬虫

主要通过python实现代码，主要的依赖库是selenium，pytesseract。

# 为什么有两个函数？
其中爬虫.py是所谓的main函数，实现爬虫的主要功能。
myverify.py是实现验证码识别使用的函数。

因为在我第一次尝试用爬虫.py爬虫的时候发现会出现验证码，也就是所谓的安全检测，于是乎搞了一个验证码检测消除影响。

# 关于验证码安全检测后续
在后面跑程序的时候发现似乎myverify.py程序不要也可以，因为似乎出现了验证码也能爬得下来。。。虽然第一次尝试的时候是爬不下来的。。。相当于白搞（或者说被知网摆了一道）。
不过myverify.py在测试的时候表现还是不错的。
