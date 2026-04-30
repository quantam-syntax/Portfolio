# GSK Portfolio

A lightweight, clean, and responsive personal portfolio written in pure HTML, CSS, and basic vanilla JavaScript.

## 📂 Project Structure

```text
Ui/
├── portfolio.html   # The main single-page portfolio
├── about.html       # A dedicated profile links page
├── styles.css       # All styling rules and CSS-driven animations (no external frameworks)
├── ganesh.jpeg      # Profile image used for the avatars
└── README.md        # Project documentation
```

## 🏗️ Architecture Details

- **`portfolio.html`**: The core landing page containing all main sections (`#home`, `#about`, `#projects`, `#skills`, `#contact`). It has different sections which explains about the technical skills and projects I have done.
- **`about.html`**: An isolated profile page formatted like a digital business card, offering easy access to email, phone, GitHub, and LinkedIn links.
- **`styles.css`**: The central stylesheet. Key features include:
  - Custom unified properties (`:root`) for color palette and layout configurations.
  - CSS variables for clean and consistent styling across both HTML files. 
  - Pure CSS animations (e.g., drifting background blobs, pulsing avatar rings).
  - Fully responsive grid layouts accommodating desktop, tablet, and mobile displays.
- **`ganesh.jpeg`**: Your main profile picture smoothly integrated into the UI.

## 🚀 Setup
No build steps or package installations are required! Simply open `portfolio.html` in any web browser to view the site locally.
