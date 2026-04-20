# 🎬 GSAP Scroll Animation Landing Page

A visually engaging landing page built using GSAP (GreenSock Animation Platform) and ScrollTrigger. This project demonstrates smooth scroll-based animations, cinematic transitions, and modern UI effects.

---

## 🚀 Features

- Smooth intro animation with scaling and overlay fade
- Scroll-based animations using GSAP ScrollTrigger
- Cinematic hero section transitions
- Dynamic gradient text effects
- Animated scroll indicator
- Fully responsive design

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- GSAP
- ScrollTrigger

---

## 📂 Project Structure

project-root/
│── index.html  
│── style.css  
│── script.js  
│── public/  
│   └── logo_white.svg  
│── assets/  
│   └── gta_logo_purple.webp  

---

## ⚙️ Installation & Setup

1. Clone the repository

2. Go to the project folder

3. Open index.html in your browser

---

## 📌 How It Works

### Initial Animation
- Hero container scales down smoothly
- Overlay fades out
- Scrolling is enabled after animation completes

### Scroll Animation
- Section is pinned using ScrollTrigger
- Animations are controlled via timeline
- Smooth transitions using scrub

### Section Transitions
- Hero section transforms into next section
- Mask and gradient effects create smooth reveal

---

## 🎯 GSAP Concepts Used

- gsap.timeline()
- ScrollTrigger
- scrub
- pin
- fromTo()
- set()
- Overlapping animations ("<", "<+=0.5")

---

## 📱 Responsive Design

- Mobile-first layout
- Scales well across devices
- Adaptive typography

---

## ⚠️ Notes

Include GSAP CDN before using:

<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>  
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>  

Ensure assets are correctly placed in folders.

---

## 💡 Future Improvements

- Add more scroll sections
- Add 3D animations using Three.js
- Improve performance optimization
  

---

## 📜 License

This project is open-source and available under the MIT License.
