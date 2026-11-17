# 1# 📱 极简应用推荐网页模板

这是一个纯前端（HTML + CSS + JavaScript）的轻量级应用推荐展示页面。
无需任何服务器或数据库，直接托管在 GitHub Pages 即可使用。

## ✨ 特性
- **极简暗黑 UI**：类似 App Store 的卡片设计，带有悬浮动画和毛玻璃效果。
- **免后端**：所有应用数据直接写在 `index.html` 的 JavaScript 数组里。
- **双通道下载**：提供 Google Play 和 官方网站的双重下载引导，拒绝流氓软件。
- **自带分类**：顶部导航栏支持社交、影音、游戏、工具等分类动态切换。

## 🛠️ 如何使用
1. Fork 或下载本仓库。
2. 打开 `源代码.HTML `，找到代码底部的 `appsData` 数组。
3. 按照格式添加你的应用：
   ```javascript
   { 
       name: "应用名称", 
       desc: "应用简介", 
       category: "分类（需和顶部按钮对应）", 
       playUrl: "Google Play 链接", 
       webUrl: "官方网站链接", 
       iconChar: "图标里显示的字母", 
       iconColor: "图标背景颜色代码" 
   }
…
