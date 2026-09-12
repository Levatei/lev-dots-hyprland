# What this environment is made of

Full overview of the applications in this dots-hyprland fork: what each one is responsible for.

## Core environment

1. **Hyprland** — Wayland compositor: manages windows, workspaces and renders the whole screen.
2. **Quickshell (ii, illogical-impulse)** — graphical shell: top bar, sidebars, widgets, overlays, settings screen.
3. **xdg-desktop-portal (hyprland/gtk/kde)** — middleware for screensharing, file pickers and portals between apps and the compositor.
4. **polkit-kde-agent** — privilege prompt agent: shows the confirmation dialog for actions requiring root.
5. **gnome-keyring** — password and secrets storage for applications.
6. **ydotool** — keyboard/mouse input emulation on Wayland, used by the shell for automations.

## Terminal and console

7. **Kitty / Foot** — terminals, opened with `Super+Enter`.
8. **Fish** (fallback — Zsh) — command-line shell inside the terminal.
9. **Starship** — fancy and informative shell prompt (git branch, time, etc.).
10. **eza** — `ls` replacement with icons and colors, aliased in Fish.
11. **yazi** — two-pane file manager right in the terminal (file manager fallback).
12. **btop** — process, CPU, RAM and network monitor in the terminal (task manager fallback).
13. **micro / neovim** — lightweight console text editors.

## Applications

14. **Fuzzel** — application launcher and search, opened with `Super`.
15. **Dolphin** (fallbacks: Nautilus, Nemo, Thunar) — file manager, opened with `Super+E`.
16. **Chrome** (fallbacks: Zen, Firefox, Brave, Chromium) — browser, opened with `Super+W`.
17. **VS Code** (fallbacks: Codium, Cursor, Zed, Kate) — code editor, opened with `Super+C`.
18. **LibreOffice / WPS / OnlyOffice** — office suite for documents and spreadsheets.
19. **Kate / GNOME Text Editor** — simple graphical text editors.
20. **GNOME System Monitor / Plasma System Monitor** — graphical task manager.
21. **mpv / mpvpaper** — video player and animated (video) wallpaper engine.
22. **System Settings (KDE) / GNOME Control Center** — graphical system settings.

## Bar, widgets and theming

23. **Matugen** — generates the Material color theme (bar colors, GTK, Kitty) from the current wallpaper.
24. **cava** — audio visualizer (equalizer bars) for shell widgets.
25. **qalc (libqalculate)** — calculator: evaluates math right in the shell search bar.
26. **SongRec** — recognizes currently playing music (Shazam-like) in the shell.
27. **translate-shell** — on-screen text translation (`Super+Shift+T`).
28. **Ollama** — local neural networks: selected-text summaries and shell assistant.
29. **kde-material-you-colors** — recolors KDE apps to match the wallpaper.

## Audio

30. **PipeWire + WirePlumber** — audio subsystem: routes audio between apps and devices.
31. **pavucontrol** — volume mixer, opened with `Ctrl+Super+V`.
32. **playerctl** — keyboard media control: play/pause, next/previous track.
33. **EasyEffects** — system equalizer and audio effects.

## Display and brightness

34. **brightnessctl** — built-in laptop screen brightness (`Fn` keys).
35. **ddcutil** — external monitor brightness over DDC/CI.
36. **hyprsunset** — night mode: removes blue light in the evening.
37. **GeoClue** — geolocation for weather, timezone and night mode.

## Screenshots, recording, OCR

38. **grim + slurp** — screen capture and region selection (`Super+Shift+S`, `Print`).
39. **hyprshot** — fallback screenshot tool when the shell is not running.
40. **swappy / satty** — quick screenshot annotation (arrows, text) before sending to clipboard.
41. **wf-recorder** — screen recording (`Super+Shift+R`).
42. **hyprpicker** — on-screen color picker to clipboard (`Super+Shift+C`).
43. **tesseract** — OCR: screenshot text recognition to clipboard (`Super+Shift+X`).
44. **wtype** — types emoji picked from search (`Super+.`) as key presses.

## Clipboard and input

45. **wl-clipboard** — Wayland clipboard (copy/paste between apps).
46. **cliphist** — clipboard history (`Super+V`).

## Session and system

47. **hyprlock** — lock screen (`Super+L`).
48. **hypridle** — dims the screen and locks the session when idle.
49. **wlogout** — logout/reboot/shutdown menu (`Ctrl+Alt+Delete`).
50. **UPower** — laptop battery: charge level and status for the bar.
51. **NetworkManager + plasma-nm** — network and Wi-Fi, applet in the shell.
52. **Bluedevil** — Bluetooth: pairing and device management from the shell.

## Fonts, cursors, themes

53. **JetBrainsMono Nerd Font** — monospace font with icons for terminal and UI.
54. **Material Symbols** — shell and bar interface icons.
55. **Readex Pro / Rubik / Space Grotesk** — shell and theme UI fonts.
56. **Twemoji** — fallback emoji font.
57. **Bibata Modern Classic** — mouse cursor theme.
58. **adw-gtk / Breeze / Darkly + Kvantum** — GTK and Qt themes so all apps look consistent.
