# 24点 — 算术卡牌游戏

一个用纯 HTML/CSS/JS 制作的 24 点卡牌游戏，无需任何依赖，直接在浏览器打开即可游玩。

🎮 **[点击这里在线游玩](https://Kimberly-Huang.github.io/24points-game/)**

---

## 游戏规则

从一副标准扑克牌中随机抽取 4 张，使用加、减、乘、除及括号，让四张牌的数值运算结果等于 **24**。

- **A** = 1，**J** = 11，**Q** = 12，**K** = 13
- 每张牌必须使用且只能使用一次
- 支持任意顺序和括号组合

经典难题：`3, 3, 8, 8` → `8 ÷ (3 − 8÷3) = 24`

---

## 功能特性

- 🃏 真实扑克牌视觉效果，红黑花色区分
- 🤖 自动求解算法，每局保证有解
- 📐 实时算式预览，每一步操作立刻显示
- ↩️ 逐步撤回，随时退回上一步
- 💡 提示系统，卡关时可查看解法
- 🏆 得分 + 连胜系统，越连胜加分越多
- 📱 响应式设计，手机电脑均可畅玩

---

## 本地运行

无需安装任何依赖，直接双击 `index.html` 用浏览器打开即可。

---

## 部署到 GitHub Pages

1. Fork 或克隆本仓库
2. 进入仓库 **Settings → Pages**
3. Source 选择 `Deploy from a branch`，Branch 选 `main`，目录选 `/ (root)`
4. 保存后等待约 1 分钟，访问 `https://你的用户名.github.io/仓库名/`

---

## 技术栈

- 纯原生 HTML / CSS / JavaScript，零依赖
- 字体：[Playfair Display](https://fonts.google.com/specimen/Playfair+Display)、[DM Mono](https://fonts.google.com/specimen/DM+Mono)、[Noto Sans SC](https://fonts.google.com/specimen/Noto+Sans+SC)（Google Fonts）

---

## License

MIT © 2024
