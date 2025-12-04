# Ramox UI

<div align="center">
  <img src="./rx.png" width="150" alt="Ramox UI Logo" />
  <h3><strong>Ultra-Flat • Pill-Shaped • Precision UI for Next.js</strong></h3>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/version-5.1.1-black?style=flat-square" />
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/style-Pill_Shape-success?style=flat-square" />
  <img src="https://img.shields.io/badge/size-Lightweight-orange?style=flat-square" />
</p>

---

Ramox UI is a **zero-runtime React component library** designed specifically for **Next.js**, focused on a *Flat Precision* interface with fully-rounded pill-style elements.  
Ideal for Cloudflare Pages, ultra-light UI systems, dashboards, and modern app design.

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🚫 **Zero Runtime CSS** | No CSS-in-JS overhead, no runtime style injection |
| 🟢 **Pill-Shaped UI** | Fully rounded edges (9999px) on *everything* |
| 🌗 **Auto Dark Mode** | Follows OS theme — no config required |
| ⚪ **Flat Precision UI** | No shadows. No 3D. Clean + Minimal |
| 🅰 **Font Agnostic** | Uses your global font — not locked |
| 📱 **Mobile First** | Better touch hit-zones + no tap highlights |

---

## 📦 Installation

```bash
npm install @ramox/rx-style

Recommended for icons (optional):

npm install lucide-react


---

🚀 Quick Usage

import { Button, Card, Input, Note } from '@ramox/rx-style';

export default function App() {
  return (
    <div style={{ padding: 20 }}>
      <Card>
        <h2>Welcome to Ramox</h2>
        <Note>Ultra-flat UI with Zero Runtime CSS</Note>

        <Input placeholder="Email..." style={{ margin: '20px 0' }} />

        <Button variant="solid" onClick={() => alert("Hello!")}>
          Get Started
        </Button>
      </Card>
    </div>
  );
}


---

📁 Components Overview

General UI

Button — Solid / Soft / Outline / Ghost

Tag, Badge, StatusDot, Note


Form & Input

Input, Textarea, Select

Switch, Checkbox, Radio

Slider, Rating

FileUploader, DatePicker


Overlay & Feedback

Modal, Drawer

Alert, Toast

Skeleton, Loading

Tooltip


Display & Layout

Card, Table, Timeline

Chart (simple bar chart)

Glass (frosted blur container)


Media

VideoPlayer

Avatar, AvatarGroup

ImageBox

CodeSnippet



---

🎨 Theming

Global Font Control

Ramox UI does not include fonts — it inherits yours.

/* globals.css */
body {
  font-family: "Inter", sans-serif;
}

Light + Dark Mode Support

Mode	Colors Used

Light	#ffffff, #f4f4f5, #000000
Dark	#000000, #18181b, #ffffff


Automatically adapts using prefers-color-scheme.


---

📄 License

Released under the MIT License — free for commercial and open-source use.


---

<div align="center"><b>Ramox UI — Flat. Precise. Pill-Shaped.</b></div>
```
