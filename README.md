# AJChat

<p align="center">
  <strong>A modern, community-focused chat experience by Aajimin.</strong><br />
  Real-time conversations wrapped in a polished, Pro Luxury interface.
</p>

<p align="center">
  <a href="https://aj-8a.github.io/AJChat/"><strong>Open AJChat</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/AJ-8A">Creator: AJ-8A</a>
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-Structure-E34F26?logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-Interface-1572B6?logo=css3&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-Client-F7DF1E?logo=javascript&logoColor=222" />
  <img alt="Cloudflare Workers" src="https://img.shields.io/badge/Cloudflare-Workers-F38020?logo=cloudflare&logoColor=white" />
  <img alt="GitHub Pages" src="https://img.shields.io/badge/Hosted%20UI-GitHub%20Pages-222?logo=githubpages&logoColor=white" />
</p>

---

## ✦ About

**AJChat** is a web-based messaging project created by **Aajimin (AJ-8A)**. It brings community conversations and direct messaging into a responsive interface with a distinctive midnight-glass look, champagne-gold accents, and subtle nature-inspired atmosphere.

- **Live app:** https://aj-8a.github.io/AJChat/
- **Source code:** https://github.com/AJ-8A/AJChat
- **Creator profile:** https://github.com/AJ-8A

## Highlights

- **Community chat** — join conversations in the global room.
- **Friends and private messages** — friend requests and one-to-one chats.
- **Profiles and status** — personal profile details, bio, and status.
- **Conversation tools** — chat history search and message interactions.
- **Voice and video calling** — calling interface and related functionality.
- **Notifications** — push-notification support where the browser and setup allow it.
- **Responsive experience** — layouts designed for desktop and mobile screens.
- **Signature visual design** — glassmorphism, dark surfaces, gold highlights, ambient glows, and sakura/forest-inspired scenery.
- **Theme options** — light/dark theme controls.
- **Progressive-web-app direction** — frontend built with a PWA-ready approach.

> Some features depend on the deployed API, browser permissions, and device support.

## Technology

| Layer | Technologies |
| --- | --- |
| Frontend | HTML, CSS, JavaScript |
| API / backend | Cloudflare Workers |
| Realtime infrastructure | Cloudflare Durable Objects |
| Data storage | Cloudflare D1 |
| Frontend hosting | GitHub Pages |

## Project structure

The repository contains the browser client and its styling, with the live frontend hosted on GitHub Pages. The backend API is deployed separately on Cloudflare.

- `index.html` — application entry point
- `app.js` — client-side application logic
- `styles.css` and `luxury.css` — core and visual styling

## Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/AJ-8A/AJChat.git
   cd AJChat
   ```
2. Open `index.html` in a browser, or start a simple local static server from the repository directory.
3. For account, messaging, and realtime features, make sure the client is configured to use a working backend API. Opening the frontend alone does not start the Cloudflare backend.

## Design principles

- **Clear hierarchy:** keep conversations and actions easy to scan.
- **Responsive by default:** support smaller screens as well as desktop layouts.
- **Atmosphere without clutter:** use motion, glow, and scenery as supporting details.
- **Accessible interaction:** preserve visible focus and respect device/browser capabilities where implemented.

## Roadmap

Ideas for continued improvement include smoother onboarding, additional accessibility refinements, and ongoing mobile performance tuning.

## Feedback and contributions

Found a bug or have an idea? Open an issue in the [AJChat repository](https://github.com/AJ-8A/AJChat) with steps to reproduce the problem, expected behavior, and screenshots if useful.

## Credits

Designed and built by **Aajimin (AJ-8A)**.

<p align="center">
  <strong>AJChat · Pro Luxury Edition</strong><br />
  <sub>Conversations with a little more atmosphere.</sub>
</p>
