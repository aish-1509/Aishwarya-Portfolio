# 💼 Aishwarya's Portfolio Website

A modern, responsive, and highly animated personal portfolio website showcasing my work and skills as a developer. Built from the ground up with HTML, CSS, and JavaScript, it leverages powerful libraries like GSAP and Particles.js to create a dynamic and engaging user experience.

### 👉 [Live Demo](https://aishwarya-portfolio-one.vercel.app/)

## 🚀 Features

### ✨ Core UI/UX & Design
- **Fully Responsive:** Adapts seamlessly to all screen sizes, from mobile phones to desktop monitors.
- **Animated Aurora Background:** A stunning, multi-layered, and animated gradient background that flows and changes across the site.
- **Dynamic Particle Systems:** Interactive particle backgrounds using `particles.js` in the Hero and Projects sections.
- **Advanced Animations:** Smooth, performant animations powered by **GSAP** for scroll-triggered reveals, fades, and complex text effects.
- **Custom Cursor:** A custom-designed cursor with a follower and unique hover effects for interactive elements.
- **Modern Navigation:** A sleek, sticky navigation bar with a "sliding pill" indicator that animates to highlight the active link.
- **Interactive Elements:** Cards and buttons feature glow effects, shadows, and transformations on hover.
- **Custom Loading Animation:** An elegant initial loading screen with an animated name display.
- **Scroll Progress Bar:** A vertical bar on the side that indicates the reading progress on the page.

### ⚙️ Functionality
- **GitHub API Integration:** Fetches and displays real-time GitHub statistics, including top languages and recent activity.
- **Project Showcase:** Detailed sections to display academic and personal projects with descriptions and images.
- **Comprehensive Sections:** Includes dedicated sections for an "About Me" bio, a career "Journey" timeline, a "Tech Stack" breakdown, "Certifications," and "Leadership" experience.
- **Contact Form:** A functional contact form with client-side validation.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Styling:**
    - **Tailwind CSS:** For utility-first styling and rapid UI development.
    - **Bootstrap 5:** Used for its grid system and base components.
    - **Custom CSS:** For bespoke styling, animations, and the overall design system.
- **Animations:**
    - **GSAP (GreenSock Animation Platform):** For all major animations, including the loading screen, scroll triggers, and navigation indicator.
- **Particles & Effects:**
    - **Particles.js:** For creating the interactive particle backgrounds.
- **Icons & Fonts:**
    - **Font Awesome:** For icons.
    - **Google Fonts:** `Space Grotesk`, `Sora`, and `Inter`.

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file for all content
├── styles.css          # Custom styling, animations, and design system
├── script.js           # Core JavaScript for interactivity, animations, and API calls
├── assets/             # Contains images, resume PDF, and other media
└── README.md           # This documentation file
```

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You'll need a modern web browser. To run a local server, you can use Python or Node.js.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/aish-1509/Aishwarya-Portfolio.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd Aishwarya-Portfolio
    ```

### Running Locally

You can open the `index.html` file directly in your browser, or for a more robust experience (to avoid any CORS issues with future API calls), run a local server.

-   **Using Python:**
    ```sh
    python -m http.server
    ```
-   **Using Node.js (with `serve` package):**
    ```sh
    npx serve .
    ```

## 🔧 Configuration

To adapt the portfolio for your own use, you'll need to update the following:

-   **Personal Information:** Edit `index.html` to change the text content, project details, and personal links.
-   **GitHub Integration:** In `script.js`, update the GitHub username to fetch your own repository data:
    ```javascript
    const username = 'YOUR_GITHUB_USERNAME';
    ```
-   **Resume:** Replace the PDF file in the `assets/` directory and update the corresponding link in `index.html`.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/aish-1509/Aishwarya-Portfolio/issues).
