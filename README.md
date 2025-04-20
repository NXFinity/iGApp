<p align="center">
  <a href="https://beamify.online" target="_blank">
    <img src="assets/icon.png" width="120" alt="Beamify Logo" />
  </a>
</p>

<h1 align="center">iGApp — Beamify Frontend</h1>
<p align="center">
  <strong>The visual interface of the Beamify Network</strong><br/>
  A cross-platform Angular 19 application built for Web, Desktop (Electron), and Mobile (Cordova).
</p>

---

## 🎨 What is iGApp?

**iGApp** is the official frontend for the Beamify Network — a high-performance, Angular 19-powered application designed to deliver a unified creative experience across devices.

Running on Web, Electron, and Cordova, iGApp serves as the primary interface for interacting with **iGCore**, Beamify’s enterprise-grade backend, and seamlessly integrates with our modular services, including real-time chat, gamification, and dynamic city visualization.

---

## 🚀 Key Features

- 🧩 **Cross-Platform Ready** – Deploy to Web, Electron (desktop), and Cordova (mobile)
- ⚡ **Angular 19** – Modern, fast, and powerful framework with signal-based reactivity
- 🔗 **Tightly Integrated with iGCore** – Interfaces directly with Beamify’s backend API
- 🎮 **Gamified UI** – Live points, rewards, and interactive elements tied to user activity
- 💬 **Chat-Ready** – Built to integrate with Beamify’s standalone encrypted messaging platform
- 🌆 **Live Visualization Hooks** – Real-time metrics drive UI components and animations
- 🔐 **Secure Routing & Auth** – Route guards, token validation, and modular permission layers
- 💡 **Responsive UX** – Built with accessibility and fluid user interaction in mind

---

## 🧬 Technologies Used

- **Angular 19** – Signal-powered modern reactive framework
- **RxJS** – Reactive state management and streams
- **Electron** – Desktop application support
- **Cordova** – Native mobile app compatibility
- **SCSS / TailwindCSS** – Custom styling and theming
- **Angular Material** – Optional component UI toolkit
- **JWT Auth** – Route-based access with token protection
- **iGCore API** – Full backend connectivity

---

## 🗂️ Project Structure

```bash
src/
├── app/
│   ├── core/             # App-wide services, interceptors, guards
│   ├── modules/          # Feature-based modules
│   ├── shared/           # Common components, directives, pipes
│   └── app.component.ts  # Root component logic
├── assets/               # Icons, logos, and static files
├── environments/         # Environment-specific configs
└── index.html            # Main HTML shell
```

---

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Run in browser (Dev)
ng serve

# Build for production
ng build

# Electron build
npm run electron:build

# Cordova mobile build
npm run cordova:build
```

> Ensure environment variables and iGCore API URLs are set in `environment.ts`.

---

## 🧪 Testing

```bash
# Unit tests
ng test

# End-to-end tests
ng e2e
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🌐 Learn More

- 🧠 [iGCore — Beamify API](https://github.com/NXFinity/iGCore)
- 💬 [Beamify Chat](https://github.com/NXFinity/iGChat)
- 🏙 [Beamify Website](https://beamify.online)  
