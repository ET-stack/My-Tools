# 🧩 个人工具导航

纯本地、开箱即用、无需服务器的浏览器工具集合。

## 🚀 快速开始

直接用浏览器打开 `index.html` 即可使用所有工具。

## 📦 工具列表

### 🖼️ 截图拼接工具
- **文件**: [tools/screenshot-stitch.html](tools/screenshot-stitch.html)
- **功能**: 多张图片左右横向拼接成长图
- **特性**:
  - 拖拽排序：拖动图片卡片调整顺序
  - 多种上传方式：点击上传、拖拽上传、Ctrl+V 粘贴上传
  - 实时预览：添加图片后自动显示拼接效果
  - 间距可调：可设置图片之间的间距
  - 一键下载：导出拼接后的 PNG 图片
  - 复制功能：支持 Ctrl+C 复制拼接图到剪贴板，单张图片也可复制

### 📝 文本工具
- **文件**: [tools/text-tools.html](tools/text-tools.html)
- **功能**: 常用文本处理工具
- **特性**:
  - JSON 格式化/压缩/校验
  - 文本对比 (Diff)
  - Base64 编解码
  - URL 编解码
  - HTML 实体编解码

### 🔢 数字工具
- **文件**: [tools/number-tools.html](tools/number-tools.html)
- **功能**: 数字格式转换工具
- **特性**:
  - Base64 编解码
  - 时间戳转换（秒/毫秒 ↔ 日期）
  - 颜色格式转换（HEX ↔ RGB ↔ HSL）
  - 取色器

### 🎨 图片工具
- **文件**: [tools/image-tools.html](tools/image-tools.html)
- **功能**: 图片处理工具
- **特性**:
  - 图片转 Base64
  - 图片缩放（按比例/按宽度/按高度）
  - 图片下载

### 🔗 URL 工具
- **文件**: [tools/url-tools.html](tools/url-tools.html)
- **功能**: URL 处理工具
- **特性**:
  - URL 编码/解码
  - URL 参数解析
  - URL 参数构建

### 📦 开发工具
- **文件**: [tools/dev-tools.html](tools/dev-tools.html)
- **功能**: 开发者常用工具
- **特性**:
  - 正则表达式测试
  - 常用正则表达式参考
  - Cron 表达式解析
  - Cron 表达式生成预设

### 📱 朋友圈分享图片
- **文件**: [tools/moments-tools.html](tools/moments-tools.html)
- **功能**: 朋友圈九宫格/多图分栏布局
- **特性**:
  - 多种布局：单图、双图、三图、四图、六宫格、九宫格
  - 上传图片后自动生成拼接图
  - 支持下载和复制到剪贴板

---

## 🔧 添加新工具

1. 在 `tools/` 文件夹下创建新的 HTML 文件
2. 在 `index.html` 中按相同格式添加模块卡片：

```html
<a href="tools/你的工具文件.html" class="module-card">
    <span class="module-icon">🛠️ icon</span>
    <div class="module-title">工具名称</div>
    <div class="module-desc">工具描述</div>
</a>
```

3. 在 `README.md` 中添加工具说明

---

## 📋 技术说明

- 纯前端实现，无需后端服务器
- 所有数据保存在浏览器内存中，刷新页面后重置
- 支持现代浏览器（Chrome、Edge、Firefox、Safari）
# My-Tools
