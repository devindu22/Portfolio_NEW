# Portfolio 

<img width="1913" height="916" alt="Screenshot 2026-07-07 121337" src="https://github.com/user-attachments/assets/f3d45ceb-73af-4b53-8978-72e95be4d9e9" />

A modern, high-performance, responsive personal portfolio website designed to showcase professional milestones, web development architecture, and technical projects. This site features integrated API asynchronous communication pipelines, interactive micro-interactions, and a cohesive custom-branded visual layout.

https://devindu-malshan-portfolio.netlify.app/ 

---

## 🎨 Design Philosophy & Aesthetics

* **Branded Visual Identity:** Built around a custom signature aesthetic featuring a sleek blue-to-purple linear color gradient, explicitly mirrored in the minimal geometric "DM" favicon emblem.
* **Modern Interface Elements:** Implements clean, hover-responsive flat-square connection badges across all anchor elements to ensure frictionless user navigation and uniform interactive depth.
* **Responsive Layout Design:** Fully optimized with fluid typography and absolute horizontal centering adjustments to provide a seamless visual equilibrium across mobile screen aspect ratios, tablets, and wide-screen desktop displays.

---

## 🚀 Key Functionalities & API Integrations

### 1. Asynchronous Contact Console
The contact form bypasses traditional backend script dependencies by routing user inquiries directly through an asynchronous processing engine.
* **API Integration:** Powered securely via **Web3Forms** using an environment-locked unique Access Key (`6f236cd7-259d-4fc9-bfe7-ec46c88b2f2a`).
* **Enhanced Security:** Configured with specific domain locks (`localhost` for isolated troubleshooting and the root InfinityFree domain for live hosting operations) to completely mitigate automated submission spam and credential scraping.
* **AJAX Handshake:** Form payloads are processed dynamically in the background via modern JavaScript `POST` requests, preventing jarring page reloads and providing clear visual feedback states upon successful dispatch.

### 2. Interactive CV Download Action
The professional resume acquisition section replaces flat hyperlinks with an engaging, event-driven action pipeline.
* **Dynamic Feedback:** Clicking the document trigger executes a scoped canvas particle animation, launching a celebration confetti burst directly onto the active viewport.
* **Target Management:** Automates browser download instructions to retrieve the local asset file (`Devindu_malshan_resume.pdf`) directly from the server's root directory directory structure.

### 3. Dynamic Memory Arena (Gallery)
- **Purpose**: Centralized visual repository for project media.
- **Features**: 
    - Responsive grid layouts with depth-enabled shadows.
    - Accented border styling for individual memory cards.
    - Optimized asset loading for high-resolution imagery.

### 4. Lab Broadcast Logs (Videos)
- **Purpose**: Chronological documentation of system testing and development logs.
- **Features**:
    - Embedded video player support with legacy fallback.
    - Categorized tagging system (e.g., "Prototype," "Deployment," "Stress Test").
    - Time-stamped event tracking.

## Design Philosophy
This interface prioritizes a "dark-first" theme to reduce eye strain, utilizing subtle drop shadows to create 3D depth and consistent border accents to differentiate UI components[cite: 2].

## File Structure
The project is architected as a single-file application for streamlined deployment[cite: 1]:

---

## 💻 Tech Stack

* **Frontend Architecture:** Semantic HTML5, CSS3 Custom Properties (featuring custom flexbox grid properties, custom borders, and gradient masks)
* **Design Utilities:** Tailwind CSS / Bootstrap components for smooth responsive design layout management
* **Runtime Logic:** Vanilla JavaScript (ES6+) for DOM manipulation, AJAX fetch pipelines, and micro-animations

---

## 📂 Project Architecture

```text
/project-root
│
├── index.php           # Main entry point (PHP/HTML/JS)
├── assets/
│   ├── css/
│   │   └── style.css   # Contains all depth and accent styling
│   ├── js/
│   │   └── app.js      # Core logic for Dynamic Arena & Broadcast Logs
│   └── images/         # Asset repository
└── README.md           # Documentation
├── js/
│   └── main.js                  # Contact handler, Web3Forms token engine, and confetti script
├── index.html                    # Master entry file containing DOM structures
└── README.md                     # Documentation file
