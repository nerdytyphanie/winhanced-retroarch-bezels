# Attribution and third-party notices

## Duimon artwork and this conversion

- **Duimon**: https://github.com/Duimon/Duimon-Mega-Bezel and https://github.com/Duimon/Duimon-Mega-Bezel-Source
- The 62 converted TV/computer/arcade system pairs use Duimon's rendered PNG artwork. Winhanced's changes crop and rearrange the side artwork, preserve its proportions, remove the drawn center screen, and create transparent full-height 4:3 apertures for 16:9 and 16:10 displays. The matching overlay and viewport files were updated for those layouts.
- Duimon's original artwork carries **CC BY-NC-ND 4.0**, reproduced in DUIMON-LICENSE.md. It is not relicensed under RetroBat's share-alike terms. Original artwork, logos and trademarks retain their respective ownership and license terms.
- Remaining RetroBat artwork and existing handheld layouts are credited below. Systems without matching Duimon artwork retain their existing 16:9 bezel and have no 16:10 overlay configuration.

## Bezel artwork

- **RetroBat Team**: https://www.retrobat.org/ and https://github.com/RetroBat-Official/retrobat-bezels
- **Batocera decoration contributors**: https://github.com/batocera-linux/batocera-bezel
- RetroBat's bezel README explicitly identifies its collection as forked from Batocera's decoration sets. The starting console artwork was taken from the RetroBat installation's default decoration set. Upstream contributor histories remain available at the linked repositories.
- **RetroBat project credits:** Adrien Chalard (Kayl), copyright 2017-2019; RetroBat Team, copyright 2020-2026, as stated in its current license notice.
- The changes in this project include corrected GB/GBC apertures, 16:10 extensions, continuous Game Gear/GBA/Lynx casing redraws, generated overlay configurations and resolution metadata. Many original 16:9 images remain unchanged. Changes do not imply endorsement by the upstream projects.
- RetroBat states CC BY-NC-SA 4.0 terms for its overall project and written/graphic material; its complete notice is preserved in `RETROBAT-LICENSE.txt`, and the CC terms in `CC-BY-NC-SA-4.0.txt`. RetroBat-derived artwork other than the separately credited Duimon artwork is distributed subject to those noncommercial/share-alike terms and any applicable original third-party terms. Upstream authors retain their rights. The bezel repositories do not provide a per-image license/author map; these credits must not be read as proof that every third-party logo has a blanket license grant.
- Original console names, logos and trademarks remain the property of their respective owners. No trademark rights are granted here.

## RetroArch shaders

Credit to **RetroArch / Libretro** and the individual shader authors:
https://www.retroarch.com/ and https://github.com/libretro/slang-shaders

| Preset / source | Credits | License information retained from source |
| --- | --- | --- |
| `gameboy.slangp`, `gb-pass0` through `gb-pass4`, `gb-params.inc`, palette/background textures | Harlequin (2013), Matt Akins (2024-2025); RetroArch/Libretro collection | Shader source states GPL version 3 or later. Supporting preset and resources retained as the upstream shader set. |
| `authentic_gbc.slangp`, `authentic_gbc.slang`, `to_lin.slang`, related `.inc` files | fishku (2024-2025) | CC0/public domain declaration in the main shader; supporting files refer to it. |
| `gba-agb001-color-motionblur.slangp` / `agb001.slang` | endrift | MPL 2.0 for AGB-001. |
| `response-time.slang` | Based on Harlequin's Game Boy/LCD response function | GPL version 2 or later. |
| `gba-color.slang` | hunterk; modifications by Pokefan531 | Public domain declaration. |
| `lcd-grid-v2.slangp` / `lcd-grid-v2.slang` | cgwg LCD shader family; RetroArch/Libretro collection | The distributed source has no explicit license header; no replacement or blanket license is asserted by this repository. |
| `lcd1x_nds.slangp` / `lcd1x_nds.slang` | jdgleaver; original LCD code by Gigaherz; color code by hunterk and Pokefan531 | GPL version 2 or later; original components credited as public domain in its header. |
| `crt-hyllian-fast.slangp` / `crt-hyllian-fast.slang` | Hyllian (2011-2015), cgwg mask, DariusG and hunterk ports | MIT permission notice retained in shader source. |

Full shader source is included in `shaders.zip`, not compiled-only binaries. Source license and copyright comments are preserved. Preset paths were flattened for portable packaging; the GBA preset's built-in border pass and BORDER texture were removed. Its three effect shaders are unchanged. LCD grid v2 and NDS shader code are unchanged.

GPL-2.0, GPL-3.0, MPL-2.0 and CC0 license texts are included. The MIT notice is preserved in `crt-hyllian-fast.slang`. There is no single license for this mixed collection; the artwork's CC terms do not relicense shaders, and shader licenses do not relicense artwork.
