# Win95 Retro Suite

Generated from prompt: Win95 Demo App – Requirements & Concept Brief ================================================ M...

## About

This application was generated using GitHub Spark with the following prompt:

> Win95 Demo App – Requirements & Concept Brief ================================================ Main Purpose • Provide a nostalgic, interactive showcase of the classic Windows 95 look-and-feel—complete with familiar UI chrome, sound effects, and three built-in mini-apps (Calculator, Notepad, Minesweeper). • Serve as a playful demo or teaching tool that illustrates how early GUIs worked, while running seamlessly on modern devices. Target Platforms • Primary: Desktop (Windows, macOS, Linux) via Electron or Tauri—easiest path to cross-platform distribution. • Secondary (optional): Web build hosted on any browser, leveraging the same React/HTML/CSS codebase. • Stretch: Tablet-sized view with mouse/trackpad support (phone screens are possible but less authentic due to limited space). Key Functional Modules 1. Shell Window • Fixed 4:3 desktop‐style canvas with a taskbar, “Start” button, and a few desktop icons. • Draggable, resizable, overlappable child windows that mimic Win95 title bars, borders, and control buttons. • System tray clock that ticks in real time. 2. Start Menu • Two-column menu with Programs → Accessories → (Calculator, Notepad, Minesweeper). • “Shut Down” & “About Win95 Demo” entries for realism. 3. Calculator • Classic Win95 “Standard” calculator skin. • Supports basic arithmetic, keyboard input, and copy/paste to the clipboard. 4. Notepad • Multi-document-interface disabled; single-document text editor with menu bar (File, Edit, Format, Help). • Core actions: New, Open, Save, Save As, Print (can be stubbed), Word Wrap toggle, Font selector, Find/Replace. 5. Minesweeper • 9×9 Beginner, 16×16 Intermediate, 30×16 Expert grids. • Standard left-click uncover, right-click flag behavior. • High-score dialog with local storage persistence. 6. Settings / Themes (optional) • Toggle between Light Gray, Desert, and teal “Hotdog Stand” color schemes. • On/Off switches for startup sound and menu click sounds. 7. Persistence Layer • Local IndexedDB or file-system save to remember user prefs, window positions, and Notepad unsaved state. UI / UX Suggestions • Use the MS Sans Serif font or equivalent bitmap font for authenticity. • 8-bit icon set (ICO files) and pixel-perfect button sprites. • Cursor changes: default arrow, I-beam for text, hourglass during loading, etc. • Animations should be snappy but minimal—no modern easing curves. • Provide a resizable outer frame so users can “fullscreen” the fake desktop if desired. • Keyboard shortcuts mirroring Win95 originals (e.g., Ctrl+N, Alt+F4). • Include the iconic startup chime on first launch (skip on mobile browsers). Technical Stack (recommended) • React + TypeScript for UI components. • Styled-components or SASS for theming with tokenized Win95 color palette. • Electron or Tauri for desktop packaging; Vite as the build tool. • Optional: use existing OSS libraries like “react95” for accelerated styling. MVP Checklist 1. Launch app → see desktop, Start button, system clock. 2. Open Calculator, Notepad, Minesweeper from Start Menu. 3. Each mini-app fully functional and independently windowed. 4. Windows can be moved, resized, minimized, maximized, closed. 5. Settings stored locally; high scores persist. 6. Packaged installers for Windows (.exe), macOS (.dmg), Linux (.AppImage). Stretch Goals • Drag-and-drop files onto Notepad icon to open. • Simulated BSOD Easter egg. • Internet Explorer stub that opens a “You are offline” vintage error. • Networked multiplayer Minesweeper race mode via WebSockets. This spec should give designers and developers a clear, streamlined blueprint to create a delightful Win95 throwback app while ensuring the initial scope stays manageable.

## Getting Started

Follow the instructions below to run this application locally.

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd win95-retro-suite
```

2. Install dependencies:
```bash
npm install
```

3. Run the application:
```bash
npm start
```

## Generated with GitHub Spark

This application was automatically generated and deployed using [GitHub Spark](https://github.com/spark).
