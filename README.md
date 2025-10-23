# ChromeOS Pure Linux Desktop GUI Experience

![Linux Desktop on ChromeOS](assets/Screenshot%202025-10-22%2021.53.50.png)

Set up a seamless Linux desktop environment on your Chromebook using Linux Beta (Crostini). This project provides `setup_desktop.sh` to automate the creation of a dedicated Linux GUI alongside ChromeOS, ideal for coding, testing, or running Linux applications.

## Features
- **Seamless Integration**: Run a Linux desktop in parallel with ChromeOS.
- **Automated Setup**: One script to configure the environment.
- **Customizable**: Supports desktop environments like XFCE, GNOME, or LXDE (defaults to XFCE).
- **Lightweight**: Optimized for Crostini’s containerized environment.

## Prerequisites
- Chromebook with **Linux Beta (Crostini)** enabled (Settings > "Linux development environment").
- Active internet connection.
- 5GB+ free storage.
- Basic terminal knowledge.

> **Note**: No Developer Mode needed—your data is safe!

## Installation
1. **Enable Linux Beta**:
   - Go to ChromeOS **Settings** > **Linux development environment** > **Turn on**.
   - Follow prompts to set up the Linux container.

2. **Clone the Repository**:
   ```bash
   git clone git@github.com:m1t1gator/chromeos-purelinux-desktopgui-experience.git
   cd chromeos-purelinux-desktopgui-experience
   ```

3. **Run the Setup Script**:
   ```bash
   chmod +x scripts/setup_desktop.sh
   ./scripts/setup_desktop.sh
   ```
   - The script installs dependencies and sets up the GUI.
   - Follow prompts to select a desktop environment (if applicable).

4. **Launch the Desktop**:
   - Run the command provided by the script (e.g., `startxfce4` for XFCE).
   - Access via the Linux apps menu in ChromeOS.

## Usage
- Launch the desktop from the Linux apps menu or terminal.
- Use for coding, Linux tools, or customization.
- Install software with `sudo apt install <package>`.

## Troubleshooting
- **GUI not starting**: Confirm Crostini support ([Google’s support page](https://www.google.com/chromebook/linux-support/)) and run `sudo apt update && sudo apt upgrade -y`.
- **Script errors**: Check permissions (`chmod +x scripts/setup_desktop.sh`) and internet connectivity.
- **Performance issues**: Use a lightweight desktop like LXDE or close ChromeOS apps.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repo.
2. Create a branch: `git checkout -b feature-name`.
3. Commit changes: `git commit -m "Add feature-name"`.
4. Push: `git push origin feature-name`.
5. Open a pull request with clear documentation.

Report issues on the [Issues page](https://github.com/m1t1gator/chromeos-purelinux-desktopgui-experience/issues).

## License
[MIT License](LICENSE) – see the LICENSE file.

## Author
Created by [m1t1gator](https://github.com/m1t1gator). Feedback welcome!

---

⭐ Star this repo if it helps!  
👀 Watch for updates.  
🍴 Fork to contribute or customize.
