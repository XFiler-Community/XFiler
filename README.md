<div align="center">
  <a href="https://x-filer.com/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=logo">
    <img alt="X-Filer" width="128" height="128" src="https://x-filer.com/app-icon.png">
  </a>
  <h1>X-Filer</h1>
  <p>
    <b>The Arc of file managers</b> for Windows and macOS.<br/>
    Spaces, split view, and cloud drives right next to your local disks.
  </p>
  <p>
    <a href="https://x-filer.com/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=hero">🌐 x-filer.com</a>
    &nbsp;·&nbsp;
    <a href="https://github.com/XFiler-Community/XFiler/issues">💬 Issues</a>
    &nbsp;·&nbsp;
    <a href="mailto:hello@x-filer.com">✉️ hello@x-filer.com</a>
  </p>
</div>

---

This is the public home of X-Filer: releases, bug reports, feature requests
and announcements. The app source lives in a private repository; the
libraries it is built on are open source (see [below](#open-source-parts)).

## Status

**Pre-1.0. There are no public builds yet**, the first release is on its way.
When it ships, installers for Windows and macOS will appear under
[Releases](https://github.com/XFiler-Community/XFiler/releases), and the app
will update itself from there.

To hear about it first, click **Watch → Custom → Releases** on this
repository, or write to [hello@x-filer.com](mailto:hello@x-filer.com).

## What it does

- ☁️ **Cloud drives, natively** — Google Drive and Yandex Disk browsed like
  local folders, connected right from the sidebar. No sync folders, no
  browser tabs.
- 🪐 **Spaces** — work, personal, project: each Space has its own pinned
  folders, open tabs and accent color.
- ⊞ **Split view** — two panes when you need them, one when you don't;
  "Open beside" from anywhere.
- 📌 **Pinned + Open** — bookmarks that stay, and tabs that tidy themselves
  up after inactivity.
- ⌨️ **The basics, done right** — search, quick preview on Space, ZIP,
  drag & drop and clipboard to and from Finder / Explorer, native shortcuts
  on each platform.
- 🪟🍎 **One app for both platforms** — Windows 10/11 (x64, ARM64) and
  macOS 12+ (Apple Silicon, Intel). AOT-compiled, no .NET runtime to install.
- 🔓 **Local files free, forever** — managing your own disks costs nothing.
  No ads.

## Feedback

- 🐞 **Found a bug?** [Open an issue](https://github.com/XFiler-Community/XFiler/issues/new)
  with your OS and version, what you did, and what you expected.
- 💡 **Missing something?** Feature requests are issues too: tell us what
  you are trying to do, not only the button you want.
- ✉️ **Rather not post in public?** Write to [hello@x-filer.com](mailto:hello@x-filer.com).

## Open-source parts

| Repo | What it is |
|---|---|
| [**FileVault**](https://github.com/XFiler-Community/FileVault) | A .NET library with one `IFileProvider` for local FS, FTP/FTPS, SFTP, Google Drive, Yandex Disk, GitHub repositories and WSL. MIT, [on NuGet](https://www.nuget.org/packages/FileVault.Core). |
| [**FileOperations**](https://github.com/XFiler-Community/FileOperations) | Platform-native copy/move/delete/trash for Windows and macOS. MIT, on NuGet as `XFiler.FileOperations.*`. |

---

<details>
<summary>🇷🇺 По-русски</summary>

<br/>

**X-Filer** — проводник для Windows и macOS, в котором Яндекс Диск и
Google Drive стали обычными дисками в сайдбаре: без sync-папок и без браузера.
Плюс Spaces и split view в духе Arc. Для локальных файлов бесплатно навсегда,
без рекламы.

Здесь — релизы, баг-репорты, пожелания и новости. Исходники приложения
закрыты, библиотеки под ним открыты (FileVault, FileOperations).

**Публичных сборок пока нет**, первый релиз готовится. Установщики появятся в
[Releases](https://github.com/XFiler-Community/XFiler/releases), дальше
приложение будет обновляться само. Чтобы узнать о релизе первым — нажмите
**Watch → Custom → Releases** или напишите на
[hello@x-filer.com](mailto:hello@x-filer.com).

Нашли баг или чего-то не хватает — [заведите issue](https://github.com/XFiler-Community/XFiler/issues/new)
(можно по-русски) или напишите на почту.

</details>
