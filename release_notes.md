# Quranium Core Build - Official Release

## Overview

This is the first official release of the Quranium Core build, compatible with systems running **Windows 11** (and above) and **Ubuntu 24 LTS** (and above). This build is set up to provide a stable environment for the Quranium blockchain's core functions and is specifically configured to default to testnet mode.

## System Requirements

### Windows:
* **Operating System**: Windows 11 or later
* **Dependencies**: All necessary dependencies are included, with additional information in the README.md file if system compatibility issues arise.

### Ubuntu:
* **Operating System**: Ubuntu 24 LTS or later
* **Dependencies**: All necessary dependencies are included, with additional information in the README.md file if system compatibility issues arise.

## Installation & Usage

### For Ubuntu:

1. **Download and Extract**
   - Unpack the `quranium-1.0-x86_64-linux-gnu.tar.gz` archive to your preferred directory.

2. **Navigate to the `bin` Directory**
   - Quranium binaries are located in the `bin` directory. To start the Quranium QT wallet, navigate to this directory before launching the application.

   Example:
   ```bash
   cd path/to/quranium-1.0-x86_64-linux-gnu/bin
   ./quranium-qt

### For Windows:

1. **Download and Extract**
   - Unpack the `quranium-1.0-x86_64-windows64-mingw32.tar.gz` archive to your preferred directory.

2. **Navigate to the `bin` Directory**
   - Quranium binaries are located in the `bin` directory. To start the Quranium QT wallet, navigate to this directory before launching the application.

   Example:
   ```powershell
   cd path\to\quranium-1.0-x86_64-windows64-mingw32\bin
   .\quranium-qt.exe


### Configuration

The application defaults to testnet mode for safe testing and transaction handling. No configuration change is needed to enable testnet, though additional custom configurations can be added to a `quranium.conf` file if desired.

### Further Instructions

For specific commands and guidance on using Quranium CLI, and other utilities, refer to README.md. The README.md also includes troubleshooting tips for common setup and runtime issues.

## Future Updates

We plan to provide updates with expanded compatibility and additional features. Feedback and reports on your experience are highly appreciated and will be addressed in subsequent releases.

---

Enjoy exploring the Quranium blockchain!