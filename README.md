# Waveshare-6-HD-epaper-with-RP2B
This is a full description, on how to implement the 6" HD epaper with a Raspberry Pi 2B. Either for simply showing text, or for Smart Home integration with Home Assistant.

Requirements


• Raspberry Pi 2B

• Waveshare 6" HD e-Paper HAT with IT8951 Driver Board

• VCOM value from the FPC ribbon cable (e.g. -2.30) — printed on the cable

• Raspberry Pi OS Trixie (Debian 13) freshly installed

• Home Assistant running somewhere on the network

• LAN cable or USB Wi-Fi adapter



Where to Find Key Values



• VCOM value: printed on the FPC ribbon cable of the display

• HA IP: Home Assistant → Settings → System → Network

• HA Token: Home Assistant → Profile → Security → Long-Lived Access Tokens

• Entity IDs: Home Assistant → Settings → Devices & Services → Entities

When copying Code, "user" must be replaced with actual user name
