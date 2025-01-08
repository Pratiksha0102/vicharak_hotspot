# Vicharak Hotspot

**Version**: 0.0.1  
**Status**: UNRELEASED  

## Description

The `vicharak-hotspot` package provides a service and scripts to create and manage a Wi-Fi hotspot on Vicharak boards. It dynamically determines the board model and configures a hotspot with a specific name and network settings.

## Features

- Dynamically detects the board model (Vaaman, Axon) and uses it for the hotspot name.
- Configures the hotspot with WPA-PSK security and custom IP settings.
- Systemd service to manage the hotspot creation automatically.
- Pre- and post-installation scripts for streamlined setup and cleanup.

## Installation

1. Download the `.deb` package:
   ```bash
   wget <link-to-vicharak-hotspot_0.0.1_arm64.deb>

**NOTE:** To enable both hotspot and Wi-Fi functionality simultaneously, Concurrent Mode must be enabled by reverting the following commit: [ac90564055da07b18d900f2d14b604f65de62e7c](https://github.com/vicharak-in/rockchip-linux-kernel-priv/commit/ac90564055da07b18d900f2d14)
