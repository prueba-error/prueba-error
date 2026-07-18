# GitHub Profile README Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create a high-quality, professional, and personal GitHub profile README using a "Laboratory Logbook" theme that showcases Diego Guaraz's (@prueba-error) project suite, commissions, academic work, productivity tools, and learnings.

**Architecture:** A single, structured, well-formatted `README.md` file in the root of the repository, leveraging clean markdown, code-block headers, custom bullet formats, and links.

**Tech Stack:** Markdown (GitHub Flavored Markdown).

## Global Constraints
- Maintain the "Laboratory Logbook" theme throughout the copy.
- The language of the README must be English.
- Do not commit any changes to git yet (work will be checked and committed by the user later).
- Project details and categories must align exactly with `docs/superpowers/specs/2026-07-18-github-profile-readme-design.md`.

---

### Task 1: Initialize README & Header Section

**Files:**
- Create: `README.md`

**Interfaces:**
- Produces: Header markdown structure and Manifesto content in the root `README.md`.

- [ ] **Step 1: Create README.md with Header & monospaced Status HUD**
  Create the file with the title, subtitle, status block, and horizontal divider.
  ```markdown
  # Diego Guaraz // @prueba-error
  > **Location:** Mar del Plata, Argentina 🌊
  
  ```text
  [experiment-state: active] [core-focus: desktop-utility-engineering] [current-lab-mode: DIY]
  ```
  
  ---
  ```
- [ ] **Step 2: Add The Manifesto section**
  Add the narrative paragraph about the laboratory mindset and trial-and-error compile loop.
  ```markdown
  ### 🧪 The Manifesto
  
  "I treat software development as a laboratory. I believe the best way to understand how things work under the hood is to build them, break them, and iterate. To me, `prueba-error` (trial and error) is more than just a username—it's my default compilation loop.
  
  I build DIY solutions to solve friction, adopting new tools and AI-driven workflows to automate the mundane and focus on building high-performance utilities."
  
  ---
  ```
- [ ] **Step 3: Verify markdown formatting**
  Verify that the README.md exists and has the correct layout up to the Manifesto.

---

### Task 2: Implement Project Logbook Showcase

**Files:**
- Modify: `README.md`

**Interfaces:**
- Consumes: Existing `README.md` from Task 1.
- Produces: Formatted showcase sections for Diego's projects: Rust Suite, Web Projects, and Productivity Hacks.

- [ ] **Step 1: Append The Windows Rust Suite section**
  Add the header and the three projects with their descriptions and "What I Learned" subheadings.
  ```markdown
  ### 📁 Project Logbook (Showcase)
  
  #### 🦀 The Windows Rust Suite (Active Experiments)
  *A suite of native, keyboard-driven Windows desktop utility tools written in Rust.*
  
  *   **[tactile-win](https://github.com/prueba-error/tactile-win)** | Keyboard-driven window tiling tool (inspired by GNOME's Tactile).
      *   *What I Learned:* Win32 hooks, native window positioning, and interfacing Rust with lower-level OS APIs.
  *   **[win-glide](https://github.com/prueba-error/win-glide)** | Move/resize active windows using keyboard shortcuts.
      *   *What I Learned:* Precise cursor simulation, input event capturing, and shell APIs.
  *   **[win-float](https://github.com/prueba-error/win-float)** | Adjust window transparency and pin always-on-top using a modal overlay HUD.
      *   *What I Learned:* Custom rendering of HUD overlays, capture hook life cycles, and Windows API shell hooks.
  ```
- [ ] **Step 2: Append Web Projects section**
  Add the React commission project and the local college project.
  ```markdown
  #### 🌐 Web Projects
  
  *   **[taura-birra-react](https://github.com/prueba-error/taura-birra-react)** | Landing page for Cervecería Taura (La Plata) built using React (Commission).
      *   *What I Learned:* Meeting client specs, styling responsive layouts, and managing modular component lifecycles in React.
  *   **[eventos-dsw](https://github.com/prueba-error/eventos-dsw)** | Local event billboard website for Mar del Plata (College project).
      *   *What I Learned:* Database integration, routing architecture, and solving real-world local community problems with software.
  ```
- [ ] **Step 3: Append Productivity & Workflow Hacks section**
  Add the AutoHotkey and Chrome extension projects.
  ```markdown
  #### 🔧 Productivity & Workflow Hacks
  
  *   **[autohotkey](https://github.com/prueba-error/autohotkey)** | A collection of personal AHK v2.0 scripts.
      *   *What I Learned:* Rapid script scripting, macro remapping, and refining OS-level workflow speed.
  *   **[one-click-logout](https://github.com/prueba-error/one-click-logout)** | Chrome extension for one-click logout from user-specified websites.
      *   *What I Learned:* Chrome WebExtension lifecycle, content script injection, and cross-site DOM events.
  
  ---
  ```
- [ ] **Step 4: Verify formatting**
  Inspect file to confirm project list matches specification.

---

### Task 3: Implement Toolkit and Visual Placeholders

**Files:**
- Modify: `README.md`

**Interfaces:**
- Consumes: Existing `README.md` from Task 2.
- Produces: The final section of `README.md` detailing the Toolkit (skills) and placeholders for stats graphs.

- [ ] **Step 1: Append The Lab Toolkit section**
  Add categorized list of instruments, environments, and amplifiers.
  ```markdown
  ### 🛠️ The Lab Toolkit
  
  *   **Primary Instruments:** Rust, JavaScript / TypeScript, React, HTML / CSS, AutoHotkey v2
  *   **Target Environments:** Windows API, Web Browsers, CLI / Shells
  *   **Workflow Amplifiers:** Git, GitHub Actions, AI-assisted development
  
  ---
  ```
- [ ] **Step 2: Append Stats & Contribution Graph placeholder**
  Add a placeholder section containing commented-out structure for stats cards and visual contribution widgets.
  ```markdown
  ### 📊 Laboratory Analytics
  <!--
  This section is reserved for future analytics (contribution graphs and language stats cards).
  Uncomment and configure the links below when ready to activate:
  
  [![Diego's GitHub stats](https://github-readme-stats.vercel.app/api?username=prueba-error&show_icons=true&theme=transparent)](https://github.com/anuraghazra/github-readme-stats)
  [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=prueba-error&layout=compact&theme=transparent)](https://github.com/anuraghazra/github-readme-stats)
  -->
  
  *Analytics components are currently offline (waiting for calibration).*
  ```
- [ ] **Step 3: Final inspection**
  Verify the complete `README.md` has no placeholders, broken links, or syntax issues.
