# sina-weibo-sdk
[新浪微博sdk](https://github.com/sinaweibosdk/weibo_android_sdk)

公告：由于新浪微博官方的线上服务器出现问题，导致不能远程依赖sdk,
所以在此将新浪微博sdk里的.aar文件发布到maven仓库里，以便于远程链接使用。

- 特别鸣谢: [Bgwan](https://zhuanlan.zhihu.com/p/22351830)
- 参考文章链接：[https://zhuanlan.zhihu.com/p/22351830](https://zhuanlan.zhihu.com/p/22351830)
<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">

使用方式如下：

项目根目录下的build.gradle 添加：

```c
  allprojects {
      repositories {
          mavenCentral()
      }
  }
```

在要使用新浪微博sdk的module或app目录下的build.gradle添加：

```c
  dependencies {
      implementation 'io.github.good-good-study:sina-weibo-sdk:10.10.1'
  }
  ```

- [x] 目前提供的版本号与新浪微博官方sdk的对应关系如下

* [10.10.1 对应新浪微博官方sdk的openDefault-10.10.0.aar](https://github.com/sinaweibosdk/weibo_android_sdk) 
* [10.9.0&nbsp;&nbsp;&nbsp;对应新浪微博官方sdk的openDefault-10.9.0.aar](https://github.com/sinaweibosdk/weibo_android_sdk) 
* [10.8.0&nbsp;&nbsp;&nbsp;对应新浪微博官方sdk的openDefault-10.8.0.aar](https://github.com/sinaweibosdk/weibo_android_sdk) 
* [10.7.0&nbsp;&nbsp;&nbsp;对应新浪微博官方sdk的openDefault-10.7.0.aar](https://github.com/sinaweibosdk/weibo_android_sdk) 
* [9.12.0&nbsp;&nbsp;&nbsp;对应新浪微博官方sdk的openDefault-9.12.0.aar](https://github.com/sinaweibosdk/weibo_android_sdk) 
* [4.4.4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对应新浪微博官方sdk的openDefault-4.4.4.aar](https://github.com/sinaweibosdk/weibo_android_sdk)
