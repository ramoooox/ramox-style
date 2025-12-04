````markdown
# Ramox UI

<div align="center">
  <img src="./rx.png" width="150" alt="Ramox UI Logo" />
</div>

<br />

**The Ultra-Flat, Precision Design System for Next.js**

![Version](https://img.shields.io/badge/version-5.1.1-black?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Style](https://img.shields.io/badge/style-Pill_Shape-success?style=flat-square)
![Size](https://img.shields.io/badge/size-Lightweight-orange?style=flat-square)

**Ramox UI** is a lightweight, zero-runtime React component library designed specifically for **Next.js** applications deployed on platforms like **Cloudflare Pages**. It features a "Flat Precision" aesthetic with fully rounded (pill-shaped) elements, matte finishes, and zero layout shifts.

## Features

- **Zero Runtime CSS:** Styles are injected efficiently without heavy CSS-in-JS runtime overhead.
- **Pill-Shaped Design:** Every interactive element (Buttons, Inputs, Modals) features smooth, fully rounded corners (9999px).
- **Auto Dark Mode:** Automatically syncs with the user's system preference (OS Theme). No configuration required.
- **Flat Precision:** Removed shadows and 3D effects for a clean, precise, and modern look.
- **Font Agnostic:** Components inherit the font-family from your application body. No font locking.
- **Mobile First:** Optimized touch targets and removed Webkit tap highlights.

## Installation

Install the package via npm:

```bash
npm install @ramox/rx-style
````

*(Optional) We recommend installing `lucide-react` for icons if you want to match the documentation style:*

```bash
npm install lucide-react
```

## Usage

Import components directly from the package. No extra CSS import is needed.

```tsx
import React from 'react';
import { Button, Card, Input, Note } from '@ramox/rx-style';

export default function App() {
  return (
    <div style={{ padding: 20, fontFamily: 'sans-serif' }}>
      <Card>
        <h2>Welcome to Ramox</h2>
        <Note>This is a completely flat design system.</Note>
        
        <div style={{ margin: '20px 0' }}>
          <Input placeholder="Enter your email..." />
        </div>

        <Button variant="solid" onClick={() => alert('Clicked!')}>
          Get Started
        </Button>
      </Card>
    </div>
  );
}
```

## Components

### General

  - `Button` (Solid, Soft, Outline, Ghost)
  - `Tag` & `Badge`
  - `StatusDot` & `Note`

### Data Entry

  - `Input` & `Textarea`
  - `Select` (Custom Dropdown)
  - `Switch`, `Checkbox`, `Radio`
  - `Slider` & `Rating`
  - `FileUploader` (Drag & Drop)
  - `DatePicker`

### Feedback & Overlay

  - `Modal` (Zoom animation)
  - `Drawer` (Slide animation)
  - `Alert` & `Toast`
  - `Skeleton` & `Loading`
  - `Tooltip`

### Data Display

  - `Card`
  - `Table` (Responsive)
  - `Timeline`
  - `Chart` (Simple Bar Chart)
  - `Glass` (Backdrop Blur Container)

### Media

  - `VideoPlayer` (Custom SVG Controls)
  - `Avatar` & `AvatarGroup`
  - `ImageBox`
  - `CodeSnippet`

## Theming

### Fonts

Ramox UI does not load any fonts. It uses `font-family: inherit`. To set a font, simply apply it to your global CSS:

```css
/* globals.css */
body {
  font-family: 'Inter', sans-serif;
}
```

### Dark Mode

Dark mode works out of the box using CSS `@media (prefers-color-scheme: dark)`.

  - **Light Mode:** White backgrounds, black accents, \#f4f4f5 surfaces.
  - **Dark Mode:** Black backgrounds, white accents, \#18181b surfaces.

## License

This project is licensed under the MIT License.

```
```
