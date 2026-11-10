# Lorenzo Maggi, PhD — Personal Portfolio & Academic Showcase

[![Website](https://img.shields.io/badge/Website-lorenzo--maggi.github.io-blue?style=flat&logo=googlechrome)](https://lorenzo-maggi.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Lorenzo%20Maggi-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/lorenzo-maggi-398340209/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Citations-4285F4?style=flat&logo=googlescholar)](https://scholar.google.it/citations?user=MI3KMgwAAAAJ)
[![GitHub](https://img.shields.io/badge/GitHub-Lorenzo--Maggi-181717?style=flat&logo=github)](https://github.com/Lorenzo-Maggi)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

Source code for the personal portfolio website of **Lorenzo Maggi, PhD** — R&D Biomedical & Robotics Engineer specializing in surgical robotics (KUKA LBR Med), knee biomechanics, spinal implant design, and medical device regulations.

🌐 **Live Website:** [https://lorenzo-maggi.github.io/](https://lorenzo-maggi.github.io/)

---

## 🛠️ About Me

Hands-on biomedical & robotics engineer (PhD) with extensive experience in surgical robotics, joint biomechanics, mechanical design, and ex-vivo experimentation. Strong maker mindset (mechanics, electronics, 3D printing) combined with a focus on translational research and medical device compliance.

* **Current Role:** R&D Spine Implants Engineer at [Clover Orthopedics Srl](https://cloverorthopedics.com)
* **PhD in Industrial Engineering (cum Laude):** University of Florence & [Orthokey Italia Srl](https://orthokey.com)
* **Professional Engineering License:** Fully qualified Professional Engineer in Italy (Section A, Industrial Engineering)

---

## 🔬 Featured Projects

| Project | Description | Tags |
| :--- | :--- | :--- |
| **[Knee-Lax](https://lorenzo-maggi.github.io/project/knee-lax/)** | Robotic system for intra-operative knee laxity assessment using KUKA LBR Med & NDI optical tracker | `robotics`, `research` |
| **[Robin® System](https://lorenzo-maggi.github.io/project/robin/)** | Active robotic assistant for Total Knee Arthroplasty (TKA) compliant with ISO 13485 & IEC 62304 | `robotics`, `research` |
| **[Knee-Ki](https://lorenzo-maggi.github.io/project/knee-ki/)** | Open-chain kinematic knee simulator with closed-loop PID quadriceps tendon actuation | `robotics`, `research` |
| **[Mouse Pose Estimation](https://lorenzo-maggi.github.io/project/mouse-dlc/)** | Markerless facial expression tracking via DeepLabCut in collaboration with CNR-IN | `research` |
| **[Normothermic Perfusion](https://lorenzo-maggi.github.io/project/normothermic-perfusion/)** | Organ maintenance platform for ex-vivo liver preservation and physiological monitoring | `research`, `maker` |
| **[VR Hand Exoskeleton](https://lorenzo-maggi.github.io/project/flexo/)** | Unity 3D physics-based indentation estimation for kinesthetic hand exoskeleton feedback | `robotics`, `research` |
| **[Bench Power Supply](https://lorenzo-maggi.github.io/project/psu/)** | Upcycled 450W ATX computer power supply into a programmable laboratory bench tool | `maker` |
| **[DIY Sous-Vide Roner](https://lorenzo-maggi.github.io/project/roner/)** | 3D printed immersion circulator with custom PID temperature control | `maker` |

▶️ *Watch the 3-minute thesis overview on YouTube:* **[My PhD in 3 Minutes](https://youtu.be/5DqW-fMwWBU)**

---

## 💻 Tech Stack

* **Programming & Control:** Python, C/C++, Java, MATLAB/Simulink, Arduino, ROS2
* **Robotics & Hardware:** KUKA LBR Med 14 R820, NDI Polaris optical tracking, Microcontrollers, Force/Torque sensors
* **CAD & Prototyping:** SolidWorks, 3D Printing (FDM/SLA), SMD soldering, Rapid electromechanical prototyping
* **Regulatory & Quality:** EU MDR 2017/745, ISO 13485, ISO 14971, IEC 60601/80601, IEC 62304

---

## 🚀 Building Locally

The site is built with [Hugo](https://gohugo.io/) and [Hugo Blox](https://hugoblox.com/) with Tailwind CSS.

### Prerequisites
* [Hugo Extended](https://gohugo.io/installation/) (v0.140+)
* [Go](https://golang.org/) (1.19+)
* [Node.js](https://nodejs.org/) (v20+) & [pnpm](https://pnpm.io/)

### Local Development Server
```bash
# Clone the repository
git clone https://github.com/Lorenzo-Maggi/Lorenzo-Maggi.github.io.git
cd Lorenzo-Maggi.github.io

# Install Node dependencies
pnpm install

# Run local development server
pnpm dev
# or
hugo server --disableFastRender
```

Visit `http://localhost:1313/` in your browser.

### Production Build
```bash
pnpm build
```

The site automatically builds and deploys to GitHub Pages on every push to `main` via GitHub Actions.

---

## 📄 License

Content © 2026 Lorenzo Maggi. Licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).
Code and templates licensed under the [MIT License](LICENSE.md).
