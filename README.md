# Custom Mod Editor Feature Portfolio

## Overview
This repository documents my work extending a popular mod editor to support loading compressed mod files.
The actual source code and implementation remain **private** to respect creator rights.

Instead, this repo highlights:
- **Problem**: The editor did not natively support mod files, only project files
- **Solution**: I engineered a loader that imports mod files, maps their resources, and links them into the project
- **Outcome**: Fully functional integration with proper resource linking and project metadata population

## Demo (videos coming soon)
Planned showcase:
- Original editor workflow (no mod import)
- Modified editor workflow (import, edit, save, and launch a project from a mod)

## Key Contributions
- Implemented **resource loader** for mod files (Bundles, EBX, RES, Chunks)
- Built **dependency mapping** (e.g., RES → MeshSet → Chunks, Textures → Chunk refs)
- Handled **data decompression and serialization** for modified assets
- Applied **project metadata integration** (title, author, screenshots, icon)
- Made **UI adjustments** so users could view/load mods within the editor window

## Skills Demonstrated
- C# (.NET), WPF/UI modifications
- Binary I/O, custom serialization, reverse-engineering
- Dependency graph linking, asset integrity handling
- Extending an existing large C# codebase
