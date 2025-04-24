🎮 Arcade ROM Builder Suite

A modular PowerShell-based automation toolkit for organizing and deploying curated game libraries across multiple emulation platforms—including MiSTer FPGA, Pandora Box 3D SAGA EX, Hyperspin with RocketLauncher, and CoinOps.

🧹 Purpose

This project streamlines the process of identifying, organizing, and distributing ROMs and media for high-quality emulation builds. Starting from a curated list of 1000 must-have games, the suite scans large collections, maps available files to the best emulator platform, and deploys ready-to-use folder structures for SD cards and emulator drives.

💡 Features

🌟 Targeted Game List MatchingPrioritizes quality over quantity by matching only games from a curated list.

🔎 ROM Inventory ScanningRecursively scans a drive for supported ROM and media formats.

🧠 Emulator Prioritization LogicAutomatically assigns each matched game to the most suitable emulator using a tiered preference system:Hyperspin > MiSTer > CoinOps > Pandora.

📃 Structured Folder BuildsOutputs properly named and organized folders for each emulator environment.

🖥️ Interactive ANSI PowerShell MenuUnified launcher script allows interactive operation and script selection.

🧱 Project Structure

/Scripts/
├── MainMenu.ps1
├── Build-MiSTerCard.ps1
├── Build-PandoraCard.ps1
├── Build-HyperspinDrive.ps1
├── Build-CoinOpsDrive.ps1
├── Generate-ROMInventory.ps1
├── Match-GameList.ps1
/Data/
├── Top1000_Games.csv
├── ROMInventory.csv
├── MatchedGames.csv
/Output/
├── MiSTer/
├── Pandora/
├── Hyperspin/
├── CoinOps/

🚀 Getting Started

Clone this repository and open it in Visual Studio Code.

Launch MainMenu.ps1 from a PowerShell terminal to access the interactive menu.

Follow prompts to generate your inventory, match games, and build emulator folders.

🔮 Planned Features

File hash validation

Dynamic scraper integration (box art, video previews)

MiSTer .chd conversion utility

Auto-deploy to USB/SD card

Logging and report generation

Frontend configuration exports (RocketLauncher XML, CoinOps DB)

🧠 Requirements

PowerShell 5.1 or later

Windows 10/11 (tested)

Visual Studio Code (recommended for development)

📄 License

MIT License (to be added)

🙌 Contributions

PRs welcome! Help expand support for more platforms, scrapers, or deployment targets.


