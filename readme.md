# FPV小车开源项目

## 项目简介
这是一个基于Xiao esp32s3 sense开发板的FPV小车项目，物料成本约100元。小车能够发出热点，移动设备连接热点后，通过在浏览器输入特定网页进入控制界面，即可实现对小车开灯以及前进、后退、左右转的控制，并且控制界面还能显示小车的实时图传。

![Car-1](.\Img\Car-1.jpg)

## 电控部分构成
- **动力电池**：650mAh 60C 652853动力电池，为小车提供稳定持久的动力。（6元）
- **电源模块**：Type-C 5V充放电一体电源模块，方便充电且能稳定输出5V电压，为各部件供电。（1.5元）
- **LED**：3mm白光发光二极管，可控提供照明。（0.5元）
- **开关**：SS-12F44 立式柄长5MM，控制开机关机。（2元）
- **电机**：716空心杯电机，小巧轻便，响应速度快，能精准控制小车的移动。（3元X4）
- **电机驱动模块**：迷你L298N 2路直流电机驱动模块，可驱动两路电机，实现小车的前进、后退、转向等动作。
- **控制核心**：Xiao esp32s3 sense开发板，具备强大的处理能力和丰富的接口，用于搭建控制逻辑、处理通信以及实现图传等功能。（79元）

## 功能特点
- **热点连接**：小车自身发出热点，无需额外网络环境，移动设备连接后即可进行控制。
- **网页控制界面**：在浏览器输入特定网页地址，即可进入简洁直观的控制界面，操作方便快捷。
- **实时图传**：控制界面可显示小车的实时图传画面，让用户能更直观地了解小车周围环境，增强操控体验。
- **多种控制指令**：可控制小车开灯以及前进、后退、左右转，满足基本的操控需求。

## 项目目标
- 打造一个低成本、高性能的FPV小车，为DIY爱好者提供一个有趣且实用的开源项目。
- 通过开源的方式，吸引更多的开发者参与进来，共同完善项目功能，拓展应用场景。

## 使用说明
1. 将小车组装完成，并确保各部件连接正确。

   ![Wiring diagram](.\Guide\Wiring diagram\Wiring diagram.png)

2. 打开小车电源，等待其发出热点。

3. 使用移动设备连接该热点。

4. 在浏览器地址栏输入特定网页地址（默认为：http://192.168.4.1），进入控制界面。

5. 通过控制界面的按钮，实现对小车的开灯以及前进、后退、左右转控制，同时查看实时图传画面。

## 项目贡献
欢迎各位开发者参与项目贡献，无论是代码优化、功能拓展，还是文档完善，都十分欢迎。您可以通过以下方式参与：
- **提交Pull Request**：对项目的代码、文档等进行修改和完善，提交Pull Request进行审核。
- **提出Issue**：如果您在使用过程中遇到任何问题，或者有好的建议，都可以通过提出Issue的方式反馈给我们。

## 联系方式
- **项目维护者**：CKCHEN
- **邮箱**：1613342367@qq.com

希望这个开源项目能给大家带来乐趣和启发，如有建议或意见欢迎与我联系，让我们一起探索FPV小车的无限可能！
