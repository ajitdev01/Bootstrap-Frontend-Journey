# 🅱️ Bootstrap — From Basics to Advanced UI

> A structured Bootstrap learning repository covering responsive layouts, grid systems, components, utilities, and JS-powered UI patterns. Built with mobile-first examples for modern frontend and full-stack development.

---

## 📚 Table of Contents

- [About This Repository](#about-this-repository)
- [Learning Path](#learning-path)
- [Folder Structure](#folder-structure)
- [Topics Covered](#topics-covered)
  - [🟢 Basics (Folders 01–04)](#-basics-folders-0104)
  - [🟡 Intermediate (Folders 05–10)](#-intermediate-folders-0510)
  - [🔴 Advanced / JS Components (Folders 11–15)](#-advanced--js-components-folders-1115)
- [How to Use](#how-to-use)
- [Prerequisites](#prerequisites)
- [Quick Reference Cheatsheet](#quick-reference-cheatsheet)
- [Contributing](#contributing)

---

## About This Repository

This repository is a **hands-on Bootstrap curriculum** — starting from basic setup and progressing to full interactive UI components with JavaScript. Each folder focuses on one topic with practical, real-world examples.

Follow the folders in order for the smoothest learning experience. By the end, you'll be building professional, responsive interfaces with confidence.

---

## Learning Path

```
01 → 02 → 03 → 04            ──▶  BASICS        (Intro, Grid, Cards, Forms)
05 → 06 → 07 → 08 → 09 → 10  ──▶  INTERMEDIATE  (Forms+, Utilities, Slider, Color tools)
11 → 12 → 13 → 14 → 15       ──▶  ADVANCED       (Modals, Music Player, Navbar, Offcanvas, Toasts)
```

---

## Folder Structure

```
bootstrap-learning/
│
├── 01_BS-intro/                  # Bootstrap Basics    — Setup & Typography
├── 02_BS-row-col/                # Grid System         — Rows, Columns, Breakpoints
├── 03_BS-card-MP/                # Cards               — Card layouts & Media
├── 04_BS-Forms/                  # Forms I             — Inputs, Labels, Validation
│
├── 05_bs_form-2/                 # Forms II            — Advanced form controls
├── 06_bs_more/                   # Utilities           — Spacing, Colors, Display
├── 07_BS-slider/                 # Carousel            — Image sliders & controls
├── 08_BS-JS-ColorSwatcher/       # JS + BS             — Color Swatcher project
├── 09_BS-JS-ColorPicker/         # JS + BS             — Color Picker project
├── 10_bs_more/                   # More Utilities      — Flex, position, shadows
│
├── 11_BS-modal/                  # Modals              — Popup dialogs & triggers
├── 12_BS-JS-SimpleMusicPlayer/   # JS Project          — Music Player UI
├── 13_BS-Navbar/                 # Navbar              — Responsive navigation bar
├── 14-BS-Offcanvas/              # Offcanvas           — Slide-in drawers/sidebars
├── 15_BS-toasts/                 # Toasts              — Notification messages
│
└── README.md
```

---

## Topics Covered

### 🟢 Basics (Folders 01–04)

| Folder | Topic | Key Concepts |
|--------|-------|--------------|
| 01 | Intro to Bootstrap | CDN setup, container, typography, buttons, badges |
| 02 | Grid System | `row`, `col`, breakpoints (`sm`, `md`, `lg`, `xl`), nesting |
| 03 | Cards & Media | Card layouts, image caps, card groups, media objects |
| 04 | Forms I | Input types, `form-control`, labels, inline forms, validation states |

**Sample — Responsive Grid:**
```html
<div class="container">
  <div class="row">
    <div class="col-12 col-md-6 col-lg-4">Column 1</div>
    <div class="col-12 col-md-6 col-lg-4">Column 2</div>
    <div class="col-12 col-md-12 col-lg-4">Column 3</div>
  </div>
</div>
```

**Sample — Card:**
```html
<div class="card shadow-sm" style="width: 18rem;">
  <img src="image.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">Some quick example text.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
```

---

### 🟡 Intermediate (Folders 05–10)

| Folder | Topic | Key Concepts |
|--------|-------|--------------|
| 05 | Forms II | Select, checkbox, radio, range, floating labels, input groups |
| 06 | Utilities I | `m-`, `p-`, `text-`, `bg-`, `d-`, `border-` classes |
| 07 | Carousel / Slider | `carousel`, `carousel-item`, indicators, controls, autoplay |
| 08 | JS ColorSwatcher | Dynamic color switching with Bootstrap + Vanilla JS |
| 09 | JS ColorPicker | Custom color picker UI using Bootstrap + JS events |
| 10 | Utilities II | Flexbox, `position-`, `shadow-`, `overflow-`, `opacity-` |

**Sample — Carousel:**
```html
<div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="slide1.jpg" class="d-block w-100" alt="Slide 1">
    </div>
    <div class="carousel-item">
      <img src="slide2.jpg" class="d-block w-100" alt="Slide 2">
    </div>
  </div>
  <button class="carousel-control-prev" data-bs-target="#myCarousel" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" data-bs-target="#myCarousel" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>
```

---

### 🔴 Advanced / JS Components (Folders 11–15)

| Folder | Topic | Key Concepts |
|--------|-------|--------------|
| 11 | Modals | `modal`, `modal-dialog`, triggers, dismiss, sizes, JS control |
| 12 | Music Player | Full BS + JS mini project — play/pause, progress, track info |
| 13 | Navbar | `navbar`, `navbar-toggler`, collapse, dropdowns, sticky/fixed |
| 14 | Offcanvas | Slide-in sidebars, placement (start/end/top), backdrop |
| 15 | Toasts | Notification popups, auto-dismiss, stacking, positioning |

**Sample — Modal:**
```html
<!-- Trigger -->
<button class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#myModal">
  Open Modal
</button>

<!-- Modal -->
<div class="modal fade" id="myModal" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Modal Title</h5>
        <button class="btn-close" data-bs-dismiss="modal"></button>
      </div>
      <div class="modal-body">Your content here...</div>
      <div class="modal-footer">
        <button class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```

**Sample — Toast:**
```html
<div class="toast-container position-fixed bottom-0 end-0 p-3">
  <div id="myToast" class="toast" role="alert">
    <div class="toast-header">
      <strong class="me-auto">Notification</strong>
      <button class="btn-close" data-bs-dismiss="toast"></button>
    </div>
    <div class="toast-body">Action completed successfully! ✅</div>
  </div>
</div>

<script>
  const toast = new bootstrap.Toast(document.getElementById('myToast'));
  toast.show();
</script>
```

---

## How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/ajitdev01/bootstrap-learning.git
   cd bootstrap-learning
   ```

2. **Open any folder** and launch the `.html` file directly in your browser — no build tools needed.

3. **Follow the folders in order** — each topic builds on the previous one.

4. **Recommended tools:**
   - [VS Code](https://code.visualstudio.com/) + [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
   - Any modern browser (Chrome / Firefox / Edge)

---

## Prerequisites

| Requirement | Details |
|-------------|---------|
| HTML & CSS | Basic understanding recommended |
| JavaScript | Needed from Folder 08 onwards |
| Bootstrap version | Bootstrap 5.x (CDN included in files) |
| Build tools | ❌ None required — pure HTML files |

---

## Quick Reference Cheatsheet

```html
<!-- ── LAYOUT ─────────────────────────────────────── -->
<div class="container">              <!-- Fixed-width centered -->
<div class="container-fluid">       <!-- Full-width -->
<div class="row">                    <!-- Grid row -->
<div class="col-md-6">              <!-- Half-width on md+ screens -->

<!-- ── SPACING ────────────────────────────────────── -->
<!-- m=margin, p=padding | t/b/s/e/x/y | 0–5 -->
<div class="mt-3 px-4 mb-2 py-5">

<!-- ── COLORS ─────────────────────────────────────── -->
<div class="bg-primary text-white">
<div class="bg-success text-light">
<span class="text-danger fw-bold">

<!-- ── FLEXBOX ────────────────────────────────────── -->
<div class="d-flex justify-content-between align-items-center gap-3">

<!-- ── BUTTONS ────────────────────────────────────── -->
<button class="btn btn-primary btn-lg">
<button class="btn btn-outline-secondary btn-sm">

<!-- ── DISPLAY / RESPONSIVE ───────────────────────── -->
<div class="d-none d-md-block">     <!-- Hidden mobile, visible md+ -->
<div class="d-block d-lg-none">     <!-- Visible mobile, hidden lg+ -->
```

---

## Contributing

Found an issue or want to add a new component example? You're welcome to contribute!

1. Fork the repo
2. Create your branch: `git checkout -b feature/add-accordion`
3. Commit: `git commit -m "Add: Bootstrap Accordion examples"`
4. Push and open a Pull Request

---

<div align="center">

Made with ❤️ by [ajitdev01](https://github.com/ajitdev01)  
⭐ Star this repo if it helped you learn Bootstrap!

</div>
