# IDE_Config
在android studio gradle构建工具中，每一次都需要添加第三方库，十分繁琐，本操作依赖远程gradle文件，省略了手动添加的操作，其它可以根据实际情况自行添加生成
```
在app相关模块的build.gradle中添加
apply from:'https://raw.githubusercontent.com/top2015/IDE_Config/master/config.gradle'
```
=======
如下图所示<p>
<img src="https://raw.githubusercontent.com/top2015/IDE_Config/master/source/1.png" width = "500" height = "100%" align=center /><p>
<img src="https://raw.githubusercontent.com/top2015/IDE_Config/master/source/2.png" width = "400" height = "200"  align=center />
