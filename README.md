# MovieHeavens
### 基于Pyqt4的电影天堂电影搜索工具

### 关于开发
@change
```
2016-3-25 为了之后添加新的搜索电影的片源,添加将界面跟电影类分离
所有的电影搜索类均继承SearchMovieParent类
2016-3-25 添加新的搜索源-片源网
2016-3-27 使用multiprocessing.dummy添加查询速度,
使用装饰器查看程序运行时间
运行时间:
MovieHeaven    num
0:00:16.968000 4
0:00:07.986000 8
0:00:12.733000 9
pianYuan
0:00:07.824000
0:00:02.770000 8
2016-3-29 解决查询过程中主页面卡顿问题
```
#### 存在的问题
由于python是64位，打包后的程序不兼容32位的操作系统

### 后续更新
重新更新了电影天堂的搜索,片源网的似乎不能访问了，仅支持会员访问

