# FunhouseF10 Hackintosh Project

This project aims to run macOS on a FunhouseF10 laptop using OpenCore EFI for booting. The configuration includes a FunhouseF10 laptop with an Intel Core i3-1005G1 processor, 8GB of RAM, and a 13.5-inch screen from BOE with a resolution of 2256x1504.

## Installation

### Step 1: Preparations
Before starting the installation, make sure you have backed up all important data as the installation may result in data loss. Additionally, you'll need the following:

- FunhouseF10 laptop
- macOS installation image (available from the official website)
- USB installer drive
- OpenCore EFI boot files

### Step 2: Create a Bootable USB Drive
1. Format the USB drive as macOS Extended (APFS) or Mac OS Extended (HFS+) using Disk Utility.
2. Install macOS onto the USB drive using the macOS installer.
3. Copy the OpenCore EFI boot files to the EFI partition of the USB drive.

### Step 3: Boot FunhouseF10
1. Start the FunhouseF10 and simultaneously press the boot menu key (usually F12 or F2) to access the boot menu.
2. Select the USB drive to boot from it.
3. Start the macOS installer.

### Step 4: Install macOS
1. In the macOS installer, choose the target disk and follow the on-screen instructions to install macOS.
2. Once the installation is complete, the system will automatically reboot.

### Step 5: Configure OpenCore
1. On the FunhouseF10, select the OpenCore boot entry and boot into macOS.
2. Configure OpenCore to ensure all hardware and drivers are working correctly.

## Usage
Once macOS is successfully installed and booted, you can enjoy the macOS experience on your FunhouseF10. You're free to install applications, customize your workflow, and take advantage of the high-resolution screen.

## Issue Reporting
If you encounter any issues during installation or usage, please feel free to raise them on GitHub. We'll do our best to provide assistance and resolve the problems.

## Contributions
If you're interested in contributing code or improving this project, feel free to submit pull requests.

## License
This project is licensed under the MIT License

---

**Disclaimer:** This project is for educational and research purposes only. When installing macOS, make sure to comply with all applicable laws, regulations, and license agreements.
