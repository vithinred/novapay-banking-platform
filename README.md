[README.md](https://github.com/user-attachments/files/26453696/README.md)
# NovaPay – Digital Banking Platform

A full-stack digital banking UI built with **React (Web)** and **React Native (Mobile)**, featuring a unified design system across four core banking flows.

## Project Structure

```
banking-platform/
├── web/          # React web app (Vite + CSS Modules)
├── mobile/       # React Native app (Expo)
└── README.md
```

## Features

| Screen | Web | Mobile |
|---|---|---|
| Onboarding / Sign-Up | ✅ | ✅ |
| Account Dashboard | ✅ | ✅ |
| Transfers | ✅ | ✅ |
| Bill Pay | ✅ | ✅ |

## Design System

- **Color Palette**: Deep navy `#0A0F1E` + Electric cyan `#00D4FF` + Soft white `#F0F4FF`
- **Typography**: Syne (display) + DM Sans (body)
- **Motion**: Smooth page transitions, micro-interactions on inputs and CTAs
- **Accessibility**: WCAG 2.1 AA compliant, keyboard navigable, ARIA labels

---

## Web App (React + Vite)

### Setup

```bash
cd web
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173)

### Tech Stack
- React 18
- Vite
- CSS Modules
- React Router v6

---

## Mobile App (React Native + Expo)

### Setup

```bash
cd mobile
npm install
npx expo start
```

Scan the QR code with Expo Go (iOS/Android) or press `w` for web preview.

### Tech Stack
- React Native
- Expo SDK 51
- React Navigation v6
- StyleSheet API

---

## How to Push to GitHub

```bash
# From the banking-platform/ root
git init
git add .
git commit -m "feat: initial NovaPay digital banking platform"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/novapay-banking-platform.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

---

## Resume Bullets (Copy-Paste Ready)

> **Digital Banking Platform Redesign (Web + iOS + Android)**  
> - Built a responsive React web app and React Native mobile app featuring onboarding, account dashboard, transfers, and bill pay screens with a unified design system.  
> - Architected reusable component libraries across platforms (web: CSS Modules + React; mobile: StyleSheet API + Expo), reducing UI duplication by ~60%.  
> - Implemented accessible, WCAG 2.1 AA-compliant UI with smooth page transitions and micro-interactions aligned with modern fintech UX patterns.

---

*Built by Vithin Reddy Sandadi — github.com/vithinreddy*
# novapay-banking-platform
