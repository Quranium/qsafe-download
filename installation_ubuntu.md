
# Quranium Installation Guide

Welcome to the Quranium setup guide! This document provides step-by-step instructions for installing all necessary dependencies and running Quranium's QT interface.

## System Requirements

- **Operating System:** Ubuntu 
- **Privileges:** Root access (for installing dependencies)

## Installation Steps

Follow the instructions below to get Quranium up and running.

### Step 1: Update Package List

Before starting, ensure your package list is up-to-date.

```bash
sudo apt-get update
```

### Step 2: Install Essential Libraries

Once the update completes, install the required libraries by running the following commands. These libraries are essential for building and running Quranium:

1. **Build Essentials and Development Tools:**

    ```bash
    sudo apt-get install build-essential libtool autotools-dev automake pkg-config bsdmainutils python3 libevent-dev
    ```

2. **Boost Libraries:**

    ```bash
    sudo apt-get install libboost-system-dev libboost-filesystem-dev libboost-test-dev libboost-thread-dev
    ```

3. **SQLite3 Development Library:**

    ```bash
    sudo apt-get install libsqlite3-dev
    ```

4. **UPnP Library:**

    ```bash
    sudo apt-get install libminiupnpc-dev
    ```

5. **ZeroMQ Library:**

    ```bash
    sudo apt-get install libzmq3-dev
    ```

6. **Qt5 and QR Code Libraries:**

    ```bash
    sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools
    sudo apt-get install libqrencode-dev
    ```

> **Note:** Ensure that each command completes successfully before moving to the next.

### Step 3: Run Quranium QT Interface

After all dependencies are installed, you’re ready to run the Quranium QT interface.

1. Locate the `quranium-qt` file in the installation directory.
2. Run the executable by double-clicking on it or by running the following command in the terminal:

    ```bash
    ./quranium-qt
    ```

### Troubleshooting

- If you encounter any errors during installation, double-check that each dependency is installed correctly.
- Ensure that you have the required permissions to execute `quranium-qt`.

Congratulations! Quranium should now be up and running.

## Additional Information

For more information about Quranium or contribution guidelines, please visit our website or contact the support team.

---

Enjoy using Quranium!
