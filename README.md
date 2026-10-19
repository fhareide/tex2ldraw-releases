# tex2ldraw

Turns LEGO decoration textures into LDraw pattern parts: printed torsos,
heads, legs, tiles and stickers, ready for LDraw editors and renderers.

This page only hosts the downloads. **[Get the latest version](../../releases/latest)**
(all versions are on the [Releases](../../releases) page).

## Which file

- **Windows**: `tex2ldraw-<version>-windows.exe`. Double-click it. SmartScreen may
  warn about an unknown publisher: More info → Run anyway.
- **macOS** (Apple silicon): `tex2ldraw-<version>-macos.dmg`. Open it and drag
  tex2ldraw to Applications. The app is not signed by Apple, so the first start
  is blocked: open System Settings → Privacy & Security and click "Open Anyway",
  or run `xattr -dr com.apple.quarantine /Applications/tex2ldraw.app` in Terminal.
- **Linux**: `tex2ldraw-<version>-linux-x86_64.tar.gz` holds one `tex2ldraw` binary.

## First start

The app opens in its own window (on Linux, in your browser). It works offline
and comes with sample textures. The LDraw library is not included: download it
from [ldraw.org](https://library.ldraw.org/updates?latest) and point the app at
it in Settings on the first start. Your parts are saved to `Documents/tex2ldraw`
unless you choose another folder.

On macOS the app may ask once to use the keychain item "tex2ldraw": that is
where it keeps your Rebrickable API key, if you connect one. Choose
**Always Allow** so it doesn't ask again for this version.
