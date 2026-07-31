# 🐱 尼古喵喵 - 节奏吸烟模拟器

> ⚡ 一款基于 BPM 节奏的 Web 网页小游戏

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Canvas-API-red?style=for-the-badge" />
</p>

---

## 🎮 在线试玩

👉 **[点击这里开始游戏](https://fbee3157.github.io/neko/)**

---

## 📖 简介

控制一只沉迷尼古丁的猫猫，跟随着 **90 BPM** 的节奏韵律，在火花燃尽每根香烟的瞬间精准点击屏幕。吸入、计分、续命——看看你能在有限的时间内「过肺」多少根？

> 🚬 **温馨提示：本游戏仅为创意娱乐，请勿在现实中模仿吸烟行为。**

---

## 🕹️ 玩法说明

| 操作 | 说明 |
|------|------|
| 🔥 判定 | 烟头的火花沿香烟移动，当火花到达烟尾（滤嘴处）时，绿色光环亮起 |
| 👆 点击 | 在火花到达烟尾时点击屏幕（手机）/ 鼠标左键（电脑）/ 空格键 |
| ✅ 成功 | 火花到达 72% 以后点击 → 成功吸入，得分 +1，计时 +0.2s |
| ❌ 失败 | 太早点击或超时未点击 → MISS，连击清零 |

---

## 🎯 核心机制
┌─────────────────────────────────────┐
│ 15 秒倒计时 │
│ 每成功一次 +0.2 秒 │
│ 目标：过肺 30 根 │
│ BPM: 90 (每拍 ≈ 667ms) │
│ 判定窗口: 火花行程 72% 之后 │
└─────────────────────────────────────┘


| 参数 | 值 |
|------|----|
| BPM | 90 |
| 初始时间 | 15.0s |
| 成功奖励 | +0.2s |
| 游戏目标 | 30 根 |
| 单根尼古丁 | 1.2 mg |

---

## ✨ 功能特性

- 🎵 **BPM 节奏系统** — 基于 Web Audio API 的节拍器 + 音效合成
- 🐱 **手绘 Canvas 猫猫** — 半眯的金色瞳孔，吐着烟圈的酷猫
- 🔥 **实时粒子特效** — 烟雾、火花、胜利彩纸
- 📊 **实时数据面板** — 分数、计时器、尼古丁摄入量、连击数
- ⚠️ **随机健康标语** — 12 条轮播香烟危害警示
- 🌈 **双结局动画** — 30 根彩虹渐变胜利 / 超时金色失败
- 📱 **全平台适配** — 支持手机触控、电脑鼠标、键盘空格
- 🎧 **合成音效** — 无需加载任何外部音频文件

---

## 🛠️ 技术栈

- **纯原生实现** — 零框架、零依赖，单个 HTML 文件
- **Canvas 2D** — 游戏画面渲染
- **Web Audio API** — 音频合成（节拍器 / 打击音 / 吸烟声 / 结算音）
- **CSS3** — UI 动画（彩虹渐变、脉冲闪烁）
- **Google Fonts** — ZCOOL QingKe HuangYou / Press Start 2P / Noto Sans SC

---



