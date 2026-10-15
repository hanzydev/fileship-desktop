<div align="center">
  <a href="https://github.com/hanzydev/Fileship">
    <img src="https://raw.githubusercontent.com/hanzydev/Fileship/main/banner.png" alt="Fileship" width="520" height="200">
  </a>

  <p align="center">
    Fileship for Windows: capture, record and upload to your Fileship, and browse it from Explorer.
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

- **Screenshots:** capture a region, a window or a whole monitor with global hotkeys or from the tray. Selections and annotations can span monitors.
- **Annotations:** add arrows, lines, rectangles, ellipses, text, highlights and numbered steps, or blur and pixelate parts of a screenshot, while selecting or in the editor afterwards.
- **Text capture:** select a region and copy its text, recognised by your instance's OCR model.
- **Screen recording:** record a region or a monitor as video or GIF, with your microphone and system audio mixed or on separate tracks.
- **Uploads:** screenshots, recordings and files go to your Fileship right away, and the link lands on your clipboard.
- **Fileship Drive:** your Fileship files and folders in File Explorer. They download on demand, and renames, moves, deletes and new files sync back.
- **History:** everything you captured or uploaded, kept locally on your PC.
- **Dashboard:** open your Fileship dashboard in its own window, already signed in.
- **Hotkeys:** editable global hotkeys with ShareX-like defaults, including Print Screen for the active monitor.
- **Automatic updates:** new versions download in the background and install the next time Fileship restarts.

## 🖥️ Requirements

- Windows 10 or 11 (64-bit)
- A Fileship instance running version 6.0.0 or newer

## 🚀 Installation

1. Download `Fileship-Setup-<version>.exe` from the [latest release](https://github.com/hanzydev/fileship-desktop/releases/latest).
2. Run it. Fileship installs for your user only and does not need administrator rights.
3. Enter your Fileship URL and sign in with your account.

Fileship starts with Windows and keeps running in the tray. Recording downloads ffmpeg the first time you use it, and you can point it to your own ffmpeg in the settings instead.

> [!TIP]
> If Windows SmartScreen says it protected your PC, choose **More info** and then **Run anyway**.

## 🔄 Updates

Fileship checks this repository for new releases. An update downloads in the background and installs when you quit or restart Fileship, never while a capture, recording or upload is in progress.

## 🗑️ Uninstalling

Uninstall Fileship from **Settings → Apps**. Uninstalling removes Fileship Drive from File Explorer; your files stay on your Fileship instance. To keep drive files that were not uploaded yet, turn the drive off in the app before uninstalling.

## 📝 License

Fileship is licensed under the [MIT License](https://github.com/hanzydev/Fileship/blob/main/LICENSE).
