# 🎬 MotionBox

> **MotionBox** — A collection of pure CSS animations, crafted and showcased with **Next.js**.  
> Learn, explore, and play with smooth, modern, and reusable motion effects — no JavaScript required!

---

## 🌈 Overview

**MotionBox** is a learning playground and demo site that showcases beautiful CSS animations — built with **Next.js** for fast development and deployment.

Each animation is implemented using **pure CSS (transitions, transforms, and keyframes)**, focusing on:
- Performance-friendly techniques  
- Readable, modular styles  
- Modern design language  

Whether you're learning CSS animation or looking for inspiration for your own UI, **MotionBox** gives you a clean and structured example base.

---

## ⚙️ Tech Stack

| Purpose | Tech |
|----------|------|
| Frontend framework | [Next.js 15](https://nextjs.org) |
| Styling | Pure CSS / CSS Modules |
| Build tool | Next.js built-in compiler |
| Hosting | Vercel / Any Node-compatible host |

---

## 📁 Project Structure

```
motionbox/
├─ public/               # Static assets (images, icons, etc.)
├─ src/
│  ├─ animations/        # Animation demos (each as a component)
│  │   ├─ bounce/
│  │   │   ├─ BounceBox.module.css
│  │   │   └─ BounceBox.tsx
│  │   ├─ fade/
│  │   ├─ rotate/
│  │   └─ slide/
│  ├─ components/        # Shared UI components (Navbar, Layout, etc.)
│  ├─ pages/             # Next.js pages
│  │   ├─ index.tsx      # Homepage (animation showcase)
│  │   └─ about.tsx
│  ├─ styles/            # Global and base CSS
│  └─ utils/             # Helper functions (optional)
├─ package.json
└─ README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the project
```bash
git clone https://github.com/your-username/motionbox.git
cd motionbox
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Run the dev server
```bash
npm run dev
```

Open **http://localhost:3000** in your browser 🚀  

---

## ✨ Features

✅ 100% **pure CSS animations** — no JS motion libs  
✅ Modular & reusable component structure  
✅ Built with **Next.js App Router**  
✅ Easy to deploy on **Vercel**  
✅ Mobile-friendly and performance-optimized  

---

## 🧠 Learning Goals

- Understand how `@keyframes` and `transition` work  
- Learn how to combine transforms (`translate`, `scale`, `rotate`)  
- Explore CSS animation timing functions (e.g., `ease-in-out`, `cubic-bezier`)  
- Build reusable UI motion effects  
- Apply clean architecture even for small animation demos  

---

## 💡 Example Animations

| Animation | Description |
|------------|-------------|
| `FadeIn` | Soft fade-in effect on load |
| `SlideUp` | Element slides up smoothly |
| `BounceBox` | Fun bouncing card motion |
| `GlowHover` | Neon-style hover glow |
| `SpinLogo` | Continuous rotation animation |

---

## 🧰 Scripts

| Command | Description |
|----------|-------------|
| `npm run dev` | Start local development |
| `npm run build` | Build production bundle |
| `npm run start` | Start production server |
| `npm run lint` | Check code style |

---

## 🌍 Deployment

**MotionBox** works perfectly with [Vercel](https://vercel.com):

```bash
vercel deploy
```

Or manually build and serve:
```bash
npm run build
npm start
```

---

## 🧑‍🎨 Author

**MotionBox** is built and maintained by **me**, as a personal learning project on CSS Animations and frontend motion design.

---

## 📜 License

MIT License © 2025 — You’re free to use, learn, and remix.  
If you enjoy it, consider giving it a ⭐ on GitHub!

---
