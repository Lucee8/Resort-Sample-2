# 🌊 The Windmill Resorts – Blue & White Premium Website

> A production-grade, fully animated luxury resort website in a clean **blue & white** professional theme. Built with pure HTML, CSS & JavaScript — no frameworks, no build tools, just open and go.


---

## 🌐 Live Demo

👉 **[View Live Site](https://your-username.github.io/windmill-resorts/)**

> Replace this link with your actual GitHub Pages URL after deployment.

---

## 🎨 Design Theme — Blue & White Professional

This website uses a clean, corporate-luxury blue and white palette — modern, trustworthy, and highly professional.

| Element | Color |
|---|---|
| Primary Blue | `#1B4F9E` |
| Medium Blue | `#2560B8` |
| Light Blue Accent | `#5A95DC` |
| Ultra Light Blue | `#EBF3FC` |
| Background | `#FAFCFF` (off-white) |
| Text | `#0A1E3D` (deep navy) |
| Borders | `#CBD9F0` (soft blue-grey) |
| Footer | Solid `#1B4F9E` blue |

### Why Blue & White?
Blue communicates trust, calm, and professionalism — perfect for a coastal resort. The white keeps the design airy and modern, letting photography breathe. Clean enough for corporate bookings, premium enough for luxury guests.

---

## ✨ Features

### 🎬 Animation System

| Animation | Description |
|---|---|
| **Page Loader** | Spinning gear ⚙ with sweep bar — plays 1.5s on first load |
| **Custom Cursor** | Blue dot + lagging ring that expands on hover |
| **Hero Drift** | Background image gently floats on an 18s CSS loop |
| **Split Hero** | Right-side photo ribbon with staggered reveal on load |
| **Scroll Reveals** | Elements slide in from left, right, or bottom on scroll |
| **Button Fill** | All buttons fill left-to-right with darker blue on hover |
| **Spinning Gear Logo** | Gear icon in navbar rotates continuously |
| **Book Fill (bottom)** | Room "Book Now" buttons fill from bottom upward |
| **Card Lift** | Cards lift + blue border glow on hover |
| **Amenity Icon Bounce** | Icons spring up with cubic-bezier on hover |
| **Review Line Sweep** | Blue gradient line sweeps across card top on hover |
| **Gallery Tint** | Photos brighten + blue overlay on hover |
| **Scroll Indicator** | Animated bobbing arrow at hero bottom |

### 📦 Sections Included

| Section | Description |
|---|---|
| **Navbar** | White glassmorphism bar, spinning gear logo, animated underline links |
| **Hero** | Full-screen photo + white overlay, right-side photo ribbon, stats row |
| **Blue Strip** | Royal blue highlight bar with 5 key resort features |
| **Booking Bar** | Date pickers + guest counters + room type → sends to WhatsApp |
| **Rooms** | 6 cards with tier badge, price overlay, hover lift |
| **About** | Blue background section with numbered list + layered image |
| **Amenities** | 8 white cards on light-blue background |
| **Gallery** | Asymmetric 5-image grid with blue hover tint |
| **CTA Strip** | Light blue call-to-action with decorative circles |
| **Reviews** | 3 white cards with gradient line sweep on hover |
| **Contact** | Info cards + WhatsApp button + animated form |
| **Footer** | 4-column blue footer with social, links, rooms, contact |

### 💬 WhatsApp — 3 Integration Points

| Location | Behaviour |
|---|---|
| **Floating button** (always visible) | Opens WhatsApp chat instantly |
| **Contact section button** | Pre-written greeting message |
| **Check Availability button** | Sends check-in, check-out, adults, children & rooms as one message |

---

## 📁 Project Structure

```
windmill-resorts/
│
├── index.html         ← Complete website (HTML + CSS + JS in one file)
├── README.md          ← This file
└── assets/            ← (Optional) Add real client photos here
    └── images/
        ├── hero.jpg
        ├── room-seaview.jpg
        ├── pool.jpg
        └── ...
```

> **Single-file website** — everything in `index.html`. No npm, no build tools, no dependencies.

---

## 🚀 Deploy to GitHub Pages (Step by Step)

### Step 1 — Rename the file
Rename `windmill_blue_white.html` → **`index.html`**
> GitHub Pages only recognizes `index.html` as the homepage.

### Step 2 — Create a Repository
1. Go to [github.com](https://github.com) → click **New**
2. Name: `windmill-resorts`
3. Set to **Public** → **Create repository**

### Step 3 — Upload Files
1. Click **"Add file" → "Upload files"**
2. Drag and drop `index.html` + `README.md`
3. Commit message: `Add Windmill Resorts website — blue & white theme`
4. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click **Settings** → left sidebar → **Pages**
2. Branch: `main`, folder: `/ (root)` → **Save**
3. Wait ~2 minutes

Your site goes live at:
```
https://your-username.github.io/windmill-resorts/
```

### Step 5 — Update the README
Edit this file, replace the live demo placeholder link at the top with your real URL.

---

## 🎨 How to Customize for Any Client

### Change the Color Theme
All colors are CSS variables at the top of the `<style>` tag:
```css
--blue: #1B4F9E;        /* Main brand color — change this first */
--blue2: #2560B8;       /* Hover / darker state */
--blue-light: #5A95DC;  /* Accents and highlights */
--blue-pale: #D6E6F8;   /* Soft fill backgrounds */
--blue-ultra: #EBF3FC;  /* Ultra-light tints */
```
Change `--blue` and the whole site updates automatically.

### Resort Details — Find & Replace

| Find this | Replace with |
|---|---|
| `The Windmill Resorts` | Client's resort name |
| `919324765292` | Client's WhatsApp number (no +, no spaces) |
| `+91 9324 765292` | Display phone number |
| `+91 88793 18879` | Second number (or delete the row) |
| `+91 9529 400429` | Reception number (or delete) |
| `Devbag Sangam Rd, Bhanji Wadi, Devbag, Tarkarli` | Client's address |
| `Maharashtra 416606` | State and PIN |
| `Devbag · Tarkarli · Malvan` | Location tagline |
| `October – February` | Client's best season |
| `1:00 PM` | Client's check-in time |
| `10:00 AM` | Client's check-out time |

### Change the Logo Icon
Find the spinning gear in the HTML:
```html
<span class="logo-gear">⚙</span>
```
Replace `⚙` with any emoji or letter — for example `🏖`, `🌿`, or the first letter of the resort name.

### Replace Photos
Swap Unsplash URLs with real client images:
```html
<!-- Placeholder -->
src="https://images.unsplash.com/photo-XXXXXXX?w=600&q=80"

<!-- Local file -->
src="assets/images/room-seaview.jpg"

<!-- Hosted URL -->
src="https://cdn.clientwebsite.com/room-seaview.jpg"
```

### Disable Custom Cursor (optional)
In `<style>`, change:
```css
body { cursor: none; }
```
to:
```css
body { cursor: auto; }
```
Then remove the two `.cursor` divs and the cursor JS block at the bottom of the page.

---

## 🏨 Real Resort Data Used

| Detail | Value |
|---|---|
| **Full Address** | Devbag Sangam Rd, Bhanji Wadi, Devbag, Tarkarli, MH 416606 |
| **Bookings** | +91 9324 765292 / +91 88793 18879 |
| **Reception** | +91 9529 400429 |
| **Guest Rating** | 4.5★ from 1,643+ reviews |
| **Check-in** | 1:00 PM |
| **Check-out** | 10:00 AM |
| **Best Season** | October – February |
| **Price Range** | ₹6,500 – ₹18,000 per night |

**Rooms** — Sea View Suite, Premium Sea View, Executive Suite (Jacuzzi), Deluxe Sea Facing, Family Room, Standard Room

**Amenities** — Infinity pool, private beach, Malvani restaurant, scuba diving, indoor games, beach cycling, gazebo & lawn, free parking

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Animations, layout, responsive, theming |
| Vanilla JavaScript | Cursor, loader, scroll reveals, counters, WhatsApp |
| Google Fonts | Cormorant Garamond (display serif) + Outfit (body) |
| CSS Custom Properties | Full theme system via variables |
| IntersectionObserver | Scroll-triggered animations |
| requestAnimationFrame | Smooth cursor lag |

**Zero dependencies. Zero frameworks. Zero build steps.**

---

## ✅ Pre-Delivery Checklist

- [ ] Rename file to `index.html`
- [ ] Replace all instances of resort name
- [ ] Update WhatsApp number (all instances of `919324765292`)
- [ ] Update all phone numbers
- [ ] Update address and location
- [ ] Change logo gear icon if needed
- [ ] Update room names, features, prices
- [ ] Replace all Unsplash images with real photos
- [ ] Adjust `--blue` CSS variable to client's brand color
- [ ] Update check-in / check-out times and best season
- [ ] Test all WhatsApp links open correctly
- [ ] Test "Check Availability" sends proper WhatsApp message
- [ ] Test on mobile — hamburger menu, stacked layout
- [ ] Test page loader and custom cursor
- [ ] Deploy to GitHub Pages
- [ ] Update live demo link in this README

---

## 🔄 Version History

| Version | Theme | Key Difference |
|---|---|---|
| v1 | Deep Ocean Navy + Azure | Dark background, teal glow, dark-mode feel |
| **v2** | **Blue & White ← this file** | Light background, clean borders, corporate-luxury, photo ribbon hero |

---

## 📄 License

Built for client delivery. Each deployed copy is customized per client. Not for redistribution as-is.

---

## 👨‍💻 Built By

**Lucee** — Student & Web Developer
Building professional websites for hotels, resorts & local businesses across India.

📱 WhatsApp: [Chat with me](https://wa.me/91XXXXXXXXXX)
📷 Instagram: [@your_handle](https://instagram.com/your_handle)
🌐 Portfolio: [your-portfolio.com](https://your-portfolio.com)

---

> ⭐ **Star this repo** if you found it useful — it helps a student developer grow!
