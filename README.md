# Engineered by Lavit

### Building AI that does things.

A personal developer portfolio exploring the intersection of **agentic AI, software engineering, intelligent systems, and practical developer tools.**

Designed with a dark, minimal aesthetic, mint-green accents, and motion-driven interactions, this portfolio showcases the projects, technologies, and engineering ideas behind my work.

**Not just a list of technologies. A record of things built, systems explored, and problems worth solving.**

---

## Overview

I'm Lavit Ramsisaria, a software developer focused on generative AI, agentic systems, backend engineering, and practical applications.

My work explores how software can move beyond basic interfaces into systems that reason, use tools, manage state, retrieve information, and help people accomplish useful tasks.

This website brings that work together in one place.

It serves as a central hub for selected projects, technical interests, engineering principles, and ways to connect.

## Design Philosophy

The portfolio follows a simple idea: the presentation should reflect the work.

- **Dark, technical aesthetic** — A near-black interface with forest-green surfaces and mint-green highlights.
- **Typography with purpose** — Space Grotesk for display text, Inter for body content, and DM Mono for technical labels.
- **Motion with restraint** — GSAP animations and scroll-triggered reveals enhance the experience without overwhelming the content.
- **Interactive details** — Hover states, animated navigation, a reading-progress indicator, and a terminal-inspired system overview.
- **Responsive by design** — Layouts adapt to desktop, tablet, and mobile screens.
- **Accessibility considerations** — Keyboard focus states, semantic HTML, navigation controls, and reduced-motion support.

## What's Inside

### Home — The introduction

The homepage introduces my approach to software development through a focused hero section, selected projects, technical interests, an engineering workflow, and contact links.

It includes a system-inspired visual that represents the journey from user intent to a useful result.

### Projects — The work

A dedicated project directory designed to present applications, AI systems, experiments, and developer tools with their purpose, technologies, and implementation details.

### About — The approach

A dedicated page for exploring my technical interests, development philosophy, and approach to learning through building working systems.

*The homepage links to `projects.html` and `about.html`; ensure these pages are included in the repository before publishing the complete multi-page experience.*

## Featured Projects

The portfolio highlights selected projects across different areas of software development.

| Project | Focus |
|---|---|
| PARALLAX | Windows AI assistant combining model reasoning, local tools, and a terminal interface |
| IGNIX | AI agent and tooling project with a command-oriented experience and dedicated documentation |
| SAHAAYA AI | Multilingual citizen assistance for public information, education, careers, and health |
| CHAOSQUEST | AI-assisted adventure game exploring NPCs, quests, inventory, and narrative |

Each project represents a different exploration of software engineering, applied AI, or interactive systems.

## Engineering Interests

### Agentic AI

Building systems that combine language models with orchestration, state, tool use, permissions, and execution.

### Generative AI and RAG

Exploring how language models, retrieval systems, and external knowledge can be combined to create useful applications.

### Backend Engineering

Designing application logic, API integrations, data flows, and the supporting infrastructure behind user-facing software.

### Developer Tools

Creating practical utilities and interfaces that help people interact with complex systems more effectively.

### System Design

Understanding how components fit together, where complexity belongs, and how to balance functionality with reliability and maintainability.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Layout, responsive design, visual styling, and effects |
| JavaScript | Interactive behavior and navigation |
| GSAP | Entrance animations and motion effects |
| GSAP ScrollTrigger | Scroll-based animation triggers |
| Lucide | Interface icons |
| Google Fonts | Space Grotesk, Inter, and DM Mono |

The website uses external CDN resources for GSAP and Lucide, and Google Fonts for typography. An internet connection is therefore needed for all externally hosted assets to load normally.

The supplied homepage is a static HTML implementation rather than a framework-based application, so no Node.js build step is required to preview that page.

## Architecture and Experience

The website is organized around a small set of clear responsibilities.

```text
engineered-by-lavit/
├── index.html       # Homepage and portfolio introduction
├── projects.html    # Project directory
├── about.html       # About and engineering philosophy
└── README.md        # Project documentation
```

This is the intended high-level structure. Add any local assets, stylesheets, scripts, or supporting pages that exist in your actual implementation.

### Interaction details

- Fixed navigation with a translucent, blurred background on scroll.
- Responsive mobile navigation with keyboard dismissal.
- Scroll-progress indicator.
- Animated hero content and console panel.
- Scroll-triggered section reveals.
- Hover transitions on project cards and interface elements.
- Reduced-motion handling for users who prefer less animation.

The implementation keeps the experience lightweight while giving the interface a distinctive visual identity.

## Getting Started

### Option 1: Open locally

1. Clone the repository.
2. Navigate to the project directory.
3. Open `index.html` in a browser.

```bash
git clone https://github.com/YOUR_USERNAME/engineered-by-lavit.git
cd engineered-by-lavit
```

You can open `index.html` directly in your browser.

### Option 2: Run a local development server

If Python is installed, run:

```bash
python -m http.server 5500
```

Then open [http://localhost:5500](http://localhost:5500).

This is useful for testing navigation, page links, and the complete site structure over HTTP.

## Deployment

The portfolio can be deployed as a static website using GitHub Pages, Vercel, or another static hosting provider.

### Vercel

1. Push the repository to GitHub.
2. Import the repository into Vercel.
3. Configure the project as a static site if prompted.
4. Set the output to the repository root when required by the selected configuration.
5. Deploy and verify the homepage, internal links, external links, and responsive layouts.

No application build command is necessary for the supplied standalone HTML page. Adjust the deployment configuration if the final project introduces a framework or build process.

## Accessibility and Performance

The implementation includes several practical considerations:

- Semantic HTML elements and navigation landmarks.
- Visible keyboard focus indicators.
- A responsive mobile navigation menu.
- A reduced-motion media query.
- Scroll handling that uses `requestAnimationFrame`.
- Deferred loading for selected external scripts.

Further improvements could include more thorough keyboard testing, automated accessibility checks, image optimization if imagery is added, and testing under slow network conditions.

## Roadmap

Potential improvements for the portfolio include:

- [ ] Complete and refine the project directory.
- [ ] Complete the dedicated about page.
- [ ] Add project screenshots and architecture diagrams.
- [ ] Link each featured project to its actual repository.
- [ ] Add project-specific technical write-ups.
- [ ] Improve accessibility testing and performance monitoring.
- [ ] Add a custom domain.
- [ ] Establish automated deployment checks.

## Contact

Interested in AI applications, agentic systems, developer tools, or software engineering problems worth exploring?

Let's connect.

- **GitHub:** [viratramsisaria-collab](https://github.com/viratramsisaria-collab)
- **Email:** [virat.ramsisaria@gmail.com](mailto:virat.ramsisaria@gmail.com)

## License

Unless a license is added to the repository, all rights remain with the copyright holder. Add an appropriate `LICENSE` file if you want to grant explicit permissions for reuse, modification, or redistribution.

---

**Engineered by Lavit**

*Software, AI, and systems — built to do useful things.*