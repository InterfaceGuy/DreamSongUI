# DreamSongUI

A dynamic web interface for visualizing and navigating Obsidian Canvas files in a linear flow layout.

## Features

- Converts Obsidian Canvas files into a linear, scrollable web interface
- Supports images and videos with autoplay functionality
- Handles both directional and non-directional connections between nodes
- Automatically arranges connected media and text in an alternating pattern
- Responsive design that adapts to different screen sizes

## Usage

1. Place your `DreamSong.canvas` file in the root directory
2. Add any referenced media files in their respective submodules
3. Open `index.html` in a web browser to view the linear flow layout

## Structure

- `linearFlowCanvas.js`: Main JavaScript file handling canvas parsing and rendering
- `update_submodules.py`: Python script for managing media submodules
- `styles.css`: CSS styling for the web interface

## Requirements

- Modern web browser with JavaScript enabled
- Python 3.x (for submodule management)
- Git (for submodule operations)
