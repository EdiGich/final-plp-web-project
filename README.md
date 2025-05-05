# Edwin Gichira's Blog Website

## Overview

This is a simple, responsive blog website developed by **Edwin Gichira** as a final project for a web development course. The site showcases HTML5, CSS3, and JavaScript skills, featuring a multi-page structure, interactive elements, and localStorage for data persistence. It is deployed on GitHub Pages and accessible at https://edigich.github.io/final-plp-web-project/.

## Features

- **Multi-Page Structure**: Includes Home, Blog Post, and About pages with a navigation menu.
- **Responsive Design**: Mobile-friendly layout using CSS media queries for seamless viewing on all devices.
- **JavaScript Interactivity**:
  - Theme toggle (light/dark mode) with preferences saved in localStorage.
  - Comment system on the Home page, allowing users to add and delete comments stored in localStorage.
- **CSS Animations**: Fade-in animations for blog articles on page load and hover scale effects for visual engagement.
- **Semantic HTML5**: Uses semantic elements (`<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`) for accessibility and structure.
- **Accessibility**: Includes ARIA attributes (e.g., `aria-label`, `role="navigation"`) for screen reader compatibility.
- **Image Support**: Placeholder image on the About page with alt text for accessibility.

## Technologies Used

- **HTML5**: For semantic structure.
- **CSS3**: For styling, animations, and responsive design.
- **JavaScript**: For interactivity (theme toggle, comment system).
- **localStorage**: For persisting user preferences and comments.
- **GitHub Pages**: For hosting and deployment.

## Project Structure

```
final-plp-web-project/
├── index.html        # Home page with blog post and comment system
├── post.html         # Sample blog post page
├── about.html        # About page with developer info'
├── styles.css        # Contains the general CSS stylings.
└── README.md         # Project documentation
```

## Setup Instructions

To run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/edigich/final-plp-web-project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd final-plp-web-project
   ```

3. Open `index.html` in a web browser (e.g., using a local server like `live-server` or directly via the file system).

No additional dependencies or build steps are required, as the project uses vanilla HTML, CSS, and JavaScript.

## Deployment

The project is deployed on GitHub Pages at https://edigich.github.io/final-plp-web-project/. To deploy your own version:

1. Create a GitHub repository and push the project files (`index.html`, `post.html`, `about.html`).
2. Go to the repository's **Settings** &gt; **Pages** section.
3. Set the source to the `main` branch.
4. GitHub Pages will generate a live URL (e.g., `https://your-username.github.io/repository-name/`).

## Usage

- **Navigation**: Use the navigation menu to switch between Home, Blog Post, and About pages.
- **Theme Toggle**: Click the "Toggle Theme" button to switch between light and dark modes; preferences are saved.
- **Comment System**: On the Home page, submit comments via the form and delete them using the "Delete" button; comments persist across sessions.
- **Responsive Viewing**: Resize the browser or access the site on a mobile device to experience the responsive design.

## Developer

- **Name**: Edwin Gichira
- **GitHub**: edigich

## License

© 2025 Edwin Gichira. All rights reserved.
