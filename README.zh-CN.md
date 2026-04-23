<div align="center">
  <h1>Thyroid TNM Tool</h1>
  <p><strong>甲状腺癌 TNM 分期与治疗计划网页工具，含 PC 原版与独立手机版</strong></p>
  <p><strong>简体中文</strong> | <a href="README.md">English</a></p>
  <p>
    <a href="https://github.com/liqi3333/thyroid/releases/latest"><img alt="最新版本" src="https://img.shields.io/github/v/release/liqi3333/thyroid?display_name=tag&label=release" /></a>
    <a href="https://github.com/liqi3333/thyroid/actions/workflows/build-html.yml"><img alt="构建 HTML" src="https://github.com/liqi3333/thyroid/actions/workflows/build-html.yml/badge.svg" /></a>
    <a href="https://github.com/liqi3333/thyroid/actions/workflows/release.yml"><img alt="发布 HTML" src="https://github.com/liqi3333/thyroid/actions/workflows/release.yml/badge.svg" /></a>
  </p>
  <p>
    <a href="https://liqi3333.github.io/thyroid/"><img alt="在线打开" src="https://img.shields.io/badge/在线打开-网页-0ea5e9?style=for-the-badge" /></a>
    <a href="https://liqi3333.github.io/thyroid/mobile.html"><img alt="打开手机版网页" src="https://img.shields.io/badge/打开-手机版网页-f59e0b?style=for-the-badge" /></a>
    <a href="https://github.com/liqi3333/thyroid/releases/latest"><img alt="下载 HTML" src="https://img.shields.io/badge/下载-最新%20HTML-10b981?style=for-the-badge" /></a>
  </p>
</div>

## 项目简介

这个项目把甲状腺癌 TNM 分期、治疗计划与随访建议工具，整理成了一个同时提供 PC 原版网页和独立手机版网页的 GitHub 项目。

## 入口

- GitHub 仓库：<https://github.com/liqi3333/thyroid>
- 在线 PC 页面：<https://liqi3333.github.io/thyroid/>
- 在线手机版页面：<https://liqi3333.github.io/thyroid/mobile.html>
- 最新 Release：<https://github.com/liqi3333/thyroid/releases/latest>

## 本地使用

直接用浏览器打开 `index.html` 即可，或者运行构建命令生成发布版 HTML：

```bash
npm run build:html
```

产物：

```text
dist-html/Thyroid-TNM-Tool-1.0.1.html
dist-html/Thyroid-TNM-Tool-mobile-1.0.1.html
```

## 自动化流程

- 推送到 `main`：自动构建 HTML，并上传 PC + 手机版 artifact
- 推送形如 `v1.0.1` 的标签：自动生成 PC/手机版独立 HTML 文件并发布到 GitHub Releases
- GitHub Pages 直接托管 `index.html` 和 `mobile.html`

## 说明

- 当前仓库只做网页版本，不含 EXE
- 医学内容仅供信息参考，不替代正式临床决策
