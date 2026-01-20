# Hexo 个人博客

这是一个基于 [Hexo](https://hexo.io/) 的个人博客项目，托管于 GitHub Pages。

## 🚀 快速开始

1.  **安装依赖**
    ```bash
    npm install
    ```

2.  **启动本地服务器**
    ```bash
    hexo server
    ```
    访问 `http://localhost:4000` 即可预览。

## 📝 常用命令

### 1. 新建文章
```bash
hexo new "文章标题"
```
文件将生成在 `source/_posts/文章标题.md`。

### 2. 生成静态页面
```bash
hexo generate
# 或者简写
hexo g
```

### 3. 本地预览
```bash
hexo server
# 或者简写
hexo s
```

### 4. 部署到 GitHub
```bash
hexo deploy
# 或者简写
hexo d
```

### 5. 清理缓存
如果发现修改没生效，可以先清理再生成：
```bash
hexo clean
```

### 组合命令（推荐）
清理、重新生成并部署：
```bash
hexo clean && hexo g && hexo d
```
*(Windows PowerShell 中请使用分号: `hexo clean; hexo g; hexo d`)*

## ✍️ 写作指南

文章是 Markdown 格式，开头包含 Front-matter（元数据）：

```yaml
---
title: 我的文章标题
date: 2026-01-21 12:00:00
tags: [标签1, 标签2]
categories: 
  - 分类
---
```

正文内容写在下方即可。

## ⚙️ 配置说明

- **_config.yml**: 网站全局配置（标题、作者、部署设置等）。
- **_config.landscape.yml**: 主题配置文件（菜单、Banner、侧边栏等）。
