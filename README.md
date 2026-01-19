# Do.
**Do.** is a single-page task management application featuring a high-contrast, Neo-Brutalist design aesthetic. It abandons modern gradients for raw, solid colors and tactile interactions, prioritizing clarity and focus.

![Project Status](https://img.shields.io/badge/status-active-facc15?style=flat-square&labelColor=0f172a&color=2952e3)
![License](https://img.shields.io/badge/license-MIT-facc15?style=flat-square&labelColor=0f172a&color=2952e3)

## ✨ Features
* **Neo-Brutalist UI:** A bold "Blue & Yellow" theme with hard edges, heavy borders, and deep drop shadows. No gradients.
* **Zero Dependencies:** Built entirely with vanilla HTML, CSS, and JavaScript. No frameworks or libraries required.
* **Local Persistence:** Uses the browser's `localStorage` API to save tasks automatically. Your list remains even after refreshing or closing the browser.
* **Tactile Animations:** Custom CSS animations for adding tasks, hovering, and checking items off.
* **Responsive:** Fully adaptive layout that maintains its bold look on mobile devices.

## 🛠 Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** CSS Variables for theming, Flexbox for layout, and keyframe animations.
* **JavaScript (ES6+):** DOM manipulation and state management.

## 🚀 Quick Start

Since this is a single-page application, no installation or build process is required.

1.  **Clone the repository** (or download the files):
    ```bash
    git clone [https://github.com/your-username/do-app.git](https://github.com/your-username/do-app.git)
    ```
2.  **Open the file:**
    Simply locate `index.html` (or `do-app.html`) in your file explorer and double-click to open it in your preferred web browser.

## 🎨 Design System

The design logic is centralized in the CSS `:root` variables for easy modification:

* **Primary Blue:** `#2952e3` (Background)
* **Cyber Yellow:** `#facc15` (Accents/Highlights)
* **Dark Slate:** `#0f172a` (Borders/Text)
* **Typography:** 'Space Grotesk' (via Google Fonts)
├── index.html      # Contains all markup, styles, and logic
└── README.md       # Documentation
