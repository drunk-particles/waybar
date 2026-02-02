# Waybar Themes for Opinionated Omarchy

A curated personal collection of Waybar styles tailored for **Omarchy** — the sleek, opinionated Arch + Hyprland experience. Dive in, customize, and make them your own!

These themes build on Omarchy's ecosystem (custom logo, screen recorder, updates, cava visualizer, waycat, weather via wttrbar, mpris, etc.), but they're flexible — strip out the Omarchy-specific modules and adjust colors to run them on any Hyprland/Arch setup.

## Key Features Across Themes

- Omarchy-flavored modules (optional): logo, recorder indicator, update notifier, cava, waycat, weather, mpris
- Standard modules: workspaces, clock, pacman updates, network, volume, CPU (btop on-click), battery, Bluetooth, tray
- Polish: Nerd Font icons, hover effects, color alerts (low battery, high load), subtle spacing/animations

## Dependencies (Full Experience)

Install these via AUR/Arch package manager:

**Core & Scripts**

- waybar
- python3 (for cava visualizer script)
- playerctl (mpris media)
- wttrbar (weather formatting)
- waybar-module-pacman-updates-git (updates counter)

**Audio/Visuals**

- cava
- PipeWire/PulseAudio + pamixer (volume/mute)

**Fonts & Icons** (critical — no boxes!)

- ttf-nerd-fonts-symbols-common (or full variant)
- Font Awesome (fallback icons)

**Utilities**

- bluez + bluez-utils
- bluetui (Bluetooth TUI)
- btop (system monitor)
- networkmanager

**Omarchy Binaries** (in $PATH)

- omarchy-menu
- omarchy-launch-wifi
- omarchy-cmd-tzupdate
- omarchy-launch-audio

**Quick Arch/AUR install command:**

Bash

```
yay -S waybar playerctl wttrbar waybar-module-pacman-updates-git cava pamixer bluetui btop ttf-nerd-fonts-symbols-common
```

## The Themes

### 1. Ancient Runes

My all-time favorite — starts from Omarchy's default CSS base, then adds refined modules, mystical icons, extra spacing, and subtle glows. Elegant, slightly arcane vibe. Perfect for a thoughtful, crafted look.

![[Ancient Runes Theme Screenshot](screenshots/ancient-runes.png)](https://github.com/drunk-particles/waybar/blob/main/Ancient%20Runes/Ancient%20Runes1.png) 

### 2. Arctic Segments

My current daily driver. Sharp, icy, modern segmented blocks with excellent info density and breathing room. Clean, productive, and visually satisfying without excess flash.

![[Arctic Segments Theme Screenshot](screenshots/arctic-segments.png)](https://github.com/drunk-particles/waybar/blob/main/Arctic%20Segments/Arctic%20Segments1.png)

### 3. Cyber Pills

Cyberpunk-inspired with rounded neon "pill" modules and bold accents. It's decent as a starting point, but rough: some color clashes, inconsistent spacing, and glow can feel cheap on certain displays. High potential — needs contrast tweaks, smoother transitions, and tighter grouping to shine.

![[Cyber Pills Theme Screenshot](screenshots/cyber-pills.png)](https://github.com/drunk-particles/waybar/blob/main/Cyber%20Pills/Cyber%20Pills1.png) 

