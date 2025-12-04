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

## 🔥 Overview

Ramox UI is a **zero-runtime React UI library** built for **Next.js**, designed around a fully rounded *pill-shape aesthetic* with a flat, shadow-less look.  
Perfect for Cloudflare Pages, clean dashboards, minimal design systems, and fast UI.

---

## ⭐ Key Features

- Zero Runtime CSS — Fast. Lightweight.
- 9999px Pill-Shaped UI — Everywhere.
- Automatic Dark / Light Mode (OS-Synced)
- Font-Inheriting (no bundled font)
- Perfect for Mobile UI & Touch Inputs
- Modern Flat-Precision Aesthetic

---

## 📦 Installation *(Fully Separated)*

### 1️⃣ Install Core Package

```bash
npm install @ramox/rx-style

2️⃣ (Optional) Add Icons Support

npm install lucide-react

3️⃣ Import Components — No CSS Needed

import { Button, Card, Input, Note } from '@ramox/rx-style';


---

🚀 Quick Start Example

import { Button, Card, Input, Note } from '@ramox/rx-style';

export default function App() {
  return (
    <div style={{ padding: 20 }}>
      <Card>
        <h2>Welcome to Ramox UI</h2>
        <Note>Ultra-flat interface with no runtime CSS</Note>

        <Input placeholder="Type here..." style={{ margin: '20px 0' }} />

        <Button variant="solid" onClick={() => alert("Clicked!")}>
          Get Started
        </Button>
      </Card>
    </div>
  );
}


---

🧩 Components

General UI

Button · Tag · Badge · StatusDot · Note

Forms & Inputs

Input · Textarea · Select
Switch · Checkbox · Radio
Slider · Rating
FileUploader · DatePicker

Feedback & Overlay

Modal · Drawer
Alert · Toast
Skeleton · Loading · Tooltip

Data & Layout

Card · Table · Timeline · Chart
Glass (blur container)

Media

VideoPlayer · Avatar · AvatarGroup
ImageBox · CodeSnippet


---

🎨 Theming

Font Control (Fully Manual — No Bundled Font)

body {
  font-family: "Inter", sans-serif;
}

Light & Dark Palettes

Mode	Background	Surface	Text

Light	#ffffff	#f4f4f5	#000000
Dark	#000000	#18181b	#ffffff


Dark mode is automatic using prefers-color-scheme.


---

📄 License

MIT Licensed — Free for commercial + open-source use.


---

<div align="center">
  <strong>Ramox UI — Flat. Precise. Beautifully Rounded.</strong>
</div>
```
