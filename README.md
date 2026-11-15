# Techfest 2026 — 3D Celestial Observatory
### Indian Institute of Technology Bombay | 3D Interactive WebGL Submission (100 Points)

[![GitHub Pages](https://img.shields.io/badge/Deployment-Live%20on%20GitHub%20Pages-22c55e?style=for-the-badge&logo=github)](https://anuragkkumar.github.io/3D-interactive-website-for-Techfest/)
[![Three.js](https://img.shields.io/badge/Three.js-WebGL%203D-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![IIT Bombay](https://img.shields.io/badge/Techfest%20IIT%20Bombay-30th%20Edition-f97316?style=for-the-badge)](https://techfest.org)

An interactive 3D Celestial Solar Observatory designed and developed for **Techfest 2026, IIT Bombay** (30th Edition). Built with Three.js (WebGL) without bloated frameworks or generic AI templates, featuring procedural planetary surface shaders, direct 3D raycasting navigation, an editorial minimalist interface, comprehensive competition dossiers, full 3-day festival schedules, international expo showcases, and a campus venue guide.

---

## ⚡ Live WebGL Experience

👉 **[Launch Interactive 3D Website](https://anuragkkumar.github.io/3D-interactive-website-for-Techfest/)**  
`https://anuragkkumar.github.io/3D-interactive-website-for-Techfest/`

---

## 🪐 Architecture & Feature Overview

### 1. Minimalist Editorial Interface & Header Navigation
- **Top Navigation Bar:**
  - **Arenas & Rules:** Flagship competition dossiers (Robowars, Hackathon, Meshmerize, Drone Prix, AI Track, Cozmo Clench) with prize pools and technical specs.
  - **3-Day Schedule:** Chronological timeline across all three festival days (Dec 18–20, 2026) at the IIT Bombay Powai campus.
  - **Exhibits & Labs:** International humanoid robotics exhibits (Unitree H1, Sophia) and certified engineering masterclasses (Quantum computing, ROS 2, Edge AI).
  - **Campus Map:** Powai venue dossiers (Convocation Hall, Gymkhana, Open Air Theatre, SAC, Computer Centre, VMCC) and transit routes from BOM Airport and Mumbai railway stations.
  - **Luminaries:** Wall of keynote speakers across 30 editions (Dr. APJ Abdul Kalam, Rakesh Sharma, Bjarne Stroustrup, Ada Yonath, Gordon Moore, Sophia).
  - **Delegation Pass:** Accreditation privileges, accommodation guidelines, and verified delegate code (`TECHFEST-IITB-2026`).
- **Unified Tabbed Dossier Modal:** All festival information is organized inside a unified tabbed modal with zero clutter on the 3D viewport.

### 2. Direct 3D Raycasting & Planet Fly-To Engine
- **Direct 3D Interaction:** Click or tap any planet or the central Sun directly in the WebGL scene to initiate smooth camera fly-to orbit.
- **Hover Detection:** Custom cursor tracking provides visual feedback when hovering over celestial bodies.
- **Bottom Celestial Dock:** Instant smooth camera fly-to navigation across Techfest sectors:
  - `☀️ Core` (30th Edition Mainframe)
  - `⚔️ Robowars` (60kg & 15kg Heavyweight combat arena, ₹12 Lakh prize pool)
  - `🧠 AI Summit` (Neural computing, LLMs & computer vision track)
  - `📍 IIT Bombay` (Main Powai grounds & Campus Ambassador network)
  - `🚀 Aerospace` (ISRO pavilion & Drone Prix racing)
  - `🔬 Exhibitions` (Humanoid robotics & global showcases from 78 nations)
  - `🎆 Technoholix` (1,000-drone formation light symphony & pro-nights)
  - `🤖 Meshmerize` (Autonomous line maze solvers)
  - `💻 Hackathon` (36-hour national continuous sprint with direct PPOs)
- **Sector Telemetry HUD:** Real-time data readouts + **"Inspect Sector Dossier & Rules"** button.

### 3. Procedural In-Memory Planetary Textures
- **Earth:** Dynamic ocean depth shaders, organic continents, and swirling cloud layer with an orbiting Moon representing the Campus Ambassador network.
- **Jupiter:** Layered horizontal fluid atmospheric bands with the Great Red Spot.
- **Saturn:** Double-sided ice particle rings with tilt (representing the 1,000-drone light show).
- **Mars:** Ochre rust canyons with polar ice caps.
- **Sun:** Multi-frequency solar turbulence with a breathing corona flare.

### 4. Interactive 3D Orbit Controls
- **Click & Drag 360°:** Orbit around the entire solar system or around individual planets with momentum damping.
- **Scroll Zoom:** Zoom in/out smoothly with mouse wheel.
- **Cursor Parallax:** Natural perspective damping tracking cursor coordinates.

---

## 🛠️ Tech Stack
- **Engine:** Three.js (r128) WebGL Renderer
- **Typography:** Space Grotesk, JetBrains Mono
- **Materials:** MeshStandardMaterial (PBR) + Procedural Canvas Textures
- **Styling:** CSS Hardware-Accelerated Glassmorphism (Zero heavy UI dependencies)

---

## 👤 Project Details
- **Developer:** Anurag Kumar
- **Event:** Techfest 2026, IIT Bombay
- **Delegate Access:** `TECHFEST-IITB-2026`
