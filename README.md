# Omarchy XP Horizon — base theme

A coastal Omarchy colour theme with an original Horizon wallpaper. This repository is the **base theme only**: it contains `colors.toml`, `icons.theme`, `backgrounds/horizon-coast.png` and `preview.png`. It does **not** install the XP Start menu, Quick Launch, Show Desktop, Task Buttons, 4 px window borders/6 px corners, screensaver branding or startup sound.

Install from this repository's public URL with Omarchy's **Install → Style → Theme** menu, or `omarchy theme install <repository-url>` on a compatible Omarchy release. Do not use the parent combined-package directory as a theme repository: its theme files are nested in `theme/`.

The preview is a real 5120×1440 desktop screenshot reduced proportionally to 2560×720. It shows the **optional, separately installed add-ons** (open Horizon Start menu and full bottom bar), not what the base theme alone installs. The base theme will not move your bar. Yaru-blue is a separately installed system icon theme, referenced but not bundled.

An optional, separately consented **combined add-on package** exists for Omarchy 4.0.6 / Quickshell 0.3.2 / Hyprland Lua, with four plugins, window styling, screensaver integration and opt-in startup audio. Its installer must be invoked manually in an unlocked graphical session; ordinary theme installation never executes it. It has its own scoped uninstall and safety checks. The combined archive is **not** part of this theme repository and needs a separately published, versioned download and instructions before it can be offered to users. No security filter is bypassed.

The supplied coast image was generated through a ChatGPT workflow and supplied by Roger; it is not a camera photograph or represented as exclusively owned. Original code/configuration is MIT; covered original media is CC BY 4.0. See `LICENSE`, `LICENSES/CC-BY-4.0.txt`, and `ATTRIBUTION.md`. XP Horizon is independent of Microsoft and is not endorsed by it. The separately installable add-on archive is not yet publicly released.
