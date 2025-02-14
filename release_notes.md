# Qsafe Wallet - A Lightweight Quranium Client (Testnet Build - Official Release)

**Version: 2.0.3**

## Overview
This is an official release of the **Qsafe Wallet** (mainnet build), compatible with systems running **Windows 11 (and above)** and **Ubuntu 24 LTS (and above)**. This build is set up to provide a stable environment for the **Quranium blockchain**'s core functions **without** running full node on our systems.

### Important: 
If you have used any older versions of Qsafe, please follow this below instructions carefully to avoid bugs.

Delete the existing Qsafe configuration folder before running the new build to maintain compatibility

#### Note:
You can skip this step if you have already done this for the previous version `>=2.0.0`.

### For Windows: Delete the folder at
```
%APPDATA%\Qsafe
```
the exact path will look like this:
```
C:\Users\<username>\AppData\Roaming\Qsafe
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

1. Download the AppImage file `./qsafe-2.0.3-x86_64.AppImage`.

2. Install appimage dependency:

    ```
    sudo apt update
    sudo apt install libfuse2
    ```
3. Open terminal and run the appimage:
    ```
    chmod +x ./qsafe-2.0.3-x86_64.AppImage
    ./qsafe-2.0.3-x86_64.AppImage
    ```

#### TESTNET
----
To access testnet, please type this command in the terminal where the AppImage was present. 
```
./qsafe-2.0.3-x86_64.AppImage --testnet
```
----
### For Windows:

1. Using standalone executable:

    * Download the `qsafe-2.0.3.zip` file.
    * Extract the zip file to your prefered directory.
    * Open the extracted folder `qsafe-2.0.3`.
    * We can directly open the software without any additional steps.

#### TESTNET
----
To access testnet please launch `qsafe-testnet.exe`.

----
## Configuration
The application defaults to **mainnet** mode. 
No further configuration changes are needed to enable mainnet.

## Future Updates
We plan to provide updates with expanded compatibility and additional features. Feedback and reports on your experience are highly appreciated and will be addressed in subsequent releases.

----
Enjoy exploring the **Qsafe Wallet - A Lightweight Quranium Client**!
