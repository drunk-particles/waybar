# Waybar Themes for opinionated Omarchy

###### A collection of my Waybar themes – have fun exploring and customizing them!



## Usability

These configs are Omarchy-based, including optional Omarchy-specific modules (logo, screen recorder, update module, cava, waycat, weather,mpris).
Aside from that, they use standard modules (e.g. pacman updates, wttrbar), so they can be used on any distro by simply removing the Omarchy modules and define colors.

## Instructions

These Waybar configurations use additional packages such as wttrbar, (weather module) and waybar-cava-module-update-git (pacman AUR updates).

yay -S waybar-module-pacman-updates-git
yay -S wttrbar



#### Core Bar & Script Dependencies

- **Waybar:** The main status bar package.

- **Python 3:** Required to execute the `cava.py` script.

- **Playerctl:** Essential for the `mpris` module to control media and fetch metadata.

- **wttrbar:** A specific helper for the `custom/weather` module to format JSON output from wttr.in.

- **waybar-module-pacman-updates:** Needed for the `custom/updatespacman` module.

  

  #### Audio & Visuals

- **CAVA:** The console-based audio visualizer used by your Python script.

- **PulseAudio or PipeWire-Pulse:** To handle audio volume and the `pulseaudio` module.

- **pamixer:** Specifically used in your `on-click-right` command to toggle mute.

  

  #### Fonts & Icons (The "Ghost" Requirement)

​    This config uses many Nerd Font symbols (e.g., ``, ``, ``). Without these, you will see boxes:

- **ttf-nerd-fonts-symbols:** Provides the specific glyphs used in your format strings.

- **Font Awesome:** Often used as a fallback for some of your status icons.

  

  #### System Integration & Utilities

- **Bluez & Bluez-utils:** For the Bluetooth module.

- **bluetui:** The specific terminal UI your config calls for Bluetooth management.

- **btop:** The system monitor launched when clicking the CPU module.

- **NetworkManager:** Typically required for the `network` module to display Wi-Fi/Ethernet status.

  

  #### Custom "Omarchy" Binaries

​    This config relies heavily on a custom suite called **Omarchy**. Ensure these scripts are in your `$PATH`:

- `omarchy-menu`, `omarchy-launch-wifi`, `omarchy-cmd-tzupdate`, and `omarchy-launch-audio`.



### Ancient Runes 

![](https://github.com/drunk-particles/waybar/blob/main/Ancient%20Runes/Ancient%20Runes.png)

I loved this one. it's based on omarchy'd default waybar css, with some added modules and tweaking.

### Arctic Segments

![](https://github.com/drunk-particles/waybar/blob/main/Arctic%20Segments/Arctic%20Segments.png)

I mostly use this one now. it's pretty good!

### Cyber Pills

![](https://github.com/drunk-particles/waybar/blob/main/Cyber%20Pills/Cyber%20Pills.png)

![](https://github.com/drunk-particles/waybar/blob/main/Cyber%20Pills/Cyber%20Pills1.png)

umm....it's not bad but not that good either. Maybe some modification is needed.





## **Quick Install Command (Arch/AUR):**

```
yay -S waybar playerctl wttrbar waybar-module-pacman-updates-git cava pamixer bluetui btop ttf-nerd-fonts-symbols-common
```

