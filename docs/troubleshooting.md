# Troubleshooting

### PhoneMistri says the Helper isn't running
- Look for the PhoneMistri icon in the system tray (Windows) or menu bar (Mac).
  If it's missing, open **PhoneMistri Helper** from the Start menu / Applications.
- It starts automatically with your computer after the first launch.

### It worked before, now PhoneMistri can't reach it
Your browser may have blocked the connection. Chrome treats dismissing its
"connect to apps on this device" prompt three times as **Block**.
- Click the icon at the left of the address bar on the PhoneMistri page →
  **Site settings** → set **Local network access** (or *Apps on device*) to **Allow**.
- Reload PhoneMistri.

PhoneMistri must be opened over `https://` — browsers block this connection on
plain `http://` pages.

### My printer isn't in the list
- Check that it's switched on and appears in your computer's printer settings.
- In the Helper window: tray icon → **Printer status** → **Set up / test this printer**.

### A print job is stuck / nothing comes out
- Helper window → **Printer status** → **Start it again**. This restarts the
  print queue and clears the stuck jobs behind it.
- Print the test page from **Settings → Printing & Documents** to check paper
  size and layout.

### Labels come out the wrong size
Set your sticker size (width × height × gap, in mm) in
**Settings → Printing & Documents → Labels** to match the roll in the printer.

### Sending logs to support
Helper window → **Logs** shows the last few hundred lines. Copy them into your
support message.

[← Back](../README.md)
