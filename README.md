# ColorMatch Round Generator

A single-page web app for filling out colormatch rounds and printing 4×6 in labels.

**Live site:** https://edellenator.github.io/colormatch-round-generator/

## How it works
- Everything runs in the browser (Chrome / Edge recommended). There is no server and no database.
- The ColorMatch Log is saved in **that browser's local storage**, on that computer only.
  Each computer/browser has its own separate log.
- Use **Download Backup** in the log regularly. A backup can be loaded on any computer with **Restore Backup**.
- **Download CSV** exports the log for Excel.

## Printing
In the print dialog, choose the label printer and set the paper size to 4 × 6 in, margins **None**, scale **100%**.

## Publishing (GitHub Pages)
Settings → Pages → Build and deployment → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
This repository is already published this way.
