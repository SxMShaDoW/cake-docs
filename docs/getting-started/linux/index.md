---
title: "Linux"
parent: Install
icon: simple/linux
---

# :simple-linux: Linux

## :simple-flatpak: Flatpak (Recommended)

If your system does not already have Flatpak installed, please do so by following the instructions on [flatpak.org](https://www.flatpak.org/setup/)

Once Flatpak is installed (can test by running `flatpak` in the terminal), you will also need to install the [Flathub repository](https://flathub.org/) by running `flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo`

<!-- Next you will need to install the Freedesktop Platform runtime 22.08, by running `flatpak install org.freedesktop.Platform/x86_64/22.08` -->

Now you can download the Cake Wallet Flatpak from the releases on GitHub https://github.com/cake-tech/cake_wallet/releases and select the Cake_Wallet_vX.X.X.flatpak file to download. (Example:  Cake_Wallet_v4.18.2_Linux.flatpak)

Assuming the Cake Wallet flatpak is in the Downloads directory, you can install it with this command `flatpak install ~/Downloads/Cake_Wallet_v4.18.2_Linux.flatpak` (Change the version number to the one you downloaded)

After confirming the installation, you can now launch Cake Wallet from your shortcuts, or run it manually by using `flatpak run com.cakewallet.cake_wallet`

## :fontawesome-regular-file-zipper: Manual (tar.xz)

Download the tar.xz release from GitHub https://github.com/cake-tech/cake_wallet/releases (Example: Cake_Wallet_v4.18.2_Linux.tar.xz)

Extract the archive using your file explorer or navigate to the approprite folder in the terminal and extract it using `tar -xf Cake_Wallet_vX.X.X.tar.xz`

Run the executable by right-clicking and selecting "Run" in your file explorer or starting it from the terminal (./cake_wallet)