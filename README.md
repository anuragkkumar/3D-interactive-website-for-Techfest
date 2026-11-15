# Techfest 2026 — 3D Celestial Observatory
### Indian Institute of Technology Bombay | 3D Interactive WebGL Submission (100 Points)

An interactive 3D Celestial Solar Observatory designed and developed for **Techfest 2026, IIT Bombay** (30th Edition). Built with Three.js (WebGL) without bloated frameworks or generic AI templates, featuring procedural planetary surface shaders, direct 3D raycasting navigation, simulation speed toggles, an in-memory procedural Web Audio space synthesizer, comprehensive competition dossiers, full 3-day schedules, international expo showcases, and a campus venue guide.

---

## ⚡ Live WebGL Experience
🔗 **GitHub Repository:** [https://github.com/anuragkkumar/techfest-3d-interactive](https://github.com/anuragkkumar/techfest-3d-interactive)  
🔗 **Live Pages Deployment:** [https://anuragkkumar.github.io/techfest-3d-interactive/](https://anuragkkumar.github.io/techfest-3d-interactive/)  
🔗 **Local Testing:** `http://localhost:8080/`

---

## 🪐 Architecture & Feature Overview

### 1. Header Navigation & Interactive Telemetry
- **Top Navigation Bar:**
  - **🌌 3D GALAXY:** Orbital panoramic overview of the Techfest universe.
  - **⚔️ ARENAS & RULES:** Live search and categorized dossiers (Robowars, Hackathon, Meshmerize, Drone Prix, AI Summit, Cozmo Clench).
  - **🗓️ 3-DAY SCHEDULE:** Full chronological itinerary for Days 1, 2, and 3 across campus venues with instant search.
  - **🔬 EXPO & WORKSHOPS:** 6 Global humanoid & aerospace exhibits (Unitree H1, Sophia, ISRO, Bionics) + 6 Certified Masterclasses (Quantum circuits, ROS 2, Edge AI).
  - **📍 CAMPUS MAP:** Powai venue dossiers (Convocation Hall, Gymkhana, OAT, SAC, CC, VMCC) and transit routes from BOM Airport and Mumbai train stations.
  - **🎓 LUMINARIES:** Wall of keynote speakers (Dr. APJ Abdul Kalam, Rakesh Sharma, Bjarne Stroustrup, Ada Yonath, Gordon Moore, Sophia).
  - **🎟️ DELEGATION PASS:** Accreditation privileges, accommodation policies, and verified entry code (`TECHFEST-IITB-2026`).
- **Interactive Controls:**
  - **AUDIO: OFF / ON:** Procedural ambient cosmic drone synthesizer created with the Web Audio API (zero external sound files needed).
  - **Speed Selector (⏸, 0.5x, 1x, 2x):** Adjust simulation physics in real-time.
  - **ORBITS Toggle:** Show/hide planetary trajectory ellipses.

### 2. Direct 3D Raycasting & Planet Fly-To Engine
- **Direct 3D Interaction:** Click or tap any planet or the central Sun directly in the WebGL scene to initiate smooth camera fly-to orbit.
- **Hover Detection:** Custom cursor tracking provides visual feedback when hovering over celestial bodies.
- **Bottom Celestial Dock:** One-click quick jump between flagship sectors:
  - `☀️ TECHFEST CORE` (30th Edition Mainframe)
  - `⚔️ ROBOWARS` (Heavyweight combat arena)
  - `🧠 AI SUMMIT` (Neural computing track)
  - `📍 IIT BOMBAY` (Main Powai grounds & CA network)
  - `🚀 AEROSPACE` (ISRO pavilion & Drone Prix)
  - `🔬 EXHIBITIONS` (Humanoid robotics & global showcases)
  - `🎆 TECHNOHOLIX` (1,000-drone formation light symphony)
  - `🤖 MESHMERIZE` (Autonomous line maze solvers)
  - `💻 HACKATHON` (36-hour continuous build sprint)
- **Sector Telemetry HUD:** Real-time data readouts + **"Inspect Sector Dossier & Rules"** button.

### 3. Procedural In-Memory Planetary Textures
- **Earth:** Dynamic ocean depth shaders, organic continents, and swirling cloud layer.
- **Jupiter:** Layered horizontal fluid atmospheric bands with the Great Red Spot.
- **Saturn:** Double-sided ice particle rings with tilt (representing the 1,000-drone light show).
- **Mars:** Ochre rust canyons with polar ice caps.
- **Sun:** Multi-frequency solar turbulence with radiating corona.

### 4. Interactive 3D Orbit Controls
- **Click & Drag 360°:** Orbit around the entire solar system or around individual planets with momentum damping.
- **Scroll Zoom:** Zoom in/out smoothly with mouse wheel.
- **Cursor Parallax:** Natural perspective damping tracking cursor coordinates.

---

## 🛠️ Tech Stack
- **Engine:** Three.js (r128) WebGL Renderer
- **Audio:** Web Audio API (procedural lowpass filtered harmonic drone)
- **Typography:** Space Grotesk, JetBrains Mono
- **Materials:** MeshStandardMaterial (PBR) + Procedural Canvas Textures
- **Styling:** CSS Hardware-Accelerated Glassmorphism

---

## 👤 Project Details
- **Developer:** Anurag Kumar
- **Event:** Techfest 2026, IIT Bombay
- **Delegate Access:** `TECHFEST-IITB-2026`
