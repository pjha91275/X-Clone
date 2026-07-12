# X-Clone 𝕏

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite_7-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev/)
[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg?style=for-the-badge)](https://opensource.org/licenses/ISC)

A pixel-perfect, highly responsive frontend clone of the **Twitter/𝕏** web application interface. This project showcases modern, responsive layouts using utility-first CSS classes, powered by the latest **Tailwind CSS v4** and **Vite** development server.

---

## 🚀 Live Demo & Visuals

Designed to feel premium and state of the art, the user interface mimics the genuine 𝕏 experience in dark mode:
- Custom custom-tailored dark mode palette matching the official 𝕏 application.
- Modern typography via Google Fonts (Roboto) and crisp icon assets (Google Material Symbols + Vector SVGs).
- Responsive view adaptation from wide screens down to compact mobile phones.

---

## ✨ Features

- **Responsive Multi-Column Layout**: Adapts seamlessly to mobile, tablet, and desktop viewpoints.
  - **Left Sidebar**: Adapts from a full-featured navigation bar (with label texts and profile cards) on desktop to a compact, icon-only drawer on mobile/tablet views.
  - **Center Feed**: Standard feed area featuring sticky headers ("For You" and "Following" tabs), an interactive post composer card, and dynamic posts.
  - **Right Sidebar**: Collapses on mobile and tablet viewports to focus on content. Displays Search, "Subscribe to Premium", "What's happening" trends, and "Who to follow" recommendations on larger viewports.
- **Rich Media & Post Types**:
  - Text-only thoughts (e.g. Elon Musk's post simulation).
  - Rich image attachments (e.g. Prince Jha's and $ur∆j's memes).
  - Video player integrations with custom styling and standard player controls.
- **Interactive Micro-Animations**:
  - Responsive hover transitions on all navigation options, buttons, and interaction counts (Likes, Reposts, Bookmarks, and Views).
  - Hover highlights matching actual 𝕏 interactions (e.g., green for reposts, pink for likes, blue for replies/views).
- **Optimized UI Details**:
  - Hides browser-default scrollbars using custom utilities in the sidebar and main feed panels to maintain a clean application look.

---

## 🛠️ Tech Stack & Libraries

- **Core**: HTML5 (Semantic Structure)
- **Styling**: Tailwind CSS v4.0 (utilizing the new `@tailwindcss/cli` engine)
- **Icons**: 
  - Google Material Symbols Outlined
  - Handcrafted SVG path vectors (for brand logos like 𝕏 and Grok)
- **Dev Tooling & Server**: Vite v7.1

---

## 📁 Project Structure

```bash
X-Clone/
├── css/
│   ├── input.css        # Source stylesheet importing Tailwind & custom scrollbar utilities
│   └── output.css       # Compiled production styles outputted by Tailwind CLI
├── media/               # Media resources (profile images, post photos, and demo videos)
│   ├── ProfilePic.jpg   # Author's profile picture
│   ├── grok.svg         # SVG icon for 𝕏 Grok
│   └── *.mp4 / *.jpeg   # Post media assets
├── index.html           # Main markup file containing the page structure
├── package.json         # Project setup scripts and dependency settings
├── package-lock.json    # Strict dependency tree resolution locking file
└── README.md            # Project documentation (this file)
```

---

## ⚙️ Installation & Local Setup

To run and explore the application locally, follow these simple setup steps:

### Prerequisites
Make sure you have **Node.js** (v18 or higher recommended) and **npm** installed on your system.

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pjha91275/X-Clone.git
   cd X-Clone
   ```

2. **Install Dependencies**:
   Install Vite and Tailwind CSS CLI:
   ```bash
   npm install
   ```

3. **Start the Tailwind compiler (optional for development edits)**:
   This watches your HTML elements and builds custom CSS styles in real time:
   ```bash
   npm run build
   ```

4. **Launch the Development Server**:
   ```bash
   npm run dev
   ```
   Open your browser and navigate to the local server URL (usually `http://localhost:5173`).

---

## 🖥️ Scripts Overview

As configured in the [package.json](file:///c:/Users/pjha9/Documents/ALL%20Coding/Projects/X-Clone/package.json):

* **`npm run dev`**: Boots the local Vite development server.
* **`npm run build`**: Runs the Tailwind CSS compiler CLI in watch mode, matching `css/input.css` as input and exporting to `css/output.css`.

---

## 🧑‍💻 Author

**Prince Jha**
* GitHub: [@pjha91275](https://github.com/pjha91275)
* Project Repo: [X-Clone](https://github.com/pjha91275/X-Clone)

---

## 📝 License

This project is open-source and available under the [ISC License](https://opensource.org/licenses/ISC). Feel free to use, modify, and build upon this code.
