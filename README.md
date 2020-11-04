# 编译说明：

- 建议大家还是拉取我的新仓库吧，同时更新两个仓库比较累，教程也要写来写去，新仓库地址：https://github.com/281677160/build-openwrt.git
#
- 以下的说明教程都是在我另外的仓库的，查看说明时候就跳转到另外仓库了，浏览器回退就会回来，别拉取到我说明的仓库，注意了！
#
- Lede源码地址：https://github.com/coolsnowwolf/lede.git
- Lienol源码地址：https://github.com/Lienol/openwrt.git
- Project源码地址：https://github.com/project-openwrt/openwrt.git
- 根目录的Lede、Lienol、Project三个文件夹就代表分别不同的三个源码
#
- 如果你们谁有兴趣的话可以建个群来的，我把群号放这里，有群比较容易沟通，不懂的问都比较有地方问，大家在编译中遇到的问题也比较容易解决
#
- 增加了微信通知跟发布功能，在没有设置好微信通知跟发布的密匙情况下，请勿打开微信通知跟发布功能，要不然直接卡在微信通知那里编译失败了。[[密匙获取跟使用方法](https://github.com/danshui-git/shuoming/blob/master/ms.md)]
#
#
- 1、`注册及登录github账号`《[注册链接](https://github.com)》
#
- 2、`拉取我的仓库到你的仓库`《[拉取仓库教程](https://github.com/danshui-git/shuoming/blob/master/1%E6%8B%89%E5%8F%96%E4%BB%93%E5%BA%93.md)》
#
- 3、拉取仓库后，在lede、Lienol、Project三个源码的文件夹里面‘diy-2.sh’修改登录IP，要编译什么源码就到对应源码文件修改，好等编译完成安装后顺利登录openwrt《[修改跟删除](https://github.com/danshui-git/shuoming/blob/master/%E5%88%A0%E9%99%A4%E5%92%8C%E4%BF%AE%E6%94%B9%E6%96%87%E4%BB%B6.md)》
#
- 4、`启动编译`《[启动教程](https://github.com/danshui-git/shuoming/blob/master/%E5%90%AF%E5%8A%A82.md)》
#
- 5、`SSH远程连接服务器配置固件`《[SSH工具下载](https://github.com/danshui-git/shuoming/blob/master/Putty%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD.md)》《[SSH连接教程](https://github.com/danshui-git/shuoming/blob/master/3SSH%E8%BF%9E%E6%8E%A5%E8%AF%B4%E6%98%8E.md)》,开启SSH远程连接服务修改固件配置，在lede、Lienol、Project三个源码的文件夹里面‘settings.ini’设置，要编译什么源码就到对应源码文件夹开启（默认SSH远程是关闭的）
#
- 6、`配置固件`《[youtube大神的固件配置视频教程](https://www.youtube.com/watch?v=jEE_J6-4E3Y)》《[恩山大神xtwz整理的插件中文对照](https://www.right.com.cn/forum/thread-3682029-1-1.html)》
#
- 7、`完成编译，下载固件`《[固件下载教程](https://github.com/danshui-git/shuoming/blob/master/4%E5%9B%BA%E4%BB%B6%E4%B8%8B%E8%BD%BD.md)》
#
- 8、`安装固件`，安装固件时出现“Please press Enter to activate this console”就表示安装好了，出现这个就不会跑码的，稍等1分钟就可以进入网页了
- 如果会跑码，就耐心等待跑码完成，应该不需要1分钟就能跑完的
#
- 9、当你成功编译一次后，看看这些东西，对你或者有点帮助的
《[定时触发编译说明](https://github.com/danshui-git/shuoming/blob/master/%E5%AE%9A%E6%97%B6%E7%BC%96%E8%AF%91%E8%AF%B4%E6%98%8E.md)》
《[本地提取.config](https://github.com/danshui-git/shuoming/blob/master/%E6%9C%AC%E5%9C%B0%E6%8F%90%E5%8F%96.config.md)》
《[其他说明](https://github.com/danshui-git/shuoming/blob/master/%E5%85%B6%E4%BB%96%E8%AF%B4%E6%98%8E.md)》
《[固件包减负](https://github.com/danshui-git/shuoming/blob/master/%E5%9B%BA%E4%BB%B6%E6%96%87%E4%BB%B6%E5%A4%B9%E6%95%B4%E7%90%86.md)》
《[banner的说明](https://github.com/danshui-git/shuoming/blob/master/banner%E8%AF%B4%E6%98%8E.md)》
#
- 10、建议准备梯子一把，虽然云编译不需要梯子，不过你使用SSH连接、下载固件、打开github网页也是需要梯子比较好的（没有也行，比较卡就是）
#
- 此编译脚本来自[P3TERX大神一键编译脚本](https://github.com/P3TERX/Actions-OpenWrt)，感谢P3TERX大神！！！
