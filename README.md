<p align="center">
  <a href="https://beamify.online" target="_blank">
    <img src="assets/icon.png" width="120" alt="Beamify Logo" />
  </a>
</p>

<h1 align="center">iGApp — Beamify Frontend</h1>
<p align="center">
  <strong>The visual interface of the Beamify Network</strong><br/>
  A high-performance Next.js 15 application for Web, Desktop (Electron), and Mobile (Capacitor).
</p>

---

## 🎨 What is iGApp?

**iGApp** is the official frontend for the Beamify Network — a modern, universal app built with **Next.js 15**. Designed for speed, flexibility, and seamless cross-platform experiences, iGApp empowers creators through an elegant interface for all things Beamify.

Powered by React Server Components and App Router, iGApp interfaces directly with **iGCore**, Beamify’s enterprise-grade backend, and connects with our ecosystem — including encrypted chat, gamified services, and a living city visualization.

---

## 🚀 Key Features

- 🌍 **Cross-Platform Support** – Web-first design with Electron (Desktop) and Capacitor (Mobile)
- ⚛️ **Next.js 15** – Latest App Router, Server Actions, and React Server Components
- 🔗 **iGCore Integration** – Direct connection to Beamify’s secure backend APIs
- 🏆 **Gamification Engine** – Real-time rewards, user progression, and interactive UI
- 💬 **Nexus Chat Integration** – Seamless plug-in with Beamify’s encrypted messaging layer
- 🌆 **Live City Visualization** – Dynamic visuals driven by real-time backend metrics
- 🔐 **Secure Auth & Routing** – Role-based guards, session tokens, and SSR protection
- 💡 **Accessible UX** – Fast, fluid, and user-focused experience across all devices

---

## 🧬 Technologies Used

- **Next.js 15** – React Server Components, App Router, Server Actions
- **React** – Core rendering and interactivity
- **TailwindCSS / SCSS** – Custom styling and theme control
- **Electron** – Cross-platform desktop builds
- **Capacitor** – Native mobile support
- **JWT / Session Auth** – Secure user authentication
- **iGCore API** – Full backend connectivity
- **Zod / TRPC (Optional)** – Validation and typed backend interaction

---

## 🗂️ Project Structure

```bash
src/
├── app/                 # App Router pages, layouts, and routes
│   ├── (auth)/          # Auth routes and guards
│   ├── dashboard/       # Main user area
│   └── layout.tsx       # Global layout file
├── components/          # Reusable UI components
├── lib/                 # Utility functions and services
├── styles/              # Global SCSS or Tailwind config
├── public/              # Static files (e.g. icons, assets)
└── middleware.ts        # Route-level protection logic
```

---

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Run in development
npm run dev

# Build for production
npm run build

# Start production server
npm run start

# Electron build
npm run electron:build

# Capacitor mobile build
npm run capacitor:build
```

> Ensure your `.env.local` contains valid API keys and iGCore URLs.

---

## 🧪 Testing

```bash
# Unit tests
npm run test

# End-to-end tests (e.g. with Playwright)
npm run test:e2e
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🌐 Learn More

- 🧠 [iGCore — Beamify API](https://github.com/NXFinity/iGCore)
- 💬 [Beamify Chat](https://github.com/NXFinity/iGChat)
- 🏙 [Beamify Website](https://beamify.online)
