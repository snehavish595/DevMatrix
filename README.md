# DevMatrix – Software Engineer Portfolio Template

---

### Welcome to DevMatrix: The Next-Gen Portfolio for Developers

**DevMatrix** is a premium, high-contrast, dark-themed portfolio template explicitly designed for **Senior Software Engineers, Tech Leads, and Engineering Managers**. It offers a sleek, structured, and fully responsive platform to showcase technical expertise, experience timelines, and code projects.

Built using the power of **Tailwind CSS**, the entire template is contained within a **single HTML file**, ensuring incredibly fast setup and customization.

---

### Key Features 

* **Niche-Specific Design:** Built around the needs of a professional developer, featuring dedicated sections for "Tech Stack Matrix" and "Experience Timeline".
* **Premium Dark Theme:** Utilizes a high-contrast aesthetic (Deep Black Background + Neon Green Accent) for a modern, technical look.
* **100% Responsive:** Optimized for desktop, tablet, and mobile screens using the latest Tailwind CSS flex and grid utilities.
* **Single-File Simplicity:** All HTML, Tailwind CSS configuration, and necessary JavaScript are contained within `index.html`—no external local files are required.
* **Clean Codebase:** Features a well-commented, semantic HTML structure that adheres to modern web standards.
* **Professional Icons:** Integrates **Lucide Icons** for high-quality, lightweight vector graphics.

---

### Getting Started (Quick Setup)

1.  **Extract the ZIP:** Unzip the main download file.
2.  **Locate Files:** Navigate to the `02_Template_Files` folder.
3.  **Launch:** Double-click `index.html` to view the template in your browser.
4.  **Customize:** Open `index.html` in your favorite code editor (like VS Code) and start replacing the demo content (Alex Mercer, text, links, etc.) with your own information.

---

### Customization Guide 

#### A. Changing the Theme Color

To change the primary accent color from the default **Neon Green (`#00FF7F`)**, modify the `tailwind.config` script block located in the `<head>` of `index.html`.

```javascript
// ... inside <script> tag
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'primary-bg': '#OAOAOA', // Deep Black
                // CHANGE THIS VALUE
                'accent-green': '#00FF7F', // <-- Find this line and replace the hex code (e.g., to
                '#3366FF' for blue)
                'text-light': '#FOFOFO',
            },
        },
    },
};
// ...
```

#### 2. Update Navigation & Content

- All sections (header links, hero text, timeline, projects) are clearly labeled with HTML comments (`<!-- ... -->`) for easy editing.

#### 3. Contact Form

- The contact form is front-end only.
- Requires a server-side script or 3rd-party service like Formspree or Netlify Forms to send emails.

---

### Credits

- **Tailwind CSS** – [https://tailwindcss.com](https://tailwindcss.com)
- **Inter Font** – [https://fonts.google.com/specimen/Inter](https://fonts.google.com/specimen/Inter)
- **Lucide Icons** – [https://lucide.dev](https://lucide.dev)

---

**Thank you for choosing DevMatrix for your professional portfolio!**
