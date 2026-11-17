# ColorMatch Round Generator

A single-page web app for filling out colormatch rounds and printing 3×8 in labels.

**Live site:** https://edellenator.github.io/colormatch-round-generator/

## How it works
- Everything runs in the browser (Chrome / Edge recommended). There is no server and no database.
- The ColorMatch Log is saved in **that browser's local storage**, on that computer only.
  Each computer/browser has its own separate log.
- Use **Download Backup** in the log regularly. A backup can be loaded on any computer with **Restore Backup**.
- **Download CSV** exports the log for Excel.

## Printing
In the print dialog, choose the label printer and set the paper size to 3 × 8 in, margins **None**, scale **100%**.

## Publishing (GitHub Pages)
The site is published by the GitHub Actions workflow in `.github/workflows/static.yml`
(Settings → Pages → Build and deployment → Source: *GitHub Actions*).

- Every commit to `main` redeploys the site automatically, usually within a minute.
- To redeploy by hand: Actions tab → *Deploy static content to Pages* → *Run workflow*.
- Check a deployment's progress or errors in the Actions tab.
