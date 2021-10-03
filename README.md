# BusyBox (no-root)
The shell script which allows you to install Busybox into your device, open Busybox usage for **Terminal Emulator** or **Material Emulator**.

This method doesn't need root access at all!

## Installation

1. Download `busybox.sh` shell script command
2. Open **Terminal Emulator**, `cd` to your download directory, where `busybox.sh` is existing.
3. Execute `busybox.sh` by type this command

```
sh ./busybox
```

Where Busybox will be installed: `$HOME/bin`

The path to **Busybox** will not be added to `PATH` variable after installation, so you have to add it manually by setting Initial command for **Terminal Emulator** in order to use **Busybox** program.

Open Terminal Emulator, click ***3 dot icon*** button > **Preferences** > **Initial Command** and type this text:

```
export PATH+=:$HOME/bin
```
