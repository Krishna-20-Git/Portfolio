# Ethereal Triangulum — Premium Bento Portfolio

A state-of-the-art, Awwwards-inspired developer portfolio designed with dynamic Bento grids, interactive system simulations, and custom micro-interactions.

Live Demo: **[Deployed on Vercel](https://vercel.com)** *(Insert your Vercel URL here!)*

---

## ✦ Key Features

* **Terminal Splash Preloader**: An interactive terminal booting sequence simulating diagnostics, socket testing, and system initializations before transitioning smoothly into the main website.
* **Interactive CLI Console**: A fully-functional, client-side mock terminal bento cell. Visitors can type interactive commands like `help`, `skills`, `projects`, `git log`, and `clear` to explore the codebase's history and configuration.
* **Ambient Canvas Backdrop**: An interactive HTML5 Canvas drawing fluid, slow-motion particle meshes that react subtly to mouse movements.
* **Web Audio API Synth Engine**: Real-time synthesized chimes, key clicks, card swooshes, and navigation beeps generated dynamically without downloading large MP3 assets. Includes a floating mute toggle.
* **Magnetic Spring Cursors**: Custom magnetic cursor trail utilizing `mix-blend-mode: difference` for high-contrast visibility, coupled with custom canvas sparkles.
* **Responsive Bento Layout**: Highly balanced CSS Grid and Flexbox layouts optimized to look stunning on ultra-wide screens, laptops, tablets, and mobile screens.

---

## 🛠 Tech Stack & Dependencies

* **Core**: Semantic HTML5, JavaScript (ES6+), Vanilla CSS3 (Custom properties/CSS Variables).
* **Smooth Scrolling**: [Lenis Smooth Scroll](https://github.com/darkroomengineering/lenis) for premium kinetic friction scrolling.
* **Audio**: Native Browser Web Audio API (Synthesizer class).
* **Typography**: Outfit, Space Grotesk, and Fira Code via Google Fonts.
* **Icons**: FontAwesome v6.

---

## 📂 Project Structure

```bash
├── index.html       # Semantic HTML5 page layout
├── style.css        # Adaptive dark/light theme properties & Bento grids
├── app.js           # Audio synthesizer, CLI console logic, & scroll reveal triggers
├── assets/
│   ├── avatar.jpg   # Circular cropped user profile photo
│   └── *.png        # Desktop previews for project cards
└── README.md        # Documentation
```

---

## 🚀 Local Development

To run this project locally without compilation, spin up a simple static file server:

### Option A: Python (Built-in)
```bash
python -m http.server 3000
```
Then open `http://127.0.0.1:3000` in your browser.

### Option B: Node.js (via npx)
```bash
npx live-server
```

---

## 📄 License

This project is licensed under the MIT License - feel free to use it to showcase your own work!
