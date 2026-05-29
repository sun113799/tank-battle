# 🎮 坦克大战 - Tank Battle

经典的坦克大战游戏，使用纯 HTML + CSS + JavaScript 实现，无需任何依赖。

![Game](https://img.shields.io/badge/game-tank--battle-brightgreen)
![Tech](https://img.shields.io/badge/tech-HTML5%20Canvas-blue)

## 🎯 游戏特性

- 🏗️ **3 个精心设计的关卡** - 难度递增
- 🧱 **多种地形** - 砖墙、钢墙、水域、树林
- 🚗 **3 种敌人类型** - 普通坦克、快速坦克、装甲坦克（多血量）
- 💥 **爆炸特效** - 粒子系统
- ⭐ **基地保护** - 鹰巢不可被摧毁
- 📊 **计分系统** - 不同敌人不同分数

## 🕹️ 操作方式

| 按键 | 功能 |
|------|------|
| `↑ ↓ ← →` 或 `W A S D` | 移动坦克 |
| `空格键` | 射击 |
| `P` | 暂停/继续 |
| `Enter` | 开始游戏 |

## 🏃 运行方式

直接用浏览器打开 `index.html` 即可游玩。

或者使用本地服务器：

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

然后访问 `http://localhost:8000`

## 🎲 敌人类型

| 类型 | 外观 | 特点 | 得分 |
|------|------|------|------|
| 普通坦克 | 灰色 | 基础敌人 | 100 |
| 快速坦克 | 青色 | 速度快、射速快 | 200 |
| 装甲坦克 | 红色 | 3 点生命值 | 300 |

## 📜 License

MIT
