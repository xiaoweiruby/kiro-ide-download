# 🚀 Kiro IDE 官方下载页面

> 基于Claude Sonnet 4.0的新一代AI集成开发环境官方下载站点

## 📖 项目简介

这是Kiro IDE的官方下载页面，为用户提供了一个现代化、响应式的下载体验。Kiro IDE是由亚马逊AWS推出的革命性AI编程工具，采用规格驱动开发(Spec-Driven Development)理念，旨在解决传统"氛围编程"带来的开发混乱问题。

## ✨ 页面特性

### 🎨 设计亮点
- **现代化UI设计**：采用紫色主题色调，符合Kiro IDE品牌形象
- **响应式布局**：完美适配桌面端、平板和移动设备
- **流畅动画效果**：滚动触发的渐入动画，提升用户体验
- **优雅交互设计**：悬停效果、平滑滚动等细节优化

### 📱 功能模块
- **产品介绍区**：详细介绍Kiro IDE的核心价值和特性
- **功能展示区**：四大核心功能的卡片式展示
- **多平台下载**：支持Windows、Mac Intel、Mac M系列、Linux四个平台
- **联系支持区**：提供微信公众号和个人微信联系方式

## 🛠️ 技术栈

### 前端框架
- **HTML5**：语义化标签，SEO友好
- **CSS3**：现代化样式，支持动画和响应式设计
- **JavaScript (ES6+)**：原生JS实现交互功能
- **Bootstrap 5.3.0**：响应式栅格系统和组件库

### 外部依赖
- **Font Awesome 6.4.0**：图标库
- **Google Fonts**：Segoe UI字体系列
- **Bootstrap Bundle**：包含Popper.js的完整Bootstrap包

### 设计系统
```css
:root {
    --primary-color: #9370DB;    /* 主紫色 */
    --secondary-color: #8A2BE2;  /* 深紫色 */
    --light-purple: #9F7AEA;     /* 浅紫色 */
    --white: #FFFFFF;            /* 纯白色 */
    --dark-text: #333333;        /* 深色文字 */
}
```

## 📁 项目结构

```
kiro-ide-down/
├── index.html              # 主页面文件
├── 二维码.jpg              # 微信公众号二维码
├── 围巾哥萧尘头像.png      # 个人微信头像
├── README.md               # 项目说明文档
└── .vercel/                # Vercel部署配置
    └── project.json
```

## 🚀 快速开始

### 本地运行

1. **克隆项目**
```bash
git clone <repository-url>
cd kiro-ide-down
```

2. **启动本地服务器**
```bash
# 使用Python 3
python -m http.server 8000

# 或使用Node.js
npx serve .

# 或使用PHP
php -S localhost:8000
```

3. **访问页面**
打开浏览器访问 `http://localhost:8000`

### 在线部署

#### Vercel部署（推荐）
1. 将项目推送到GitHub
2. 在Vercel中导入项目
3. 自动部署完成

#### Netlify部署
1. 拖拽项目文件夹到Netlify
2. 或连接GitHub仓库自动部署

#### GitHub Pages部署
1. 在仓库设置中启用GitHub Pages
2. 选择主分支作为源
3. 访问 `https://username.github.io/repository-name`

## 🔧 自定义配置

### 修改下载链接
在 `index.html` 中找到下载按钮，修改对应的链接地址：

```html
<!-- Windows版本 -->
<a href="https://pan.quark.cn/s/0944441a8c9b" target="_blank" class="download-btn">
    <i class="fas fa-download me-1"></i> 下载
</a>
```

### 更新联系信息
1. 替换 `二维码.jpg` 为新的二维码图片
2. 替换 `围巾哥萧尘头像.png` 为新的头像图片
3. 修改微信号等联系信息

### 自定义主题色彩
在CSS的 `:root` 选择器中修改颜色变量：

```css
:root {
    --primary-color: #your-color;    /* 修改主色调 */
    --secondary-color: #your-color;  /* 修改辅助色 */
}
```

## 📊 SEO优化

页面已包含完整的SEO优化：

- **Meta标签**：title、description、keywords
- **语义化HTML**：正确使用header、nav、section、footer等标签
- **图片Alt属性**：所有图片都包含描述性alt文本
- **结构化数据**：清晰的页面结构便于搜索引擎理解

## 🌐 浏览器兼容性

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ 移动端浏览器

## 📱 响应式断点

```css
/* 移动端 */
@media (max-width: 768px) {
    /* 移动端样式 */
}

/* 平板端 */
@media (min-width: 769px) and (max-width: 1024px) {
    /* 平板端样式 */
}

/* 桌面端 */
@media (min-width: 1025px) {
    /* 桌面端样式 */
}
```

## 🔄 更新日志

### v1.0.0 (2025-01-XX)
- ✨ 初始版本发布
- 🎨 完整的响应式设计
- 📱 多平台下载支持
- 🔗 联系方式集成
- ⚡ 性能优化和动画效果

## 🤝 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 联系我们

- **微信公众号**：围巾哥萧尘
- **个人微信**：xiaochenwin（添加时请注明"Kiro用户"）
- **官方网站**：[Kiro IDE官网](https://kiro.aws.amazon.com)

---

<div align="center">
    <p>🌟 如果这个项目对您有帮助，请给我们一个Star！</p>
    <p>Made with ❤️ by Kiro IDE Team</p>
</div>