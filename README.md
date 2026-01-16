# 🌋 Magma | Web3 Real Estate Platform (Clone)

An advanced frontend experiment in motion design and scroll-driven interactivity. By bridging GSAP ScrollTrigger with Locomotive Scroll, this Magma.io clone achieves ultra-smooth transitions and high-frame-rate Canvas animations, transforming static property data into a dynamic visual journey.

---

### 🔗 Live Demo
[👉 View Project Live]() 


---

## 🚀 Key Features

* **Locomotive Scroll:** Provides a premium, smooth-scrolling experience across all browsers.
* **Canvas Sequence Animation:** Three different sections (Page 3, 5, & 7) featuring high-quality 3D image sequences that play based on scroll depth.
* **Text Reveal Effect:** Interactive "letter-by-letter" color-changing animation using GSAP.
* **Locomotive-ScrollTrigger Proxy:** Seamless synchronization between custom smooth scrolling and GSAP's ScrollTrigger.
* **Modern UI:** Clean, minimalist design with a focus on typography and video backgrounds.

## 🛠️ Built With

* **HTML5 & CSS3:** Structure and advanced layouts (Flexbox, Positioning).
* **JavaScript (ES6):** Core logic for canvas rendering and DOM manipulation.
* **GSAP (GreenSock):** For industry-leading web animations.
* **ScrollTrigger:** To trigger animations on scroll.
* **Locomotive Scroll:** For the signature "smooth" feel.

---

## 📸 Technical Highlights

### 1. Scroll-Based Canvas Rendering
Instead of heavy videos, I used image sequences rendered on a `<canvas>` element. This ensures high performance and allows the user to "scrub" the animation back and forth by scrolling.



### 2. Text Splitting Logic
The project dynamically wraps every character of the headings into a `<span>` using JavaScript to animate them individually.

