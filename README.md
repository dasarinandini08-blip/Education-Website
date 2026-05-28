# 🎓 World's Largest University Website

A responsive university landing page built with HTML, CSS, and vanilla JavaScript.

---

## 📁 Project Structure

```
university-website/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet
│
└── images/             # Image assets
    ├── logo.png
    ├── london.png
    ├── newyork.png
    ├── washington.png
    ├── library.png
    ├── basketball.png
    ├── cafeteria.png
    ├── user1.jpg
    └── user2.jpg
```

---

## 🚀 Features

- **Responsive Navigation** — Hamburger menu for mobile with show/hide toggle
- **Hero Section** — Full-width banner with headline and call-to-action button
- **Courses Section** — Highlights offered programs (Intermediate, Degree, Post Graduation)
- **Global Campus Section** — Showcases campus locations (London, New York, Washington)
- **Facilities Section** — Library, Playground, and Cafeteria highlights
- **Testimonials Section** — Student reviews with star ratings
- **Call to Action** — Enrollment prompt with contact button
- **Footer** — About info and social media icons

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling and layout |
| JavaScript (Vanilla) | Mobile menu toggle |
| Font Awesome 4.7 | Icons (social, stars, menu) |
| Google Fonts (Poppins) | Typography |

---

## ⚡ Getting Started

1. **Clone or download** the repository.
2. Make sure all **images** are placed inside the `images/` folder.
3. Open `index.html` in any modern browser — no build tools required.

```bash
# If using VS Code with Live Server
Right-click index.html → Open with Live Server
```

---

## 📱 Responsive Behavior

| Screen | Behavior |
|---|---|
| Desktop | Full horizontal navigation bar |
| Mobile | Navigation hidden off-screen; hamburger icon (☰) reveals it |

The mobile menu is controlled by two JavaScript functions:

```javascript
function showMenu() {
    navLinks.style.right = "0";      // Slide menu into view
}
function hideMenu() {
    navLinks.style.right = "-200px"; // Slide menu out of view
}
```

---

## 🔗 Navigation Pages

| Link | File |
|---|---|
| Home | `index.html` |
| About | `about.html` |
| Courses | `course.html` |
| Blog | `blog.html` |
| Contact | `contact.html` |

> **Note:** Only `index.html` is provided in this project. The other pages (`about.html`, `course.html`, etc.) need to be created separately.

---

## 🐛 Known Issues

- Typo in campus section: `WASHIGNTON` should be `WASHINGTON`
- Hero and CTA buttons have empty `href=""` attributes — update with real links
- Social media icons in the footer are not linked to any URLs

---

## 📄 License

This project was built for educational/tutorial purposes. Feel free to use and modify it for your own projects.