<div align="center">
  <a href="https://github.com/hanzydev/Fileship">
    <img src="https://raw.githubusercontent.com/hanzydev/Fileship/main/banner.png" alt="Fileship" width="520" height="200">
  </a>

  <p align="center">
    Fileship for Windows: capture, record and upload to your Fileship, and browse it from File Explorer.
    <br />
    <br />
    <a href="https://github.com/hanzydev/fileship-desktop/releases/latest"><strong>Download the latest version</strong></a>
    <br />
    <br />
    <a href="https://github.com/hanzydev/Fileship/issues/new?template=bug-report.yml">Report a bug</a>
    ·
    <a href="https://github.com/hanzydev/Fileship/issues/new?template=feature-request.yml">Request a feature</a>
    ·
    <a href="https://github.com/hanzydev/Fileship">Fileship</a>
  </p>
</div>

> [!NOTE]
> This repository only hosts the releases of the desktop app. The source code lives in [`apps/desktop`](https://github.com/hanzydev/Fileship/tree/main/apps/desktop) of the main Fileship repository, and issues and pull requests go there too.

## 📦 Features

- **Screenshots:** capture the active monitor, the active window, the whole screen, a region or the last region, with global hotkeys or from the tray. One region picker covers every monitor, highlights the window or control under the mouse and has a magnifier for pixel exact selections.
- **Annotations:** add shapes, arrows, pen strokes, highlights, text, numbered steps and emoji, or blur and pixelate parts of the screen, while you pick the region.
- **Text capture:** select a region and copy its text, recognised by your Fileship's OCR model.
- **Screen recording:** record a region or a monitor as video or GIF, with pause and resume, hardware encoders, and your microphone (with Windows' noise suppression and echo cancellation) and system audio mixed or on separate tracks.
- **Uploads:** screenshots, recordings and files go to your Fileship with your upload settings (file name style, expiry, view limit, compression, password, folder), and the link lands on your clipboard. If an upload fails, the screenshot or recording is saved on your PC instead of being lost. You can also upload from the clipboard or by dropping files on the app, and shorten links from the clipboard.
- **Fileship Harbor:** your Fileship files and folders in File Explorer, folders inside folders included. Files download only when you open them, thumbnails show without downloading, and new files, renames and moves sync back, while deleted files go to the Fileship trash. Your notes are Markdown files in the **Notes** folder and your short links are shortcuts in the **Links** folder. The status button in File Explorer shows your storage use and what is syncing, with buttons to upload, pause syncing, open the trash and free up space.
- **Explorer context menu:** right-click any file and choose **Upload to Fileship**. Inside Harbor, copy a file's link, open it in the browser, show it in Fileship, or copy a folder's public or inbox link.
- **History:** everything you captured or uploaded, kept locally on your PC, with its link and saved file.
- **Dashboard:** open your Fileship dashboard in its own window, already signed in.
- **Hotkeys:** editable global hotkeys with ShareX-like defaults: Print Screen captures the active monitor and Ctrl + Print Screen opens the region picker.
- **Lightweight:** it starts with Windows and stays in the tray using only a few megabytes of memory; the app window opens only when you need it.
- **Languages:** English, Turkish, German, Spanish, French, Italian, Brazilian Portuguese, Russian, Azerbaijani, Japanese, Korean and Simplified Chinese, following Windows or the language you pick in the settings.
- **Automatic updates:** new versions download in the background and install the next time Fileship restarts.

See the [full feature list and setup guide](https://github.com/hanzydev/Fileship/blob/main/docs/desktop.md) in the Fileship documentation.

## 🖥️ Requirements

- 64-bit Windows 11, version 24H2 (build 26100) or newer
- A Fileship server running version 6.0.0 or newer

Fileship for Windows 2.0 and newer do not run on Windows 10 or older Windows 11 versions. On those, [version 1.1.1](https://github.com/hanzydev/fileship-desktop/releases/tag/v1.1.1) keeps working but does not update to 2.0.

## 🚀 Installation

1. Download `Fileship-Setup-<version>.exe` from the [latest release](https://github.com/hanzydev/fileship-desktop/releases/latest).
2. Run it. Fileship installs for your user only and does not need administrator rights.
3. Enter your Fileship server's address and log in with your Fileship account, or with single sign-on if your server uses it.

The app signs in as a normal session, shown as **Fileship for Windows** in your Fileship's **Settings → Sessions**, where you can revoke it. Recording downloads FFmpeg the first time you use it, and you can point it to your own FFmpeg in the settings instead. Harbor is off until you turn it on in **Settings → Harbor**, and it needs an empty folder.

> [!TIP]
> The installer is not code signed yet. If Windows SmartScreen says it protected your PC, choose **More info** and then **Run anyway**.

## 🔄 Updates

Fileship checks this repository for new releases. An update downloads in the background and installs when you quit or restart Fileship, never while a capture, recording or upload is in progress.

## 🗑️ Uninstalling

Uninstall Fileship from **Settings → Apps**. Uninstalling removes Fileship Harbor and the context menu entries from File Explorer; your files stay on your Fileship server. To keep Harbor files that were not uploaded yet, turn Harbor off in the app before uninstalling.

## 📝 License

Fileship is licensed under the [MIT License](https://github.com/hanzydev/Fileship/blob/main/LICENSE).
