# Odyssey 🌌
### Reimagine Social - Frontend Hackathon Submission

Odyssey is a next-generation social interaction prototype that completely abandons the traditional "infinite scrolling feed." Instead of relying on addictive algorithms and vanity metrics, Odyssey visualizes social connections as a **living, breathing constellation of ideas**.

## 🚀 The Vision: Beyond the Feed
Traditional social media isolates users in algorithmic silos. Odyssey reimagines social spaces as an interactive map:
*   **Topics** act as gravitational centers (e.g., Philosophy, Design).
*   **Discussions** orbit these topics as dedicated spaces for deep conversation.
*   **People** organically cluster around the ideas they care about.

By interacting with the 3D node graph, users can visually explore where conversations are happening, see how ideas connect, and join spaces based on curiosity rather than popularity.

## 🛠 Tech Stack
*   **Frontend Framework:** React (18.x)
*   **Styling:** Tailwind CSS (Dark Mode optimized)
*   **Physics/Graph Engine:** `react-force-graph-2d` (D3 force-directed graph)
*   **Animations:** Vanilla-Tilt.js (3D card hover effects) & tsParticles
*   **Icons:** Lucide 

## ⚡ Zero-Build Architecture
For maximum portability and instant deployment, this project utilizes a **Zero-Build Architecture**. 
All React components, Babel transpilation, and Tailwind classes are resolved directly in the browser via CDN. 
**There is no need to run `npm install` or configure Webpack/Vite.**

### How to Run Locally
1. Clone the repository.
2. Open `index.html` in your browser.
*(Note: Some browsers require a local server for CORS when loading modules. You can run `python -m http.server 8000` or use the VSCode Live Server extension).*

### How to Host (Vercel / GitHub Pages / Netlify)
Simply drop the `index.html` file into your hosting provider. No build commands (`npm run build`) are required! The directory is ready to serve as a static site immediately.

## ✨ Key Features
1.  **The Constellation Map:** A fully interactive, draggable, and zoomable physics node graph representing the social network.
2.  **Interactive 3D Cards:** The Discover tab features cards with 3D tilt and glare mechanics powered by Vanilla-Tilt.
3.  **Live Activity Overlay:** A real-time activity feed that highlights meaningful interactions ("sparked a thought") rather than vanity metrics ("liked your post").
4.  **Glassmorphism UI:** Premium frosted glass (backdrop-blur) elements and smooth, staggered entry animations.
