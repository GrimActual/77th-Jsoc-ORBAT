77th-Jsoc-ORBAT
Easy to use Orbat mapper. by Grim

Overview
77th-Jsoc-ORBAT is a dedicated tactical order of battle (ORBAT) mapping and unit planning application built for the 77th JSOC military simulation unit. It provides mission planners and unit leaders with an intuitive interface to rapidly construct, visualize, and distribute tactical command hierarchies, team structures, and operational assets.

Features
MIL-STD-2525 / Tactical Symbology: Render standard military map symbols using integrated milsymbol.js libraries.

Custom Asset Catalog: Built-in roster and vehicle asset catalog tailored for modern combined-arms operations.

Interactive Canvas: Drag-and-drop planning interface for building complex command trees, squad layouts, and fireteam configurations.

Data Persistence & Backups: Save, export, and restore ORBAT layout selections and custom unit configurations.

Desktop & Mobile Support: Cross-platform layout rendering optimized for desktop operations and quick mobile viewing.

Getting Started
Prerequisites
Operating System: Windows 10 or 11 (64-bit)

Runtime: Pre-packaged standalone distribution (no separate Node.js installation required for end users)

Installation
Go to the Releases section of this repository.

Download the latest release package (Everon-ORBAT-Planner-v2.2.0-Windows.zip).

Extract the contents of the .zip archive to a local folder on your computer.

Run Everon ORBAT Planner.exe to launch the application.

Quick Start Guide
Launch App: Double-click Everon ORBAT Planner.exe.

Select Faction / Framework: Choose your operating unit parameters from the side panel.

Build Hierarchy: Drag unit templates onto the canvas to construct your ORBAT hierarchy.

Customize Assets: Click on individual nodes to modify callsigns, assigned assets, personnel numbers, and tactical roles.

Export / Save: Save your plan locally or export images for mission briefings and briefing documents.

Repository Structure
Plaintext
├── index.html                  # Main application UI layout
├── planner.js                  # Core planning logic and state management
├── planner-core.js             # Calculations and symbol generation engine
├── planner.css                 # Interface styling and canvas layout
├── main.js                     # Electron main process entry point
├── preload.js                  # IPC bridge and preload scripts
├── presentation.js             # Viewport and presentation controls
├── asset-catalog.json          # Equipment, vehicle, and unit symbol definitions
├── vendor/                     # Third-party libraries (milsymbol.js)
├── CHANGELOG.md                # Version release history
└── QUICK-START.md              # User quick-reference guide
Unit Usage Notice
This repository and its distribution builds are restricted for 77th JSOC operational use and internal unit planning.

Created by Grim
