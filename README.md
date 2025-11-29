<div align="center">

# 🌑 Pitch Black Swiss Portfolio

### A stunning, award-worthy portfolio template with Swiss design aesthetics

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-11-FF0055?style=for-the-badge&logo=framer)](https://www.framer.com/motion/)
[![Three.js](https://img.shields.io/badge/Three.js-r170-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<p align="center">
  <strong>🎨 Digital Noir Design • 🚀 60fps Animations • 📱 Fully Responsive • ⚡ Lightning Fast</strong>
</p>

[**Live Demo**](https://your-demo-link.vercel.app) • [**Report Bug**](https://github.com/dev-sufyaan/pitch-black-portfolio/issues) • [**Request Feature**](https://github.com/dev-sufyaan/pitch-black-portfolio/issues)

</div>

---

## 📸 Screenshots

<div align="center">

### 🏠 Hero Section
![Hero Section](https://raw.githubusercontent.com/dev-sufyaan/Portfolio-Pitch-Black-Swiss/main/images/hero-section.png)
*Immersive 3D hero with reactive elements and flip words animation*

### 👤 About Section
![About Section](https://raw.githubusercontent.com/dev-sufyaan/Portfolio-Pitch-Black-Swiss/main/images/about-section.png)
*Encrypted text reveal with skill tags and glassmorphism effects*

### 💼 Works Section
![Works Section](https://raw.githubusercontent.com/dev-sufyaan/Portfolio-Pitch-Black-Swiss/main/images/works-section.png)
*Cinema-mode focus cards with smooth hover transitions*

### ⚙️ Process Timeline
![Process Section](https://raw.githubusercontent.com/dev-sufyaan/Portfolio-Pitch-Black-Swiss/main/images/process-section.png)
*Interactive tracing beam timeline with scroll-based animations*

### 🎯 Skills Grid
![Skills Section](https://raw.githubusercontent.com/dev-sufyaan/Portfolio-Pitch-Black-Swiss/main/images/skills-section.png)
*Bento grid layout with mouse-reactive glowing effects*

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎬 Animations & Effects
- **60fps Smooth Scroll** - Lenis-powered buttery experience
- **Custom Cursor** - Lerped cursor with multiple states
- **3D Hero Section** - Three.js reactive 3D elements
- **Film Grain Effect** - Premium noise overlay
- **Glassmorphism UI** - Modern frosted glass effects
- **Magnetic Buttons** - Interactive hover physics

</td>
<td width="50%">

### 🧩 UI Components
- **Focus Cards** - Cinema-mode project showcase
- **Encrypted Text** - Hacker-style text reveals
- **Tracing Beam** - Scroll-based timeline
- **Glowing Effects** - Mouse-reactive glow
- **Stateful Buttons** - Loading → Success states
- **Flip Words** - Animated text transitions

</td>
</tr>
</table>

### Font Setup

The project uses **Google Fonts** as fallbacks for optimal performance:
- **Display**: Playfair Display (serif, elegant headlines)
- **Body**: Inter (neo-grotesque, excellent readability)

To use custom fonts, add your font files to the respective folders and update `app/layout.tsx` as described in the customization guide.

---

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/dev-sufyaan/pitch-black-portfolio.git

# Navigate to the project
cd pitch-black-portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see your portfolio! 🎉

### Build for Production

```bash
# Create optimized build
npm run build

# Start production server
npm start
```

---

## 📁 Project Structure

```
pitch-black-portfolio/
├── 📂 app/
│   ├── globals.css          # Global styles & Tailwind
│   ├── layout.tsx           # Root layout with fonts
│   └── page.tsx             # Main page component
│
├── 📂 components/
│   ├── 📂 sections/         # Page sections
│   │   ├── hero-section.tsx      # 3D immersive hero
│   │   ├── about-section.tsx     # Bio & encrypted text
│   │   ├── works-section.tsx     # Project focus cards
│   │   ├── process-section.tsx   # Timeline with tracing beam
│   │   ├── skills-section.tsx    # Bento grid skills
│   │   └── footer-section.tsx    # CTA & contact
│   │
│   ├── 📂 ui/               # Reusable UI components
│   │   ├── floating-navbar.tsx   # Sticky navigation
│   │   ├── flip-words.tsx        # Animated text swap
│   │   ├── sparkles.tsx          # Particle effects
│   │   ├── encrypted-text.tsx    # Hacker text reveal
│   │   ├── focus-cards.tsx       # Cinema-mode cards
│   │   ├── timeline.tsx          # Process timeline
│   │   ├── tracing-beam.tsx      # Scroll indicator
│   │   ├── glowing-effect.tsx    # Mouse glow
│   │   ├── stateful-button.tsx   # Loading states
│   │   ├── magnetic-button.tsx   # Hover physics
│   │   ├── kinetic-marquee.tsx   # Scrolling text
│   │   └── hover-border-gradient.tsx
│   │
│   ├── custom-cursor.tsx    # Custom cursor component
│   ├── lenis-provider.tsx   # Smooth scroll provider
│   └── noise-overlay.tsx    # Film grain effect
│
├── 📂 lib/
│   └── utils.ts             # Utility functions (cn)
│
├── 📂 Nohemi/               # Nohemi font files
├── 📂 Harmond.../           # Harmond font files
│
├── tailwind.config.js       # Tailwind configuration
├── next.config.js           # Next.js configuration
└── package.json
```

---

## 🎯 Customization Guide

### 1. Personal Information

Edit the content in each section file:

<details>
<summary><b>📝 Hero Section</b> - <code>components/sections/hero-section.tsx</code></summary>

```tsx
// Change the flip words
const words = ["Developer", "Designer", "Creator", "Your Title"];

// Update headline
<h1>Your Name Here</h1>
```
</details>

<details>
<summary><b>👤 About Section</b> - <code>components/sections/about-section.tsx</code></summary>

```tsx
// Update your bio
const aboutText = "Your bio description here...";

// Change skill tags
const skills = ["React", "Next.js", "Your Skills"];
```
</details>

<details>
<summary><b>💼 Works Section</b> - <code>components/sections/works-section.tsx</code></summary>

```tsx
// Add your projects
const projects = [
  {
    title: "Project Name",
    description: "Project description",
    image: "/path-to-image.jpg",
    link: "https://project-link.com"
  },
  // Add more projects...
];
```
</details>

<details>
<summary><b>⚙️ Process Section</b> - <code>components/sections/process-section.tsx</code></summary>

```tsx
// Customize your workflow
const processSteps = [
  { title: "Discovery", description: "Understanding requirements" },
  { title: "Design", description: "Creating mockups" },
  // Add your process steps...
];
```
</details>

<details>
<summary><b>🎯 Skills Section</b> - <code>components/sections/skills-section.tsx</code></summary>

```tsx
// Update your skills
const skillCategories = [
  { name: "Frontend", skills: ["React", "Vue", "Angular"] },
  { name: "Backend", skills: ["Node.js", "Python", "Go"] },
  // Add categories...
];
```
</details>

<details>
<summary><b>📧 Footer Section</b> - <code>components/sections/footer-section.tsx</code></summary>

```tsx
// Update contact info
const email = "your@email.com";
const socials = {
  twitter: "https://twitter.com/yourusername",
  github: "https://github.com/yourusername",
  linkedin: "https://linkedin.com/in/yourusername"
};
```
</details>

### 2. Colors & Theme

Edit `tailwind.config.js`:

```js
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: '#000000',    // Change primary color
        accent: '#3B82F6',     // Change accent color
      }
    }
  }
}
```

### 3. Fonts

The project uses Google Fonts as fallbacks. To use custom fonts:

1. Add your font files to `/Nohemi` and `/Harmond-Free-For-Personal-Use` folders
2. Update `app/layout.tsx` to use `localFont` instead of Google Fonts:

```tsx
import localFont from "next/font/local";

// Replace Google Font imports with local fonts
const harmond = localFont({
  src: "../Harmond-Free-For-Personal-Use/...",
  // ... font config
});
```

---

## 🛠 Tech Stack

<div align="center">

| Technology | Purpose |
|------------|---------|
| ![Next.js](https://img.shields.io/badge/Next.js_14-000?logo=next.js) | React Framework (App Router) |
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) | Type Safety |
| ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white) | Styling |
| ![Framer Motion](https://img.shields.io/badge/Framer_Motion-FF0055?logo=framer&logoColor=white) | Animations |
| ![Three.js](https://img.shields.io/badge/Three.js-000?logo=three.js) | 3D Graphics |
| ![Lenis](https://img.shields.io/badge/Lenis-000?logo=data:image/svg+xml;base64,) | Smooth Scroll |

</div>

---

## ⚡ Performance

<table>
<tr>
<td>

### Optimizations
- ✅ 60fps animations throughout
- ✅ Lazy-loaded 3D elements
- ✅ GPU-accelerated transforms
- ✅ Efficient requestAnimationFrame
- ✅ Font preloading with next/font
- ✅ Image optimization with Next.js
- ✅ Code splitting & tree shaking

</td>
<td>

### Lighthouse Scores
```
Performance:    95+
Accessibility:  90+
Best Practices: 95+
SEO:            100
```

</td>
</tr>
</table>

---

## 📱 Responsive Design

| Breakpoint | Screen Size | Optimizations |
|------------|-------------|---------------|
| 📱 Mobile | < 768px | Touch-optimized, simplified animations |
| 📱 Tablet | 768px - 1024px | Adapted grid, scaled components |
| 🖥️ Desktop | > 1024px | Full experience, all effects enabled |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contributions
- [ ] Add more color themes
- [ ] Create additional section layouts
- [ ] Add blog section template
- [ ] Improve accessibility
- [ ] Add i18n support
- [ ] Create more UI components

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### Font Licenses
- **Nohemi**: See `/Nohemi/Nohemi/License/`
- **Harmond**: Free for personal use only

---

## 🙏 Acknowledgments

- [Aceternity UI](https://ui.aceternity.com/) - UI component inspiration
- [Framer Motion](https://www.framer.com/motion/) - Animation library
- [Lenis](https://lenis.studiofreight.com/) - Smooth scroll
- [Three.js](https://threejs.org/) - 3D graphics

---

<div align="center">

### ⭐ Star this repo if you find it useful!

**Made with ❤️ by [Sufyaan](https://github.com/dev-sufyaan)**

[![GitHub followers](https://img.shields.io/github/followers/dev-sufyaan?style=social)](https://github.com/dev-sufyaan)
[![Twitter Follow](https://img.shields.io/twitter/follow/dev_sufyaan?style=social)](https://twitter.com/dev_sufyaan)

</div>
