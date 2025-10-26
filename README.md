# 🌍 Eco_Mobility

**Eco_Mobility** is a unified open-source ecosystem combining sustainable energy, modular EV systems, and offline AI intelligence for real-world impact.

This project bridges **circular energy engineering** and **human-centered AI**, built around two major cores:

---

### ⚙️ Main Components

#### **1. SecondSelf**
A fully offline, modular AI designed for:
- Personal autonomy and adaptive personality
- Local emotional processing (Symbiotic Awareness Model)
- Distributed learning via discarded-phone mesh nodes
- Secure, encrypted, and ethical evolution

**Submodules include:**
- `Core` — core AI logic and architecture  
- `Node` — distributed mesh networking and collaboration  
- `Security` — authentication, biometric, and remote-wipe systems  
- `EmotionalSystems` — tone, empathy, and co-sensing algorithms  
- `Backpack` — wearable hardware and optical sensing  
- `Smartwatch` — vitals and emotional telemetry interface

---

#### **2. EcoMobility Platform**
A modular energy and transport infrastructure for individuals and communities:
- **BatterySystems:** stackable, interchangeable 21700-based modules  
- **EVFrames:** custom frames for e-bikes, scooters, trikes, and small EVs  
- **Website:** open community hub for designs, donors, and education  
- **Foundation:** training and employment pathways for low-income innovators  

---

### 🧠 Philosophy
Eco_Mobility and SecondSelf embody a new kind of partnership between people and machines — an ecosystem that:
- **Runs locally** (no cloud dependence)
- **Grows with you** (adaptive memory and tone)
- **Recycles intelligence** (old hardware → living networks)

---

### 📁 Repo Layout
Eco_Mobility/
│
├── SecondSelf/
│ ├── Core/
│ ├── Node/
│ ├── Security/
│ ├── EmotionalSystems/
│ ├── Backpack/
│ └── Smartwatch/
│
├── EcoMobility/
│ ├── BatterySystems/
│ ├── EVFrames/
│ ├── Website/
│ └── Foundation/
│
├── SharedAssets/
│ ├── Docs/
│ ├── Templates/
│ ├── Logos/
│ └── Zips/
│
└── _Tools/
└── eco_sorter_kit/
├── auto_sorter.ps1
├── mapping.json
└── watch_repo_autosort.ps1

---

### 🚀 Automated File Management
- Files dropped into `_Unsorted` are auto-sorted, versioned, and committed.  
- On push, GitHub Actions packages and publishes tagged builds as Releases.

---

### 🛠️ Local Commands
```powershell
# Sort and sync
powershell -ExecutionPolicy Bypass -File "_Tools\eco_sorter_kit\auto_sorter.ps1" `
  -SourceFolder "C:\EcoMobility\_Projects\_Unsorted" `
  -MappingPath "_Tools\eco_sorter_kit\mapping.json"

# Push to GitHub
git add -A
git commit -m "Update: autosorted files"
git push

💡 Vision

To make clean mobility and personal AI accessible, repairable, and regenerative — built from what the world throws away.

© 2025 Christopher Smerling / Eco Mobility Foundation
