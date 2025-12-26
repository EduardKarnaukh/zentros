# Changelog

All notable changes to Zentros will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2024-12-26

### Added
- **Multi-language Support** - Switch between languages (English, Polish, Russian, Ukrainian) directly in Settings
- **Windows Support** - Full support for Windows platform

### Improved
- Enhanced UI responsiveness and stability
- Various bug fixes and performance improvements

---

## [1.0.0] - 2024-12-17

### Initial Release

First public release of Zentros - an Agentic Development Environment (ADE) for AI-powered software development.

### Added

#### Core Features
- **Workspace Management** - Create, open, and manage multiple project workspaces
- **Claude Code Integration** - Full integration with Claude Code CLI for AI-assisted development
- **Chat Interface** - Intuitive chat UI for communicating with Claude
- **Permission System** - Approve or reject AI-proposed file changes and commands

#### Editor & Files
- **File Explorer** - Browse project files with tree view navigation
- **Monaco Editor** - Full-featured code editor with syntax highlighting
- **File Preview** - Quick file content preview without opening editor
- **Multi-tab Support** - Work with multiple files simultaneously

#### Terminal
- **Built-in Terminal** - xterm.js-based terminal emulator
- **Multiple Sessions** - Run multiple terminal tabs in parallel
- **Command History** - Navigate through previous commands

#### Git Integration
- **Git Status** - View modified, staged, and untracked files
- **Branch Management** - Switch branches, view branch list
- **Diff Viewer** - Visual diff for changed files
- **Commit & Push** - Stage changes and commit directly from UI

#### Docker Support
- **Container Management** - Start, stop, and monitor Docker containers
- **Docker Compose** - Support for docker-compose.yml projects
- **Log Viewer** - Real-time container log streaming

#### Advanced Features
- **Matrix Mode** - Run multiple AI agents in parallel grid layout
- **Pipelines** - Create custom multi-stage development workflows
- **Templates** - Save and reuse prompt templates
- **Code Map** - Visual project structure diagram

#### UI/UX
- **Dark Theme** - Eye-friendly dark interface
- **Resizable Panels** - Customize layout with draggable panels
- **Bottom Panel** - Docker, Files, and Code Map in collapsible panel
- **Right Panel** - Terminal, Tools, Templates, and more
- **Internationalization** - Support for English, Russian, Ukrainian, Polish

### Technical Details
- Built with Electron 33
- React 18 with TypeScript
- Tailwind CSS for styling
- SQLite for local data storage
- Zustand for state management

### Known Limitations
- macOS and Windows only (Linux coming soon)
- Requires Claude Code CLI to be installed separately
- Requires active Anthropic API subscription

---

[1.1.0]: https://github.com/EduardKarnaukh/zentros/releases/tag/v1.1.0
[1.0.0]: https://github.com/EduardKarnaukh/zentros/releases/tag/v1.0.0