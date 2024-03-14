# **Arch-Darwin**
An Arch linux splash screen for plymouth.

In this fork I changed the speed of the progress bar to reach the end before login screen or before it shuts down. Moreover I removed and optimized unnecessary code and files to reduce overhead.
 
<img src="./preview.gif" alt="arch-darwin">

<!---
# Installation from AUR
- Install and setup [Plymouth](https://wiki.archlinux.org/title/plymouth)
- Install [plymouth-theme-arch-darwin](https://aur.archlinux.org/packages/plymouth-theme-arch-darwin) package from the [AUR](https://aur.archlinux.org)
```
$ yay -S plymouth-theme-arch-darwin
```
(assuming you have yay as your AUR helper)
--->

# Manual Installtion
clone repo
```
$ git clone https://github.com/FedericoCalzoni/plymouth-theme-arch-darwin-fast.git
```

move content to theme directory of plymouth
```
$ sudo mv ./plymouth-theme-arch-darwin-fast /usr/share/plymouth/themes/arch-darwin-fast
```
Apply theme
```
$ sudo plymouth-set-default-theme -R arch-darwin-fast
```
