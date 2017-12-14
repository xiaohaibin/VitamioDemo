# VitamioDemo
Vitamio简介：Vitamio是一个支持所有Android设备的多媒体框架。Vitamio与Android默认的MediaPlayer工作方式相似，但包含更加强大的功能！（注意：Vitamio商业化后个人免费、公司收费）

[vitamio官网](https://www.vitamio.org)

[vitamio SDK地址](https://github.com/yixia/VitamioBundle)

之前开发一个视频播放类的项目，需要实现在线播放的功能，找了很多视频播放框架，觉得Vitamio视频播放框架还不错，也相对稳定，
但是在网上找了很多教程都少之又少，Vitamio官网写的教程也不是很清晰，所以就自己就把Vitamio在github上的demo进行研究，
花了点时间写了个demo出来并且将Vitamio的视频控制器界面进行自定义，支持视频亮度、音量的调节，话不多说，先上效果图。
  
  
### 效果图
  
   ![ABC](http://upload-images.jianshu.io/upload_images/1956769-182cab258d9a3b45.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 
    
### 使用步骤  
  - 引入vitamio SDK的方式有两种：
  - 直接以module的方式引入
  - 通过Complie的方式引入
 作者是采用的第一种方式，下面是一些需要注意的地方：
  - 清单文件配置：

1）权限设置：
```
<uses-permission android:name="android.permission.WAKE_LOCK" />
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
```  
2）application配置：
```
<!-- 必须初始化 -->
<activity    
android:name="io.vov.vitamio.activity.InitActivity"    
android:configChanges="orientation|screenSize|smallestScreenSize|keyboard|keyboardHidden|navigation"    
android:launchMode="singleTop"    
android:theme="@android:style/Theme.NoTitleBar"    
android:windowSoftInputMode="stateAlwaysHidden" />
```
  
### 关于我
  

* **Email**: <xhb_199409@163.com>
* **Home**: <http://www.jxnk25.club>
* **掘金**: <https://juejin.im/user/56fcba0a71cfe4005ca1a57b>
* **简书**: <http://www.jianshu.com/users/42aed90cf5af/latest_articles>



## 如果觉得文章帮到你，喜欢我的文章可以关注我和朋友一起运营的微信公众号，将会定期推送优质技术文章，求关注~~~##

![欢迎关注“大话安卓”微信公众号](http://upload-images.jianshu.io/upload_images/1956769-2f49dcb0dc5195b6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

License
--
    Copyright (C) 2016 xhb_199409@163.com

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
  

