# 🔥 Code Roast & Re-Factor

An elitist, terminal-themed MVP for roasting "peasant-tier" code and providing high-aura refactors. Built for developers who want to 67maxx their technical debt and improve their developer rizz.

## ✨ Features

- **Dynamic Roasting**: Language-aware roasting engine for JavaScript, Python, and C++.
- **Terminal Aesthetic**: Dark, high-contrast UI with scanlines, glowing borders, and Fira Code integration.
- **The Ascension**: One-click refactor section to help you achieve "67maxxing" efficiency.
- **Single-File Portability**: Entire application logic contained in a single `index.html` via Tailwind CSS and Alpine.js.

## 🚀 Deployment

This project is configured for seamless deployment on **Vercel**.

### Configuration
The `vercel.json` file is included to handle routing and ensure the application behaves correctly as a single-page application.

```json
{
  "name": "code-roast-mvp",
  "rewrites": [
    { "source": "/(.*)", "destination": "/index.html" }
  ]
}
```

### How to Deploy
1. **Vercel CLI**:
   ```bash
   cd code-roast-mvp
   vercel
   ```
2. **GitHub Integration**:
   Push this folder to a GitHub repository and link it to your Vercel account.

## 🛠 Tech Stack

- **Styling**: Tailwind CSS
- **Interactivity**: Alpine.js
- **Typography**: Inter & Fira Code (via Google Fonts)
- **Deployment**: Vercel

---
&copy; 2026 Interaction Company of California. *Elevating logic, one roast at a time.*