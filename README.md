# Display2D Engine

Display2D is an advanced 2D game engine built entirely inside Scratch. Its goal is to recreate the structure and capabilities of a modern game engine using a fully custom runtime, renderer, memory system, and editor environment.

Display2D is not just a Scratch project. It is designed to function as a complete engine framework capable of running games, editors, and interactive software while demonstrating how real engines work internally.

This project is currently in active development and will continue to expand with many new systems and capabilities.

# Vision and Goals

The goal of Display2D is to become a fully featured engine that provides the same core systems found in professional engines, adapted to work within Scratch.

The engine is being designed to support:

- Full game creation
- Integrated editor tools
- Custom user interfaces
- Large worlds and maps
- Efficient object management
- Expandable architecture

Display2D is intended to be both a practical engine and a technical experiment in pushing Scratch beyond its normal limitations.

# Core Architecture

Display2D is built around several core systems:

### Custom Rendering Pipeline

All objects are rendered manually using engine-controlled rendering instead of Scratch’s default sprite behavior. This allows full control over how objects are displayed.

### Memory-Based Object System

Objects exist as memory elements, with their properties stored in engine memory. These elements can be created, modified, rendered, and deleted dynamically.

This allows:

- Large numbers of objects
- Flexible object control
- Scalable world design

### RAM-Style Variable System

The engine uses address-based RAM storage to manage internal state, settings, and runtime data.

This creates a structured and expandable internal memory system.

### Texture and Asset System

Display2D supports loading external image data and rendering it at runtime.

This allows:

- Custom textures
- Sprite graphics
- Asset management

### Scene and Screen System

The engine supports multiple screens and modes, allowing separation between:

- Games
- Editors
- Menus
- Tools

### GUI and Window System

Display2D includes a window system that allows creation of custom interface elements such as:

- Windows
- Text displays
- Buttons
- Editor tools

# Planned Features

Display2D is planned to expand significantly beyond its current capabilities.

Future systems may include:

### Editor Environment

A full built-in editor for:

- Creating levels
- Placing objects
- Editing properties
- Managing assets

### Camera System

- Support for camera movement, allowing large scrollable worlds.

### Tilemap System

- Efficient rendering and management of large tile-based environments.

### Animation System

- Support for animated textures and objects.

### Collision and Physics

- Object interaction and collision detection.

### Layer and Depth System

- Control over render order and visual layering.

### Asset Management System

- Improved loading, storage, and reuse of textures and data.

### UI Framework

- A complete system for building user interfaces.

### Project and File System

- Support for saving and loading engine data and projects.
