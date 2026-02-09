# ✨ 光之径 | Light Path

[![Game](https://img.shields.io/badge/类型-益智解谜-blue)](https://github.com/chenhaubin/light-path)
[![Tech](https://img.shields.io/badge/技术-HTML5%20Canvas-orange)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![License](https://img.shields.io/badge/许可证-MIT-green)](LICENSE)

一款精美的光线反射物理益智游戏，通过放置镜子引导激光从光源到达接收器。

![Game Screenshot](https://via.placeholder.com/800x400/1a1a2e/00d4ff?text=Light+Path+Screenshot)

## 🎮 游戏特色

- **8个精心设计的关卡** - 从入门到精通，难度逐步提升
- **真实的物理光线模拟** - 精确的光线反射计算
- **霓虹赛博朋克风格** - 炫酷的视觉效果和动画
- **多种光学元件** - 镜子、分光镜、障碍物
- **粒子特效** - 光束击中目标时的华丽反馈
- **响应式设计** - 支持各种屏幕尺寸

## 🎯 玩法说明

1. **目标**: 引导光线从 💡 光源到达 🎯 接收器
2. **放置镜子**: 从工具箱拖动 🪞 镜子到网格中
3. **旋转镜子**: 点击已放置的镜子可旋转45°
4. **移除镜子**: Shift+点击 或 右键点击可移除镜子
5. **分光镜**: 💠 可将一束光分成两路

## 🚀 快速开始

### 在线试玩
直接打开 `index.html` 即可游玩，无需安装任何依赖。

### 本地运行
```bash
git clone https://github.com/chenhaubin/light-path.git
cd light-path
# 用浏览器打开 index.html
open index.html  # macOS
xdg-open index.html  # Linux
start index.html  # Windows
```

### 部署到服务器
```bash
# 使用 Python 简易服务器
python3 -m http.server 8000

# 或使用 Node.js
npx serve .
```

## 🏗️ 技术栈

- **HTML5 Canvas** - 游戏渲染
- **原生 JavaScript** - 游戏逻辑
- **CSS3** - UI 样式和动画
- **无依赖** - 纯前端实现

## 📁 项目结构

```
light-path/
├── index.html      # 主游戏文件（单文件完整游戏）
├── README.md       # 项目说明
└── LICENSE         # 许可证
```

## 🎨 关卡设计

| 关卡 | 名称 | 难度 | 特色 |
|------|------|------|------|
| 1 | 初识光线 | ⭐ | 基础直线传播 |
| 2 | 拐角 | ⭐⭐ | 引入障碍物 |
| 3 | 迷宫 | ⭐⭐ | 复杂路径规划 |
| 4 | 双镜之谜 | ⭐⭐⭐ | 精确角度计算 |
| 5 | 分光挑战 | ⭐⭐⭐ | 分光镜引入 |
| 6 | 回环 | ⭐⭐⭐⭐ | 螺旋路径 |
| 7 | 螺旋 | ⭐⭐⭐⭐ | 复杂迷宫 |
| 8 | 终极挑战 | ⭐⭐⭐⭐⭐ | 所有机制综合 |

## 🔮 未来计划

- [ ] 关卡编辑器
- [ ] 玩家自制关卡分享
- [ ] 更多光学元件（棱镜、透镜）
- [ ] 音效和背景音乐
- [ ] 移动端优化
- [ ] 排行榜系统

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

[MIT License](LICENSE)

---

Made with 💜 by [chenhaubin](https://github.com/chenhaubin)
