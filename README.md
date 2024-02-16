# Cherno Alpha



## 项目简介
Cherno Alpha是一个集成了先进AGI的多功能6轴机械臂项目，旨在通过自动化技术提升机器人的适用性和精确性。

## 快速开始
```
git clone https://gitee.com/SpannerJun/cherno-alpha-robot.git
cd cherno-alpha-robot
```

## 特色功能
- 自主坐标系统
- 双目视觉算法
- 模块化互换工具头

## 技术架构
- 运动学模型
- 机械结构设计
- 深度学习模型
- 基于CAN中枢神经系统
- 控制器和驱动器

## 目标

- [X] 电机驱动电路
- [X] RCM(Robot Computing Module)
- [ ] 双目深度相机
- [ ] 不同功能的可互换头部
- [ ] 物品分类


## 关于电路模块

电路为了实现主要的机械臂运动控制功能其实核心就4块板子：

* RCM核心板
* RCM底板
* 步进电机驱动
* 无线显示器

步进电机驱动采用了TMC5240及TMC5160两款斩波驱动芯片，它集成了先进的运动控制功能，允许精确设置位置或速度。并且通过了外置磁编码器对电机实现了闭环控制，保证了机械臂运动精度。步进电机驱动**将会在方案验证完后整理资料进行开源**


## 开发文档
- [Gitee仓库](https://gitee.com/SpannerJun/cherno-alpha-robot)
- [GitHub仓库](https://github.com/SpannerJun/ChernoAlpha-Robot)

## Wiki
- [Wiki](https://gitee.com/SpannerJun/cherno-alpha-robot/wikis/Home)

## 开发日志
- [开发博客](https://www.spannerjun.club/category/Cherno-Alpha/)

## 致谢
我们欢迎所有形式的贡献。特别感谢所有支持者和贡献者。

## 许可证
本项目采用 [MIT许可证](LICENSE)。

## 联系我们
- 电子邮件：spannerjun@icloud.com
- 微信：Spanner_Jun
