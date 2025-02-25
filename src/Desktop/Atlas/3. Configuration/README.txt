- Animations
  Default: Disabled
  Virtually all Windows animations are disabled

- Bluetooth
  Default: Disabled
  Enable if you use bluetooth-connected devices, make sure you have proper drivers for them as well.

- Clipboard History
  Default: Disabled
  Clipboard History, seems to break any UWP copying to clipboard as well. Minimal impact, do not resist to re-enable it.

- DEP
  Default: Disabled
  In layman's terms, a mitigation to prevent unauthorized programs from writing to protected memory. Game anti-cheats like Valorant/FACEIT use this. So if you play any of those, enable it.

- DWM
  QoL script to kill DWM then launch your game. (will be improved soon)

- Firewall
  Default: Enabled
  Configures windows firewall, frequently needed for Microsoft Store.

- FSO
  Default: Disabled
  FSO (Fullscreen Optimizations) runs Fullscreen Exclusive games in a "highly optimized" borderless window. Which allows for faster alt-tabbing.
  All you need to know is that Fullscreen Exclusive > borderless window, so it is highly recommended to keep it disabled.

- HDD
  Default: Disabled
  Enables features that improve hard disk performance, like prefetching and font caching.

- Network Discovery
  Default: Disabled
  Also known as network sharing, used to, as the name implies share files over the netork. There is no disable script as it is only other dependencies.

- Notifications
  Default: Disabled
  If you do not understand what this is you should not be allowed to use a computer.

- Power
  Default: Enabled
  - Sleep States:
    https://github.com/Atlas-OS/Atlas/wiki/3.-Post-Install#sleep-states
    Allows you to use sleep/hibernate.
  - Idle:
    Disables system idle, will DISPLAY your CPU being used at 100%. It is not actually under 100% load.

- Printing
  Default: Disabled

- Search Indexing
  Default: Disabled
  Enables indexing of files for faster searching within explorer (uses lots of cycles)

- Start Menu
  Various scripts, including removing the start menu and replacing it with Open-Shell

- Store
  Default: Enabled
  Disables Microsoft Store, can break a lot of things in the process. Please READ THE DISCLAIMER in the script before continuing.

- UAC
  Default: Enabled (Minimum)
  If you disable it and later re-enable it and then you have issues starting apps: go into safe mode and enable the Appinfo service with ServiWin.

- UWP
  Default: Enabled
  Disables UWP entirely, breaks a lot in the process. Only use if you know what you are doing and understand the drawbacks.

- VPN
  Default: Disabled

- Wifi
  Default: Enabled

- Workstation (SMB)
  Default: Disabled
  If you use SMB shares or AMD Ryzen Master, enable this.
