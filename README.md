# Event Explorer 🎟️

Live Demo: [https://dynamic-lily-a7c45f.netlify.app/](https://dynamic-lily-a7c45f.netlify.app/)

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack & Dependencies](#tech-stack--dependencies)
- [Installation & Setup](#installation--setup)
- [Environment Variables](#environment-variables)
- [Available Scripts](#available-scripts)
- [Folder Structure](#folder-structure)
- [Responsive Design](#responsive-design)
- [Deployment](#deployment)
- [Author](#author)

---

## 📝 Project Overview

**Event Explorer** is a dynamic event discovery platform that connects users with exciting events across multiple categories including music festivals, sports tournaments, tech conferences, art exhibitions, and more. The app features secure authentication, rich content, and a modern, responsive UI.

---

## 🚀 Features

- **Multi-Category Event Discovery**
  - Browse events by type: Music, Sports, Tech, Arts, Food, and more.
- **Secure User Authentication**
  - Login/Register system with Firebase Authentication.
- **Interactive Components**
  - Event sliders
  - Program marquee display
  - Responsive event cards
- **Engaging Content**
  - Featured event highlights
  - Blog section with career/event tips
- **Modern UI**
  - Built with Tailwind CSS and DaisyUI for a sleek design

---

## 🛠 Tech Stack & Dependencies

| Category         | Technologies Used               |
|------------------|---------------------------------|
| Frontend         | React.js                        |
| Routing          | React Router v6                 |
| Styling          | Tailwind CSS + DaisyUI          |
| UI Components    | react-slick, react-fast-marquee |
| Authentication   | Firebase                        |
| SEO              | react-helmet                    |

**Main dependencies:**
```bash
"react": "^18.2.0"
"react-dom": "^18.2.0"
"react-router-dom": "^6.14.1"
"firebase": "^10.5.0"
"tailwindcss": "^3.3.3"
"daisyui": "^3.7.3"
"react-slick": "^0.29.0"
"react-fast-marquee": "^1.5.2"
"react-helmet": "^6.1.0"
```

---

## 📥 Installation & Setup

1. **Clone the repository**
    ```bash
    git clone https://github.com/arifurrahmansajid/Event-Explorer.git
    cd Event-Explorer
    ```

2. **Install dependencies**
    ```bash
    npm install
    ```

3. **Start the development server**
    ```bash
    npm run dev
    ```
    Open your browser and go to [http://localhost:5173](http://localhost:5173) (or as specified by your setup).

---

## 🔑 Environment Variables

If you are using Firebase or other APIs, create a `.env.local` file in the root directory:

```
VITE_API_BASE_URL=https://your-api-url.com
VITE_FIREBASE_API_KEY=your-firebase-api-key
VITE_FIREBASE_AUTH_DOMAIN=your-firebase-auth-domain
# ...other Firebase or custom env variables
```

> **Note:** Be sure to include `.env.local` in your `.gitignore` file to keep your credentials safe.

---

## 📋 Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## 📂 Folder Structure

```
Event-Explorer/
├── public/                # Static assets
├── src/
│   ├── assets/            # Images, icons, etc.
│   ├── components/        # Reusable UI components (EventCard, Slider, etc.)
│   ├── pages/             # Pages (Home, EventDetails, Blog, etc.)
│   ├── styles/            # Tailwind/other styles
│   ├── utils/             # Helper utilities (API, formatters, etc.)
│   ├── App.jsx            # App root
│   └── main.jsx           # Entry point
├── .env.local             # Environment variables (ignored)
├── vite.config.js         # Vite configuration (if using Vite)
└── README.md              # Project documentation
```

---

## 📱 Responsive Design

Event Explorer is fully responsive and mobile-first. It adapts seamlessly to:

- **Mobile:** 320px+ width
- **Tablet:** 768px+ width
- **Desktop:** 1024px+ width

All components are tested for smooth experience across devices.

---

## 🚀 Deployment

You can deploy your production build to any static hosting provider (Vercel, Netlify, Firebase Hosting, etc.):

```bash
npm run build
# Deploy the 'dist/' folder as per your hosting provider's guidelines
```

_Example: For Firebase Hosting_

```bash
npm run build
firebase deploy
```

If using React Router, ensure your host is configured for single-page app routing.

---

## 👤 Author

**Arifur Rahman Sajid**  
GitHub: [arifurrahmansajid](https://github.com/arifurrahmansajid)

---

Happy exploring! 🚀
