Catppuccinfier is available for Linux and Windows

<details>
  <summary>Linux</summary>
  
  ## Arch Linux
  Arch users have the option to install the programs through the AUR.
  
  For the cli tool:
  
    paru catppuccinifier-cli-git
  
  For the gui tool:
  
    paru catppuccinifier-gui-git
  
  For both tools:
  
    paru catppuccinifier-cli-git
    paru catppuccinifier-gui-git
    
  ## General Install
  ### Dependencies
  
  ##### Arch Linux
  ```bash 
  sudo pacman -S libadwaita webkit2gtk base-devel curl wget openssl appmenu-gtk-module gtk3 libappindicator-gtk3 librsvg libvips
  ```
  ##### Debian / Ubuntu
  ```bash
  sudo apt install libadwaita-1-0 libwebkit2gtk-4.0-dev build-essential curl wget libssl-dev libgtk-3-dev libayatana-appindicator3-dev librsvg2-dev
  ```
  ##### Fedora
  ```bash
  sudo dnf install libadwaita webkit2gtk4.0-devel openssl-devel curl wget libappindicator-gtk3 librsvg2-devel
  ```
  
  ### Installation
  - Download Linux version in the [releases](https://github.com/lighttigerXIV/catppuccinifier/releases) page
  - Extract the zip and go inside the folder
  - Run the following:
  ```bash
  chmod +x ./install
  chmod +x ./uninstall
  chmod +x ./installation-files/catppuccinifier
  chmod +x ./installation-files/catppuccinifier-gui
  ./install
  ```
</details/>

<details>
  <summary>Windows</summary>
  
  ### Installation
  - Download Windows version in the [releases](https://github.com/lighttigerXIV/catppuccinifier/releases) page
  - Extract the zip and go inside the folder
  - Run the `install.exe` as administrator 
  
</details/>