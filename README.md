
# 🎴✨ **Animated Card Effects — 3D Neon Hover UI**

A cinematic, futuristic **3D Hover Card Animation** powered by **Conic Gradient Borders**, **Depth Tilt**, and **Neon Glow Effects** — created using **pure HTML + CSS + SCSS**.
This component adds a premium animated feel to portfolios, landing pages, and modern UI designs.

---

## 🧪 **Tech Stack**

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E44D26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/SCSS-CF649A?style=for-the-badge&logo=sass&logoColor=white" />
</p>

---

## 🔗 **Connect With Me**

<p>
  <a href="https://www.linkedin.com/in/vikas0905/" target="_blank">
    <img src="https://img.shields.io/badge/CONNECT%20ON%20LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

## 🖥️ **Best Viewed on Desktop**

⚠️ *This 3D animation renders best on Desktop/Laptop for full depth, glow & cinematic feel.*

---

## 🔗 **Project Links**

<p>
  <a href="https://github.com/vikaskumar098/Animated-card-effects">
    <img src="https://img.shields.io/badge/🧩 VIEW SOURCE CODE-000000?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <a href="https://vikaskumar098.github.io/Animated-card-effects/">
    <img src="https://img.shields.io/badge/🚀 LIVE DEMO-2962FF?style=for-the-badge&logo=netlify&logoColor=white" />
  </a>
</p>

---


## 📁 **Project Structure**

```
Animated-card-effects/
│── index.html
│── style.css
│── style.scss
│── style.css.map
```

---

## 🧩 **How It Works**

### 🌐 HTML Layout

```html
<main>
  <div class="card">
    <img src="IMAGE_URL" alt="">
    <h1>Hey!!</h1>
    <p>"AI transforms ideas into innovation, empowering everyone for a smarter future."</p>
  </div>
</main>
```

---

### 🎨 SCSS — Neon Glow + 3D Tilt Effect

```scss
.card:hover {
    box-shadow: 0 0 50px #dc3a0d;
    background:
      linear-gradient(black, black) padding-box,
      conic-gradient(from var(--rotate), black, #f52a06, black) border-box;
    animation: rotateBg 3s linear infinite;
    transform: rotateX(20deg);

    img {
        transform: rotateX(-20deg) translateZ(80px);
    }
}
```

---

## 🚀 **How to Run**

### Clone the Repo

```bash
git clone https://github.com/vikaskumar098/Animated-card-effects.git
```

### Run Locally

Open `index.html` in any browser — done!

---

## 🌟 **Where This UI Shines**

* Portfolio hero sections
* UI animations & micro-interactions
* Product display cards
* Animated landing pages
* CSS-only creative components
* Showcasing animation / CSS skills

---

## 🧭 **Future Enhancements**

* [ ] Glassmorphism overlay
* [ ] Mouse-follow tilt animation
* [ ] Multi-card animated gallery
* [ ] Light & Dark theme support

---

## 👨‍💻 **Author - Vikas Kumar**

<p>
  <a href="https://www.linkedin.com/in/vikas0905/" target="_blank">
    <img src="https://img.shields.io/badge/👨‍💻 CONNECT%20WITH%20ME%20ON%20LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

⭐ *If you like this project — please give it a star on GitHub!*


