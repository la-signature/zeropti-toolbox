# Zeropti Toolbox

Zeropti Toolbox is a modified version of **AtlasOS Toolbox** (https://github.com/Atlas-OS/atlas-toolbox),
distributed under the **GNU General Public License version 3** (see `LICENSE`). It is the Toolbox that
**Zeropti OS** (https://github.com/la-signature/zeropti-os, based on AtlasOS) installs.

Zeropti Toolbox is not affiliated with, nor endorsed by, AtlasOS or its authors. "AtlasOS" is named only to
credit the original software. The complete source code of Zeropti Toolbox is this repository.

## Changes made by Zeropti (November 2026)

- Visible name "AtlasOS Toolbox" / "Atlas Toolbox" -> "Zeropti Toolbox" (window title, headers, settings,
  installer name, Start menu and desktop shortcuts, file description); old "Atlas Toolbox" shortcuts are
  removed on install.
- AtlasOS brand images replaced by Zeropti images (icon, logos, banner from the Zeropti OS wallpaper).
- Translations: "AtlasOS" / "Atlas" -> "Zeropti OS" where they name the installed system; the warning
  still credits the AtlasOS team; the documentation tile still opens the AtlasOS documentation.
- Links: GitHub tile and settings -> Zeropti OS / Zeropti Toolbox repositories; Discord tile and "report a
  bug" -> Zeropti Discord (https://discord.gg/MzxwsmqER); the Ko-fi tile (AtlasOS donations) is removed.
- Updates: checks https://github.com/la-signature/zeropti-toolbox releases (installed through Zeropti OS).
- Build: paths no longer depend on the repository name; a tag `vX.Y.Z` makes a draft release with
  `AtlasToolbox-Setup.exe`.
- Version 0.2.1 (based on AtlasOS Toolbox 0.2.0).

Unchanged on purpose, because Zeropti OS (like AtlasOS) relies on them: the install folder
`C:\Program Files\Atlas Toolbox`, `AtlasToolbox.exe`, the installer asset name `AtlasToolbox-Setup.exe`,
the registry key `HKLM\SOFTWARE\AtlasOS\Toolbox`, the data folder `C:\ProgramData\AtlasOS\Toolbox`, and the
installer AppId (so it replaces an installed Atlas Toolbox).
