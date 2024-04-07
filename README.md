# New Proot Distro

[![Ubuntu Desktop](https://raw.githubusercontent.com/TecnicalBot/modded-distro/main/images/ubuntu.jpg)](https://youtu.be/gzbHaxuWT2E)

<p align="center"><b>Easily Install Full Ubuntu Desktop on Android Without Root</b></p>
<p align="center"><i>Works Until Termux Crashes - Use Termux Float to Prevent Crashes</i></p>

## Features
- Ubuntu Desktop Environment
- Lightweight (Uses XFCE Desktop Environment)
- Fixed Audio Output

## Video Guide
[![Video Guide](https://raw.githubusercontent.com/TecnicalBot/modded-distro/main/images/thumbnail.jpg)](https://youtu.be/gzbHaxuWT2E)

## Tested on Android 13
- Verified Working ✅

## Requirements
- Android Device (No Root Required)
- 2GB RAM (Minimum)
- SoC Any
- Termux (Get it from their [GitHub page](https://github.com/termux/termux-app/releases/latest))
- VNC Viewer (Get it from [Play Store](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android))
- 4GB Storage (or Less)

## Installation
1. Paste the following command in Termux:
    ```bash
    curl https://raw.githubusercontent.com/frostbitecloudhost/proot-distro/main/install.sh >> install.sh
    bash install.sh
    ```
2. Follow the setup instructions (e.g., choose your timezone and keyboard layout, English US keyboard recommended).

## Restart Instructions
- Open Termux or Termux Float
- Type 'ubuntu'
- Enter the Ubuntu password (if prompted)
- Note the localdomain number
- Open RealVNC and enter 'localhost:<localdomain number>' (without spaces)
- Ignore any warnings and enter your VNC password set during setup

## Important Notes
- Restarting Ubuntu VNC doesn't delete your files or settings.
- You may encounter issues with the browser; YouTube has tutorials to address this.
- Do not use Ubuntu for illegal activities; we're not responsible for any misuse.
