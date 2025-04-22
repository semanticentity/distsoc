# Distsoc Playground

Live demo: https://codepen.io/semanticentity/full/xbbVpdX

![distsoc](https://github.com/user-attachments/assets/f5d98b55-de3c-4d59-bf3c-d11d37107e53)

An interactive playground for exploring distributed systems, CLIs, and APIs visually, with an expanded world and enhanced features.

## Features

### Navigation & Interaction
- Arrow keys to move your character around the expanded world
- Double-click on nodes or any location to move there directly
- Click on nodes to open the info panel
- When near a node, press `E` to open the terminal
- Use the terminal to interact with nodes - type `help` for a list of commands

### Camera System
- **Unlimited World**: Explore beyond the canvas edges with the new camera system
- **Zoom Controls**: Use mouse wheel to zoom in/out for detailed or overview perspectives
- **Camera Panning**: Hold middle mouse button to pan the camera
- **Auto-Follow**: Camera follows player by default (hidden feature: Shift+Double-click to toggle)
- **Mini-Map**: Shows your position relative to all nodes in the bottom-right corner

### Enhanced Visualization
- **Task Guidance**: Clear visual guidance showing which nodes to connect
- **Node Tooltips**: Hover over nodes to see detailed information
- **Input/Output Tooltips**: Hover over node edges to see connection compatibility
- **Network Scan**: Run `scan network` in terminal to see all nodes with current connection highlighted
- **Visual Indicators**: Source, middle, and target nodes are clearly labeled during tasks

### Enhanced UI
- **Random Tasks**: Each session starts with a random pipeline-building challenge
- **Resizable Terminal**: Drag the bottom-right corner to resize the terminal window
- **Auto-focus**: Terminal input is automatically focused when opened
- **Node Status Indicators**: 
  - Orange dot: Active node
  - Red dot: Locked node
  - Gray dot: Idle node
- **Multi-tasking**: Click on other nodes while the terminal is open to view their info
- **Controls Help**: Basic controls displayed in the bottom-left corner

## Getting Started

1. Open `distoc.html` in your browser
2. Follow the on-screen guidance to complete tasks
3. Move to a node and press `E` to connect
4. Use `help` to see available commands
5. Try zooming in/out with the mouse wheel to explore the expanded world

## Future Enhancements
- Ability to move nodes around and add new nodes
- READMEs for tools, nodes, and pipelines
- Visual documentation that can be read while looking at zoomed-out graphics

**License:** CC BY-NC-ND 4.0  
Attribution-NonCommercial-NoDerivatives 4.0 International

---

**Note:** This README is for the Distsoc playground (`distoc.html`). Do not overwrite or copy over the original file.
