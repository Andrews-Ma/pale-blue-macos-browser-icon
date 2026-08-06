# Pale Blue macOS Browser Icon

A light-blue, minimalist replacement icon designed for Firefox on macOS.

> Unofficial community artwork. This project is not affiliated with, sponsored by, or endorsed by Mozilla.

![Icon preview](assets/icon-preview-on-gray.png)

## Download

- [Download the macOS `.icns` icon](dist/Pale-Blue-Browser-Icon.icns)
- For versioned downloads, see this repository's **Releases** page.

## Installation on macOS

1. Download `Pale-Blue-Browser-Icon.icns`.
2. Open **Applications** in Finder.
3. Right-click `Firefox.app` and choose **Get Info**.
4. Drag the `.icns` file onto the small application icon in the upper-left corner of the Info window.
5. If the Dock does not refresh, open Terminal and run:

   ```bash
   killall Dock
   ```

Firefox updates may restore the original application icon. If that happens, apply this icon again.

## Included files

```text
assets/
  icon-preview-on-gray.png
  icon-preview-transparent.png
dist/
  Pale-Blue-Browser-Icon.icns
source/
  Pale-Blue-Browser-Icon-1024.png
LICENSE
NOTICE.md
RELEASE_NOTES_v1.0.0.md
SHA256SUMS.txt
```

## License

The original icon artwork in this repository is licensed under the
[Creative Commons Attribution 4.0 International License](LICENSE).

Suggested attribution:

```text
"Pale Blue macOS Browser Icon" by Andrews-Ma, licensed under CC BY 4.0.
```

## Trademark notice

Firefox is a trademark of the Mozilla Foundation in the United States and other countries.
This artwork is an independent replacement icon and is not the official Firefox logo.
