# ART: Creative Expression 🎨

This is a single-page interactive site about the meaning of art, created for the SheCodes Basics Add-on workshop. The page features a personal essay on creativity and two JavaScript-powered interactive elements: a theme switcher and a quote carousel.

**[View Live Demo](https://benevolent-unicorn-ac532a.netlify.app)** 👈 

---

### Key Features

* **Dark Theme Toggle:** A button that switches the page between light and dark themes. This is done by adding or removing a `.dark-theme` class to the `body` element with JavaScript, which then activates different CSS styles.
* **Interactive Quote Carousel:** A component that allows the user to click "next" and "previous" arrows to cycle through an array of art-related quotes.

### Technologies Used

* **HTML5:** Used for the core structure and content.
* **Internal CSS:** All styling is contained in a `<style>` tag, using CSS Grid (`.image-grid`), transitions, and hover effects.
* **JavaScript (ES6):** Used for all interactive features, including:
    * `document.querySelector`
    * `document.getElementById`
    * `addEventListener`
    * `classList.toggle` (or `.add`/`.remove`)
    * Storing data in an Array (for the quotes)
    * Manipulating `textContent`

### What I Learned

This project helped me build on my foundational skills. The key skills I learned were:

* How to build a "dark mode" theme switcher.
* How to create an interactive carousel by storing string data in a JavaScript array.
* How to manage an array `currentIndex` to loop forwards and backward through the content.
* How to use CSS Grid to create a simple two-column image layout.
