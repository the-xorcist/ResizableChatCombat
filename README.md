# ResizableChatCombat

**Version:** 1.0.0  
**Author:** the-xorcist  
**Release Date:** 2026-02-19

## Description

A BepInEx mod for Erenshor that makes the chat and combat log windows resizable when UI edit mode is enabled. Drag the corner handles to customize window sizes to your preference, with settings automatically saved and restored.

## Features

- **Resizable Windows** - Drag corner handles to resize both chat and combat windows
- **UI Edit Mode Integration** - Resize handles appear when you enable "Toggle UI Movement" in game options
- **Persistent Settings** - Window sizes are automatically saved to config and restored on game load
- **Click-Through Prevention** - Resize handles block game input while dragging to prevent accidental actions
- **Configurable Limits** - Adjustable width and height ranges for both windows via config file

## Installation

1. Install BepInEx for Erenshor
2. Copy `ResizableChatCombat.dll` to your `BepInEx/plugins/` folder
3. Launch the game

## Usage

1. Enable UI edit mode in-game by pressing the "Toggle UI Movement" key (check your keybindings)
2. Blue resize handles will appear at the corners of the chat and combat windows
3. Drag the handles to resize the windows to your desired size
4. Settings are automatically saved when you release the mouse

## Source Code

Source code is included in the `-source.zip` archive.
