# Quranium Core v1.0.0 Release Notes

## Overview

This is the first official release of the Quranium Core build for Ubuntu, compatible with systems running Ubuntu 24 LTS and above. This build is set up to provide a stable environment for the Quranium blockchain's core functions and is specifically configured to default to testnet mode.

## System Requirements

* **Operating System**: Ubuntu 24 LTS or later
* **Dependencies**: All necessary dependencies are included, with additional information in the README.md file if system compatibility issues arise

## Installation & Usage

### Download and Extract

Unpack the `quranium-1.0-x86_64-linux-gnu.tar.gz` archive to your preferred directory.

### Navigate to the bin Directory

Quranium binaries are located in the bin directory. To start the Quranium QT wallet, navigate to this directory before launching the application.

Example:
```bash
cd path/to/quranium-1.0-x86_64-linux-gnu/bin
./quranium-qt
```

### Configuration

The application defaults to testnet mode for safe testing and transaction handling. No configuration change is needed to enable testnet, though additional custom configurations can be added to a `quranium.conf` file if desired.

### Further Instructions

For specific commands and guidance on using Quranium CLI, and other utilities, refer to README.md. The README.md also includes troubleshooting tips for common setup and runtime issues.

## Future Updates

We plan to provide updates with expanded compatibility and additional features. Feedback and reports on your experience are highly appreciated and will be addressed in subsequent releases.

---

Enjoy exploring the Quranium blockchain!
