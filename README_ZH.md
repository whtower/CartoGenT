# CartoGenT

<p align="center">
  <a href="README.md">English</a> | 简体中文
</p>

<p align="center">
  <a href="https://huggingface.co/spaces/whtower/CartoGenT"><img src="https://img.shields.io/badge/🤗-Demo-yellow" alt="Demo"></a>
  <a href="https://figshare.com/s/5bdeaee85be6267bd178"><img src="https://img.shields.io/badge/📊-Dataset-blue" alt="Dataset"></a>
</p>

**CartoGenT: 一个用于矢量原生制图建筑物合并的生成式多尺度Transformer框架**

本仓库是 CartoGenT 论文的官方资源库,提供数据集和在线演示。

<p align="center">
  <img src="figures/Fig0.png" alt="CartoGenT Overview" width="800"/>
</p>

## 📖 简介

建筑物合并是制图综合中的关键操作,用于生成清晰连贯的多尺度地图。CartoGenT 是一个端到端的矢量原生生成式 Transformer 框架,专门用于建筑物合并任务。

### 主要特点

- 🎯 **矢量原生处理**: 直接在矢量域操作,避免栅格化带来的精度损失
- 🔄 **多尺度架构**: 采用尺度自适应模块建模跨尺度上下文依赖
- 🤖 **生成式建模**: 联合预测顶点和连接性,实现拓扑有效的几何重建
- 📐 **端到端训练**: 从输入建筑群到输出合并结果的完整端到端学习

## 🚀 在线演示

体验 CartoGenT 的在线演示:

👉 [https://huggingface.co/spaces/whtower/CartoGenT](https://huggingface.co/spaces/whtower/CartoGenT)

在线演示允许您:
- 上传自定义建筑物数据
- 实时查看合并结果
- 调整模型参数
- 下载处理结果

## 📊 数据集

本项目使用的数据集已公开发布在 Figshare 上:

👉 [https://figshare.com/s/5bdeaee85be6267bd178](https://figshare.com/s/5bdeaee85be6267bd178)

数据集基于英国 Ordnance Survey 和 OpenStreetMap 的矢量建筑数据构建,包含训练集、验证集和测试集。

## 📄 论文

论文目前处于投稿阶段,更多详细信息将在论文发表后公开。

