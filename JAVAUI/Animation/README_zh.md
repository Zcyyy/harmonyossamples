# 动画<a name="ZH-CN_TOPIC_0000001080120356"></a>

### 简介

-   动画是组件的基础特性之一，精心设计的动画使 UI 变化更直观，有助于改进应用程序的外观并改善用户体验。

    1.帧动画是利用视觉暂留现象，将一系列静止的图片按序播放，给用户产生动画的效果。

    2.AnimatorValue 数值从0到1变化，本身与 Component 无关。开发者可以设置0到1变化过程的属性，例如：时长、变化曲线、重复次数等，并通过值的变化改变组件的属性，实现组件的动画效果。

    3.AnimatorProperty 可以为 Component 设置某个属性或多个属性而实现动画效果。

### 使用说明

本示例展示了4种动画效果，包括图片动效，物体运动，物体变换以及多个物体移动。

### 约束与限制

1.本示例仅支持在大型系统上运行。

2.验证本示例的系统版本号：2.0.0.202110110309(DEVC00E1R53dexlog) GPU Turbo。

3.验证本示例的HarmonyOS版本：2.0.0 Devloper Beta3。

4.本示例需要使用 DevEco Studio 3.0 Beta3 (Build Version:3.0.0.533,built on September 26,2021) 才可编译。
