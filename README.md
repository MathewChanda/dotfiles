# Mathew's Dotfiles

## Ghostty 

ghostty is a minimal terminal emulator configuration used here. It supports a transparent background for blending with your desktop wallpaper and includes the "Tokyo" color theme for a vibrant, high-contrast look. 

## .zshrc

The .zshrc uses a set of common plugins to improve shell productivity and appearance:

- oh-my-zsh: framework for managing Zsh configuration and themes.
- zsh-autosuggestions: suggests commands as you type based on history.
- zsh-syntax-highlighting: highlights command syntax and potential errors.
- zsh-completions: additional completion definitions for many tools.
- powerlevel10k: fast, highly customizable prompt theme with icons and git info.
- fzf (integration): fuzzy finder for history, files and command completion.

Configuration notes:
- Load plugins in .zshrc via the plugins=() array or individual source lines.
- Keep zsh-autosuggestions before zsh-syntax-highlighting in sourcing order for best behavior.
- Tune powerlevel10k via its configuration wizard (~/.p10k.zsh).

## tmux.config 
Added tmux keybindings similar to WASD keys bindings 

## Development tools
- [NotchNook](https://lo.cafe/notchnook)
  - A macOS utility that transforms the MacBook notch into an interactive hub for media controls, file storage, widgets, and quick system interactions.
- [Raycast](https://www.raycast.com/)
  - A productivity launcher for macOS that lets you quickly open apps, run scripts, manage windows, search files, use AI tools, and automate workflows from your keyboard.

- [Ollama](https://ollama.com/)
  - A local AI runtime that allows you to download and run large language models (LLMs) directly on your machine for private and offline AI development.

- [Xnapper](https://xnapper.com/)
  - A screenshot tool for macOS focused on creating clean, polished screenshots with padding, backgrounds, redactions, and quick annotations for sharing online.

- [yabai](https://github.com/koekeishiya/yabai)
  - A tiling window manager for macOS that automatically organizes application windows into efficient layouts and enables keyboard-driven window management.

- [Bartender](https://www.macbartender.com/)
  - A macOS utility that helps organize and hide menu bar icons, reducing clutter and giving more control over what appears in the top menu bar.