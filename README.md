# TVBoxOSC
云编译TVbox--M
前提条件：有一github账号（你的账号）(比如ABC)
步骤：
1.	fork 项目https://github.com/Wsine/android_builder   使用这个复刻过来，用这个打包就是debug版（即9M版）
修改android_builder项目下的project-to-build文件里的地址为https://github.com/ABC/CatVodTVOSC（官仓）或者你自己的复刻过来官版的地址

2.	fork 项目https://github.com/CatVodTVOfficial/CatVodTVOSC    这个官仓复刻过来直接打包就是release版（即6M版）

3.	至此，ABC（你的账号）账号下有上述两项目，
https://github.com/ABC/android_builder
https://github.com/ABC/CatVodTVOSC
 
进入点击标注位置文件
 
修改成你自己复制的官仓地址，默认是tvbox官仓地址，可忽略不改
 
进行导出操作，两个图是一样的，中英文对比而已
 

 
 

以下操作只针对此两项目;
3.1修改android_builder项目下的project-to-build文件里的地址为https://github.com/ABC/CatVodTVOSC
3.2修改CatVodTVOSC项目下app/src/main/java/com/github/tvbox/osc/api/ApiConfig.java此文件的127行，把"http://10.80.8.70:8890/baddychen/baddychen.json"改为你自己的接口JSON文件地址
3.3点击android_builder项目的Action，详细操作可参阅https://github.com/Wsine/android_builder的readme，此处特别感谢Wsine！！！当然更感谢CatVodTVOSC项目组所有人！！！
4.	坐等2分钟，下载安装即可最先使用TVbox


改背景：
1.	电脑操作方式
下载后先不要解压，找到apk文件，双击
 
 
 
替换成自己想要的背景图，小编用的是直接命名成png格式的方法，注意文件名和格式不要变
 
效果展示，注意重命名后不要有空格，小编就是因为重命名后里面带了个空格，安装后总闪退
 

2.	mt管理器替换，同时也是使用的重命名为vod_thumb.png格式
①左侧和右侧分别照片apk所在位置和你要使用的图片所在位置
 
②点击apk程序点击查看
 
③找到原背景图所在位置，并删除
 
4.在右侧选中图片点击添加即可
 
⑤注意使用次方法操作后需要签名后才能正常安装
 
