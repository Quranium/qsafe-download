# Qsafe Wallet - A Lightweight Quranium Client (Testnet Build - Official Release)

**Version: 2.0.0**

## Overview
This is an official release of the **Qsafe Wallet** (mainnet build), compatible with systems running **Windows 11 (and above)** and **Ubuntu 24 LTS (and above)**. This build is set up to provide a stable environment for the **Quranium blockchain**'s core functions **without** running full node on our systems.

### Important: 
To maintain compatibility with the new release, delete the existing Quranium folder:

### For Windows: Delete the folder at
```
%APPDATA%\Qsafe
```

### For Ubuntu: Delete the folder at
```
~/.qsafe/
```
If you have placed the Qsafe folder in a different location, please delete that folder in the corresponding location.

## System Requirements

### Ubuntu:
* **Operating System:** Ubuntu 24 LTS or later

* **Dependencies:** All necessary dependencies are included.

### Windows:

* **Operating System:** Windows 11 or later

* **Dependencies:** All necessary dependencies are included.

## Installation & Usage

### For Ubuntu:

1. Download the AppImage file `./qsafe-2.0.0-x86_64.AppImage`.

2. Install appimage dependency:

    ```
    sudo apt update
    sudo apt install libfuse2
    ```
3. Open terminal and run the appimage:
    ```
    chmod +x ./qsafe-2.0.0-x86_64.AppImage
    ./qsafe-2.0.0-x86_64.AppImage
    ```


### For Windows:

1. Using standalone executable:

    * Download the `qsafe-2.0.0.exe` file.
    * We can directly open the software without any additional steps.

## Configuration
The application defaults to **mainnet** mode. 
No further configuration changes are needed to enable mainnet.
For testing purpose use testnet flag `--testnet`.

## Future Updates
We plan to provide updates with expanded compatibility and additional features. Feedback and reports on your experience are highly appreciated and will be addressed in subsequent releases.

----
Enjoy exploring the **Qsafe Wallet - A Lightweight Quranium Client**!
