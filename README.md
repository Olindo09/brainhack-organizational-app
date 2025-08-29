# 🧠 BrainHack — ADHD Assistant (React MVP)

A minimal, mobile‑friendly React app designed to help manage ADHD with **checklists, finances, and a Pomodoro focus timer**. Built with a bright matte amber palette to maximize visibility and focus.

## ✨ Features

- **Checklist Manager**  
  Add tasks manually or by typing journal notes. The app auto‑splits sentences into multiple tasks.

- **Pomodoro Timer**  
  Full‑screen focus timer (15, 20, 25, or 45 minutes). Pick a task → focus → track progress.

- **Finance Tracker**  
  Track savings and bills. Mark bills as paid to subtract from your saved amount. Shows unpaid total and remaining balance.

- **Simple, Mobile‑First UI**  
  Rounded, matte amber cards. Designed for small screens with clear contrast.

- **Voice Input (coming soon)**  
  A 🎤 mic button placeholder is included; integrates with Web Speech API.

## 📂 Project Structure

```
/Adhd Brain Hack Assistant — React Mvp
  ├── App.js (main BrainHackApp component)
  ├── Pomodoro component
  ├── Checklist + Finance views
  └── README.md (this file)
```

## 🚀 Getting Started

### Prerequisites
- Node.js ≥ 16
- npm or yarn

### Install & Run
```bash
# install dependencies
npm install

# run locally
npm start

# build for production
npm run build
```

### PWA Deployment
You can deploy as a static Progressive Web App (PWA):
1. Run `npm run build` → creates `/build` folder.
2. Drag `/build` folder into [Netlify Drop](https://app.netlify.com/drop) or host with Vercel/GitHub Pages.
3. Add to Home Screen on your phone for an app‑like experience.

## 🛠️ Tech Stack
- **React** (functional components + hooks)
- **Tailwind CSS** (utility classes)
- **Local state** for tasks & bills
- PWA‑ready structure (add manifest + service worker to build)

## 📌 Roadmap
- [ ] Voice command → auto extract tasks from speech
- [ ] Cloud sync via Netlify Identity + Blobs
- [ ] Daily 3‑priority task enforcement (red until 15m focus achieved)
- [ ] Export/Import data as JSON

## 🤝 Contributing
Pull requests welcome! For major changes, open an issue first to discuss what you’d like to change.

## 📄 License
MIT — free to use, share, and adapt.
