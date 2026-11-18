<div align="center">
  <a href="https://x-filer.com/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=logo">
    <img alt="X-Filer" width="128" height="128" src="https://x-filer.com/app-icon.png">
  </a>
  <h1>X-Filer</h1>
  <p>
    <b>Every cloud and server in one file manager.</b><br/>
    For Windows, macOS and Linux.
  </p>
  <p>
    <a href="https://x-filer.com/download/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=hero"><b>Download</b></a>
    &nbsp;·&nbsp;
    <a href="https://x-filer.com/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=hero">Website</a>
    &nbsp;·&nbsp;
    <a href="https://x-filer.com/docs/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=hero">Docs</a>
    &nbsp;·&nbsp;
    <a href="https://github.com/XFiler-Community/XFiler/issues">Issues</a>
  </p>
  <br/>
  <img alt="X-Filer with two panes open side by side" width="820" src="https://x-filer.com/docs/img/en/split-view@2x.webp">
</div>

---

This is the public home of X-Filer: releases, bug reports, feature requests and
announcements. The app's source is private; the libraries it is built on are
[open source](#open-source-parts).

## Status

**Public beta.** Installers are on the
[Releases](https://github.com/XFiler-Community/XFiler/releases) page, and the app
updates itself from there. To follow new versions, click
**Watch → Custom → Releases**.

## Download

| System | Versions | Builds |
|---|---|---|
| **Windows** | 10 and 11 | x64, ARM64 |
| **macOS** | 14 Sonoma and later | Apple Silicon, Intel |
| **Linux** | glibc 2.35+ (Ubuntu 22.04, Debian 12, Fedora 36 and later) | x64 AppImage |

**[Get X-Filer on x-filer.com](https://x-filer.com/download/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=download)**
or pick a file from [Releases](https://github.com/XFiler-Community/XFiler/releases).
No .NET runtime needed.

The macOS app is signed and notarized by Apple. The Windows build is not code-signed
yet, so SmartScreen may warn you: click **More info → Run anyway**.

## What it does

- **All your storage in one sidebar.** OneDrive, Dropbox, Yandex Disk and Google
  Drive, plus SFTP, FTP, WebDAV (Nextcloud, Synology, ownCloud), S3-compatible
  storage and SMB. iCloud Drive on a Mac, WSL on Windows. No sync clients.
- **Copy between clouds.** See progress from the first second, with retries and
  resume after a failure. Yandex Disk and Dropbox can fetch a file from another
  cloud themselves, without passing it through your computer.
- **A workspace that fits the job.** Spaces for separate contexts, up to nine panes
  in any grid, pinned folders and tabs that tidy themselves up.
- **The file-manager basics.** Search by name and contents, quick preview, archives
  as folders, batch rename, undo, folder sizes and a size map.
- **Projects you run with an AI agent.** See what Claude Code changed since your
  last visit, compare before and after, and put a file back, without git or an IDE.
- **Your language.** The interface is available in 13 languages.

Cloud drives open as folders inside X-Filer. They are not mounted as system drives,
and their files are not kept offline.

## Pricing

Local files are free forever, with no account and no ads.

Cloud drives and servers need an X-Filer account. A new account starts with 30 days
of Pro, no card. After that, the Free plan keeps one connection; Pro has no limit and
adds copying between clouds. Paid plans are not on sale yet.
[Plans and prices](https://x-filer.com/pricing/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=pricing).

Until X-Filer passes Google's security review, Google limits how many people can
connect Google Drive, so places there may run out.

## Your data

- Sign-in tokens for your clouds and servers stay on your computer.
- The X-Filer server keeps your email, devices, plan and payments. It never receives
  your files, file names or cloud tokens.
- Anonymous usage statistics and crash reports are sent only if you allow them.

Details are in the [Privacy Policy](https://x-filer.com/privacy/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=privacy).

## Feedback

- **Found a bug?** [Open an issue](https://github.com/XFiler-Community/XFiler/issues/new)
  with your OS and version, what you did, and what you expected.
- **Missing something?** Feature requests are issues too: tell us what you are trying
  to do, not only the button you want.
- **Rather not post in public?** Write to [hello@x-filer.com](mailto:hello@x-filer.com).

## Open-source parts

| Repo | What it is |
|---|---|
| [**FileVault**](https://github.com/XFiler-Community/FileVault) | A .NET library with one `IFileProvider` for local files, FTP/FTPS, SFTP, WebDAV, S3-compatible storage, Google Drive, OneDrive, Dropbox, Yandex Disk, GitHub repositories and WSL. MIT, [on NuGet](https://www.nuget.org/packages/FileVault.Core). |
| [**YandexDisk.Client**](https://github.com/XFiler-Community/YandexDisk.Client) | A .NET client for the Yandex Disk REST API, AOT- and trim-safe. MIT, [on NuGet](https://www.nuget.org/packages/XFiler.YandexDisk.Client). |
| [**FileOperations**](https://github.com/XFiler-Community/FileOperations) | Platform-native copy, move, delete and trash for Windows and macOS. MIT, on NuGet as `XFiler.FileOperations.*`. |

---

<details>
<summary>🇷🇺 По-русски</summary>

<br/>

**X-Filer** — файловый менеджер для Windows, macOS и Linux, в котором все облака и
серверы собраны в одной боковой панели: Яндекс Диск, OneDrive, Dropbox, Google Диск,
SFTP, FTP, WebDAV, S3 и SMB. Клиенты синхронизации не нужны.

Файлы можно копировать между облаками, а Яндекс Диск и Dropbox умеют забирать их из
другого облака сами, минуя компьютер. Ещё в X-Filer есть пространства, до девяти
панелей, поиск, быстрый просмотр, архивы как папки, карта размеров и проекты с
ИИ-агентом: видно, что Claude Code изменил с прошлого визита.

**Сейчас идёт публичная бета.** Скачать можно на
[x-filer.com](https://x-filer.com/ru/download/?utm_source=github&utm_medium=xfiler_repo&utm_campaign=download_ru)
или в [Releases](https://github.com/XFiler-Community/XFiler/releases), дальше
приложение обновляется само. Сборка для Windows пока не подписана, поэтому SmartScreen
может предупредить о запуске: нажмите **Подробнее → Выполнить в любом случае**.

Локальные файлы бесплатны навсегда, без аккаунта и рекламы. Для облаков и серверов
нужен аккаунт: новый начинается с 30 дней Pro без карты, затем на Free остаётся одно
подключение. Платные планы пока не продаются, а оплата из России сейчас недоступна.

Нашли ошибку или чего-то не хватает? [Заведите issue](https://github.com/XFiler-Community/XFiler/issues/new)
(можно по-русски) или напишите на [hello@x-filer.com](mailto:hello@x-filer.com).

</details>
