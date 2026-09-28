# 🟣 ZenTask

a tiny macro recorder + auto clicker widget for windows.

it sits on top of your screen, you hit record, do your thing, hit stop,
and it plays it back. no account, no telemetry, nothing weird running in
the background.

## download

**→ [ZenTask-Setup-1.0.6.exe](https://github.com/sitezu/zentask/releases/latest)** ←

windows 10/11 (64-bit) · single installer · free

> ⚠️ windows smartscreen might say "unknown publisher" — i don't pay for a
> code signing certificate for a free project, so that's expected.
> the file is clean. you can verify it:
> `MD5: 21f4a76fd3a220fb6f89cf68116aef97`
> (in powershell: `Get-FileHash -Algorithm MD5 .\ZenTask-Setup-1.0.6.exe`)

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

## faq

**is it safe?** it's a normal desktop app — no installer extras, no ads,
no telemetry, no account. verify the MD5 above if you want to be sure.

**antivirus flagged it?** unsigned indie exes sometimes get false-flagged.
you can upload it to virustotal.com yourself and see.

**can i use it in games?** it simulates normal mouse/keyboard input, but
whether a specific game's anti-cheat allows that is between you and the
game. use your judgment.

**something's broken / i want a feature** — open an issue here or tell me
wherever you found this. i'm actively working on it.

## license

MIT — do whatever you want with it.
