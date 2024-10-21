# DAY_021 | Video-Based Animated Landing Page

## Project Overview

For **DAY_021** of my daily code challenge series, I built a **video-based animated landing page** using **HTML**, **CSS**, and **GSAP**. The landing page features a looping video background and smooth animations to create a visually appealing and engaging experience.

---
### Inspiration from Awwwards Element by Elkruff 
Check the site out here! [Elkruff](https://elkruff.ava-case.com/)

---

## Preview

![DAY_021 Preview](./assets/DAY_021_1.gif)

## Inspiration

![Elkruff](./assets/DAY_021_2.gif)

---

## Key Features

- **Video Background**: A looping video background creates visual interest and sets the tone of the landing page.
- **GSAP Animations**: Key animations are powered by **GSAP**, providing smooth transitions and dynamic effects.
- **Static Layout**: The page is designed to be visually captivating without requiring scrolling interactions.
- **Clean Design**: Focuses on a minimalist design approach with carefully placed animations for a polished look.

---

## GSAP in Action

### Video Fade-in Animation

```javascript
gsap.from(".hero-video", {
  opacity: 0,
  duration: 2,
  ease: "power3.out",
});
```

The video background smoothly fades in when the page loads, creating an elegant entrance effect.

### Header Animation

```javascript
gsap.from(".header-item", {
  y: 100,
  opacity: 0,
  duration: 1.5,
  ease: "power3.out",
  stagger: 0.2,
});
```

This snippet animates the header items, sliding them into view with staggered timing to make the introduction more dynamic.

---

## How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/thounny/DAY_021.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd DAY_021
   ```

3. **Open the `index.html` file** in your browser, or use a local development server like **Live Server** in VSCode.

---

## Project Structure

```bash
DAY_021/
├── assets/
├── fonts/
├── styles.css
├── index.html
```

---

## Technologies Used

- **HTML5**: Provides structure and layout.
- **CSS3**: For styling and visual presentation.
- **JavaScript (ES6)**: Implements logic and animation control.
- **GSAP (GreenSock Animation Platform)**: Powers smooth transitions and animations.

---

## Author

![Logo](./assets/index_dwn.gif)

**Thounny Keo**  
Creative Developer & Designer  
Frontend Development Student | Year Up United

---

![miku](./assets/miku.gif)