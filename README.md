# 🌐 Manish Kumar — Personal Portfolio

Welcome to my personal portfolio! 👋

I'm a passionate **Front-End Developer** who enjoys creating responsive, user-friendly, and visually appealing websites using modern web technologies. This portfolio showcases my technical skills, certifications, projects, and journey as a developer.

The website is designed with a modern interface, smooth animations, interactive components, and dark/light theme support to provide a better user experience across different devices.

## ✨ Features

- 📱 **Responsive Design** — Adapts to desktop, tablet, and mobile screens.
- 🎨 **Dark & Light Mode** — Switch between themes with preferences saved in local storage.
- 🍔 **Mobile Navigation** — Interactive navigation drawer with an overlay backdrop.
- 👨‍💻 **Hero Section** — Introduction, profile photo, and call-to-action button.
- 🙋 **About Me** — Information about my background and development interests.
- 🛠️ **Skills Section** — Organized technical skills and tools.
- 🏆 **Certificates Section** — View certificates in a PDF modal and download them.
- 💼 **Projects Section** — Showcase projects with technology tags and demo/source links.
- 💬 **Feedback Form** — Interactive form with a simulated submission response.
- ✨ **Scroll Animations** — Reveal elements as they enter the viewport.
- 🔗 **Smooth Scrolling** — Navigate smoothly between page sections.
- ⬆️ **Scroll-to-Top Button** — Quickly return to the top of the website.
- 🌐 **Social Media Links** — Connect through social profiles.
- 📅 **Dynamic Copyright Year** — Automatically displays the current year.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling, layouts, animations, and responsive design |
| JavaScript | Interactivity and DOM manipulation |
| Google Fonts | Inter and Outfit typography |
| Local Storage | Save the selected theme |
| Intersection Observer API | Scroll-reveal animations |
| Git & GitHub | Version control and repository hosting |
| GitHub Pages / Netlify / Vercel | Static website deployment |

## 📂 Project Structure

```text
portfolio/
├── index.html
├── styles.css
├── script.js
│
├── Media/
│   ├── profile.png
│   ├── Skills/
│   ├── Certificate/
│   │   └── Logo/
│   └── social-media-logo/
│
└── projects/
    ├── project-one/
    │   └── index.html
    └── project-two/
        └── index.html
```

### 📁 Folder Description

- **`index.html`** — Main portfolio webpage containing the website sections.
- **`styles.css`** — Styles the layout, colors, themes, animations, and responsive components.
- **`script.js`** — Handles navigation, theme switching, certificate modals, feedback interactions, and scroll animations.
- **`Media/`** — Contains images, skill icons, certificates, logos, and social media assets.
- **`Media/Skills/`** — Stores icons representing technical skills.
- **`Media/Certificate/`** — Stores certificate PDF files.
- **`Media/Certificate/Logo/`** — Contains certificate issuer logos.
- **`Media/social-media-logo/`** — Stores social media icons.
- **`projects/`** — Contains individual project folders.
- **`project-one/` and `project-two/`** — Contain standalone HTML pages for individual projects.

*Note: The folder structure above shows the main directories. Keep all required images and certificate files in their actual locations and preserve the paths referenced by your code.*

## 🚀 Getting Started

Follow these steps to run the portfolio locally.

### 1. Clone the Repository

Open your terminal and run:

```bash
git clone <your-repository-url>
```

Replace `<your-repository-url>` with the URL of your GitHub repository.

### 2. Navigate to the Project Directory

```bash
cd portfolio
```

### 3. Open the Project

Open the folder in Visual Studio Code or your preferred code editor.

### 4. Run the Website

**Option 1: Using a browser**

Open `index.html` directly in your browser.

**Option 2: Using VS Code Live Server**

1. Install the Live Server extension in Visual Studio Code.
2. Open the project folder.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

Your portfolio will open in the browser.

No package installation or build process is required for the current HTML, CSS, and JavaScript implementation.

## 🎨 Website Sections

### 1. Home

Introduces me as a front-end developer and provides a call-to-action button to explore my projects.

### 2. About Me

Describes my interest in building accessible, polished, and user-friendly web experiences.

### 3. Skills

Displays technical skills in categories such as:

- **Frontend Core:** HTML5, CSS3, JavaScript
- **Frameworks & Styling:** React, Responsive Design, Bootstrap, UI/UX Styling
- **Tools & Deployment:** Git, GitHub, VS Code

