# TYSnapshotScroll


[English](README_EN.md)|简体中文
## 一句代码保存截图,将scrollView相关的页面保存为图片,支持UIScrollView,UITableView,UICollectionView,UIWebView,WKWebView。
> Save the scroll view page as an image,support UIScrollView,UITableView,UICollectionView,UIWebView,WKWebView。

[![](https://img.shields.io/badge/Supported-iOS7-4BC51D.svg?style=flat-square)](https://github.com/TonyReet/TYSnapshotScroll)
[![](https://img.shields.io/badge/Objc-compatible-4BC51D.svg?style=flat-square)](https://github.com/TonyReet/TYSnapshotScroll)


### 方法一:cocopods
- 1、:

```objc
在Podfile文件里面添加:pod 'TYSnapshotScroll'
```
- 2、:对应文件添加头文件

```objc
#import "TYSnapshotScroll.h"
```

### 方法二:手动添加
- 1、下载TYSnapshotScroll，将TYSnapshotScroll放到工程中

- 2、引入头文件:

```objc
#import "TYSnapshotScroll.h"
```


### 用法
```objc
//在需要截图的地方调用此方法
[TYSnapshotScroll screenSnapshot:yourView finishBlock:^(UIImage *snapShotImage) {
        // doSomething
    }];
```


![TYSnapshotScroll](Snapshot.gif)


