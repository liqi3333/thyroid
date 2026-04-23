<div align="center">
  <h1>Thyroid TNM Tool</h1>
  <p><strong>Product-style PC and mobile web app for thyroid cancer TNM staging, treatment planning, and follow-up reference.</strong></p>
  <p><a href="README.zh-CN.md">简体中文</a> | <strong>English</strong></p>

  <p>
    <a href="https://github.com/liqi3333/thyroid/releases/latest"><img alt="Latest Release" src="https://img.shields.io/github/v/release/liqi3333/thyroid?display_name=tag&label=release" /></a>
    <a href="https://github.com/liqi3333/thyroid/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/liqi3333/thyroid/total?label=downloads" /></a>
    <a href="https://github.com/liqi3333/thyroid/actions/workflows/build-html.yml"><img alt="Build HTML" src="https://github.com/liqi3333/thyroid/actions/workflows/build-html.yml/badge.svg" /></a>
    <a href="https://github.com/liqi3333/thyroid/actions/workflows/release.yml"><img alt="Release HTML" src="https://github.com/liqi3333/thyroid/actions/workflows/release.yml/badge.svg" /></a>
  </p>

  <p>
    <a href="https://liqi3333.github.io/thyroid/"><img alt="Open PC Web" src="https://img.shields.io/badge/Open-PC%20Web-0ea5e9?style=for-the-badge" /></a>
    <a href="https://liqi3333.github.io/thyroid/mobile.html"><img alt="Open Mobile Web" src="https://img.shields.io/badge/Open-Mobile%20Web-f59e0b?style=for-the-badge" /></a>
    <a href="https://github.com/liqi3333/thyroid/releases/latest"><img alt="Download Latest HTML" src="https://img.shields.io/badge/Download-Latest%20HTML-10b981?style=for-the-badge" /></a>
  </p>
</div>

## Overview

Thyroid TNM Tool packages a single-file clinical HTML interface into a deliverable product with a public GitHub repository, standalone HTML downloads, GitHub Pages deployment, and automated releases.

It now provides two separate web entry points:

- **PC web version**: preserves the original desktop-style layout
- **Mobile web version**: a separate `mobile.html` optimized for phone browsers

## Why this project is useful

- Fast AJCC 8th edition thyroid cancer staging lookup
- Treatment planning and follow-up suggestions in the same screen
- No backend, no installation required for web usage
- Can be opened online or downloaded as a standalone HTML file
- Keeps PC and mobile experiences separate instead of forcing one responsive compromise

## Access

- GitHub repository: <https://github.com/liqi3333/thyroid>
- PC web page: <https://liqi3333.github.io/thyroid/>
- Mobile web page: <https://liqi3333.github.io/thyroid/mobile.html>
- Latest release: <https://github.com/liqi3333/thyroid/releases/latest>
- All releases: <https://github.com/liqi3333/thyroid/releases>

## Delivery formats

The repository currently ships these forms:

- `index.html`, original PC web version
- `mobile.html`, separate phone-optimized version
- Release asset: `Thyroid-TNM-Tool-1.0.1.html`
- Release asset: `Thyroid-TNM-Tool-mobile-1.0.1.html`

## Quick Start

### Use online

- Open the PC page: <https://liqi3333.github.io/thyroid/>
- Open the mobile page: <https://liqi3333.github.io/thyroid/mobile.html>

### Download standalone HTML

Download the latest files from:

- <https://github.com/liqi3333/thyroid/releases/latest>

Then open either HTML file directly in a browser.

### Build locally

```bash
npm run build:html
```

Build outputs:

```text
dist-html/Thyroid-TNM-Tool-1.0.1.html
dist-html/Thyroid-TNM-Tool-mobile-1.0.1.html
```

## Product highlights

- Thyroid cancer TNM staging interface
- Treatment plan and follow-up recommendation panel
- Standalone offline-friendly HTML distribution
- Separate PC and mobile web entry points
- Public GitHub Pages deployment
- Automated GitHub Actions build and release workflow
- Bilingual project documentation

## Release automation

This repository includes GitHub Actions workflows for delivery automation.

- Push to `main`: build validation and upload HTML artifacts
- Push a tag such as `v1.0.1`: generate desktop and mobile standalone HTML files, then publish them to GitHub Releases
- GitHub Pages serves both `index.html` and `mobile.html`

Example:

```bash
git tag v1.0.1
git push origin v1.0.1
```

## Project structure

```text
.
├── docs/
│   └── RELEASE_TEMPLATE.md
├── scripts/
│   └── build-html-release.js
├── index.html
├── mobile.html
├── package.json
├── README.md
├── README.zh-CN.md
└── .github/workflows/
    ├── build-html.yml
    └── release.yml
```

## Notes

- This repository currently focuses on web delivery only, not EXE packaging
- Medical content is for informational use only and does not replace formal clinical decision-making
