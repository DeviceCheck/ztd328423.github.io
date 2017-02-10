#[个人博客](http://ztd328423.github.io)

### 应用架构
| 类库  | 应用架构|
|-------|---------|
|应用架构采用 [clean 架构](http://fernandocejas.com/2014/09/03/architecting-android-the-clean-way/)|官方介绍|
|Google 提供的 Android 架构 [MVP+Clean](https://github.com/googlesamples/android-architecture/tree/todo-mvp-clean)|github|

<details>
  <summary>展开列表</summary>

### 第三方库
| 类库  | 类库说明|
|-------|---------|
|[leakcanary](https://github.com/square/leakcanary)|检查内存泄露的工具|
|[compile "com.google.guava:guava:20.0"](https://github.com/google/guava) | Guava 库|
|[compile "com.jakewharton:butterknife:8.4.0" ; "com.jakewharton:butterknife-compiler:8.4.0"](https://github.com/JakeWharton/butterknife)|注解,获取视图控件的ID，可以简化代码|
|[compile 'com.android.support:design:24.2.1'](https://design.google.com/)|Google 设计库|
|[compile 'com.google.zxing:core:3.3.1'](https://github.com/zxing/zxing)|二维码|
|[compile 'org.greenrobot:eventbus:3.0.0'](https://github.com/greenrobot/EventBus)|EventBus|
|[compile 'com.alibaba:fastjson:1.2.21'](https://github.com/alibaba/fastjson)|[fastJson解析](http://blog.csdn.net/zadarrien_china/article/details/54630790)|
|[compile 'com.google.dagger:dagger:2.x'](https://github.com/google/dagger)|Dragger2依赖注入|
|[Android-PullToRefresh-master -> library](https://github.com/chrisbanes/Android-PullToRefresh)|PullToRefresh下拉刷新|
|[compile 'com.orhanobut:logger:1.15'](https://github.com/orhanobut/logger)|开源日志库Logger|
|[compile 'com.squareup.okhttp3:okhttp:3.4.2'](http://square.github.io/okhttp/)|Okhttp网络请求|
|[compile 'com.squareup.okhttp3:logging-interceptor:3.5.0'](https://github.com/square/okhttp/tree/master/okhttp-logging-interceptor)|okhttp网络日志拦截器|
|--图片加载框架--|
|[compile 'com.github.bumptech.glide:glide:3.7.0'](https://github.com/bumptech/glide)|Glide图片加载，适用于少量图片加载|
|[compile 'com.facebook.fresco:fresco:1.0.1'](https://github.com/facebook/fresco)|FaceBook出品，适用于大量图片加载|
|[compile 'com.yalantis:ucrop:2.2.0'](https://github.com/Yalantis/uCrop)|图片剪裁库|
|--动画实现--|
|[compile 'com.airbnb.android:lottie:1.0.1'](https://github.com/airbnb/lottie-android)|Lottie 动画实现|
|--数据库--|
|[Android sqlite](https://developer.android.com/training/basics/data-storage/databases.html?hl=zh-cn)|sqlite数据库|
|[classpath "io.realm:realm-gradle-plugin:2.3.0"](https://realm.io/)|Relam移动端的新型轻量数据库(ORM框架)|
|--工具类--|
|[检查网络的工具类](http://www.jianshu.com/p/fa877daf7406)|[当前连接的网络类型检测--github](https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/NetworkUtils.java)|

###Components
| 类库 |  类库说明  |
|-------|------|
|[compile 'com.roughike:bottom-bar:2.1.1'](https://github.com/roughike/BottomBar)|底部导航栏|
|[awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)|UI效果实现|

###博客文章
| 文章  | 说明  |
|-------|-------|
|[Android知识梳理](https://gold.xitu.io/post/587dbaf9570c3522010e400e)|android基本知识|
|[2016 Top 10 Android Library](https://gold.xitu.io/post/587d83d4570c3522010c71b8)|优秀的安卓库|
|[AndroidStudio快捷键](http://jaeger.itscoder.com/android/2016/02/14/android-studio-tips.html)|AndroidStudio|
|[sqlite database数据库升级](https://www.cnblogs.com/liqw/p/4264925.html)|Android sqlite|
|[MVC，MVP, MVVM博客](http://www.ruanyifeng.com/blog/2015/02/mvcmvp_mvvm.html)|Android 架构介绍|
|[Android系统服务一览表](http://blog.csdn.net/zhgxhuaa/article/details/24835065)|Android 系统服务|
</details>
