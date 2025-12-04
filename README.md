# Ramox UI

<div align="center">
  <img src="./rx.png" width="150" alt="Ramox UI Logo" />
  <h3><strong>Ultra-Flat • Pill-Shaped • Precision UI for Next.js</strong></h3>
  <p>Zero-runtime, fast, modern and beautifully rounded interface components.</p>
</div>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/version-5.1.1-black?style=flat-square">
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square">
  <img src="https://img.shields.io/badge/design-PillShape-success?style=flat-square">
  <img src="https://img.shields.io/badge/runtime-ZeroCSS-red?style=flat-square">
</p>

---

## 📌 Overview

Ramox UI is a **fully-rounded pill-style design system** built for **Next.js + React**.  
It ships with **Zero Runtime CSS**, automatic **Dark Mode**, and a clean, shadowless **Flat Precision** UI.

Perfect for Cloudflare Pages, dashboards, SaaS panels, mobile-first apps, and minimal UIs.

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| ⚡ Zero Runtime CSS | no CSS-in-JS, no injection cost |
| 🔵 Fully Pill Shaped UI | 9999px radius everywhere |
| 🌗 Auto Dark Mode | syncs with OS theme — no config |
| 🔥 Featherlight Size | minimal bundle impact |
| 🅰 Font Agnostic | inherits your global font |
| 📱 Mobile First | natural touch feel, no tap highlight |

---

# 📦 Installation  *(Fully separated — clean steps)*

---

### 🔹 Step 1 — Install Core Package

```bash
npm install @ramox/rx-style


---

🔹 Step 2 — (Optional) Install Icons Support

If you want icons as used in examples & docs:

npm install lucide-react


---

🔹 Step 3 — Import Components

No CSS file, no provider, no setup.

import { Button, Card, Input, Note } from '@ramox/rx-style';


---

🧪 Quick Usage Example

export default function App() {
  return (
    <div style={{ padding: 20 }}>
      <Card>
        <h2>Welcome to Ramox UI</h2>
        <Note>Ultra-flat interface with zero-runtime styling</Note>

        <Input placeholder="Email..." style={{ margin: '20px 0' }} />

        <Button variant="solid" onClick={() => alert("Hello!")}>
          Get Started
        </Button>
      </Card>
    </div>
  );
}


---

📁 Components Library


---

🎛 General UI

✔ Button (Solid / Soft / Outline / Ghost)
✔ Tag · Badge
✔ StatusDot · Note


---

📝 Inputs & Forms

✔ Input · Textarea · Select
✔ Switch · Checkbox · Radio
✔ Slider · Rating
✔ FileUploader · DatePicker


---

🔔 Feedback / Overlay

✔ Modal · Drawer
✔ Alert · Toast
✔ Skeleton · Loading · Tooltip


---

📊 Data Display

✔ Card · Table
✔ Timeline · Chart (Bar)
✔ Glass (Blur surface)


---

🎥 Media + Code

✔ VideoPlayer
✔ Avatar · AvatarGroup
✔ ImageBox
✔ CodeSnippet


---

🎨 Theming

Font Styling (Fully manual — never forced)

body {
  font-family: "Inter", sans-serif;
}


---

Light & Dark Mode Support

Mode	Background	Surface	Text

Light	#ffffff	#f4f4f5	#000000
Dark	#000000	#18181b	#ffffff


Ramox UI automatically switches using prefers-color-scheme.


---

📜 License

Released under the MIT License — free for commercial + open-source use.


---

<div align="center">
  <strong>Ramox UI — Flat. Precise. Beautifully Rounded.</strong>
  <br>
  <sub>Minimal Design · Max Comfort · Zero Runtime</sub>
</div>
```
