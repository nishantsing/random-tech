# random-tech

- When you install a distribution using wsl --install -d <distro> or from the Microsoft Store, it is installed by default in %USERPROFILE%\AppData\Local\Packages\<PackageName>. These can be "moved" by exporting them and re-importing them.
- [Installing WSL on another drive in Windows](https://dev.to/mefaba/installing-wsl-on-another-drive-in-windows-5c4a)

## To get hardwae component rating
- open windows powershell as admin
- paste this command "Get-CimInstance Win32_WinSat"

## Dark mode in chrome
chrome://flags -> search for dark mode -> enable
  
## WSL-2 (Linux on windows)

- wsl --set-version Ubuntu-22.04 2 to move from wsl to wsl-2 and able to run ollama models

- [YT WSL - Network Chuck](https://youtu.be/vxTW22y8zV8) 
- BIOS (enable Virtualization)
- winver // to get windows version type this in search
- open terminal with admin rights
    - wsl --install (default installs ubuntu)
    - wsl --list online
    - wsl -d ubuntu
    - wsl --install kali-linux // To install kali linux || or you can also install from windows store
    - kali-tweaks (metapackages - top10)
    - wsl --shutdown // close all
    - wsl --terminate kali-linux // close kali-linux
    - wsl --unregister kali-linux // To uninstall
    - explorer.exe .//To open current location in windows explorer
    - sudo apt install wireshark
    - sudo wireshark
    - sudo apt install kali -win -kex -y // To install linux GUI
    - kex // to run the GUI
    - kex --win --stop// TO stop the GUI
    - sudo apt install docker.io
    - wsl --export kali-linux nslinux.tar // To export your machine
    - wsl --import ns <location of nslinux> // To import
- sudo apt-install spiderfoot
- spiderfoot -l 127.0.0.1:5001
- truthfinder // get details about anyone if you want to delete these details use icogni
- With new updates in Virtual Box with hyperversion it doesn't interfere with wsl


