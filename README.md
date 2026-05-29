# scoop-bucket

A [Scoop](https://scoop.sh) bucket for [trafmon](https://github.com/Schweik7/trafmon) — a tiny, frameless, always-on-top Windows widget that shows live network speed.

## Usage

```powershell
scoop bucket add trafmon https://github.com/Schweik7/scoop-bucket
scoop install trafmon
```

The portable build needs the [WebView2 runtime](https://developer.microsoft.com/microsoft-edge/webview2/) (preinstalled on Windows 11 and recent Windows 10). Per-process network speed requires running trafmon as Administrator.
