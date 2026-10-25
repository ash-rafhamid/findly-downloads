# Findly for Windows

Find files on your PC with a small, simple search window.

## Download

**[Download Findly for Windows](https://github.com/ash-rafhamid/findly-downloads/releases/latest/download/Findly-portable.zip)**

Free portable app for Windows 10 and 11 with .NET Framework 4.8. No GitHub account, installation, or administrator access is needed.

1. Download **Findly-portable.zip** using the link above.
2. Right-click the ZIP and choose **Extract All**. Keep the extracted folder somewhere writable, such as Documents.
3. Open the extracted folder and double-click **Findly.exe**. Keep **Findly.exe.config** beside it.
4. Type a filename to search. The first scan runs in the background; results appear as files are indexed.

The app is currently unsigned, so Windows may display an unknown-publisher warning. Release checksums are available alongside the ZIP.

## Using Findly

- Search files, folders, documents, videos, photos, music, apps, and archives by name.
- Filter with **All types**, or type `ext:pdf`, `type:video`, or `in:Downloads`.
- Double-click a result to open it. Use its menu to open its folder or copy its path.
- Press **Ctrl + Alt + Space** to bring Findly forward while it is running.
- Use the settings gear to choose search locations, exclusions, sorting, or pause indexing.

Findly searches filenames and paths. It does not search inside documents or recognize the contents of videos or photos.

## Your data

Indexing and searching happen on your computer. Findly has no telemetry or network code. Its index and settings are stored in the **data** folder beside the app. The first scan can take time on large drives; choose fewer locations in Settings to reduce the work.

Closing the window exits Findly. To remove it, close the app and delete its extracted folder, including the index if you no longer need it.

## Updates and feedback

Get new versions from the [releases page](https://github.com/ash-rafhamid/findly-downloads/releases). To update, close Findly, extract the new ZIP, and replace the app and configuration files in your existing folder. Keep your existing **data** folder to retain settings and the index.

Report problems in [Issues](https://github.com/ash-rafhamid/findly-downloads/issues). Do not include private filenames or personal information in public reports.

This public repository distributes Findly's app and instructions. The development source repository remains private.
