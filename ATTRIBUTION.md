# Elysia — third-party icon attribution

Elysia is licensed **GPL-3.0**. It incorporates icons derived from two upstream themes.

## Papirus icon theme — GPL-3.0
- © Papirus Development Team — https://github.com/PapirusDevelopmentTeam/papirus-icon-theme
- License: **GPL-3.0**
- Used: the **symbolic** icon set for `actions/` and `status/` (the bulk of Elysia's
  monochrome/taskbar icons), plus a few symbolic companions in `devices/`, `places/`,
  `categories/` (e.g. `drive-removable-media-usb-symbolic`, `user-desktop-symbolic`,
  `start-here-kde`, `kdeconnect-tray`, `preferences-desktop-display-randr`, `help-contents`).
- Modifications: layout transposed to Elysia's `<context>/<size>` structure; inline
  `style="fill:currentColor"` moved to a `fill="currentColor"` presentation attribute for
  dual-toolkit (Qt + GTK) recoloring; default `.ColorScheme-Text` unified to `#808080`.

## Breeze icons — LGPL-3.0
- © KDE Community / Breeze contributors — https://invent.kde.org/frameworks/breeze-icons
- License: **LGPL-3.0**. LGPLv3 §2 permits conveying under GPLv3, so these are included in
  this GPL-3.0 work; the Breeze-derived files remain available under LGPL-3.0 terms.
- **Include the LGPL-3.0 license text** (`LICENSES/LGPL-3.0-only.txt` from breeze-icons) in
  the repo to satisfy the notice requirement.
- Used (18 icons, niche names Elysia had no equivalent for), each **modified** with the same
  recolor fix + `#808080` default:
  `checkmark`, `computer-laptop`, `document-open-folder`, `edit-clear-history`,
  `edit-clear-locationbar-rtl`, `emblem-error`, `lighttable` (`-symbolic` companion only),
  `network-disconnect`, `network-wireless-off`, `osd-duplicate`, `osd-sbs-left`,
  `osd-sbs-sright`, `osd-shutd-laptop`, `osd-shutd-screen`, `system-suspend-uninhibited`,
  `video-display-brightness`, `view-barcode-qr`, `weather-none-available`.

## Notes
- Someday these icons will be replaced, who knows when.
