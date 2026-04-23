<div align="center">
  <h1>Thyroid TNM Tool</h1>
  <p><strong>Standalone thyroid cancer TNM staging and treatment planning web app.</strong></p>
  <p><a href="README.zh-CN.md">简体中文</a> | <strong>English</strong></p>
  <p>
    <a href="https://github.com/liqi3333/thyroid/releases/latest"><img alt="Latest Release" src="https://img.shields.io/github/v/release/liqi3333/thyroid?display_name=tag&label=release" /></a>
    <a href="https://github.com/liqi3333/thyroid/actions/workflows/build-html.yml"><img alt="Build HTML" src="https://github.com/liqi3333/thyroid/actions/workflows/build-html.yml/badge.svg" /></a>
    <a href="https://github.com/liqi3333/thyroid/actions/workflows/release.yml"><img alt="Release HTML" src="https://github.com/liqi3333/thyroid/actions/workflows/release.yml/badge.svg" /></a>
  </p>
  <p>
    <a href="https://liqi3333.github.io/thyroid/"><img alt="Open Online" src="https://img.shields.io/badge/Open-Online%20Page-0ea5e9?style=for-the-badge" /></a>
    <a href="https://github.com/liqi3333/thyroid/releases/latest"><img alt="Download HTML" src="https://img.shields.io/badge/Download-Latest%20HTML-10b981?style=for-the-badge" /></a>
  </p>
</div>

## Overview

This project packages a standalone HTML interface for thyroid cancer TNM staging, treatment planning, and follow-up suggestions into a shareable GitHub repository with release automation and GitHub Pages deployment.

## Access

- GitHub repository: <https://github.com/liqi3333/thyroid>
- Online page: <https://liqi3333.github.io/thyroid/>
- Latest release: <https://github.com/liqi3333/thyroid/releases/latest>

## Local usage

Open `index.html` directly in a browser, or generate the release-ready HTML file:

```bash
npm run build:html
```

Output:

```text
dist-html/Thyroid-TNM-Tool-1.0.0.html
```

## Automation

- Push to `main`: run HTML build and upload workflow artifact
- Push a tag like `v1.0.0`: build the standalone HTML file and publish it to GitHub Releases
- GitHub Pages serves the root `index.html`

## Notes

- This repository currently focuses on the web version only
- Medical content is for informational use only and does not replace formal clinical decision-making
