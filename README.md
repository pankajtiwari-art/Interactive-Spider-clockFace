# Interactive Spider Clock Face 🕷️⏱️

Welcome to the **Interactive Spider Clock Face**! This project is a highly creative, animated web-based clock that displays the current time using smooth, moving SVG graphics. The hands of the clock bounce and morph, giving it a unique, organic "spider-like" feel.

## 🚀 Live Demo
Experience the clock in action here: [Interactive Spider Clock Face](https://pankajtiwari-art.github.io/Interactive-Spider-clockFace/)

## ✨ Key Features
* **Real-Time Synchronization:** The clock automatically fetches your device's local time (hours, minutes, and seconds) and updates continuously.
* **Advanced SVG Morphing:** The clock hands don't just rotate; they physically change shape (morph) as they move. This creates a breathing, lifelike effect.
* **Bouncing Animations:** Custom easing functions make the seconds, minutes, and hours snap into place with a satisfying, realistic bounce effect.
* **Fully Responsive:** Built entirely with Scalable Vector Graphics (SVG), meaning the clock looks crystal clear and sharp on any screen size, from mobile phones to large desktop monitors.
* **Clean Dark UI:** A sleek, deep black background makes the white SVG clock elements pop, providing an immersive viewing experience.

## 🛠️ Technologies & Tools Used
* **HTML5 / SVG:** Used to draw the complex gears, clock face, and spider-like hands using coordinate paths directly in the browser.
* **CSS3:** For the layout, centering the clock perfectly on the screen, and applying beautiful drop-shadow filters to give the clock a 3D effect.
* **JavaScript (Vanilla):** Handles the mathematical logic to convert the current time (`new Date()`) into exact rotation degrees for each individual hand.
* **GSAP (GreenSock Animation Platform):** The powerful core engine driving the timeline, delays, and repeating animations.
* **MorphSVGPlugin:** Used to smoothly transition between different SVG path states (e.g., animating `handSec01` into `handSec02`).

## ⚙️ How to Run Locally
If you want to download and test this project on your own computer, it is very simple! No servers or complicated setups are required.

1. Clone this repository or download it as a ZIP file.
2. Extract the files to a folder on your computer.
3. Open the `index.html` file directly in any modern web browser (Google Chrome, Firefox, Edge, or Safari).
4. Watch the clock come to life!

## 👨‍💻 About the Author
Created by **Pankaj Tiwari**. 
I am a passionate developer with experience in building dynamic websites and interactive games. Beyond coding, I explore the depths of the human mind and have authored books, including *Control Psychology: The Illusionary Game* 😉.

## 📄 License
This project is open-source and proudly licensed under the **Mozilla Public License Version 2.0 (MPL 2.0)**. You are free to use, modify, and distribute this code according to the terms of the license.
