# MONO - Sustainable & Eco-Friendly Architecture Landing Page

**MONO** is a premium, modern, and highly interactive landing page template designed specifically to promote sustainable, eco-responsible modular housing (passive homes). The website combines minimalist contemporary design aesthetics with smooth, high-performance scroll-driven animations without relying on heavy third-party animation libraries.

---

## 🎥 Demo Video
Here is a preview of the interactive experience of the **MONO** landing page:

<video src="https://github.com/user-attachments/assets/e9c7ed64-1fd4-4155-ac2a-4160218790b3" width="100%" controls autoplay loop muted></video>

*If the video above does not play automatically, you can download or watch it directly at: [public/demo.mp4](./public/demo.mp4)*

---

## 🏠 What is the MONO Website?
This website is a showcase and e-commerce landing page for the eco-friendly modular home brand **MONO**. Focusing on the concept of energy-efficient, environmentally friendly, and carbon-saving passive houses, the site is designed to engage potential buyers with stunning visuals and precise technical specifications.

The website showcases 3 distinct model sizes (*Surface Options*):
1. **Compact Model** (120m²) – Focusing on optimal energy efficiency ($285,000).
2. **Standard Model** (180m²) – The perfect balance of space and sustainability ($395,000).
3. **Premium Model** (250m²) – Expansive design with maximum comfort ($525,000).

---

## ✨ Key Features & Interactive Animations
This landing page is built to the highest aesthetic standards and includes advanced micro-interactions:
- **Interactive Hero Bento Grid**: As the user scrolls down, the side images of the bento grid slide in smoothly while the main center image scales down, creating a cinematic bento grid transition.
- **3D Rotation Philosophy**: In the philosophy section, text titles rotate in 3D based on the user's scroll progress.
- **Blur Scroll Reveal Text**: Description text fades in word-by-word with a custom blur and opacity animation driven by scroll progress.
- **Day-to-Night Adaptive Simulation (Technology Section)**: In the passive house technology section, images slide in and smoothly transition from **Sunrise ➔ Daylight ➔ Dusk ➔ Starry Night** as the user scrolls.
- **Stacked Card Gallery**: An interactive stacked deck of cards representing various perspectives of the house, which scale and expand to full screen.
- **Specs Dashboard**: Displays the key environmental performance metrics of the home (Surface Area, Energy Use, Solar Panels, and Carbon Balance).
- **Responsive Navigation**: A floating header with a glassmorphism blur effect that adjusts on scroll, complete with an intuitive mobile menu.

---

## 🛠️ Tech Stack
This website is built with a modern stack:
- **Framework**: [Next.js](https://nextjs.org/) (React 19, App Router)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) & [PostCSS](https://postcss.org/)
- **UI Components**: [Shadcn UI](https://ui.shadcn.com/) (built on Radix UI primitives)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Animations**: Performance-driven vanilla scroll animations implemented using custom React hooks (`React.useState`, `React.useEffect`, `requestAnimationFrame`) to calculate scroll progress precisely with zero external animation dependencies (no Framer Motion or GSAP).

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Node.js installed on your machine.

### Installation Steps

1. **Clone this repository:**
   ```bash
   git clone <your-repository-url>
   cd mono-e-commerce-template
   ```

2. **Install dependencies:**
   Using npm:
   ```bash
   npm install
   ```
   Or using pnpm:
   ```bash
   pnpm install
   ```

3. **Run the local development server:**
   ```bash
   npm run dev
   # or
   pnpm dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser to see the live site.

4. **Build for Production:**
   ```bash
   npm run build
   # or
   pnpm build
   ```

---

## ✍️ Credits & Appreciation
The base template and design concept for this website were created by **[@kerroudj](https://github.com/kerroudj)**. Thank you for this amazing and inspiring template!
