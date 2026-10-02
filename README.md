# Winhanced RetroArch bezels

Runtime assets for Winhanced users with a detected RetroBat installation. Artwork is a test snapshot awaiting visual validation.

## Downloads and installation

- manifest.json lists each package, its SHA-256 hash, and the paths and hashes of its installed files.
- shaders.zip contains all shared RetroArch shader presets, shader source, textures, includes and notices. Winhanced downloads it when ROM scanning identifies a RetroBat installation.
- <system>.zip contains that system's 16:9 and 16:10 bezel PNGs, overlay CFGs, INFO files, viewport JSON and notices. Winhanced downloads it only when ROMs for that RetroBat system are detected. A system with no 16:10 configuration includes its existing 16:9 bezel only.
- Extract archives under Winhanced's data directory (normally %LOCALAPPDATA%/Winhanced/). Each archive contains the RetroArchAssets/ directory structure used by the application.
- Packages whose installed file hashes match the manifest are skipped. A changed package or missing file is downloaded again. Download failures leave ROM importing available.
- Downloads are not enabled for standalone RetroArch, ES-DE, EmuDeck or other ROM libraries.

## Artwork and licenses

Converted TV systems use a transparent full-height 4:3 viewport. Existing handheld layouts are unchanged. See [ATTRIBUTION.md](ATTRIBUTION.md) for Duimon, RetroBat/Batocera and shader credits, and the included source-specific license notices. There is no single blanket license for this mixed collection.
