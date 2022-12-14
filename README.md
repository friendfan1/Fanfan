# OurMusic
## 产品概述
- 基于QT带图形界面的音乐播放器
## 目录结构
```  
│  LICENCE
│  README.md
├─build-musicplayer-Desktop_Qt_5_9_0_MinGW_32bit-Release
│  │    ...
│  │  
│  ├─debug // debug生成的文件夹
│  │    ...
│  │
│  │      
│  ├─music //项目存放音乐的文件夹
│  │    ...
│  │      
│  └─release
└─musicplayer  //项目文件
    │    ...
    └─res //图片素材
        ...
```         
## V0.5
- 实现了音乐播放功能，歌曲切换，通过列表点歌功能
## V1.0
- 增加了专辑界面提取显示、歌词同步提取显示
## V1.1
- 修复才进入程序时封面会动的错误，新增了窗口控件自适应
## v1.2
- 新加入了自主设计的软件图标，美化了图标显示效果，~~实现了窗口控件自适应功能~~（由于显示效果不好，已予以取消）
## v1.5
- 增加了列表新增歌曲的功能，增加了删除列表中的歌曲的功能，美化了专辑封面显示效果
## v1.7
- 美化歌词显示效果
## v2.0
- 新加入了新增歌曲时，自动新增同目录下的同名歌词文件
## 参考资料
1. [QT读取MP3信息](https://blog.csdn.net/weixin_37608233/article/details/82930197)
[QT读取MP3信息](https://blog.csdn.net/weixin_33881050/article/details/94761065?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1-94761065-blog-122425190.pc_relevant_multi_platform_whitelistv3&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1-94761065-blog-122425190.pc_relevant_multi_platform_whitelistv3&utm_relevant_index=1)

2. [二进制读取器](https://www.onlinedown.net/soft/118779.htm) //官网无法进入，这是第三方网站，注意辨别

3. [jpeg格式解析可以参考博文](https://blog.csdn.net/u012819339/article/details/46544061)

4. [png格式解析可以参考博文](https://blog.csdn.net/bisword/article/details/2777121)

5. [git中的needs merge问题](https://www.cnblogs.com/zengsf/p/7517769.html)

6. [git强制覆盖本地代码](https://blog.csdn.net/Amnesiac666/article/details/121392833)

7  [查看git日志]git log --pretty=oneline --all --graph --abbrev-commit