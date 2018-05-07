# IDE_Config
在android studio gradle构建工具中，每一次都需要添加第三方库，十分繁琐，本操作依赖远程gradle文件，省略了手动添加的操作，其它可以根据实际情况自行添加生成
```
在app相关模块的build.gradle中添加
apply from:'https://raw.githubusercontent.com/top2015/IDE_Config/master/config.gradle'
```
### 主要依赖
```
 dependencies{
        implementation 'com.jakewharton:butterknife:8.8.1'
        annotationProcessor 'com.jakewharton:butterknife-compiler:8.8.1'
        implementation 'com.android.support:recyclerview-v7:26.1.0'
        implementation 'com.squareup.retrofit2:retrofit:2.3.0'
        implementation 'com.squareup.retrofit2:converter-gson:2.3.0'
        implementation 'io.reactivex.rxjava2:rxjava:2.1.11'
        implementation 'io.reactivex.rxjava2:rxandroid:2.0.1'
        implementation 'com.github.bumptech.glide:glide:4.7.1'
        annotationProcessor 'com.github.bumptech.glide:compiler:4.7.1'
        implementation 'com.android.support:design:26.1.0'
    }
 ``````
### 主要步骤
--------------------
如下图所示<p>
<img src="https://raw.githubusercontent.com/top2015/IDE_Config/master/source/1.png" width = "500" height = "100%" align=center /><p>
<img src="https://raw.githubusercontent.com/top2015/IDE_Config/master/source/2.png" width = "100%" align=cente/><p>
