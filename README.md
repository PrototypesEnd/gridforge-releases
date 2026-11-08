# GridForge

An Excel-style spreadsheet app for Windows. It opens and saves real Excel files
(.xlsx, .xlsm, .xls, .csv), looks and works like Excel, and has offline smart helpers
plus an optional local AI assistant that runs on your own PC.

## Download

**[Download the latest GridForge installer](https://github.com/PrototypesEnd/gridforge-releases/releases/latest)**:
on that page, click **GridForge-Setup-1.0.2.exe** under **Assets**.

1. Open the downloaded file. The installer isn't code-signed, so Windows SmartScreen says
   "Windows protected your PC": click **More info**, then **Run anyway**.
2. Click through setup. It installs for your Windows user only, so no admin rights are
   needed, and it upgrades an earlier GridForge in place.
3. Leave "Make GridForge the default for Excel files" unticked to keep Excel as your
   default. To open a file in GridForge, right-click it and choose
   **Open with** > **GridForge**.

Each release lists the installer's SHA-256, so you can check your download with
`certutil -hashfile GridForge-Setup-1.0.2.exe SHA256`.

From 1.0.1 on, GridForge checks this page for new versions and installs them itself
(Help > Check for Updates; the daily check can be turned off in File > Account).

## Requirements

- Windows 10 or 11, 64-bit.
- About 170 MB of disk space.
- The optional AI assistant needs a one-time model download, started from GridForge:
  4.6 GB (Standard) or 19 GB (Large, for graphics cards with 20 GB or more).
  Nothing is downloaded unless you choose it.

## About this repository

This repository only hosts the installers. GridForge's source code isn't public.
Third-party components and their licenses are listed in
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt); the same file is installed with
the app.
