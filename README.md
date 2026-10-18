# 🌱 AGRI TECH — Smart Farming Companion & C Practice Lab

> **“Smart Farming. Better Decisions. Stronger Future.”**  
> **Team:** Agri Tech Titans (2 Members)  
> **Category:** Smart Agriculture & Farmer Assistance  
> **Contest Alignment:** Web Application + On-Spot C Programming Debugging Lab (Linux GCC)

---

## 📌 Project Overview

**AGRI TECH** is a comprehensive, production-grade agricultural assistance web application designed to empower smallholder and commercial farmers with actionable intelligence. It brings together crop advisory, plant disease triage, agro-meteorological forecasting, live-simulated Mandi market rates, smart irrigation scheduling, and localized farm management.

To satisfy the **Code Debugging & On-Spot Programming** contest requirements, AGRI TECH incorporates a dedicated **C Programming Practice Lab** featuring a 150-minute practice timer, preliminary-round quiz, interactive C debugging arena, and Linux GCC setup guide.

---

## 🚀 Key Features

### 1. 🌿 Smart Crop Advisor
- Evaluates **6 critical farm parameters**: Soil Type, Season (Kharif/Rabi/Zaid), Water Availability, Land Area & Unit, Previous Crop in rotation, and Region.
- Deterministic agronomic scoring engine calculating top matched crops with duration, indicative yields (quintals/acre), projected profit ranges, and seasonal risk warnings.

### 2. 🔬 AI Plant Doctor (Visual Health Triage)
- Image upload (supports JPEG, PNG, WebP with size validation).
- 5 pre-loaded sample leaves (Tomato Early Blight, Rice Blast, Potato Late Blight, Cotton Leaf Curl, Healthy Maize).
- High-tech scanning simulation with pathogen classification, confidence score, observed foliar symptoms, organic/cultural remedies, chemical treatments, and prevention protocols.
- **Honest Disclaimer:** Clearly labeled as *Demo Analysis — Not a Confirmed Diagnosis*.

### 3. 🌦️ Weather & Spraying Advisories
- Current temperature, feels like, humidity, precipitation probability, wind speed & direction, UV index, and soil moisture index.
- One-click live Open-Meteo telemetry testing.
- 7-day agricultural forecast with daily farming recommendations.
- Critical agro-advisories (e.g., Favorable Spraying Window before 10 AM).

### 4. 📈 Mandi Market Insights (Benchmark Rates)
- Tracks 7 core commodities: **Tomato, Onion, Potato, Rice, Wheat, Maize, Cotton**.
- Shows spot prices (₹/Quintal), 24h price changes, arrival volumes, and quality grade.
- Interactive SVG price trend charts (7-Day and 30-Day curves).
- Terminal APMC market comparison tables (e.g., Kolar vs Azadpur vs Lasalgaon).

### 5. 💧 Smart Irrigation Planner
- Calculates watering intervals, pump run durations (minutes), and water volume consumed (liters).
- Displays water-saving efficiency percentage (up to 48% with drip vs flood).
- Outlines agronomic factors that modify watering schedules.

### 6. 🚜 My Farm Dashboard
- Active plot profiles (Plot A Tomato, Plot B Basmati Rice).
- **Full Task CRUD**: Add, edit, complete, delete farm tasks (stored in `localStorage`).
- Farm notepad persisted on current device.
- Irrigation schedule, fertilization reminders, and harvest pipeline.
- Quick action triggers (Ask AI, Scan Crop, Check Weather, View Mandi Rates).

### 7. 👥 Farmer Community Forum
- Interactive social feed: write questions, attach photos, tag crops & topics.
- Filter by topic: *Pest Alerts, Organic Practices, Irrigation & Equipment, Market Discussion*.
- Like posts and reply with localized farming advice (persisted in `localStorage`).

