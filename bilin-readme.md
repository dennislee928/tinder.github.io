# Tinder GitHub Pages

[English](#english) | [繁體中文](#繁體中文)

---

## 繁體中文

### 歡迎來到 Tinder GitHub Pages

這是 Tinder 官方技術團隊的 GitHub Pages 網站，展示我們的開源專案、技術文章和開發資源。

### 🚀 功能特色

- **開源專案展示**: 瀏覽我們最新的開源專案和工具
- **技術部落格**: 閱讀技術文章和最佳實踐
- **API 文件**: 完整的 API 參考文件
- **開發資源**: 設計系統、程式碼規範等資源
- **多語言支援**: 支援繁體中文和英文

### 📁 專案結構

```
tinder.github.io/
├── _config.yml          # Jekyll 配置檔案
├── index.md             # 首頁內容
├── README.md            # 專案說明文件
├── _posts/              # 部落格文章
├── _pages/              # 靜態頁面
├── assets/              # 靜態資源
└── _layouts/            # 頁面佈局模板
```

### 🛠️ 本地開發

#### 前置需求

- Ruby 2.7 或更新版本
- Jekyll 4.0 或更新版本
- Bundler

#### 安裝步驟

1. **克隆專案**

   ```bash
   git clone https://github.com/Tinder/tinder.github.io.git
   cd tinder.github.io
   ```

2. **安裝依賴**

   ```bash
   bundle install
   ```

3. **啟動本地伺服器**

   ```bash
   bundle exec jekyll serve
   ```

4. **瀏覽網站**
   開啟瀏覽器前往 `http://localhost:4000`

### 📝 新增內容

#### 新增部落格文章

1. 在 `_posts/` 目錄建立新的 Markdown 檔案
2. 檔案名稱格式：`YYYY-MM-DD-title.md`
3. 在檔案開頭添加 front matter：

```yaml
---
layout: post
title: "文章標題"
date: 2024-01-01
author: "作者名稱"
categories: [技術, 開發]
tags: [react, javascript, 前端]
---
```

#### 新增靜態頁面

1. 在 `_pages/` 目錄建立新的 Markdown 檔案
2. 在檔案開頭添加 front matter：

```yaml
---
layout: page
title: "頁面標題"
permalink: /page-url/
---
```

### 🎨 自訂樣式

- 主要樣式檔案位於 `assets/css/`
- 使用 SCSS 進行樣式開發
- 支援響應式設計

### 📊 部署

這個網站使用 GitHub Pages 自動部署：

1. 推送程式碼到 `main` 分支
2. GitHub Actions 自動建置和部署
3. 網站會在幾分鐘內更新

### 🤝 貢獻指南

我們歡迎所有形式的貢獻！

#### 如何貢獻

1. Fork 這個專案
2. 建立功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交變更 (`git commit -m 'Add amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 建立 Pull Request

#### 貢獻類型

- 🐛 **錯誤回報**: 使用 GitHub Issues
- 💡 **功能建議**: 建立 Feature Request
- 📝 **文件改善**: 直接提交 Pull Request
- 🔧 **程式碼貢獻**: 遵循程式碼規範

### 📞 聯絡資訊

- **技術支援**: [GitHub Issues](https://github.com/Tinder/tinder.github.io/issues)
- **一般詢問**: support@tinder.com
- **合作提案**: partnerships@tinder.com

### 📄 授權條款

本專案採用 MIT 授權條款 - 詳見 [LICENSE](LICENSE) 檔案

---

## English

### Welcome to Tinder GitHub Pages

This is the official GitHub Pages website for Tinder's technical team, showcasing our open source projects, technical articles, and development resources.

### 🚀 Features

- **Open Source Projects**: Browse our latest open source projects and tools
- **Technical Blog**: Read technical articles and best practices
- **API Documentation**: Complete API reference documentation
- **Development Resources**: Design system, coding standards, and more
- **Multi-language Support**: Support for Traditional Chinese and English

### 📁 Project Structure

```
tinder.github.io/
├── _config.yml          # Jekyll configuration
├── index.md             # Homepage content
├── README.md            # Project documentation
├── _posts/              # Blog posts
├── _pages/              # Static pages
├── assets/              # Static assets
└── _layouts/            # Page layout templates
```

### 🛠️ Local Development

#### Prerequisites

- Ruby 2.7 or newer
- Jekyll 4.0 or newer
- Bundler

#### Installation Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/Tinder/tinder.github.io.git
   cd tinder.github.io
   ```

2. **Install dependencies**

   ```bash
   bundle install
   ```

3. **Start local server**

   ```bash
   bundle exec jekyll serve
   ```

4. **Browse the website**
   Open your browser and go to `http://localhost:4000`

### 📝 Adding Content

#### Adding Blog Posts

1. Create a new Markdown file in the `_posts/` directory
2. File naming format: `YYYY-MM-DD-title.md`
3. Add front matter at the beginning of the file:

```yaml
---
layout: post
title: "Post Title"
date: 2024-01-01
author: "Author Name"
categories: [Technology, Development]
tags: [react, javascript, frontend]
---
```

#### Adding Static Pages

1. Create a new Markdown file in the `_pages/` directory
2. Add front matter at the beginning of the file:

```yaml
---
layout: page
title: "Page Title"
permalink: /page-url/
---
```

### 🎨 Customizing Styles

- Main style files are located in `assets/css/`
- Use SCSS for style development
- Supports responsive design

### 📊 Deployment

This website uses GitHub Pages for automatic deployment:

1. Push code to the `main` branch
2. GitHub Actions automatically builds and deploys
3. Website updates within minutes

### 🤝 Contributing

We welcome all forms of contributions!

#### How to Contribute

1. Fork this project
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Create a Pull Request

#### Types of Contributions

- 🐛 **Bug Reports**: Use GitHub Issues
- 💡 **Feature Suggestions**: Create Feature Request
- 📝 **Documentation Improvements**: Submit Pull Request directly
- 🔧 **Code Contributions**: Follow coding standards

### 📞 Contact Information

- **Technical Support**: [GitHub Issues](https://github.com/Tinder/tinder.github.io/issues)
- **General Inquiries**: support@tinder.com
- **Partnership Proposals**: partnerships@tinder.com

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
