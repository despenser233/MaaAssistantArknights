# MeoAssistance

A game assistance for Arknights

一款明日方舟的游戏辅助，目前仅支持蓝叠模拟器

龟速开发中……

## 优缺点

- 所有操作，都是点击按钮内随机位置，且模拟泊松分布，不会像鼠标宏一样一直是同一个点，没有封号风险
~~（虽然好像也没听说过谁用鼠标宏被封号的）~~
- 模拟器窗口可以被遮挡，即使全屏看视频、玩游戏，也完全不影响辅助运行
~~（但是模拟器还是不能最小化）~~
- 使用C++ WinAPI开发，效率高，对系统性能占用小

## 使用说明

### alpha_1 版本

1. 使用蓝叠模拟器打开明日方舟，进入有**蓝色的开始行动按钮**的界面，勾上代理指挥
2. 解压压缩包，使用管理员权限，打开"Test.exe"
3. 目前只有最基本的功能，刷完体力自动停，也不会使用体力药，也不会碎石头……

## Todo

~~在做了在做了.jpg~~

- [ ] 图形化界面
- [ ] 功能
    - [ ] 支持剿灭
    - [ ] 支持刷指定次数
    - [ ] 支持使模拟器窗口不可见
    - [ ] 自动吃体力药（根据设置）
    - [ ] 自动吃石头（根据设置，指定数量）
    - [ ] 代理失败的情况
    - [ ] 支持更多模拟器
    - [ ] 支持等级提升
    - [ ] 支持凌晨4点更新数据
    - [ ] 信用访问
    - [ ] 基建收菜
- [ ] 算法
    - [ ] 更换算法为找图，而不是当前的区域相似度对比


## 致谢

感谢以下开源库/API

- WinAPI
- OpenCV
- MeoJson
