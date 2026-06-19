# 👔 Happy Father's Day, Dad!

![HTML](https://img.shields.io/badge/Language-HTML5-orange.svg)
![CSS](https://img.shields.io/badge/Style-CSS3-blue.svg)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow.svg)
![Tailwind CSS](https://img.shields.io/badge/Framework-TailwindCSS-38BDF8.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

An interactive, elegant digital Father's Day celebration card website created by Sarah for Dad. 

This project is a single-page web application featuring high-quality customized animations, interactive gifts, personal photo memories, and randomized message scrolls designed to celebrate Father's Day in a modern, sophisticated style.

<img width="2858" height="1450" alt="image" src="https://github.com/user-attachments/assets/4ac0df56-6eb3-401a-afcf-afbf29a129d0" />

---

## ✨ Features

### 🎈 Welcome Screen
- Elegant, responsive design with a subtle geometric background grid.
- Soft floating gold balloons rendered with layered vector SVGs.
- Sophisticated serif typography pairing using Google Fonts' *Playfair Display*.
- Touch-friendly "Open" button with sleek sliding transition animations.

### 🔐 Secret Passcode Screen
- **Two-Column Interactive Grid Layout:**
  - **Left Side:** A retro Polaroid-styled photo frame featuring a memorable picture from Universal Studios (`photos/photo0.jpg`).
  - **Right Side:** An interactive virtual numeric touchpad protected by a secret passcode.
- Passcode challenge (**0621** — the date of Father's Day).
- Visual feedback indicators (dot markers) and responsive error/success animations.
- Colorful canvas-based confetti explosion upon successfully unlocking.

### 🎁 Gift Hub
An elegant gold-themed grid showcasing three beautifully styled 3D interactive gifts:

#### 💌 Gift 1 — Card & Cake
- **Interactive Envelope:** Open a gold envelope using CSS 3D perspectives to reveal the hidden letter.
- **Father's Day Letter:** A beautiful, responsive card highlighting a heartfelt message from Sarah to Dad.
- **Realistic 2-Tier Cake:** An elegant vector cake complete with shadows, cream icing, and berries.
- **Interactive Candle:** Tap the burning candle flame to "blow it out", which triggers a celebratory burst of custom gold confetti.

#### 📸 Gift 2 — Our Memories Album
- An interactive collection of 4 retro Polaroid-style photographs:
  - **Polaroid 1:** "Universal!" — Family portrait in Orlando (`photos/photo0.jpg`)
  - **Polaroid 2:** "Seafood Feast! 🦪" — Seafood feast dinner (`photos/photo1.jpg`)
  - **Polaroid 3:** "Sunny days outdoors" — Nature park walk (`photos/photo2.jpg`)
  - **Polaroid 4:** "Let's go Blue Jays! ⚾" — Baseball game selfie (`photos/photo3.jpg`)
- Interactive hover transitions that dynamically scale up and align the photos.
- Responsive mobile-first grid layout.

#### 🏺 Gift 3 — Jar of Warm Messages
- A stunning CSS glassmorphism glass jar containing rolled-up scrolls inside.
- Sparkle hover effects that react dynamically to touch and cursor movements.
- Interactive randomized message extraction engine pulling personalized messages from Sarah.
- An anti-repetition filter to prevent the same note from appearing twice consecutively.

---

## 🎨 Design Guidelines

- **Sophisticated Color Palette:** A carefully curated pastel yellow and warm cream layout featuring `#FFFDF0` (light warm cream), `#FFF9D4` (soft pastel yellow), and rich gold accents (`#F5D547`, `#C5A059`).
- **Typography:** Designed with classic *Playfair Display* for premium headings and modern *Inter* for maximum paragraph legibility.
- **Device Adaptability:** Built to be fully fluid across standard desktop screens, tablets, and smartphones.

---

## 🛠️ Technologies Used

- **HTML5:** Clean, semantic element structuring.
- **CSS3:** Keyframe layouts, custom polaroid rotators, and 3D envelope transitions.
- **JavaScript (Vanilla):** Keypad lock checks, state machines, and view rendering.
- **Tailwind CSS:** Modern utility-first class implementation for styling.
- **Canvas Confetti:** Lightweight engine utilized for micro-celebration events.

---

## 📂 Project Structure

```text
fathers-day-card/
│
├── index.html          # Main interactive single-file application
│
├── photos/             # Family memory photographs folder
│   ├── photo0.jpg      # Universal Orlando Cover / Polaroid 1
│   ├── photo1.jpg      # Seafood Feast / Polaroid 2
│   ├── photo2.jpg      # Nature Park Walk / Polaroid 3
│   └── photo3.jpg      # Blue Jays Game / Polaroid 4
│
└── README.md           # Documentation file

```

---

## 🎮 User Experience Flow

```text
Welcome Screen
      │
      ▼
Passcode Screen (Verify '0621')
      │
      ▼
   Gift Hub
 ┌────┼────┐
 ▼    ▼    ▼
Gift1 Gift2 Gift3

```

### Gift 1 (Card & Cake Flow)

```text
Envelope Clicked
       ↓
Letter Slides Up
       ↓
Interactive Candle Tap
       ↓
Gold Confetti Burst

```

### Gift 2 (Memories Flow)

```text
Photo Grid Loaded
       ↓
Hover/Tap Polaroids
       ↓
Vibrant Colors & Dynamic Scale-up

```

### Gift 3 (Message Jar Flow)

```text
Glass Jar Tapped
       ↓
Sparkles Particle Animation
       ↓
Random Note Display

```

---

## 👩‍💻 Author

**Sarah**

Created with ❤️ for Dad on Father's Day.
