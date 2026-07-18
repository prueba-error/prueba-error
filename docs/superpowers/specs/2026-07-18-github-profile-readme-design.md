# Design Specification: GitHub Profile README for Diego Guaraz (@prueba-error)

This specification defines the copy, structure, and style choices for Diego Guaraz's GitHub profile README.

## Goal
To create a unique, memorable, and premium profile README designed around a "Laboratory Logbook" concept. It highlights Diego's systems programming, web development, and automation skills while emphasizing learning and pragmatism through building (DIY).

## Core Concepts & Theme
- **Username Alignment:** Leans into `@prueba-error` (trial and error) as an engineering methodology.
- **Narrative Philosophy:** Emphasizes DIY, experimentation, and learning by building and breaking systems.
- **Project Structure:** Grouped by category (Rust utilities suite, college project, commissions, productivity scripting, browser utility) to show depth and range.
- **Aesthetic:** Minimalist, clean markdown with high-contrast elements, custom status-bar widgets, and clean code blocks.

---

## 1. Structure and File Layout

The final file will be created at:
- `README.md` (root directory)

---

## 2. Content & Copy Details

### Header
- Title: `Diego Guaraz // @prueba-error`
- Subtitle: `Software Developer based in Mar del Plata, Argentina 🌊`
- Status bar component (using monospaced text to look like a terminal HUD):
  ```text
  [experiment-state: active] [core-focus: desktop-utility-engineering] [current-lab-mode: DIY]
  ```

### The Manifesto
A short paragraph framing Diego's relationship with software as a series of active experiments:
> "I treat software development as a laboratory. I believe the best way to understand how things work under the hood is to build them, break them, and iterate. To me, `prueba-error` (trial and error) is more than just a username—it's my default compilation loop.
>
> I build DIY solutions to solve friction, adopting new tools and AI-driven workflows to automate the mundane and focus on building high-performance utilities."

### Project Logbook (Showcase)
This section organizes Diego's work. Crucially, each project specifies what was built and what was *learned*.

1. **The Windows Rust Suite**
   *A suite of native, keyboard-driven Windows desktop utility tools written in Rust.*
   - **`tactile-win`**: Keyboard-driven window tiling tool (inspired by GNOME's Tactile).
     - *Learned:* Win32 hooks, native window positioning, and interfacing Rust with lower-level OS APIs.
   - **`win-glide`**: Move/resize active windows using keyboard shortcuts.
     - *Learned:* Precise cursor simulation, input event capturing, and shell APIs.
   - **`win-float`**: Adjust window transparency and pin always-on-top using a modal overlay HUD.
     - *Learned:* Custom rendering of HUD overlays, capture hook life cycles, and Windows API shell hooks.

2. **Web Projects**
   - **`taura-birra-react`**: Landing page for Cervecería Taura (La Plata) built using React (Comission).
     - *Learned:* Meeting client specs, styling responsive layouts, and managing modular component lifecycles in React.

   - **`eventos-dsw`**: Local event billboard website for Mar del Plata (College project).
     - *Learned:* Database integration, routing architecture, and solving real-world local community problems with software.

4. **🔧 Productivity & Workflow Hacks**
   - **`autohotkey`**: A collection of personal AHK v2.0 scripts.
     - *Learned:* Rapid script scripting, macro remapping, and refining OS-level workflow speed.
   - **`one-click-logout`**: Chrome extension for one-click logout from user-specified websites.
     - *Learned:* Chrome WebExtension lifecycle, content script injection, and cross-site DOM events.

### The Lab Toolkit (Tech Stack)
- **Primary Instruments:** Rust, JavaScript / TypeScript, React, HTML / CSS, AutoHotkey v2.
- **Target Environments:** Windows API, Web Browsers, CLI / Shells.
- **Workflow Amplifiers:** Git, GitHub Actions, AI-assisted development.

### Placeholder & Stats
- A comment section with pre-formatted markup for adding a contribution graph and stats card in the future.

---

## 3. Visual Styling
- Use clear visual dividers (`---`).
- Apply code formatting to key terms (e.g., `Rust`, `Win32`, `React`).
- Keep emojis strategic and minimal to maintain a professional yet personal "engineering notebook" aesthetic.
