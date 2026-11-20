# Whale Roulette V1.0 — 鲸渊轮盘

原创氛围风格的回合制概率博弈网页小游戏。单文件 `index.html`，无需后端、安装或构建。

## 在 iPad 上游玩

将 `index.html` 上传至现有 GitHub Pages 仓库的 `roulette/` 文件夹（或创建新仓库并放在根目录）。通过 HTTPS 页面访问，例如 `https://<username>.github.io/<repo>/roulette/`。

## 玩法

4 HP 起始。每轮公布实弹和空包弹数量并随机洗牌；射中对手的实弹造成 1 HP 伤害；对自己射出空包弹可额外行动。使用放大镜、啤酒、手铐、香烟等道具进行策略决策。击败庄家即胜利。

## 当前限制

这是无需服务器的单人 AI 版本。场景由 CSS 透视和图层绘制，**不是真实 Three.js 3D 模型**。暂未实现多人 WebRTC、存档、完整 3D 动画或真人设备测试。音效使用 Web Audio API，需要用户点击开始后才能播放。
