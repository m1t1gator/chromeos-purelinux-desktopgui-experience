# ChromeOS Pure Linux Desktop GUI Experience

![Screenshot](Screenshot%202025-10-22%2021.53.50.png)

Welcome to the **ChromeOS Pure Linux Desktop GUI Experience**! This project provides a script to set up a separate, automated Linux desktop environment that runs alongside ChromeOS on your Chromebook using Linux Beta (Crostini). It creates a dedicated space for your Linux projects, offering a full-fledged Linux GUI experience without interfering with ChromeOS.

## About

This project automates the setup of a Linux desktop environment on a Chromebook via Crostini, running in parallel with ChromeOS. It’s ideal for developers, hobbyists, or anyone seeking a pure Linux GUI for coding, testing, or running Linux applications on their Chromebook.

### Features
- **Seamless Integration**: Run a Linux desktop alongside ChromeOS without replacing it.
- **Automated Setup**: Use the `setup_desktop.sh` script to quickly configure the environment.
- **Customizable**: Choose your preferred desktop environment (e.g., XFCE, GNOME, LXDE).
- **Lightweight**: Optimized for Chromebook hardware and Crostini’s containerized environment.

## Prerequisites

Before you begin, ensure you have:
- A Chromebook with **Linux Beta (Crostini)** enabled (available in ChromeOS settings under "Linux development environment").
- An active internet connection.
- At least 5GB of free storage for the Linux environment.
- Basic familiarity with terminal commands.

> **Note**: This project uses Crostini, so Developer Mode is **not** required. Your Chromebook’s data remains safe during setup.

## Installation

1. **Enable Linux Beta**:
   - Go to ChromeOS Settings > "Linux development environment" and turn on Linux Beta.
   - Follow the on-screen instructions to set up the Linux container.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/m1t1gator/chromeos-purelinux-desktopgui-experience.git
   cd chromeos-purelinux-desktopgui-experience