### 8. 📚 Agri Knowledge Hub & Government Schemes
- Searchable articles across 8 categories with bookmarks and reading time.
- Direct cards for verified schemes: **PM-KISAN, PMFBY, Soil Health Card, PMKSY, Kisan Credit Card** with verified `.gov.in` links.

### 9. 🤖 Mitra AI Farming Assistant
- Fixed bottom-right pulsing button expanding to "AI Assistant".
- Multilingual chat support: **English, Kannada (ಕನ್ನಡ), Hindi (हिन्दी)**.
- Voice input interface (Speech-to-Text) & read-aloud option (Speech Synthesis TTS).
- Suggested farming queries with loading states and transparent demo disclosure.

### 10. 💻 C Programming Practice Lab (Contest Requirement)
- **150-Minute Practice Timer (2 hr 30 min)** with Start, Pause, Reset.
- **Preliminary Round Practice Quiz**: 10 curated MCQs on format specifiers, pointer arithmetic, operator precedence, short-circuit evaluation, storage classes, with instant explanations and score tracking.
- **C Debugging Arena**: Interactive in-browser C code editor with line numbers, bug locator, simulated Linux GCC compile & run, progressive hints, and solution loader.
- **Linux GCC Cheatsheet**: Compilation flags (`-Wall -Wextra -O2 -g`), GDB debugger reference, Valgrind memory leak checks, and Linux process signal codes.

---

## 🎨 Premium Design System & Micro-Interactions

1. 🖱️ **Mouse Cursor Trail:** Lightweight emerald particles with occasional gold highlights following the cursor and natural fade-out.
2. ✨ **Cursor-Reactive Background:** Subtle radial glow dynamically tracking mouse movement.
3. 🧲 **Magnetic Buttons:** Buttons gently move towards the cursor within proximity with smooth hover glow and physics return.
4. 💫 **Click Ripple:** Expanding light rings on mouse click.
5. 🪄 **Interactive Cards:** 3D perspective tilt towards cursor with dynamic glare/reflection highlight.
6. 🌊 **Scroll Reveal:** Smooth IntersectionObserver fade-and-slide on scroll.
7. 🌌 **Floating Particles:** Ambient dust/leaf micro-particles drifting slowly in the background.
8. ⚡ **Performance Safe:** Auto-disabled on touchscreens and when `prefers-reduced-motion` is enabled.

---

## 👥 Two-Member Team Configuration

The team details are centralized in `src/config/teamConfig.js`:

```javascript
// src/config/teamConfig.js
export const teamConfig = {
  teamName: "Agri Tech Titans",
  tagline: "Smart Farming. Better Decisions. Stronger Future.",
  teamSize: 2,
  members: [
    {
      id: 1,
      name: "Member 1 [Your Name]", // EDIT HERE
      role: "Team Leader & Full-Stack Project Lead",
      secondaryRole: "UI/UX & Interactive Systems Architecture"
    },
    {
      id: 2,
      name: "Member 2 [Your Partner's Name]", // EDIT HERE
      role: "Agriculture Features, C Lab Lead & Testing",
      secondaryRole: "Agronomic Data Models & Quality Assurance"
    }
  ]
};
```

---

## 🛠️ Technology Stack

- **Frontend:** React 18, Vite 5, Tailwind CSS, Lucide React, Canvas Confetti
- **Typography:** Plus Jakarta Sans, Inter, Fira Code (monospace for C Lab)
- **State & Storage:** React Hooks, HTML5 LocalStorage, Web Speech API (STT & TTS)
- **Build System:** Vite bundler (ESM)

---

## 💻 Installation & Local Setup

### Prerequisites
- Node.js (v18 or higher)
- npm (v9 or higher)

### Setup Commands (Windows / Linux / macOS)
```bash
# 1. Navigate to the project root directory
cd "d:/NEW HACKATHON"

# 2. Install dependencies
npm install
# Note for Windows PowerShell execution policy: Use cmd.exe /c "npm install" if script running is restricted.

# 3. Start local development server
npm run dev

# 4. Open in browser:
# http://localhost:5173
```

