# Assets

The `assets/` directory contains media and graphical resources used in the AI Battle Arena project.

## Contents:

- **images/** - Visual assets such as UI elements, logos, and game backgrounds.
- **sounds/** - Audio files used in the game, including sound effects and music.

## Usage:

All assets are loaded dynamically within the game engine. Ensure that the file paths are correctly referenced in the code.

Example to load an image:

```python
import pygame
bg_image = pygame.image.load('assets/images/background.png')
