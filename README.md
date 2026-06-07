# 🧩 拼图游戏 (Jigsaw Puzzle)

一个纯前端、零依赖的网页拼图游戏。上传本地图片，选择片数与玩法，拼出带**真实凹凸锯齿边缘**的经典拼图。单个 HTML 文件即可运行，支持桌面与 iOS / 安卓触屏。

## ✨ 功能

- 📁 **本地图片**：图片只在浏览器内处理，不上传服务器
- 🔢 **2~16 片**：自动选择最接近正方形的行列布局
- 🧩 **真实锯齿边缘**：用 Canvas 贝塞尔曲线生成凸/凹互锁拼块，拼对严丝合缝
- 🎮 **两种玩法**：
  - 交换模式（棋盘内互换）
  - 拖放模式（从下方待拼区拖入对应格子）
- 📊 计时 / 步数 / 进度统计，一键查看原图
- 📱 自适应屏幕，鼠标 + 触摸统一拖拽，适配 iOS Safari

## 🚀 在线体验

部署到 GitHub Pages 后，访问：
`https://<你的用户名>.github.io/jigsaw-puzzle/`

## 💻 本地运行

直接用浏览器打开 `index.html` 即可，无需任何安装或联网。

## 📦 部署到 GitHub Pages

```bash
# 1. 在 GitHub 上新建一个空仓库（例如命名为 jigsaw-puzzle）

# 2. 关联远程仓库并推送（在本项目文件夹内执行）
git remote add origin https://github.com/<你的用户名>/jigsaw-puzzle.git
git branch -M main
git push -u origin main

# 3. 打开仓库 Settings → Pages
#    Source 选择 "Deploy from a branch"
#    Branch 选择 main / (root)，保存
#    等待约 1 分钟即可通过上面的网址访问
```

## 📄 License

MIT
