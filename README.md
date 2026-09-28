<p align="center">
  <img src="assets/banner.png" alt="ZenTask — tiny macro recorder & auto clicker for windows" width="100%">
</p>

<p align="center">
  <a href="https://github.com/sitezu/Zentask/releases/latest"><img src="https://img.shields.io/github/v/release/sitezu/Zentask?style=flat-square&color=5a57f5&labelColor=14122a&label=latest%20release" alt="latest release"></a>
  <a href="https://www.virustotal.com/gui/file/e130a9a6d4128aa824091a3dd5be4539c185866a844e7f055571b8d971602d2b"><img src="https://img.shields.io/badge/virustotal-0%2F68%20clean-brightgreen?style=flat-square&labelColor=14122a" alt="virustotal 0/68 clean"></a>
  <img src="https://img.shields.io/badge/platform-windows%2010%2F11-blue?style=flat-square&labelColor=14122a" alt="windows 10/11">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square&labelColor=14122a" alt="MIT license">
  <img src="https://img.shields.io/github/downloads/sitezu/Zentask/total?style=flat-square&color=8b89ff&labelColor=14122a" alt="downloads">
</p>

<p align="center">
  <a href="https://github.com/sitezu/Zentask/releases/latest/download/ZenTask-Setup-1.0.6.exe"><b>⬇ download ZenTask 1.0.6</b></a>
  &nbsp;·&nbsp;
  <a href="https://sitezu.github.io/Zentask/">project website</a>
</p>

---

a tiny widget that sits on top of your screen. you hit record, do your
thing, hit stop, and it plays it back. that's basically it.
no account, no telemetry, nothing weird running in the background.

## 📸 what it looks like

<table>
<tr>
<td width="33%" align="center"><img src="assets/shot-library.png" alt="macro library"><br><sub>macro library — save, rename, load</sub></td>
<td width="33%" align="center"><img src="assets/shot-composer.png" alt="webhook embed composer"><br><sub>webhook embed composer + live preview</sub></td>
<td width="33%" align="center"><img src="assets/shot-clicker.png" alt="auto clicker"><br><sub>auto clicker</sub></td>
</tr>
</table>

<details>
<summary>more screens</summary>

<table>
<tr>
<td width="50%" align="center"><img src="assets/shot-main.png" alt="main widget"><br><sub>the widget, collapsed & always on top</sub></td>
<td width="50%" align="center"><img src="assets/shot-themes.png" alt="theme menu"><br><sub>themes, one click away</sub></td>
</tr>
</table>

</details>

## what it does

**🎥 record & replay**
- records mouse moves, clicks and keystrokes
- global hotkeys for record / play / pause (changeable in settings)
- loop a macro a set number of times or forever
- playback speed control

**🖱️ auto clicker**
- speed slider (clicks per second)
- left / right / middle button, single or double click
- follow your cursor or click one fixed spot on screen
- toggle mode or hold mode

**🗂️ macro library**
- save macros with the normal windows "save as" dialog — name it right there
- rename any macro with the pen icon
- load, delete, and see step count / duration for each one

**✨ the little things**
- always-on-top widget, draggable, gets out of your way
- minimize to tray, run at startup (optional)
- themes + light mode
- works properly on 125% / 150% display scaling

## quick start

1. install and open it
2. click the record button (or press the record hotkey)
3. do the clicks/keys you want to automate
4. press the hotkey again to stop
5. hit play — or save it to your library first

## is it safe?

> ✅ **virustotal: 0/68 engines flagged it — clean.**
> [see the scan yourself](https://www.virustotal.com/gui/file/e130a9a6d4128aa824091a3dd5be4539c185866a844e7f055571b8d971602d2b)
>
> ⚠️ windows smartscreen might still say "unknown publisher" — i don't pay
> for a code signing certificate for a free project, so that's expected.
> to confirm you downloaded the exact file that was scanned:
> `SHA256: e130a9a6d4128aa824091a3dd5be4539c185866a844e7f055571b8d971602d2b`
> (powershell: `Get-FileHash .\ZenTask-Setup-1.0.6.exe`)

## faq

**antivirus flagged it?** it's 0/68 on virustotal (link above), so a flag
on your machine would be a false positive on the unsigned exe — re-upload
it to virustotal and compare the SHA256 if you want proof it's the same file.

**can i use it in games?** it simulates normal mouse/keyboard input, but
whether a specific game's anti-cheat allows that is between you and the
game. use your judgment.

**something's broken / i want a feature** — open an issue here or tell me
wherever you found this. i'm actively working on it.

## license

MIT — do whatever you want with it.
