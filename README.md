# Vex-Harvest-Havoc-Event-System

A production-ready, fully standalone, single-file web application designed for real-time tournament scoring, multi-screen displaying, and localized state management. Built entirely with vanilla HTML5, CSS3, and JavaScript, it requires no external dependencies, builds, or server setups to deploy.

---

## 🚀 Features

*   **⚡ All-in-One Architecture:** The entire UI, logic, styling, and state management live inside a single, highly optimized HTML file[cite: 8].
*   **📊 Multi-Screen Scoreboard:** An integrated, dynamic scoreboard interface optimized for secondary displays, projectors, or stream overlays.
*   **💾 Localized State Persistence:** Tournament data, team records, and match histories are automatically preserved across page refreshes using browser storage.
*   **📱 Fully Responsive Layout:** Adapts flawlessly across modern smartphones, tablets, laptops, and ultra-wide tournament displays.
*   **🛠️ Real-Time UI Control:** Seamlessly update team names, scores, match statuses, and brackets on the fly with instantaneous visual updates.

---

## 🛠️ Tech Stack & Architecture

*   **Structure:** HTML5 Semantic Markup
*   **Styling:** Modern CSS3 featuring Flexbox, Grid layouts, and CSS Variables for easy theme/color tweaking.
*   **Logic:** Vanilla ES6+ JavaScript (compiled in-file with decoupled, event-driven state updates).
*   **Persistence:** Local Storage API.

---

## 📂 Quick Start

Because this project is entirely self-contained, getting it up and running takes less than 10 seconds:

1.  **Download or copy** the `index.html` file to your local machine.
2.  **Double-click** the file to open it directly in any modern web browser (Chrome, Edge, Firefox, Safari).
3.  *(Optional)* Host it for free on platforms like **GitHub Pages**, **Vercel**, or **Netlify** by uploading the single file.

---

## ⚙️ Configuration & Customization

### Themes & Branding
You can easily customize the tournament's branding, primary colors, and typography by editing the CSS custom properties (variables) located at the top of the `<style>` block:

```css
:root {
  --primary-color: #0d6efd;   /* Change tournament accent color */
  --secondary-color: #6c757d; /* Change secondary element color */
  --dark-bg: #212529;        /* Change scoreboard background */
  --font-family: 'Segoe UI', system-ui, sans-serif;
}
```


## AI Disclaimer
Significant portions of this code were generated with Artificial Intelligence LLMs including but not limited to Claude and Gemini