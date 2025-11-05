# 🪖 AimOlive - SSB Practice Platform

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A free, all-in-one web platform for Indian Armed Forces aspirants to practice for the SSB interview (PPDT & TAT) and access a comprehensive PDF library.

**[Link to Live Demo]** 👈 (Add your GitHub Pages or deployment link here)

![AimOlive Screenshot](featurespic/aimolive-demo.png)
*(Suggestion: Add a screenshot of your live site and name it `aimolive-demo.png` in the `featurespic` folder)*

---

## 🎯 About The Project

**AimOlive** is a non-profit, static website built to help fellow Service Selection Board (SSB) aspirants. It provides a dedicated, free platform to improve Picture Perception & Discussion Test (PPDT) and Thematic Apperception Test (TAT) story-writing skills through time-bound, self-paced practice.

Beyond the practice arenas, it also solves a major problem for aspirants: resource management. It consolidates hundreds of essential preparation PDFs (OIR, GTO, WAT, SRT, etc.) into a single, organized, and easy-to-navigate HTML page.

This project was built by an aspirant, for aspirants, with the mission to help train our minds and improve through disciplined, smart practice.

---

## ✨ Key Features

* **📖 All-in-One PDF Library:** A single, clean interface (`ALL-PRACTICE_PDF.html`) to access your entire local library of SSB books and materials, organized by stage (OIR, GTO, WAT, SRT, etc.).
* **⏱️ Realistic Timed Practice:** Dedicated practice "arenas" for PPDT and TAT that simulate real exam time constraints to train your mind for pressure.
* **✅ 100% Free & Accessible:** No logins, no subscriptions, no fees. All features and materials are open for everyone.
* **📱 Fully Responsive:** Built with Bootstrap 4, the entire site is usable on desktop, tablet, and mobile.
* **📇 Dynamic "About Me" Page:** Features a dynamic Gravatar pull for the profile picture and a professional layout.

---

## 🛠️ Built With

This is a static website built with:

* **HTML5**
* **CSS3** (Custom properties, transitions, and responsive design)
* **Bootstrap 4** (For grid layout, cards, and navbar)
* **FontAwesome 5** (For all icons)
* **Google Fonts** (Orbitron, Ubuntu, Raleway)
* **JavaScript** (To power Bootstrap's dynamic components like dropdowns and collapses)

---

## 🚀 How to Use

This project is designed to run locally, as it links to your personal collection of PDF files.

**Prerequisite:** You must have your own collection of SSB practice PDFs and images organized into a folder structure. The `ALL-PRACTICE_PDF.html` file is built to work with the specific structure shown in the user's screenshots (i.e., a main folder named `SSB-Interview-main`).

**Running Locally:**

1. **Clone the repository:**

    ```sh
    git clone [https://github.com/sumanisfr/AimOlive.git](https://github.com/sumanisfr/AimOlive.git)
    ```

2. **Navigate to the directory:**

    ```sh
    cd AimOlive
    ```

3. **Set up your materials (Crucial Step):**
    * Place your main folder of PDFs (e.g., `SSB-Interview-main`) **inside** the cloned `AimOlive` directory, at the same level as `index.html`.
    * The links in `ALL-PRACTICE_PDF.html` are relative (e.g., `SSB-Interview-main/Book/RS (AGARWAL) APPTITUDE.pdf`). Your folder name and file names **must match** those in the HTML file for the links to work.

4. **Open the site:**
    * Simply double-click `index.html` to open it in your default web browser.

---

## 📁 Project File Structure

AimOlive/ ├── index.html # The main landing page ├── about.html # About the creator page ├── ALL-PRACTICE_PDF.html # The consolidated PDF library ├── PPDT-arena.html # PPDT practice page (Not included in prompt, but linked) ├── TAT-arena.html # TAT practice page (Not included in prompt, but linked) ├── featurespic/ │ ├── free.png │ ├── content-huge.jpg │ └── clock.jpg ├── images/ │ └── ssb-bg.jpg ├── favicon/ │ └── favicon-32x32.png └── README.md # This file

## 👨‍💻 About the Creator

This project was built and is maintained by **Suman Kumar Ghosh** ([@sumanisfr](https://github.com/sumanisfr)).

I'm a B.Tech Computer Science student (9.18 CGPA), AI/ML enthusiast, GSSOC Mentor, and defence aspirant. This project is my way of combining my passion for technology with my deep respect for the armed forces community.

🔗 **Connect with me:**

* **Portfolio:** [sumanisfr.github.io/My-Portfolio/](https://sumanisfr.github.io/My-Portfolio/)
* **LinkedIn:** [linkedin.com/in/suman-kumar-ghosh/](https://www.linkedin.com/in/suman-kumar-ghosh/)
* **LeetCode:** [leetcode.com/sumanisfr/](https://leetcode.com/sumanisfr/)

---

## ⚠️ Disclaimer

This website does not provide coaching, tips, or any guarantee of SSB recommendation. It is a self-practice tool. All materials linked are assumed to be owned by the user.
