<h1 align="center">PhoneMistri Helper</h1>

<p align="center">
  Print from <a href="https://phonemistri.com">PhoneMistri</a> to your receipt and label printers —<br>
  through Windows or macOS, with your printer's own driver. No Zadig, no driver swaps.
</p>

<p align="center">
  <a href="https://github.com/h3llix/rms-release/releases/latest/download/PhoneMistri-Helper-Setup.exe"><b>Download for Windows</b></a> ·
  <a href="https://github.com/h3llix/rms-release/releases/latest/download/PhoneMistri-Helper-arm64.dmg"><b>Mac (Apple Silicon)</b></a> ·
  <a href="https://github.com/h3llix/rms-release/releases/latest/download/PhoneMistri-Helper-x64.dmg"><b>Mac (Intel)</b></a>
</p>

---

## What it does

PhoneMistri runs in your browser. Browsers can't talk to most USB printers on
their own, and the usual workaround — replacing the printer's Windows driver
with Zadig — breaks every other program that uses that printer.

PhoneMistri Helper is a small app that sits in your system tray. When you print
a receipt, job sheet or label in PhoneMistri, the Helper hands it to your
computer's normal print queue, so your printer keeps its original driver and
everything else on the computer keeps printing too.

Works with thermal receipt printers (ESC/POS), label printers (TSPL, ZPL) and
regular A4 printers.

## Downloads

| Computer | File |
|---|---|
| Windows 10 / 11 | [PhoneMistri-Helper-Setup.exe](https://github.com/h3llix/rms-release/releases/latest/download/PhoneMistri-Helper-Setup.exe) |
| Mac with Apple Silicon (M1 and newer) | [PhoneMistri-Helper-arm64.dmg](https://github.com/h3llix/rms-release/releases/latest/download/PhoneMistri-Helper-arm64.dmg) |
| Mac with Intel | [PhoneMistri-Helper-x64.dmg](https://github.com/h3llix/rms-release/releases/latest/download/PhoneMistri-Helper-x64.dmg) |

Not sure which Mac you have? Apple menu → **About This Mac**. "Chip: Apple M…"
means Apple Silicon; "Processor: Intel" means Intel.

Older versions are on the [Releases](https://github.com/h3llix/rms-release/releases) page.

## Set up in 3 steps

1. **Install** the Helper — [Windows](docs/install-windows.md) · [Mac](docs/install-mac.md).
2. In PhoneMistri, open **Settings → Printing & Documents** and choose
   **PhoneMistri Helper** for your receipt or label printer.
3. Pick your printer from the list and print the test page.

The Helper starts with your computer and updates itself — install it once.

## Help

- [Troubleshooting](docs/troubleshooting.md)
- [Security & privacy](docs/security.md)
- Still stuck? Contact PhoneMistri support from inside the app.

---

<sub>© PhoneMistri. Free to use with a PhoneMistri account. This repository
contains release files only; it is not open source.</sub>
