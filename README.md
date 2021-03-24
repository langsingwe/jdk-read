### 项目结构
```properties
jdk-read
|_ src
    |_ jdk8:jdk源码
    |_ native:native本地方法源码
    |_ test:测试代码
```

### 阅读方法
1. 下载项目，导入项目，用jdk8目录下的代码，作为jdk源码断点调试，添加注释等，
2. 不知道怎么把jdk8目录设置成源码目录的，可以参考这篇文章：[idea阅读jdk源码环境搭建](https://blog.csdn.net/w139074301/article/details/114981944?spm=1001.2014.3001.5501)
3. 注意：添加注释的时候，尽量不要改变行号，推荐使用行尾注释，否则会影响断点调试

