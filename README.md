# 6️⃣4️⃣ base64ed

[![Version](https://img.shields.io/badge/version-2.1.0-emerald?style=flat-square)](https://github.com/ranggakd/base64ed/releases/tag/v2.1.0)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-10b981?style=flat-square&logo=github)](https://ranggakd.github.io/base64ed/)

> Instant, zero-latency image to Base64 encoder, decoder, and full-resolution lightbox viewer. Tailored for Markdown, HTML embeds, and CSS stylesheets.

**Live Application**: [https://ranggakd.github.io/base64ed/](https://ranggakd.github.io/base64ed/)

---

## ✨ Features

- **Semantic Versioning**: Formally tracked as `v2.1.0` in both `package.json` and the interactive front-end UI.
- **Full-Resolution Lightbox Viewer**:
  - Click any thumbnail (uploaded image, decoded output, or demo sample) to inspect it in a high-fidelity popup modal.
  - Switch between **1:1 Real Pixels** and **Fit to Screen**.
  - Dimension metadata display with direct in-modal download and copy actions.
- **Image &rarr; Base64 (Encoder)**:
  - Drag-and-drop zone with animated glow states.
  - File picker (PNG, JPEG, WEBP, SVG, GIF, AVIF).
  - Global clipboard paste (`Ctrl+V` / `Cmd+V`) anywhere on the page.
  - Image metadata: live thumbnail preview, dimensions ($W \times H$), original file size, and Base64 size with overhead indicator.
  - Multi-format exports:
    - **Markdown**: `![filename](data:image/png;base64,...)`
    - **Data URI**: `data:image/png;base64,...`
    - **HTML `<img>`**: `<img src="..." alt="..." width="..." height="..." />`
    - **CSS**: `background-image: url("...");`
    - **Raw Base64**: Clean unformatted base64 payload.
  - 1-click clipboard copy with animated toast notification.
- **Base64 &rarr; Image (Decoder)**:
  - Paste any Data URI, raw Base64 string, or Markdown image tag.
  - Reconstructs and previews the image with dimensions.
  - Full-resolution preview popup and direct 1-click image download button.
- **Interactive Demo**: 1-click test button loaded with the iconic "Cat WOULD" sample image.
- **Zero External Dependencies**: Pure vanilla HTML5, CSS3, and ES6. 100% private and runs fully client-side.

---

## 📦 Versioning

This project adheres to [Semantic Versioning (SemVer)](https://semver.org/):
- **Current Version**: `v2.1.0` (Minor feature bump: Real-size image modal lightbox viewer)
- Click the `v2.1.0` badge on the web UI to inspect release notes and SemVer breakdown.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
