<div align="center">

# 🚀 Nexo: Turn Code into Stories You Can See and Hear

**Transform cold, static code into a living, breathing story you can see and hear.**

<img src="client/public/logo-white.png" alt="Nexo Logo" width="200" style="border-radius: 20px;" />

<br />

[![Made with React](https://img.shields.io/badge/Made%20with-React-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
[![Powered by Gemini](https://img.shields.io/badge/Powered%20by-Gemini-4285F4?style=for-the-badge&logo=google)](https://ai.google.dev/)
[![Voice by ElevenLabs](https://img.shields.io/badge/Voice-ElevenLabs-000000?style=for-the-badge)](https://elevenlabs.io/)

<br />

[![🏆 View on Devpost](https://img.shields.io/badge/🏆%20View%20Project%20on-Devpost-003E54?style=for-the-badge&logo=devpost)](https://devpost.com/software/nexo-the-audio-visual-gps-for-your-codebase)

<br />

[Demo](#-demo) • [Features](#-features) • [Tech Stack](#-tech-stack) • [Installation](#-installation) • [Usage](#-usage)

</div>

---

## 📖 Table of Contents

- [💡 Inspiration](#-inspiration)
- [❓ What it Does](#-what-it-does)
- [✨ Features](#-features)
- [🛠️ How We Built It](#️-how-we-built-it)
- [🏗️ Tech Stack](#️-tech-stack)
- [🎯 Architecture](#-architecture)
- [🚩 Challenges We Faced](#-challenges-we-faced)
- [🧠 What We Learned](#-what-we-learned)
- [🚀 Installation](#-installation)
- [🔮 What's Next](#-whats-next)
- [👥 Team](#-team)
- [📄 License](#-license)

---

## 💡 Inspiration

Every developer has faced the **"Wall of Code"** nightmare: joining a massive legacy project with zero documentation and thousands of interconnected functions. Hours turn into days as you trace function calls, decipher cryptic variable names, and try to understand the mental model of developers who left years ago.

**We realized that while we have powerful tools to _write_ code, we lack intuitive tools to _experience_ it.**

Traditional documentation is:

- 📝 Often outdated or non-existent
- 🥱 Boring to read and hard to maintain
- 🧩 Disconnected from the actual code structure
- 🚫 Inaccessible for visual or auditory learners

We built **Nexo** to turn cold, static text into a **living, breathing story** that you can both **see and hear**—a revolutionary approach to code onboarding that reduces weeks of confusion into minutes of clarity.

---

## ❓ What it Does

**Nexo** is an AI-powered code documentation and visualization platform that transforms any codebase into an interactive, multi-modal learning experience.

### The Nexo Experience:

1. **🔗 Paste a Repository URL**  
   Simply provide a GitHub/GitLab link to any project.

2. **🧠 AI Analysis**  
   Our Gemini-powered engine analyzes the code structure, dependencies, and logic flow.

3. **📊 Visual Flow Generation**  
   See your codebase as an interactive dependency graph with modules, functions, and their relationships.

4. **🎙️ Audio Narration**  
   Listen to AI-generated "Code Podcasts" that explain each file's purpose, logic, and integration points—perfect for commuting, exercising, or simply giving your eyes a rest.

5. **🗄️ Instant Access**  
   Once analyzed, the documentation is cached and available instantly for your entire team.

---

## ✨ Features

### 🎯 Core Features

- **🔍 Smart Analysis**  
  Deep code understanding powered by Gemini API, extracting functions, classes, and their relationships.

- **🎧 Code Podcasts**  
  AI-narrated explanations of code logic in natural, human language—learn on the go.

- **📱 Responsive Design**  
  Works seamlessly on desktop, tablet, and mobile devices.

### 🎨 Developer Experience

- **🚀 Zero Configuration**  
  No SDKs to install, no config files to write—just paste and analyze.

- **🔐 Secure & Private**  
  Your code is processed securely and never stored permanently without permission.

- **👥 Team Collaboration**  
  Share generated documentation links with your entire team instantly.

- **📈 Usage Analytics**  
  Track which parts of your codebase need better documentation based on view counts.

---

## 🛠️ How We Built It

Nexo is a sophisticated orchestration of cutting-edge AI, cloud infrastructure, and modern web technologies:

### **🧠 Intelligence Layer**

The **Gemini API** acts as our senior architect, performing deep static analysis to:

- Extract function signatures, classes, and imports
- Map dependencies and call graphs
- Generate human-readable summaries of code logic
- Structure data into JSON-friendly formats for visualization

### **🎙️ Audio Synthesis Layer**

**ElevenLabs** transforms technical analysis into natural narration:

- Converts code summaries into conversational scripts
- Generates high-quality, human-like voice audio
- Creates segmented "chapters" for different modules
- Optimizes audio compression for web delivery


### **🗄️ Data Layer**

- **MongoDB Atlas:** Stores graph metadata, audio links, and analysis results
- **Caching Strategy:** Once analyzed, subsequent loads are near-instantaneous
- **Scalable Schema:** Optimized for quick lookups and graph traversal queries

### **🎨 Frontend Layer**

- **React 18 + TypeScript:** Type-safe, component-based architecture
- **Vite:** Lightning-fast development and optimized production builds
- **D3.js/Cytoscape:** Interactive graph visualizations with physics simulations
- **CSS Modules:** Scoped styling for maintainable design

---

## 🏗️ Tech Stack

### **Frontend**

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite&logoColor=white)

- **React 18** with Hooks and Context API
- **TypeScript** for type safety
- **Vite** for blazing-fast builds
- **CSS Modules** for scoped styling

### **Backend**

![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104-009688?logo=fastapi&logoColor=white)

- **FastAPI** for high-performance REST APIs
- **Pydantic** for data validation
- **JWT Authentication** for secure user sessions

### **AI & ML**

![Gemini](https://img.shields.io/badge/Gemini-API-4285F4?logo=google&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-Voice-000000)

- **Google Gemini API** for code analysis
- **ElevenLabs API** for voice synthesis

### **Infrastructure**

![Docker](https://img.shields.io/badge/Docker-24-2496ED?logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white)

- **MongoDB Atlas** for database
- **Docker/Podman** for containerization

---

## 🎯 Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                         User Browser                         │
│  ┌────────────┐  ┌────────────┐  ┌─────────────────────┐   │
│  │   React    │  │   Graph    │  │   Audio Player      │   │
│  │    App     │  │  Renderer  │  │  (ElevenLabs)       │   │
│  └────────────┘  └────────────┘  └─────────────────────┘   │
└─────────────────────────────────────────────────────────────┘
                           │
                           │ HTTPS
                           ▼
┌─────────────────────────────────────────────────────────────┐
│              Cloudflare Workers (Edge Layer)                 │
│  • Static Asset Delivery  • API Proxying  • Caching         │
└─────────────────────────────────────────────────────────────┘
                           │
                           │
        ┌──────────────────┴──────────────────┐
        │                                      │
        ▼                                      ▼
┌──────────────────┐                  ┌──────────────────┐
│  FastAPI Server  │                  │  MongoDB Atlas   │
│   (Vultr VM)     │◄────────────────►│   (Database)     │
│                  │                  │                  │
│  ┌────────────┐  │                  │  • Graph Data    │
│  │   Gemini   │  │                  │  • Audio URLs    │
│  │    API     │  │                  │  • User Data     │
│  └────────────┘  │                  │  • Cache Layer   │
│                  │                  └──────────────────┘
│  ┌────────────┐  │
│  │ ElevenLabs │  │
│  │    API     │  │
│  └────────────┘  │
└──────────────────┘
```

---

## 🚩 Challenges We Faced

### **1. 🕸️ Graph Complexity**

**Problem:** Large codebases create overwhelming "spaghetti code" visualizations with thousands of interconnected nodes.

**Solution:**

- Implemented AI-driven clustering to group related modules
- Created hierarchical views with drill-down capabilities
- Added intelligent filtering to show only relevant dependencies
- Used force-directed layouts with customizable physics

### **2. 🧩 Context Window Limitations**

**Problem:** Codebases often exceed the token limits of AI models (even Gemini's extended context).

**Solution:**

- Developed smart chunking logic that preserves semantic relationships
- Prioritized entry points and high-traffic functions
- Implemented incremental analysis for large repositories
- Created a summary-first approach: analyze file structure before diving into details

### **3. ⚡ Real-time Audio Synthesis**

**Problem:** ElevenLabs produces high-quality audio but has processing latency that could ruin UX.

**Solution:**

- Implemented asynchronous job queues with progress indicators
- Pre-generated audio for popular repositories
- Offered text-to-speech fallback for instant (lower quality) narration
- Cached all generated audio in MongoDB and CDN
  
---

## 🧠 What We Learned

Building Nexo taught us the transformative power of **Multi-Modal Onboarding**.

### **The Science Behind It**

We discovered that combining visual metrics with auditory explanations significantly reduces **cognitive load** compared to reading raw text. The formula we observed:

$$
L_c \approx \frac{T_x}{\text{Visual Flow} \cdot \text{Audio Context}}
$$

Where:

- $L_c$ = Cognitive Load (mental effort required)
- $T_x$ = Complexity of raw text documentation

**Key Insights:**

1. **🎨 Visual Learning:** 65% of people are visual learners—graphs leverage spatial memory
2. **🎧 Auditory Reinforcement:** Hearing explanations while seeing structure creates dual encoding
3. **⚡ Reduced Context Switching:** No need to jump between files—see the big picture first
4. **🧠 Pattern Recognition:** Visual patterns reveal architectural insights text can't convey

### **Technical Lessons**

- **Prompt Engineering is an Art:**  
  We iterated dozens of times to ensure Gemini outputs strictly valid JSON for real-time rendering.

- **AI Hallucination Mitigation:**  
  Validate all AI outputs against the actual code structure—never trust blindly.

- **Caching is King:**  
  A well-designed cache strategy makes a 30-second analysis feel instant on repeat visits.

- **UX > Features:**  
  We cut 40% of planned features to polish the core experience—less is more.

---

## 🚀 Installation

### **Prerequisites**

- Node.js 18+ and npm/yarn
- Python 3.11+
- Docker or Podman
- MongoDB instance (or MongoDB Atlas account)
- API Keys:
  - Google Gemini API
  - ElevenLabs API

### **Clone the Repository**

```bash
git clone https://github.com/Hacktown-BSB/Nexo.git
cd Nexo
```

### **Backend Setup**

```bash
cd server

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cat > .env << EOF
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
JWT_SECRET=your_secret_key
EOF

# Run the server
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```

### **Frontend Setup**

```bash
cd client

# Install dependencies
npm install

# Create .env file
cat > .env << EOF
VITE_API_URL=http://localhost:8000
EOF

# Run development server
npm run dev
```

### **Docker Compose (Recommended)**

```bash
# From project root
docker-compose up --build

# Or with Podman
podman-compose up --build
```

The application will be available at:

- Frontend: `http://localhost:5173`
- Backend API: `http://localhost:8000`
- API Docs: `http://localhost:8000/docs`

---

## 🔮 What's Next

### **Roadmap**

- [ ] **🔌 IDE Integrations**  
      VS Code, JetBrains, and Vim plugins for in-editor visualizations

- [ ] **📝 Auto-Generated Docs**  
      Export to Markdown, HTML, or PDF with embedded graphs

- [ ] **👥 Collaboration Features**  
      Annotate graphs, leave comments, track team onboarding progress

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Google Gemini** for powerful code analysis capabilities
- **ElevenLabs** for natural-sounding voice synthesis
- **MongoDB Atlas** for scalable database solutions
- The open-source community for inspiration and tools

---

<div align="center">

**Star ⭐ this repo if you find it useful!**

</div>
