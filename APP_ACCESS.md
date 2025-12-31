### ?? Agent Protocol: Central Port Registry System

**Objective**: This file is the **SINGLE SOURCE OF TRUTH** for all application ports on this machine.

**When you encounter this file:**

1. **Read-Only for Verification**: If just checking ports, read the table.
2. **Assigning New Ports**:
    * Find the highest used port in the "Master Port Registry".
    * Assign the next available port(s) to the new application.
    * **IMMEDIATELY ADD** the new app to this table.
    * **SAVE** this file.

**When you are in a Project Folder (e.g., c:\Users\SREphoto\Reia):**

1. **CHECK HERE FIRST**: Always read R:\Antigravity Multiple\_CENTRAL_REGISTRY\APP_ACCESS.md before assigning ports.
2. **UPDATE HERE**: If you assign a port, update THIS file.
3. **SYNC LOCAL**: You may copy this file to the project folder as APP_ACCESS.md for local reference, or create a stub pointing here.

# ?? Global Application Access & Port Registry

## ?? Master Port Registry

| Application Name | Frontend Port | Backend Port | Port Details | Description |
|------------------|---------------|--------------|--------------|-------------|
| **WellNest (V1)** | 5173 | 3000 | 5173: Frontend, 3000: Backend API | Original App |
| **WordSlide** | 3001 | - | 3001: Game Interface | Word Puzzle Game |
| **storyweaver** | 3002 | 3003 | Live on Render: <https://storyweaver-api.onrender.com> | [Live App](https://srephoto.github.io/storyweaver/#/) - Fully Functional |
| **HomePlanner** | 3004 | - | 3004: Frontend (Vite) | AI Home Design Tool |
| **SREdesigns** | 3005 | - | 3005: Frontend (Vite) | Professional Portfolio |
| **WellNest V2 (B2GTHR)** | 3009 | - | 3009: Reimaged UI (React/Vite) | New Tab-based Version (Frontend Only) |
| **Flirt Game** | 3010 | - | 3010: Frontend (Vite) | Character Connection Quest |
| **Reia** | 3011 | 3011 | 3011: Game Server (Rust/Godot) | Action-Adventure RPG |
| **Diablo JS Remastered** | 3012 | - | 3012: Frontend (Vite) | Isometric ARPG Engine |
| **TopGunPrompter** | 3020 | - | 3020: Frontend (Vite) | Top Gun & Blockbuster Style Prompter |
| **Interactive Launchpad** | 3021 | - | 3021: Frontend (Vite) | AI Deployment Guide & Toolset |
| **IodineGBA** | 3023 | - | 3023: Frontend (http-server) | JS GameBoy Advance Emulator |
| **Dynamic Probability** | 3024 | - | 3024: Streamlit | Advanced Probability & Stats Suite |
| **Gemini-Turbo-Outrun** | 3025 | - | 3025: Frontend (Vite) | Retro Outrun Style Racer |
| **MadMenPromptCreator** | 3026 | - | 3026: Frontend (Vite) | Mad Men Fashion Styling App |
| **3D Asset Studio** | 3027 | - | 3027: Frontend (Vite) | 3D Model Viewer & Manager |
| **Tetris** | 3028 | - | 3028: Frontend (Vite) | Classic Tetris Clone |
| **Fantasy Map Designer** | 3029 | - | 3029: Frontend (Vite) | World Map Creation Tool |
| **Iconify** | 3030 | - | 3030: Frontend (Vite) | Icon Management System |
| **Punchline Master** | 3031 | - | 3031: Frontend (Vite) | Meme & Joke Calendar |
| **StoryBoard Creator** | 3032 | - | 3032: Frontend (Vite) | Scene Planning Tool |
| **OCR App** | 3033 | - | 3033: Frontend (Vite) | Image Text Extraction |
| **SuperTuxKart** | 3034 | - | 3034: Game Client | Open Source Racing Game |
| **Word-Music-Game** | 3035 | - | 3035: Frontend (Vite) | Word Guided Real-time Music |
| **LaneShark (Strike King Bowling)** | 3036 | - | 3036: Frontend (Vite) | Premium Bowling Game with AI Commentary |
| **PixelArt Pro** | 3037 | - | 3037: Frontend (Vite) | Professional suite for pixel artists |
| **Antigravity Hub** | 3038 | - | 3038: Next.js Dashboard | **NEW** Ecosystem Manager |

### *Note: Add new projects above this line. Keep table sorted by Port if possible.*
