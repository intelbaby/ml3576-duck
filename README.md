# 🦆 ML3576 Duck

**Open-source SDK & hardware interface docs for the ML3576-powered biped robot duck.**
**基于 ML3576 的双足机器鸭 · 开源 SDK 与硬件接口文档**

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Made by Intelbaby](https://img.shields.io/badge/Made%20by-Intelbaby-green)](https://www.intelbaby.top)

&gt; A desktop-sized biped robot duck powered by the **ML3576** AI compute board
&gt; (RK3576, 6 TOPS NPU, Debian + ROS 2 Humble), with reinforcement-learning locomotion.
&gt; Compatible with the open Microduck software ecosystem.
&gt;
&gt; 一只由 **ML3576** AI 算力板驱动的桌面级双足机器鸭，支持强化学习步态，
&gt; 兼容 Microduck 开源软件生态。

---

## 📌 Open Source Scope / 开源范围

| Content | Status | License |
|---|---|---|
| Upper-layer SDK, examples, docs | ✅ Open source | Apache-2.0 |
| Hardware interface specs (pinout, servo protocol) | ✅ Open source | Apache-2.0/CC-BY-4.0 |
| Structural design (CAD), PCB, BOM | ❌ Proprietary | Contact us for licensing |

&gt; 本仓库仅开源上层 SDK、示例与硬件接口文档；结构设计、PCB 与物料清单为专有技术，
&gt; 商业合作请联系我们。

## ✨ Features / 特性

- 🧠 **ML3576** core board: RK3576 SoC, 6 TOPS NPU, 4/8GB LPDDR4
- 🦵 15-DOF bipedal locomotion, RL-trained policies
- 🤖 Debian 11 + ROS 2 Humble onboard
- 🔌 Documented hardware interface for secondary development
- 🌏 中文 & English documentation

## 🚀 Quick Start / 快速开始

*Coming soon — SDK v0.1.0 is in preparation.*
*SDK 正在准备中，即将发布。*

```bash
# 示例（发布后将更新）
pip install ml3576-duck-sdk
