# WordCraft for Windows and Linux

Ready-to-run builds of [WordCraft](https://github.com/storytold/wordcraft), an open-source, Rust-native word processor, with **Greek** spelling, grammar suggestions and hyphenation built in. Nothing to install: no Rust, Visual Studio or other tools.

Downloads: [latest release](https://github.com/eee-Andrew/Word-editor-copy/releases/latest).

## Windows (64-bit)

1. Download `wordcraft-0.6.1-windows-x64-portable.zip`.
2. Right-click the ZIP and choose **Extract All...**
3. Open the extracted folder and double-click `wordcraft.exe`.

If Windows SmartScreen says "Windows protected your PC", click **More info**, then **Run anyway** (the build is not code-signed).

## Linux (x86_64)

Works on distributions with glibc 2.35 or newer (Ubuntu 22.04+, Debian 12+, Fedora 36+, ...).

1. Download `wordcraft-0.6.1-linux-x86_64.AppImage`.
2. Make it executable and run it:

   ```sh
   chmod +x wordcraft-0.6.1-linux-x86_64.AppImage
   ./wordcraft-0.6.1-linux-x86_64.AppImage
   ```

   Or right-click it, choose **Properties > Permissions > Allow executing file as program**, then double-click it.

The `.tar.gz` contains the same app as a plain `bin/` + `share/` tree, for use without AppImage.

## Writing in Greek

- Switch your keyboard to Greek with your system shortcut (GNOME: **Super + Space**; Windows: **Win + Space** or **Alt + Shift**).
- For Greek spelling and hyphenation, select the text and choose **Review › Language › Greek (Greece)**. With nothing selected, the language applies to what you type next.
- Save as **.docx** to keep the language setting; plain text does not store it.

`wordcraft-cli` is the optional command-line tool (convert, run, mcp).

## Licence

WordCraft is dual-licensed under MIT or Apache-2.0. Third-party material is listed in `NOTICE` and `ATTRIBUTION.md` in the downloads.
