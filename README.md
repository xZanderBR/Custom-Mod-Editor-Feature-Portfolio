# Custom Mod Editor Feature Portfolio

## Overview
This repository documents my work extending a popular mod editor to support loading compressed mod files.
The actual source code and implementation remain **private** to respect creator rights. The developers didn't intend for assets to be obtainable from mods.

Instead, this repo highlights:
- **Problem**: The editor did not natively support mod files, only project files
- **Solution**: I engineered a loader that imports mod files, maps their resources, and links them into the project
- **Outcome**: Fully functional integration with proper resource linking and project metadata population

## Demo
[![Youtube Video](https://github.com/user-attachments/assets/558a6086-721a-4122-9dad-dd3ce8fe3fd5)](https://www.youtube.com/watch?v=Hw3yRm_RkQg)

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

## FAQ
**Q: Can I try the loader?**  
A: The implementation is private; the videos show the workflow. I’m happy to discuss the approach in interviews.

**Q: Why no code?**  
A: Sharing internals could enable misuse and violate community expectations. This portfolio focuses on **design, scope, and results**.

**Q: Is this a fork or a plug-in?**  
A: It’s a **built-in feature** integrated directly into the editor’s codebase (not an external extension).
