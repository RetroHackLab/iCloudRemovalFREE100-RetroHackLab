# iCloudRemovalFREE100 (RetroHackLab)

A Python-based security research utility designed for bypassing Apple A5(X) to A9 devices running legacy iOS versions (7.0 to 9.3.4) via an established local OpenSSH connection.

## ⚠️ MANDATORY EDUCATIONAL & RESEARCH DISCLAIMER
This project is developed strictly for **educational purposes, security auditing, and the preservation of legacy hardware (abandonware)**. 
* The author (RetroHackLab) does not condone, encourage, or facilitate the use of this utility on lost or stolen devices.
* You must only use this software on hardware that you legally own.
* The end-user assumes full responsibility for any actions performed using this software.

## 🔒 License & Closed Source Notice
This repository is **NOT Open Source**. The Python source code is proprietary, private, and protected. 
* Do not request the source code; it will not be shared.
* Reverse engineering, decompiling, or modifying the published executable is strictly prohibited by law.
* See the accompanying `LICENSE` file for full legal terms.

## 📋 Device Requirements & Technical Settings
For this tool to successfully communicate, the target device and environment must meet the following criteria:

### 1. Hardware & Firmware Compatibility
* **Chipsets:** Apple A5, A5X, A6, A6X, A7, A8, A8X, or A9.
* **iOS Versions:** Legacy iOS 7.0 up to iOS 9.3.4.
* **Jailbreak:** The device must already be jailbroken with OpenSSH installed.

### 2. Connection Profile (Hardcoded Settings)
The compiled binary connects exclusively using the following network parameters (**Source: Legacy iOS Kit/SSH RAMDISK & OpenSSH**):
* **Host / IP:** `127.0.0.1` (Localhost)
* **SSH Port:** `6414`
* **SSH Username:** `root`
* **SSH Password:** `alpine`

*Note: You must run your own USB SSH tunnel (such as iProxy or iproxy.exe) to forward your iOS device's port 22 to your local PC port 6414 BEFORE launching the utility.*

## 🚀 How to Download and Run (Executable Version)
Since the source code is hidden, you must use the pre-compiled Windows binary:

1. Navigate to the **Releases** section on the right side of this GitHub repository page.
2. Download the latest version of `iCloudRemovalFREE100 (RetroHackLab).exe`.
3. Connect your jailbroken iOS device to your PC via a USB cable.
4. Launch your USB tunnel tool to bridge the connection to port `6414`.
5. Run `iCloudRemovalFREE100 (RetroHackLab).exe` as an **Administrator**.
6. Follow the on-screen instructions to complete the process.

## 🤝 Support & Contact
For research discussions or bug reports regarding the executable execution, please open an **Issue** directly on this repository.
