
<h1 align="center"><b>RunParrot OS GUI on Termux X11</b></h1>

## This is a fork of another repo: https://github.com/sabamdarif/parrot-gui

## ⚠️ Droidmaster modifications: 
* Change default repositories to `http://mirrors.ustc.edu.cn/parrot`
* Install basic parrot OS packages by default: `parrot-apps-basics` `parrot-core`

<br>
<br>

---
---
---

<br>
<br>

## Installation:

- Firstly install [Termux](https://termux.com) apk from [HERE](https://f-droid.org/repo/com.termux_118.apk)
- Secondly Clone the Repository & Run the setup File

  - `pkg update -y && pkg upgrade -y`
  - `pkg install git wget -y`
  - `wget https://raw.githubusercontent.com/LinuxDroidMaster/parrotOS-GUI-proot/main/setup-parrot-cli`
  - `chmod +x setup-parrot-cli`
  - `./setup-parrot-cli`
  - `parrot`
  - `./install-parrot-desktop`

- **You have to note your VNC password !!**

- Parrot OS image is now successfully installed .
- Enjoy :D

## NOTE :

- **Type `parrot` to run PARROT OS CLI.**
- **Type `parrot -r` to run Parrot CLI as root user**
- **Type `bash remove-parrot.sh` to removeParrot OS**

