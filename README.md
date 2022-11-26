# Swirl Packages

## Install Instructions

### Arch linux (PKGBUILD)
1. Clone the arch branch with `git clone -b arch https://github.com/SwirlLang/packages.git`
2. Change directory to *packages* with `cd packages`
3. Install using **MKPKG**: `makepkg -si`

### Arch linux (Pacman)
1. Go to the [releases page](https://github.com/SwirlLang/packages/releases) and download the `tar.gz` archive
2. Move to the directory you downloaded the archive in
3. Install using **PACMAN**: `sudo pacman -U *.tar.gz`

### Any Linux distribution
1. Go to the [releases page](https://github.com/SwirlLang/packages/releases) and download the `AppImage`
2. Give it executable permission: `chmod +x *.AppImage`
3. Execute it using `./Swirl-x86_64.AppImage`

### Windows Builds
*Work in progress*