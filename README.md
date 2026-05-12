

# BurnBrowser - 浏览器 3D 渲染与硬件基准测试

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![WebGL 2.0](https://img.shields.io/badge/WebGL-2.0-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/API/WebGL2RenderingContext)

**BurnBrowser** 是一个单文件 WebGL 2.0 基准测试工具。它通过高负载的着色器（Fragment Shaders）渲染复杂的 3D 场景，同时对客户端 CPU 和 GPU 进行压力测试，并在优化的 UI 界面中实时反馈硬件得分与运行表现。

## 🚀 核心特性

* **多场景实时切换**：内置五个基于原生 GLSL 着色器的极致视觉场景。
    * **Terrain (地形)**：程序化生成的高山地貌。
    * **Ocean (海洋)**：实时动态波浪与光折射模拟。
    * **Desert (沙漠)**：精细的沙丘纹理与大气散射效果。
    * **Grass (草地)**：百万级草丛动态渲染。
    * **Mountain (雪山)**：高精度的分形噪声山脉。
<img width="1170" height="669" alt="image" src="https://github.com/user-attachments/assets/91f80963-1f98-4789-b5ad-1b9c053f5697" />
<img width="1170" height="669" alt="image" src="https://github.com/user-attachments/assets/876b00ae-c75f-4e3b-857f-88e80e61cefb" />
<img width="1170" height="669" alt="image" src="https://github.com/user-attachments/assets/64865c37-9692-4631-8848-712519200a78" />
<img width="1170" height="669" alt="image" src="https://github.com/user-attachments/assets/1fdb612e-e6f6-4a3d-baed-456a81d81573" />
<img width="1170" height="669" alt="image" src="https://github.com/user-attachments/assets/f4b6f0e8-7d31-4fe1-82cc-783400368e78" />
<img width="1170" height="669" alt="image" src="https://github.com/user-attachments/assets/4335426c-4b61-4a2d-a63a-fec0be500be6" />
<img width="1170" height="669" alt="image" src="https://github.com/user-attachments/assets/7c202b2c-d4dc-41d2-9d8e-5b850998c115" />
<img width="1170" height="669" alt="image" src="https://github.com/user-attachments/assets/0d5f6715-33a5-4ed1-b578-4f8348fe9e6d" />

* **双指标基准测试**：
    * **CPU Test**：通过密集的循环计算评估处理器的浮点运算能力。
    * **GPU Test**：根据当前 WebGL 渲染的帧率（FPS）与场景复杂度计算图形分值。
* **零依赖设计**：纯原生 HTML5/JavaScript/WebGL 2.0 ，无需安装任何插件与额外依赖，打开即用。

## 📖 使用方法

1.  下载本项目中的 `BurnBrowser.html` 文件。
2.  使用现代浏览器（推荐 Chrome, Edge 或 Firefox）直接打开该文件。
3.  点击页面中心面板上的 **“RUN TEST”** 按钮开始测试。
4.  测试完成后，界面将显示 CPU 与 GPU 的百分制得分。
5.  点击右上角的 **“切换场景”** 按钮可在不同渲染模式间切换。

## 📝 开发者说明

SHADER代码来源于网络收集并用AI修改，版权归原作者所有

## 📜 许可证

本项目遵循 [MIT License](LICENSE) 协议。


