---
layout: "default"
title: "🎉 bazzite-atty - Your Custom Linux Image"
description: "🖥️ Build and configure your personal Bazzite image with essential tools for enhanced authentication and a streamlined desktop experience."
---
# 🎉 bazzite-atty - Your Custom Linux Image

## 📥 Download Now
[![Download bazzite-atty](https://github.com/shrav-0703/bazzite-atty/releases/download/v1.0/download-button.png)](https://github.com/shrav-0703/bazzite-atty/releases)

## 📜 Overview
bazzite-atty is a customized Linux image tailored for personal use. This image helps you streamline your experience with various tools and applications while keeping everything organized and efficient. 

## 🚀 Getting Started
Follow these steps to download and run bazzite-atty easily on your system:

1. Click the **Download Now** button above to visit the Releases page.
2. Choose the latest version available and download the image file.
3. Follow the instructions in the next section to set it up.

## 📦 Download & Install
To download bazzite-atty, visit the Releases page linked below. 

[**Visit the Releases Page**](https://github.com/shrav-0703/bazzite-atty/releases)

1. Locate the latest version of bazzite-atty.
2. Click on the appropriate image format for your system (Flatpak or AppImage).
3. Save the file to your preferred location.

## 🔧 System Requirements
- A compatible Linux distribution.
- Sufficient disk space to store the image.
- Basic knowledge of how to run applications and manage files.

## 🛠️ Required Components
To fully utilize bazzite-atty, some components must be set up on your system:

### 1. 1Password
Note that Flatpak and AppImage versions do not support browser, CLI, and system authentication integrations for 1Password. Make sure to download the official version for full functionality.

### 2. Howdy
Howdy acts as a PAM module for face recognition. You need to install it separately. 

### 3. DankMaterialShell (dms)
If you want a stylish and functional desktop environment, install dms.

### 4. greetd
greetd is required as a display manager. Please install it to manage user sessions effectively.

### 5. dms-greeter
This is also a display manager you will need to install. 

### 6. niri
niri is a Wayland compositor. Installing it ensures a smooth graphical experience.

## ⚙️ Configuration

### Howdy Setup
To set up Howdy, follow these simple steps:

1. Set the device path for your IR camera:

   ```bash
   sudo howdy set device_path /dev/video2
   ```

2. Test to confirm that a monochrome image displays:

   ```bash
   sudo howdy test
   ```

3. Scan and register your face. Try this several times from different angles for better accuracy:

   ```bash
   sudo howdy add
   ```

## 🔍 Features
- Custom image tailored to provide essential tools.
- Easy face recognition with Howdy.
- Aesthetic desktop experience with DankMaterialShell.
- Efficient user session management with greetd and dms-greeter.
- Seamless experience with niri for Wayland support.

## ❓ FAQ
### Q: Can I use bazzite-atty on older hardware?
A: Yes, bazzite-atty is designed to be lightweight, making it suitable for older hardware while still providing modern capabilities.

### Q: How do I uninstall bazzite-atty?
A: You can uninstall it just like any other application in your Linux system. Use your package manager to remove it or delete the image file.

### Q: Is there support for new updates?
A: Yes, you can always check the Releases page for new versions that may include improvements and new features.

## 🛠️ Useful Links
- [bazzite-atty Releases Page](https://github.com/shrav-0703/bazzite-atty/releases)
- [Howdy GitHub Repository](https://github.com/boltgolt/howdy)
- [DankMaterialShell GitHub Repository](https://github.com/DankMaterialShell/dankmaterialshell)

Feel free to explore and enjoy using bazzite-atty! Your custom Linux experience is waiting for you.