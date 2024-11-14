# Qsafe Wallet - A Lightweight Quranium Client (Testnet Build - Official Release)

**Version: 1.0.0**

## Overview
This is the first official release of the **Qsafe Wallet** (testnet build), compatible with systems running **Windows 11 (and above)** and **Ubuntu 24 LTS (and above)**. This build is set up to provide a stable environment for the **Quranium blockchain**'s core functions **without** running full node on our systems and is specifically configured to default to **testnet** mode.

## System Requirements

### Ubuntu:
* **Operating System:** Ubuntu 24 LTS or later

* **Dependencies:** All necessary dependencies are included.

### Windows:

* **Operating System:** Windows 11 or later

* **Dependencies:** All necessary dependencies are included.

## Installation & Usage

### For Ubuntu:

1. Download the AppImage file `./qsafe-1.0.0-x86_64.AppImage`.

2. Install appimage dependency:

    ```
    sudo apt install libfuse2
    ```
3. Open terminal and run the appimage:
    ```
    chmod +x ./qsafe-1.0.0-x86_64.AppImage
    ./qsafe-1.0.0-x86_64.AppImage
    ```


### For Windows:

1. Using qsafe installer:

    * Download the `qsafe-1.0.0-setup.exe` file.
    * Execute the setup to complete the installation.
    * After installation, we can open the qsafe software from anywhere.

2. Using standalone executable:

    * Download the `qsafe-1.0.0.exe` file.
    * We can directly open the software without any additional steps.

3. Using portable version:

    * Download the `qsafe-1.0.0-portable.exe` file.
    * We can directly open the software without any additional steps.

**Security Advice**: Using **portable softwares** can be risky, as they store data in the program’s directory instead of the secure `username\AppData\` path. This can make data vulnerable to loss, unauthorized access, or exposure if the program is moved or deleted.

## Configuration
The application defaults to **testnet** mode for safe testing and transaction handling. No further configuration changes are needed to enable testnet.

## Future Updates
We plan to provide updates with expanded compatibility and additional features. Feedback and reports on your experience are highly appreciated and will be addressed in subsequent releases.

----
Enjoy exploring the **Qsafe Wallet - A Lightweight Quranium Client**!