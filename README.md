# Paper Design 3D 翻书卷曲效果 (WebGL & Three.js)

基于 WebGL 与 Three.js 还原的 Paper.design 拟真 3D 纸张卷曲、阴影与翻页物理交互效果。

## 特性

- 📖 **拟真物理卷曲**：自定义顶点着色器（Vertex Shader）实时计算纸张弯曲与形变
- 💡 **动态阴影与环境光**：模拟书脊遮挡与纸张背光透光效果
- 🖱️ **平滑手势拖拽**：支持鼠标/触控拖拽翻页与惯性回弹动画
- ⚡ **单文件即开即用**：零构建依赖，浏览器直接打开 `index.html` 即可运行

## 在线体验 / 运行方式

无需安装任何构建工具，直接在浏览器中打开 `index.html` 或通过任何静态服务器启动：

```bash
# Python
python -m http.server 8080

# 或 Node.js
npx serve .
```

## 灵感来源

- Concept inspired by [Paper.design](https://paper.design)
