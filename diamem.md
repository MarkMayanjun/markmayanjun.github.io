---
layout: default
title: DiaMem 记忆力评估小程序
---

# 🧠 DiaMem — 基于随机刺激替换的移动记忆监测工具

> 一款专为老年人设计的微信小程序，用于**高频次、无学习效应的记忆自评**，适用于认知训练效果追踪、社区筛查和临床研究。

---

## 📌 项目背景

当前，我国阿尔茨海默病及相关痴呆患者已超 2000万，轻度认知障碍在 60 岁以上人群中患病率达 15.5%。然而，现有认知评估工具（如 MoCA、MMSE）存在明显的**学习效应**，不适用于短期重复测量；而一些数字工具（如 n-back、MemTrax）虽然支持重复测试，但**生态效度较差**（孤立、单模态刺激），难以反映日常记忆需求。

**DiaMem** 应运而生，旨在填补“可重复、生态效度高、易用”的记忆监测工具空白。

---

## 🎯 核心设计理念

### 1. 结构化场景 + 随机替换
- 测试遵循固定叙事框架（“王阿姨的一天”），包含 **家庭介绍、公园场景、朋友相遇、照片识别、购物清单、延迟回忆** 等生活情节。
- 但每次测试的**所有素材（图片、语音、文字）** 都从一个大型多模态素材库中**随机抽取**，保证每次内容新颖，**极大降低记忆特定内容的练习效应**。

### 2. 高生态效度
- 模拟真实生活记忆（人物、场景、购物），而非抽象符号，更贴近老年人日常认知需求。
- 包含**即时回忆**和**延迟回忆**双模块，全面评估情景记忆。

### 3. 适老化交互
- 大字体、语音引导、点选式作答（无需打字）。
- 基于微信小程序，**无需下载安装**，即开即用。
- 提供“标准版”和“关怀版”两种界面。

---

## 📊 研究验证（摘要）

> 我们已在社区老年人中完成了一项随机交叉试验（NCT07416019），初步验证了 DiaMem 的可靠性、效度和可用性。

- **重测信度**：ICC = 0.836（95% CI 0.725–0.912），属“良好”水平。
- **最小可检测变化（MDC）**：单次测量 13.5 分；三次平均 7.8 分（可助力减少临床试验样本量）。
- **练习效应**：第一次与第三次测试差异 Cohen's *d* = 0.02，**无显著练习效应**。
- **效标效度**：与 MoCA 总分相关系数 *r* = 0.766（*P* < 0.001），与 AVLT 总分 *r* = 0.458（*P* = 0.011）。
- **内容效度**：专家评分 S‑CVI/Ave = 0.976。
- **可用性**：系统可用性量表（SUS）得分为 69.3，显著高于参考工具 MemTrax（64.1）。

**结论**：DiaMem 具有良好的信度和可接受的效度及可用性，适用于认知训练、药物试验等需要高频重复测量的场景。

---

## 📱 如何使用 DiaMem

- 打开微信 → 搜索 **“DiaMem”** 或 **“记忆力评估”** → 点击进入小程序。
- 首次使用需同意隐私协议，无需注册，直接开始测试。
- 整个测试约 **15~20 分钟**，建议在安静环境中完成。
- 测试完成后自动生成得分报告，并可查看历史变化趋势。

> 下面是小程序二维码，微信扫码即可直接进入：

![DiaMem 二维码](assets/DiaMem_figures/DiaMem二维码.png)

---

## 🖼️ 界面截图

<table>
  <tr>
    <td><img src="assets/DiaMem_figures/1.首页.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/2.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/3.9baeb1be571e2305666b690f5b33a9b9.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/4.0aeb5daea8dcb869ba837ad9032cf1d7.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/5.18f8aae5741e939f63d19c6c5f0b06d8j.jpg" width="100%"></td>
  </tr>
  <tr>
    <td><img src="assets/DiaMem_figures/6.14e0bc53174538fb453318dde298e294.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/7.3774af0e188ba381a1cb846cb2794a64.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/8.8f25122cfbfa623303a9fe09322481d2j.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/9.036ed42d775062476eabb2f2feabb014.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/10.ae6fdb6a4d21b39db427cc41f6620b0a.jpg" width="100%"></td>
  </tr>
  <tr>
    <td><img src="assets/DiaMem_figures/11.0a243f4b3f1813331c3a66a4b8935d21.jpg" width="100%"></td>
    <td><img src="assets/DiaMem_figures/12.e89d4e2e1e55fabe5764bc92c3d80ae6.jpg" width="100%"></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

---

## 📬 联系与反馈

- **研究者**：马燕军（markmayanjun@163.com）

欢迎同行交流与合作！
