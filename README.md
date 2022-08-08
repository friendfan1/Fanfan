# OurMusic
## 产品概述
- 基于QT带图形界面的音乐播放器
## 目录结构
│  README.md
│  
├─build-musicplayer-Desktop_Qt_5_9_0_MinGW_32bit-Release
│  │  Makefile
│  │  Makefile.Debug
│  │  Makefile.Release
│  │  object_script.musicplayer.Debug
│  │  object_script.musicplayer.Release
│  │  ui_mainwindow.h
│  │  
│  ├─debug // debug生成的文件夹
│  │
│  │      
│  ├─music //项目存放音乐的文件夹
│  │
│  │      
│  └─release
└─musicplayer
    │  config.h
    │  cover.cpp
    │  cover.h
    │  lyricwidget.cpp
    │  lyricwidget.h
    │  main.cpp
    │  mainwindow.cpp
    │  mainwindow.h
    │  mainwindow.ui
    │  mainwindow_BACKUP_1276.cpp
    │  mainwindow_BASE_1276.cpp
    │  mainwindow_LOCAL_1276.cpp
    │  mainwindow_REMOTE_1276.cpp
    │  mp3header.cpp
    │  mp3header.h
    │  musicplayer.pro
    │  musicplayer.pro.user
    │  musicplayer.pro.user.763bf7a
    │  musicplayer.pro_BACKUP_1080.user
    │  musicplayer.pro_BASE_1080.user
    │  musicplayer.pro_LOCAL_1080.user
    │  musicplayer.pro_REMOTE_1080.user
    │  res.qrc
    │  stylus.cpp
    │  stylus.h
    │  stylusandrecord.cpp
    │  stylusandrecord.h
    │  
    └─res //图片素材
            10001.jpg
            left.png
            pause.png
            record.png
            right.png
            start.png
            stylus.png
            volume.png
            volume_muted.png
## V0.5
- 实现了音乐播放功能，歌曲切换，通过列表点歌功能
## V1.0
- 增加了专辑界面提取显示、歌词同步提取显示
## 参考资料
1. [QT读取MP3信息](https://blog.csdn.net/weixin_37608233/article/details/82930197)
[QT读取MP3信息](https://blog.csdn.net/weixin_33881050/article/details/94761065?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1-94761065-blog-122425190.pc_relevant_multi_platform_whitelistv3&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1-94761065-blog-122425190.pc_relevant_multi_platform_whitelistv3&utm_relevant_index=1)

2. [二进制读取器](https://binary-viewer.en.softonic.com/)

3. [jpeg格式解析可以参考博文](https://blog.csdn.net/u012819339/article/details/46544061)

4. [png格式解析可以参考博文](https://blog.csdn.net/bisword/article/details/2777121)
