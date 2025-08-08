# 📱 Responsive Website with CSS Media Queries

## 📌 Project Overview
This project is a conversion of a **desktop-only webpage** into a **fully responsive, mobile-friendly layout** using **CSS media queries**.  
It demonstrates **mobile-first design principles**, flexible layouts, and adaptive styling.

---

## 🛠️ Features
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile screens.
- **CSS Media Queries**: Adjusts font sizes, layouts, and images for smaller screens.
- **Mobile Navigation**: Stacks navigation vertically for smaller devices.
- **Fluid Images**: Images scale within their containers.
- **Backup Version**: Original non-responsive desktop version included in `/backup`.

---

## 📂 Project Structure
Media_Queries/
│
├── index.html # Updated responsive HTML
├── style.css # Main CSS with media queries
│
├── backup/ # Original desktop-only files
│ ├── index.html
│ └── style.css
│
└── images/ # Optional images used in the pag


---

## 🚀 How to View the Project
1. **Clone the repository**
   ```bash
   git clone https://github.com/<YourGitHubUsername>/media-queries.git
   cd media-queries
2. **Open in browser**
  Double-click index.html
  OR
  Use VS Code Live Server for better testing.
3. **Test Responsiveness**
  Open in Google Chrome.
  Press F12 or Right-click → Inspect.
  Click Toggle Device Toolbar (📱 icon).
  Try different screen sizes (Mobile, Tablet, Desktop).

 **CSS Media Queries Used**
css
Copy code
@media (max-width: 768px) {
  /* Adjust layout for tablets and smaller screens */
}

@media (max-width: 480px) {
  /* Adjust layout for mobile screens */
}
🎯 **Learning Outcomes**
Understanding @media queries and breakpoints.
Implementing mobile-first design.
Creating flexible, fluid layouts.
Ensuring images and text adapt to viewport changes.

🖼️ **Screenshots**
Desktop View
Mobile View
