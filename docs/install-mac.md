# Install on Mac

1. Download the file for your Mac:
   - Apple Silicon (M1 and newer): **[PhoneMistri-Helper-arm64.dmg](https://github.com/h3llix/rms-release/releases/latest/download/PhoneMistri-Helper-arm64.dmg)**
   - Intel: **[PhoneMistri-Helper-x64.dmg](https://github.com/h3llix/rms-release/releases/latest/download/PhoneMistri-Helper-x64.dmg)**
2. Drag **PhoneMistri Helper** into **Applications**.
3. Open it. macOS will warn you — that's expected; the app isn't notarized yet.
4. Go to **System Settings → Privacy & Security** and click **Open Anyway**.
5. Back in PhoneMistri → **Settings → Printing & Documents** → choose
   **PhoneMistri Helper**, then click **Allow** when the browser asks.

### "PhoneMistri Helper is damaged and can't be opened"

Some macOS versions show this instead of the Open Anyway button. Open
**Terminal** and run:

```
xattr -dr com.apple.quarantine "/Applications/PhoneMistri Helper.app"
```

Then open the app again.

[← Back](../README.md)