### Production Build
```bash
npm run build
npm run preview
```

---

## 🔍 Feature Realism & Boundary Matrix

| Feature | Implementation State | Boundary Disclosure |
|---|---|---|
| **Smart Crop Advisor** | Deterministic Heuristic Model | Rule-based agronomic algorithm; does not replace on-field soil tests. |
| **Plant Doctor** | Simulated Vision Engine | Pattern-matched demo presets; clearly labeled *Not a Medically Confirmed Diagnosis*. |
| **Weather Dashboard** | Dual Mode (Simulated + Live API) | Fallback realistic simulation + live Open-Meteo endpoint integration. |
| **Mandi Market Rates** | APMC Benchmark Data Layer | Realistic benchmark wholesale rates; ready for Agmarknet/e-NAM API key. |
| **Mitra AI Assistant** | Localized Agronomic Engine | Multilingual deterministic chat + Web Speech STT/TTS; clearly labeled as demo. |
| **My Farm Tasks & Notes** | Local Storage Persistence | Persisted in current browser session; does not require cloud database. |
| **C Practice Lab** | In-Browser Simulator | Independent C practice suite; separate from React code for Linux contest prep. |

---

## 🎤 3-Minute Hackathon Demonstration Script

- **0:00 – 0:30 (The Problem):** "Judges, smallholder farmers lose up to 30% of their net revenue juggling fragmented apps for weather, disease control, and mandi rates. AGRI TECH solves this with a unified digital companion."
- **0:30 – 1:00 (Interactive Experience):** "Notice our modern design system: subtle cursor physics, 3D card tilts, and ambient leaf particles. Everything is accessible, lightweight, and responsive."
- **1:00 – 2:00 (Core Demos):**
  1. *Crop Advisor:* Fill in the form or click a quick preset to see multi-factor cultivar scoring.
  2. *Plant Doctor:* Click 'Tomato Early Blight' and hit 'Analyze Leaf Sample' to observe the scanning laser and organic triage checklist.
  3. *Market Insights:* Switch between commodities and inspect the 7-day SVG trend lines and mandi comparisons.
- **2:00 – 2:30 (Farmer Productivity & Mitra AI):** Open *My Farm* to show task creation persisted locally, and open *Mitra AI* to demonstrate Kannada/Hindi voice assistance.
- **2:30 – 3:00 (Contest C Lab):** Click *C Practice Lab* in the navbar to showcase the 150-minute timer, prelim quiz, C debugging challenges, and Linux GCC guide complying with event rules.

---

## 📋 Testing Checklist

- [x] Sticky Navbar with working links and active section highlights
- [x] Mobile drawer toggle opens and closes smoothly
- [x] Cursor trail and reactive background run without lag
- [x] Reduced motion preference and touch device detection active
- [x] Smart Crop Advisor validates and generates sorted recommendations
- [x] AI Plant Doctor accepts file uploads and validates type (< 10MB)
- [x] Sample leaf presets trigger simulated scanner and triage report
- [x] Weather Dashboard switches regions and tests live Open-Meteo API
- [x] Market Insights SVG charts render with hover price tags
- [x] Smart Irrigation calculates pump duration and water savings %
- [x] My Farm adds, completes, and deletes tasks with `localStorage` sync
- [x] Community forum creates posts, likes, and comments
- [x] Knowledge Hub filters across 8 categories and bookmarks articles
- [x] Government schemes display verified links and eligibility criteria
- [x] Login modal validates inputs and provides 1-click demo accounts
- [x] Two editable member cards load directly from `teamConfig.js`
- [x] C Practice Lab 150-minute countdown timer starts, pauses, and resets
- [x] C Prelim Quiz scores answers and reveals compiler explanations
- [x] C Debugging Arena simulates GCC compilation and displays hints
