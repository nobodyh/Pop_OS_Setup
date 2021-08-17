# Pop!_OS Setup
A Pop!_OS  installation guide with a few tweaks for peeps switching from Windows to Linux for the first time.

# Installation

You can install the Disk Image (.iso) from the [Official Website](https://pop.system76.com/).

If you have a Nvidia Graphics Card use the Nvidia version of the Disk Image.

## 📕 Official Installation Guide:

[Creating a Live Disk](https://support.system76.com/articles/live-disk)

[balena Etcher](https://www.balena.io/etcher/) 

[Installation](https://support.system76.com/articles/install-pop)

## 🔗 Useful Links:

[Link 1](https://www.youtube.com/watch?v=EXZ7_DVxztQ): Short Video Installation Guide

[Link 2](https://www.youtube.com/watch?v=3Rcxjx3H9jo): Descriptive Video Installation Guide

## Bootloader Customization:

### Using rEFInd to customize the Bootloader

[Installation](https://www.youtube.com/watch?v=bg0BV5ZJCZU): Setting up rEFInd

```bash
$ sudo apt-add-repository ppa:rodsmith/refind
$ sudo apt-get update
$ sudo apt-get install refind
```

[Custom Theme Installation](https://www.youtube.com/watch?v=g2YYC1f3mnw): How to install a custom rEFInd theme

[Themes](https://github.com/topics/refind-theme): rEFInd Themes which are available on GitHub

### Favourites:

[rEFInd Theme Regular](https://github.com/bobafetthotmail/refind-theme-regular)

[darkmini](https://github.com/LightAir/darkmini)

[rEFInd-glassy](https://github.com/Pr0cella/rEFInd-glassy)

[rEFInd-minimal-dark](https://github.com/PillTime/rEFInd-minimal-dark)

**[rEFInd-Maia-Reskin](https://github.com/Fantailed/Refind-Maia-Reskin)**

**[rEFInd-dawn](https://github.com/ajlende/rEFInd-dawn)**

**[refind-ambience-deer-and-fireflies](https://github.com/jpmvferreira/refind-ambience-deer-and-fireflies)**

### Using Grub Customizer to customize the Bootloader

Installation: Setting up Grub Customizer

```bash
$ sudo apt-get install grub2-common
$ sudo update-grub
$ sudo add-apt-repository ppa:danielrichter2007/grub-customizer
$ sudo apt-get update
$ sudo apt-get install grub-customizer

To Uninstall:
$ sudo apt-get remove --autoremove grub-customizer
```

[Custom Theme Installation](https://www.youtube.com/watch?v=3s7qBJ-H7vw): How to install a custom GRUB theme; [Another Link](https://www.youtube.com/watch?v=BAyzHP1Cqb0)

[Themes](https://www.gnome-look.org/browse?cat=109&ord=rating): GRUB Themes which are available online

### Favourites:

[Grub-theme-vimix](https://www.gnome-look.org/p/1009236): [GitHub](https://github.com/vinceliuice/grub2-themes)

[Tela grub theme](https://www.gnome-look.org/p/1307852)

[CyberRe](https://www.gnome-look.org/p/1420727)

[Sleek GrubBootloader](https://www.gnome-look.org/p/1414997)

[BigSur GRUB Theme](https://www.gnome-look.org/p/1443844)

## Customizations required to make it feel like a Windows Machine

### Keyboard Shortcuts

Change the Home Folder (File Explorer)to: Super(Win Key) + E

Navigation: Hide all normal windows to: Super + D; Switch Windows: Alt + Tab (Disabled by default)

Screenshots: Check out the screenshot shortcuts and map it based on your comfortablity.

System: Disable Show the notification list 

Windows: Close Window: Alt + F4

### Clipboard Manager

Personally have been using CopyQ, once you have installed it set up the shortcut to toggle the clipboard manager.

Installation:

```bash
sudo apt install software-properties-common python-software-properties
sudo add-apt-repository ppa:hluk/copyq
sudo apt update
sudo apt install copyq
```

Preferences:

<img title="" src="Pop!_OS/CopyQ Preference.png" alt="Untitled" data-align="center" width="429">

## Must Have Applications

### Timeshift: Backup

```bash
sudo apt-add-repository -y ppa:teejee2008/ppa
sudo apt-get update
sudo apt-get install timeshift
```

## Deja Dup: Backup

```bash
sudo apt install deja-dup
```

### Gnome-Tweaks: Customization

```bash
sudo apt install gnome-tweak-tool
```

### Stacer: Performance

```bash
sudo apt install stacer
```

### Enable Gnome Extensions in Browser

### [Volume Mixer](https://extensions.gnome.org/extension/3499/application-volume-mixer/)

### GParted: System Software for partitioning

```bash
sudo apt install gparted
```

### Synaptic

```bash
sudo apt install synaptic
```

### PulseAudio Volume Control: Audio Device Manager

```bash
sudo apt install pavucontrol
```

### qBittorent: Torrent App

```bash
sudo apt-get update && sudo apt-get install qbittorrent
sudo add-apt-repository ppa:qbittorrent-team/qbittorrent-stable
```

### Oracle VirtualBox: [Link](https://download.virtualbox.org/virtualbox/6.1.26/virtualbox-6.1_6.1.26-145957~Ubuntu~eoan_amd64.deb) and [Extension Pack](https://download.virtualbox.org/virtualbox/6.1.26/Oracle_VM_VirtualBox_Extension_Pack-6.1.26.vbox-extpack)

### [Rambox](https://rambox.pro/api/downloadCE?os=linux&filetype=AppImage&arch=x86_64): Productivity App for Messaging

### [Notion](https://github.com/davidbailey00/notion-linux/releases/download/v2.0.6-windows/notion-desktop_2.0.6_amd64.deb): Productivity App for Note Taking
