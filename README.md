# Pyae Hlan Bo (Steven) Portfolio Website

This is my **personal portfolio website**, which I **designed and built entirely from scratch**. The site demonstrates my skills, projects, experience, and personal background. During this project, I learned to integrate **HTML, CSS, and JavaScript** to create a fully responsive, interactive website without relying on frameworks or templates.

---

## Learning Highlights

Through building this portfolio, I gained hands-on experience in:

### 1. HTML5
- Structuring a multi-section website: Profile, About, Experience, Projects, Contact, and Footer.
- Using semantic elements and attributes for accessibility and SEO.
- Embedding images, links, and buttons that interact with JavaScript.

### 2. CSS3
- Designing a modern and clean user interface with **flexbox** for layout.
- Applying **responsive design** principles using **media queries** to ensure the website looks great on desktop, tablet, and mobile.
- Implementing smooth **transitions** for buttons, links, and menu animations.
- Learning to style complex components like skill cards, project sections, and contact cards.

### 3. JavaScript
- Creating an **interactive mobile side navigation menu** that toggles open and closed when the hamburger icon is clicked.
- Manipulating the DOM using `classList.toggle()` to add/remove classes and trigger CSS animations.
- Understanding event handling and combining JS with HTML/CSS to enhance user experience.

### 4. Integration & Responsiveness
- Learning to combine HTML, CSS, and JS effectively.
- Managing layout changes across multiple screen sizes (desktop, tablet, and mobile).
- Handling images, icons, and buttons in a flexible way that maintains aesthetics across devices.

---

## Features

- **Profile Section:** Profile picture, name, title, CV download button, and social icons.
- **About Section:** Education, current focus, and personal bio with flexible layout.
- **Experience Section:** Software and hardware skills presented with cards and icons.
- **Projects Section:** Showcases multiple projects with buttons linking to GitHub and more details.
- **Contact Section:** Email, LinkedIn, and phone information displayed using responsive cards.
- **Footer:** Navigation links and copyright notice.
- **Interactive Menu:** Hamburger menu for mobile devices with smooth open/close animations.

---

## Code Highlights

### JavaScript Menu Toggle
```javascript
function toggleMenu() {
    const menu = document.querySelector(".menu-links");
    const icon = document.querySelector(".side-icon");
    menu.classList.toggle("open");
    icon.classList.toggle("open");
}
