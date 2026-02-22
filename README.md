# Cursor Text Masking (Hover Reveal Effect)

A clean, modern text masking hover effect built with HTML, CSS, and GSAP.

This project creates a "spotlight" effect that follows the user's cursor. When hovered, the spotlight acts as a magnifying glass or x-ray, revealing a hidden, humorous "reality" behind a professional statement about web development.

## 🚀 Features
- **GSAP Animations:** Smooth, performant cursor tracking using `gsap.to()`.
- **CSS Masking:** Uses `-webkit-mask-image` and standard `mask-image` with an SVG circle to create the spotlight.
- **Interactive:** The spotlight expands significantly when the user hovers over the text area.
- **Humorous Content:** A funny take on the reality of web development hiding beneath a professional facade.

## 🛠️ Technologies Used
- HTML5
- CSS3 (Variables, Masking)
- JavaScript
- [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/) for smooth animations.
- Google Fonts (Archivo)

## 💻 How to Use
1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. Move your mouse around the screen to see the spotlight text reveal effect.
4. Hover directly over the text paragraph to see the spotlight expand!

## 🔧 Customization
You can easily customize the effect by adjusting the following variables in the `index.html` file:

- **Text:** Modify the `<p>` tags inside `.og` (original) and `.mask` (reveal) divs.
- **Spotlight Size:** Adjust `maskSizeSmall` (default: 20) and `maskSizeLarge` (default: 150) in the JavaScript block.
- **Spotlight Color/Shape:** The spotlight shape is an inline SVG in the `.mask` CSS (`mask-image`).
- **Animation Ease:** Change the GSAP `ease` property (currently `back.out(1.7)`) to achieve different physics-based movements.

## 📄 License
Feel free to use and modify for your own projects!
