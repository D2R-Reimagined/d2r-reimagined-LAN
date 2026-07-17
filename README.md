# D2R Reimagined Online

D2R Reimagined Online is an unofficial multiplayer-compatible build of **D2R Reimagined** for single-player and LAN TCP/IP play using **D2RLoader**.

This project is maintained separately from the official D2R Reimagined mod.

Official D2R Reimagined repository:  
https://github.com/D2R-Reimagined/d2r-reimagined-mod


## Purpose

This version is intended for players who want to enjoy D2R Reimagined in:

- Single-player
- LAN TCP/IP multiplayer
- A D2RLoader-compatible setup
- Reign of the Warlock (ROTW)

D2RLoader provides TCP/IP support for ROTW without the former class and mechanic restrictions. Warlock and Herald are therefore available in this build. Additionally, many hard-coded elements are being added.

## D2RLoader

D2RLoader aims to provide core features similar to PlugY for Diablo II: Lord of Destruction, as well as development tools for creating mods. Its planned and current capabilities include plugin support, soft-coded mechanics, and other modding utilities.

D2RLoader is currently in alpha and may change significantly. It currently supports D2R versions **3.0 through 3.2**, including the **Reign of the Warlock (ROTW)** DLC.

Supported D2RLoader features include:

- TCP/IP multiplayer
- Infinite stash
- Material capacity increased to 999
- Maximum socket count displayed on normal and superior ground items
- Global and mod-local plugin loading

## Supported Features

- LAN TCP/IP multiplayer through D2RLoader
- Reign of the Warlock support
- Warlock class support
- D2R Reimagined gameplay systems
- D2RLoader's expanded stash and material capacity features
- Global and mod-local plugin support and Even hard-coding

## Installation


### 1. Install the Reimagined compatibility build

Download the compatibility build from the following Google Drive folder:

**[Download the Reimagined compatibility build](https://drive.google.com/drive/folders/1j9iWBFg5hsocjVa97jKQRX0Gv2AlCErf?usp=sharing)**

The official Reimagined release on Nexus is not directly compatible with D2RLoader. Download the files from the link above, extract the archive, and place the extracted `Reimagined` folder in:

```text
Diablo II Resurrected\mods
```

### 2. Install and configure D2RLoader

Open the **[D2RLoader link](https://discord.gg/eEHT2kcBMf)**, then download the latest release from the project's **Download** category.

After extracting the D2RLoader archive, move all three items shown below into the Diablo II Resurrected installation folder containing `D2R.exe`.

<p align="center">
  <img src="https://i.imgur.com/MoZFytC.png" alt="Extracted D2RLoader files" width="260">
</p>

Open `d2rloader\config\d2rloader.toml` in a text editor and set the default mod to Reimagined:

```toml
default_mod = "Reimagined"
```

<p align="center">
  <img src="https://i.imgur.com/sOKfIun.png" alt="D2RLoader configuration file" width="645">
</p>

Press <kbd>Ctrl</kbd>+<kbd>S</kbd> to save the file, then launch the game by running `D2RLoader.exe`.

### 3. Set up Radmin VPN for LAN play

The basic game installation is now complete. To play TCP/IP with friends over the internet, all players must first join the same virtual LAN.

Download and install **[Radmin VPN](https://www.radmin-vpn.com/)**, then turn it on.

<p align="center">
  <img src="https://i.imgur.com/BOILHmA.png" alt="Radmin VPN start screen" width="348">
</p>

Open the **Network** menu. You can create a private network for your group or select **Join Network** to connect to an existing one.

<p align="center">
  <img src="https://i.imgur.com/y8rOE3I.png" alt="Radmin VPN Network menu" width="390">
  <img src="https://i.imgur.com/kRCg0PY.png" alt="Radmin VPN Join Network dialog" width="487">
</p>

Example public network details:

```text
Network name: D2RR TCP/IP
Password:     DeckardLikesWine@69
```

Enter the details and click **Join**. Radmin VPN should then show the shared network and its connected players.

<p align="center">
  <img src="https://i.imgur.com/XWZocSN.png" alt="Players connected through Radmin VPN" width="361">
</p>

### 4. Connect in-game through TCP/IP

From the character selection screen, click **TCP/IP** at the bottom center.

- To host, click **Host Game**. Other players must use the host's Radmin VPN IP address.
- To join, click **Join Game**, enter the host's Radmin VPN IP address, and click **OK**.

<p align="center">
  <img src="https://i.imgur.com/qhHWPIj.jpeg" alt="Hosting a D2R Reimagined TCP/IP game" width="800">
</p>

<p align="center">
  <img src="https://i.imgur.com/6Nz3Q4p.png" alt="Joining a D2R Reimagined TCP/IP game" width="600">
</p>

All players joining the same TCP/IP game must use compatible game, loader, and mod versions.

## Multiplayer Notes

For LAN TCP/IP multiplayer, all players should use:

- The same D2R version
- The same D2RLoader version and configuration
- The same D2R Reimagined Online version
- Matching mod files

Mismatched versions or files may cause connection failures, crashes, missing visuals, broken skills, or other unexpected behavior.

## Disclaimer

This repository is a separate compatibility project for D2RLoader and LAN TCP/IP multiplayer. It is not an official branch, official release, or officially supported version of D2R Reimagined or D2RLoader.

Please support and follow the original D2R Reimagined project:

https://github.com/D2R-Reimagined/d2r-reimagined-mod
