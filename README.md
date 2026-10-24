# Doudiandian / 豆点点 — Windows Fuse Bead Pattern Maker

**Official downloads:** [Microsoft Store](https://apps.microsoft.com/detail/9NLJH5HG9L5V) · [itch.io — complete portable Windows app](https://heykim.itch.io/doudiandian)

**中文入口：** [完整中文使用说明](docs/zh-CN.md) · [图片转拼豆图纸实例教程](https://heykim.itch.io/doudiandian/devlog/1724459/windows)

Doudiandian is an offline tool for turning JPG and PNG images into editable fuse bead patterns on Windows 10/11 x64. Refine individual beads, check per-color quantities, and export a PNG chart or A4 PNG pages. Images are processed and projects are saved locally; no app account is required.

This repository contains product documentation, tutorials, and feedback only. The desktop application's source code is not provided here. It is maintained by the developer: HeyKim on itch.io and DaMiZhou Studio on Microsoft Store.

## Download and start

These instructions describe the Windows 1.0.3 portable edition. The full itch.io download is free. You can skip the suggested US$3.99 contribution; optional support funds development and unlocks no additional features or rights.

1. Download `Doudiandian-1.0.3-Windows-x64.zip` from the official itch.io page.
2. Choose **Extract All**, then open the extracted folder and run `Doudiandian.exe`.
3. Keep the DLLs, `resources`, and `locales` folders together. No Node.js or developer tools are needed.
4. Choose **Language settings > English** or **Simplified Chinese** to save your language preference.

The portable executable is not code-signed, so Windows may show a publisher warning. Read `README-English.txt` and the notices included in the download.

## Make your first pattern

1. **Import one image.** Choose a JPG or PNG up to 10 MB and 6,000 pixels per side. Start with a clear silhouette. Transparent areas stay empty; an opaque background becomes part of the design.
2. **Choose the grid and colors.** Grids support 8–100 cells per side, with conversion presets from 2 to 30 colors. Fit the whole image with padding or crop to fill. Compare previews before accepting the result.
3. **Refine and count.** Use brush, eraser, fill, eyedropper, undo, and redo. Zoom in to adjust individual cells. Quantities update as you edit.
4. **Save locally.** Use **My projects** to keep up to 50 editable designs on this computer and reopen them later.
5. **Export a chart.** Save a coded grid or bead-style PNG, optionally including the color-and-quantity list. A PNG is a chart image, not a complete editable project backup.

You can also edit one of 60 included original patterns, draw on a blank grid, or create short text patterns with three bundled fonts. Text patterns support up to 20 characters, including line breaks.

![Edited sequence of actual Doudiandian screens showing sunflower conversion, a one-bead edit, quantities, and PNG export](https://img.itch.zone/aW1nLzMxMjQzMjM1LmdpZg==/original/I0KOfn.gif)

The GIF combines real app states; it is not a continuous recording or speed test. [Open the actual edited sunflower PNG](https://img.itch.zone/aW1nLzMxMjQzMjUyLnBuZw==/original/lUNOG8.png): 50 × 50 grid, 17 colors, 836 beads.

## Read the tutorials

- [How to Turn an Image into a Fuse Bead Pattern on Windows](https://heykim.itch.io/doudiandian/devlog/1724439/how-to-turn-an-image-into-a-fuse-bead-pattern-on-windows)
- [How to Adjust Colors and Count Beads in a Fuse Bead Pattern](https://heykim.itch.io/doudiandian/devlog/1724446/how-to-adjust-colors-and-count-beads-in-a-fuse-bead-pattern)
- [How to Export A4 PNG Fuse Bead Pages on Windows](https://heykim.itch.io/doudiandian/devlog/1726114/how-to-export-a4-png-fuse-bead-pages-on-windows)
- [Windows 怎么把图片转成拼豆图纸？附修改与用珠统计实例](https://heykim.itch.io/doudiandian/devlog/1724459/windows)

## Before making the design

The palette uses 221 MARD community screen-color references, without a guarantee of physical bead colors. Compare with your own beads. For A4 PNG pages, use **Actual size / 100%** in external printing software, turn off **Fit to page**, and measure the printed scale before using a pegboard. There is no PDF export, direct printer control, automatic background removal, batch conversion, or cloud sync.

Development used AI-assisted coding, and the sunflower input was made with AI image tools. The demonstrated bead results are actual local image-processing output.

## Feedback

Open an issue with your Windows version, app version, steps, expected result, and actual result. Please do not upload private photos, personal information, or images you cannot share. Use a small non-sensitive sample if needed. You can also comment on the [itch.io product page](https://heykim.itch.io/doudiandian).
