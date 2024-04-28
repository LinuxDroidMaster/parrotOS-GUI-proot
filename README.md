
<h1 align="center"><b>RunParrot OS GUI on Termux X11</b></h1>

## This is a fork of another repo: https://github.com/sabamdarif/parrot-gui

## ⚠️ Droidmaster modifications: 
* Change default repositories to `http://mirrors.ustc.edu.cn/parrot`
* Install basic parrot OS packages by default: `parrot-apps-basics` `parrot-core`
* Using Parrot OS rootfs from EXALAB instead of RiSecID
* Removed unnecesary packages

<br>
<br>

---
---
---

<br>
<br>

## Installation:

* Clone the Repository & run the commands: 
```
pkg update -y && pkg upgrade -y
pkg install git wget -y
git clone https://github.com/LinuxDroidMaster/parrotOS-GUI-proot
cd parrotOS-GUI-proot
chmod +x setup-parrot-cli
./setup-parrot-cli
```
```
#Inside parrot OS
./install-parrot-desktop
```

- Parrot OS image is now successfully installed .
- Enjoy :D

## NOTE :

- **Type `parrot` to run PARROT OS CLI.**
- **Type `parrot -r` to run Parrot CLI as root user**
- **Type `bash remove-parrot.sh` to removeParrot OS**

