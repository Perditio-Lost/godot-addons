## License Notice

Each plugin included in this repository retains its **original LICENSE file** and **copyright notices**.  
All rights belong to their respective authors.

I may apply modifications or adjustments to some plugins to better fit my personal usage or workflow.  
All such changes will be clearly documented, and the original authors’ licenses and credits will be fully preserved.  

Almost all plugins have had unessential files or directories removed (e.g., README.md, images, screenshots) that do not affect functionality.  

If any author wishes their plugin or derivative version to be removed from this repository, please open an issue and the request will be handled promptly.

## Usage

To use the plugins in your own Godot project:

1. **Clone this repository**, or download it as a ZIP.
2. Locate the `addons/` folder inside this repository.
3. **Move the entire `addons` directory** into the root folder of your Godot project.
4. Open Godot and go to:
   **Project > Project Settings > Plugins**
5. Find the plugins you want to use and **enable them**.

## Plugins Overview

This section provides a brief overview of each plugin included in this repository.  
Along with any personal modifications and their main features.

### 1. godot-vim

**Original Author:** joshnajera  
**Repository:** <https://github.com/joshnajera/godot-vim>  
**License:** MIT

#### Features

- Vim-style keybindings and navigation inside Godot script editor
- Supports normal, insert, visual modes
- Provides basic motion, text editing, and search commands

#### Modifications

- Customized keybindings to match personal Vim workflow

---

### 2. relative_line_numbers

**Original Author:** CrankyCranton  
**Repository:** <https://github.com/CrankyCranton/Relative-Line-Numbers>  
**License:** MIT

#### Features

- Renders the script editor line numbers relative to the cursor.

#### Modifications

- Changed font size and line height positioning to better suit my personal preferences.
- Adjusted the display of line numbers above the current line to always be positive, instead of the original design which could show negative numbers.
- The current line, previously displayed as 0, is now shown with its absolute line number for clarity.
