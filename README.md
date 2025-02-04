# 空洞骑士计时器生成器（中文版）

![](https://img.shields.io/github/languages/top/CuteReimu/hksplitmaker "Language")
[![](https://img.shields.io/github/workflow/status/CuteReimu/hksplitmaker/Go)](https://github.com/CuteReimu/hksplitmaker/actions/workflows/golangci-lint.yml "Analysis")
[![](https://img.shields.io/github/license/CuteReimu/hksplitmaker)](https://github.com/CuteReimu/hksplitmaker/blob/master/LICENSE "LICENSE")

<img src=".github/hksplitmaker.png" alt=""/>

## 使用前请检查版本号

使用前打开LiveSplit -> 右键 -> Edit Splits -> Settings，如果在插件设置界面看不到版本号，或者看到的版本号低于本程序的版本号，那么生成出来的文件不一定能够生效。
 
如何升级LiveSplit的空洞骑士插件？一般情况下，打开LiveSplit时就会提示更新。如果没有提示更新，可以向其他人寻求`LiveSplit.HollowKnight.dll`文件，并覆盖到LiveSplit的安装目录下的`Components`文件夹中即可。

## 如何使用

1. 运行`hksplitmaker.exe`

2. 你可以选择一个已有的模板或者打开一个lss文件，也可以自己从头开始编辑

3. 点击右侧的加号和删除可以增加或者删除一行

4. 第一列的文本框里填写自己想要显示的片段名称，第二列的下拉框用来选择在游戏中会自动分割的触发事件。

5. 如果是一个全关速通或者万神殿某一门的速通，不需要勾选`自动开始`

6. 最后一行的复选框的意思是：
   - 如果你想要以**游戏结束**（打出任何一个结局）为计时器结束的标志，那么请勾上这个复选框；
   - 如果你想要以**并非游戏结束**的一个事件作为计时器结束的标志，那么请不要勾选这个复选框。

7. 全部设置好以后，点击下方的`另存为`按钮，即可保存成Splits文件。

8. 打开LiveSplit -> 右键 -> Open Splits -> From File... ，选择刚刚保存的文件即可。

## 如何优化翻译

请不要直接在这个repo修改`translate.tsv`文件，请前往[CuteReimu/hk-split-maker](https://github.com/CuteReimu/hk-split-maker)修改，修改后会自动同步到这里。

## 特别鸣谢

本程序的所有**非代码部分**（图标和模板）全部都来自：https://hksplitmaker.com/

该项目的Github地址是：https://github.com/slaurent22/hk-split-maker