# AR/VR 智能手套项目

## 项目简介

本项目旨在开发一款 AR/VR 智能手套，通过集成温度感应、虚拟交互和智能动画技术，打造沉浸式的用户体验。项目结合了嵌入式系统开发、虚拟现实界面设计和人工智能模型，最终实现了用户与虚拟环境的自然交互。

## 功能概述

### 1. 温度传感系统
设计并实现了基于 Arduino 的温度传感系统。使用 Python 开发嵌入式系统，能够精确控制并响应环境温度的变化。

### 2. VR/AR 交互界面
利用 Unity3D 和 Blender 构建了高交互性的 VR/AR 界面。通过该界面，用户可以与虚拟角色进行互动，体验到更加真实的虚拟环境。

### 3. 智能动画驱动
基于 GPT 模型驱动角色动画，使用 OpenAI 平台进行模型微调，从而增强了产品的智能化，提升了用户体验的沉浸感。

## 项目结构

- `arduino/`：Arduino 温度传感器代码及硬件配置说明。
- `python/`：嵌入式系统的 Python 脚本，包括数据采集和控制逻辑。
- `unity/`：VR/AR 交互界面的 Unity3D 项目文件。
- `blender/`：Blender 制作的 3D 模型及场景设计文件。
- `gpt-model/`：GPT 模型的训练脚本及微调参数配置。

## 使用说明

1. **硬件设置**
   - 使用 Arduino 进行温度传感器的设置，连接至指定的嵌入式系统。

2. **软件环境**
   - 安装 Python 及必要的依赖库，执行 `python/main.py` 进行数据采集和传感器控制。
   - 打开 Unity3D 项目文件，进行 VR/AR 界面的测试和运行。
   - 通过 OpenAI API 进行 GPT 模型的微调，并运行动画驱动脚本。

3. **运行示例**
   - 示例 1：如何通过温度传感器控制虚拟角色的动态变化。
   - 示例 2：基于用户语音指令，如何使用 GPT 模型生成角色动画。

## 贡献指南

欢迎对本项目提出问题、建议或提交 pull request。如果你有更好的想法或发现任何问题，请随时与我联系。

## 许可证

本项目采用 [MIT License](LICENSE)。

## 联系方式

- **开发者**：张君仪
- **邮箱**：zhangjy79@outlook.com
- **GitHub**：[@yourusername](https://github.com/yourusername)

