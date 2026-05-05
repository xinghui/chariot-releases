<p align="center">
  <img src="https://raw.githubusercontent.com/xinghui/chariot/main/icon.png" width="128" alt="Chariot Icon">
</p>

# Chariot

A visual desktop application for managing AI agent coding loops. Built with Tauri + React 19.

Chariot takes its name from the ancient horse-drawn vehicle — not a symbol of brute force, but of precision control and steady momentum.

Just as a chariot harnesses raw horsepower and channels it toward a destination, Chariot harnesses the power of large language models and drives autonomous AI coding loops. It turns a single prompt into a sustained, self-driving development process:

1. You define a goal or requirement
2. Chariot manages the AI agent loop
3. The agent iterates, reasons, and executes until the task is complete

## Download

Go to [Latest Release](https://github.com/xinghui/chariot-releases/releases/latest) to download the latest macOS `.dmg`.

## Install

1. Download `Chariot_<version>_aarch64.dmg`
2. Open the `.dmg`
3. Drag **Chariot** to your **Applications** folder
4. Launch from Applications

> On first launch, you may need to right-click the app and select **Open** to bypass Gatekeeper.

## Tech Stack

- **Tauri 2** – lightweight desktop runtime (Rust backend)
- **React 19** – UI framework with TypeScript
- **Zustand** – state management
- **Radix UI + Tailwind CSS** – component library and styling
- **Rust** – backend logic, process management, file system operations
- **LLM orchestration** – spawns and manages Claude Code instances
