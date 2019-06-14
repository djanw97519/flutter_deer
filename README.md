# Flutter Deer

<img src="preview/logo.jpg"/>

本项目为个人Flutter的学习练习项目（暂时不包括网络请求，只有简单的数据处理，主要为UI练习）。

通过设置、修改、组合自带部件以及自定义来实现具体的设计效果，满足日常开发的需求。

本项目设计图见design目录。

## 预览

部分页面效果如下：

| ![](./preview/Screenshot_1.png)    |  ![](./preview/Screenshot_2.png)    | ![](./preview/Screenshot_3.png)   |  ![](./preview/Screenshot_4.png)   |
| :--------------------------------: | :---------------------------------: | :-------------------------------: | :-------------------------------:  |
| ![](./preview/Screenshot_5.png)    |  ![](./preview/Screenshot_6.png)    | ![](./preview/Screenshot_7.png)   |  ![](./preview/Screenshot_8.png)   |
| ![](./preview/Screenshot_9.png)    |  ![](./preview/Screenshot_10.png)   | ![](./preview/Screenshot_11.png)  |  ![](./preview/Screenshot_12.png)  |
| ![](./preview/Screenshot_13.png)   |  ![](./preview/Screenshot_14.png)   | ![](./preview/Screenshot_15.png)  |  ![](./preview/Screenshot_17.png)  |
| ![](./preview/Screenshot_18.png)   |  ![](./preview/Screenshot_19.png)   | ![](./preview/Screenshot_20.png)  |  ![](./preview/Screenshot_21.png)  |

## 实现效果包括

* 输入框等部件的处理封装
* 自定义列表滑动效果
* PopupWindow
* 简易的过渡动画
* 侧滑删除
* 城市选择
* 类似京东的三级联动
* 各种自定义Dialog
* 头部列表吸顶
* 密码输入键盘
* 验证码输入框
* 自定义简易日历
* 曲线图及饼状图

具体可以下载体验：

Android版安装包：[点击下载](https://www.pgyer.com/gYXj)

IOS需要自行下载代码运行。（效果是一致的）

**注意**：

    1. `debug`模式下会有部分卡顿现象，属于正常现象。良好的体验需要打`release` 包。
        IOS可以执行命令`flutter build ios` 以创建`release`版本。
        Android可以执行命令`flutter build apk` 以创建`release`版本。

    2. 因为页面有点多，不清楚业务流程可能会导致部分页面无法找到。具体可以参看设计图，或者页面上都随便点点。。。

**觉得还可以的话，来个Star、Fork支持一波！有问题欢迎提Issue。**

## 项目环境

    1. Flutter version 1.5.4-hotfix.2

    2. Dart version 2.3.0 (build 2.3.0-dev.0.5 a1668566e5)
    
## 使用到的三方库

| 库                         | 功能             |
| -------------------------- | --------------- |
| [flutter_oktoast](https://github.com/OpenFlutter/flutter_oktoast)     | **Toast**       |
| [common_utils](https://github.com/Sky24n/common_utils)                | **Dart 常用工具类库**     |
| [flutter_slidable](https://github.com/letsar/flutter_slidable)        | **侧滑删除**      |
| [flustars](https://github.com/Sky24n/flustars)                        | **Flutter 常用工具类库**       |
| [flukit](https://github.com/flutterchina/flukit)                      | **Flutter UI组件库**       |
| [url_launcher](https://github.com/flutter/plugins/tree/master/packages/url_launcher)   | **启动URL的插件**       |
| [image_picker](https://github.com/flutter/plugins/tree/master/packages/image_picker)   | **图片选择插件** |
| [rxdart](https://github.com/ReactiveX/rxdart)                         | **Dart的响应式扩展** |
| [webview_flutter](https://github.com/flutter/plugins/tree/master/packages/webview_flutter)    | **WebView插件**       |
| [keyboard_actions](https://github.com/diegoveloper/flutter_keyboard_actions)                  | **处理键盘事件**       |
| [sticky_headers](https://github.com/fluttercommunity/flutter_sticky_headers)   | **列表悬浮头**       |
| [azlistview](https://github.com/flutterchina/azlistview)              | **城市选择列表** |
| [date_utils](https://github.com/apptreesoftware/date_utils)           | **常用的日期工具类** |
| [bezier_chart](https://github.com/aeyrium/bezier-chart)               | **曲线图表** |

具体可以参看[pubspec.yaml](https://github.com/simplezhli/flutter_deer/blob/master/pubspec.yaml)文件    

## TODO

已知问题：

    1. ListView在没有设置分割线的情况下，个别Item之间存在大约1像素的间隔。（像素对齐问题）

    2. 输入框在不设置`obscureText`属性的情况下(false)，无法弹出密码模式键盘。


## 心得

- [Flutter开发中的一些Tips](https://weilu.blog.csdn.net/article/details/90546727)

## Thanks For

- [flutter-go](https://github.com/alibaba/flutter-go)

- [flutter_wanandroid](https://github.com/Sky24n/flutter_wanandroid)

- [Flutter-TianYue](https://github.com/ZDfordream/Flutter-TianYue)


## License

	Copyright 2019 simplezhli

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