### 4. Certificates

Displays certifications and learning achievements. Users can open certificates in a modal PDF viewer and access the download option.

### 5. Projects

Showcases selected projects with technology tags and links to live demos and source code.

The `projects/` directory contains separate folders for individual project webpages.

### 6. Feedback

Provides a form where visitors can enter their name, email address, and feedback message.

**Important:** The current form demonstrates front-end interaction only. It does not send or permanently store submissions.

## ⚙️ Interactive Functionality

### 🌙 Dark & Light Theme

The theme toggle switches between dark and light modes. The selected preference is saved using browser `localStorage` under the key `portfolio-theme`.

When no saved preference exists, the website can use the system's light-mode preference.

### 📱 Mobile Navigation

The navigation drawer opens and closes using a menu button. An overlay appears behind the drawer, and clicking a navigation link or the overlay closes the menu.

### 🏆 Certificate PDF Viewer

Certificate cards use the `data-pdf` and `data-title` attributes to identify the PDF file and display title.

Selecting a certificate opens a modal containing the PDF viewer and download link.

### ✨ Scroll Reveal Animations

The Intersection Observer API detects when elements enter the viewport and activates their reveal animations.

Elements inside `.reveal-group` can use staggered animation delays.

### ⬆️ Scroll-to-Top

A floating button appears after scrolling down the page. Clicking it smoothly scrolls back to the top.

### 📅 Dynamic Year

The footer copyright year is automatically updated using JavaScript.

## 🔧 Customization Guide

You can personalize the portfolio by editing the following files:

| File or Folder | What to Customize |
|---|---|
| `index.html` | Name, introduction, About section, skills, certificates, and projects |
| `styles.css` | Colors, fonts, spacing, layouts, themes, and animations |
| `script.js` | Interactive functionality and event handlers |
| `Media/profile.png` | Profile photo |
| `Media/Skills/` | Skill icons |
| `Media/Certificate/` | Certificate PDFs |
| `Media/social-media-logo/` | Social media icons |
| `projects/` | Individual project webpages |

### Adding a New Certificate

1. Place the certificate PDF inside `Media/Certificate/`.
2. Add a certificate card to `index.html`.
3. Set the correct `data-pdf` and `data-title` attributes.
4. Add the certificate logo and description if needed.
5. Test the modal and download functionality.

### Adding a New Project

1. Create a new folder inside `projects/`.
2. Add an `index.html` file.
3. Include the required HTML, CSS, and JavaScript files or references.
4. Test the project independently.
5. Add the project's title, description, technologies, and links to the portfolio's Projects section.

### Updating Social Links

Replace the existing social media URLs in `index.html` with your own profile links. Ensure that all external links point to the correct destinations.

## 🌍 Deployment

You can deploy this static portfolio using GitHub Pages, Netlify, or Vercel.

### Deploy Using GitHub Pages

1. Push your portfolio code to a GitHub repository.
2. Open the repository on GitHub.
3. Navigate to **Settings → Pages**.
4. Select the appropriate branch and root directory.
5. Save the configuration.
6. Open the published URL after GitHub Pages finishes deployment.

Make sure `index.html` is located in the selected publishing directory and that all asset paths work correctly.

## 🔮 Future Improvements

- Connect the feedback form to a backend API or form service.
- Add more projects with live demos and GitHub repositories.
- Improve form validation and error handling.
- Enhance keyboard accessibility and focus management in the certificate modal.
- Optimize images and website loading performance.
- Add SEO metadata and social sharing previews.
- Add more interactive components and project filters.

## 👨‍💻 About the Developer

**Manish Kumar — Front-End Developer**

I'm passionate about web development and continuously improving my skills in HTML, CSS, JavaScript, React, responsive design, and modern UI development.

I enjoy transforming ideas into functional and visually appealing web experiences.

### 🔗 Connect With Me

- **GitHub:** [manish001co-cmd](https://github.com/manish001co-cmd)
- **LinkedIn:** [Manish Kumar](https://www.linkedin.com/in/manish-kumar-3bb405322/)
- **Portfolio:** [Visit My Portfolio](https://manish001co-cmd.github.io/protfolio/)

## 📄 License

No license is currently specified for this project. Add a `LICENSE` file if you want to define how others may use, modify, or distribute the source code.

---

⭐ **If you like this project, consider giving the repository a star!**

**Built with ❤️ using HTML, CSS, and JavaScript by Manish Kumar.**