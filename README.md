# Avengers: Doomsday — Multiverse Lore Atlas

An interactive, fan-made companion website for **Avengers: Doomsday**. Explore the Multiverse Saga through a cinematic landing page, an interactive 3D character display, a connected multiverse map, a movie timeline, character dossiers, and a section for reviewing reported leaks and speculation.

> **Fan project notice:** This is an unofficial, non-commercial fan-made project. It is not affiliated with, endorsed by, or sponsored by Marvel Studios, Disney, or any related rights holder. All third-party names, characters, logos, artwork, and media remain the property of their respective owners.

## ✨ Highlights

- **Cinematic landing experience** — a full-screen Doomsday-inspired hero section with animated visual effects.
- **3D Holo-Stage** — an interactive character showcase with a floating holographic presentation. Drag the stage to inspect its perspective.
- **Multiverse connection map** — explore relationships between characters, films, and story elements through a pannable, interactive node map.
- **Saga timeline** — browse movie/story entries and see how they connect to the events leading toward *Avengers: Doomsday*.
- **Character dossiers** — inspect character information and related story details in a slide-over information panel.
- **Leak and theory review** — a dedicated area for separating reported information, speculation, and unofficial material.
- **Global search** — search across characters, movies, and leak-related entries.
- **Canon filters** — switch between all entries, official material, and unofficial material.
- **Theme switcher** — toggle between dark and light appearances.
- **Background theme audio** — optional looping music with an on-page play/pause control.
- **Responsive layout** — navigation and content adapt for desktop and mobile screens.

## 🧰 Technology

The project is implemented as a lightweight, browser-based frontend.

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Layout, themes, glassmorphism, and animations |
| JavaScript | Interactive components and page behaviour |
| [Tailwind CSS](https://tailwindcss.com/) CDN | Utility styling |
| [Three.js r128](https://threejs.org/) | Real-time 3D hero visual |
| Google Fonts | Inter and Cinzel typography |

There is currently no Node.js build pipeline or package installation step required by the repository's single-page setup. Third-party libraries and fonts are loaded from their respective CDNs, so an internet connection is needed for those resources.

## 🚀 Getting Started

### Prerequisites

- A modern browser (Chrome, Edge, Firefox, or Safari).
- Python 3, or another simple static HTTP server.
- An internet connection for CDN-hosted libraries, fonts, and externally hosted media.

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/SherwinImmanuelRaj/Avengers-Doomsday.git
   ```

2. Open the project directory:

   ```bash
   cd Avengers-Doomsday
   ```

3. Start a local web server:

   ```bash
   python -m http.server 8000
   ```

4. Open the site in your browser:

   ```text
   http://localhost:8000
   ```

You can also use the VS Code **Live Server** extension or any equivalent static-file server.

> Using a local HTTP server is recommended over opening `index.html` directly, particularly for browser features and externally loaded resources.

## 🗺️ Explore the Website

The main navigation is organised into these areas:

1. **Hero** — the cinematic introduction.
2. **3D Holo-Stage** — interactive character presentation.
3. **Multiverse Map** — connected story and character relationships.
4. **Timeline** — movie and saga context.
5. **Dossier** — character-focused information.
6. **Leak Audit** — reported leaks, theories, and unofficial material.

Use the search field to find entries, the canon filter to narrow the displayed information, and the theme control to change the appearance. Theme music is optional and can be toggled from the top navigation.

## 📁 Project Structure

```text
Avengers-Doomsday/
├── index.html     # Main application: markup, styles, and client-side logic
├── README.md      # Project documentation
└── LICENSE        # Apache License 2.0
```

The current implementation is intentionally self-contained in `index.html`. The page includes its styling and application scripts rather than splitting them into separate source files.

## 🛠️ Development

- Edit `index.html` to update the layout, content, styles, or interactions.
- Keep external resource URLs and their licences/attributions documented when adding assets.
- Test the page at both desktop and mobile viewport sizes.
- Verify the search, canon filters, theme switcher, audio control, 3D interaction, map interactions, and information drawer after making changes.
- If you add local assets or split the application into separate files, update the project structure and setup instructions in this README.

## 🌐 Deployment

This is a static website and can be deployed to services that host HTML/CSS/JavaScript, for example:

- GitHub Pages
- Netlify
- Vercel
- Any static web server

For GitHub Pages, open the repository's **Settings → Pages**, choose the deployment source/branch, and publish the repository root (where `index.html` is located).

## ⚖️ Credits & Disclaimer

- Created and maintained by [SherwinImmanuelRaj](https://github.com/SherwinImmanuelRaj).
- Built as an independent fan project for entertainment and learning.
- Marvel, Avengers, Doomsday, character names, and related intellectual property belong to their respective owners.
- The project should not be interpreted as official Marvel information. Unofficial theories, rumours, and leak-related content should be treated as unverified unless supported by an authoritative source.
- External fonts, libraries, and media are provided by their respective hosts and remain subject to their own terms and licences.

## 📄 License

This repository includes an [Apache License 2.0](LICENSE). Refer to the `LICENSE` file for the complete terms. Third-party intellectual property and externally sourced assets are not relicensed by this project.