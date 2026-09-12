# 🎓 GRE Timer

A **lightweight, standalone offline timer** for practising GRE exam sections — built as a Windows `.hta` (HTML Application) file. No installation, no browser required. Just double-click and start practising.

---

## ✨ Features

| Feature | Details |
|---|---|
| **GRE Section Timers** | Writing (30 min), Verbal 1 (18 min), Verbal 2 (23 min), Quant 1 (21 min), Quant 2 (26 min) |
| **Full Exam Mode** | All 5 sections auto-advance in sequence (1h 58m total) |
| **Custom Timer** | Set any duration from 1–999 minutes |
| **⏱ Stopwatch** | Count up from 0:00 with no time limit |
| **⏰ Overtime Counting** | When time is up, alarm fires and timer keeps running +MM:SS so you see how much extra time you used |
| **🔔 Ringing Alarm** | 3-layer alarm: Windows WAV file + synthesised beep + SAPI speech ("Time is up!") |
| **Warning Beeps** | Beeps at 5 min, 1 min, and 30 sec remaining |
| **Collapse / Expand** | Collapse to a slim bar with Start/Pause/Reset still accessible |
| **Resizable Window** | Drag any edge or corner to resize; content scales to fill |
| **Dark / Light Theme** | Toggle with T key; preference saved across sessions |
| **Sound Toggle** | Toggle with S key |
| **Reset Confirmation** | Modal dialog prevents accidental resets |
| **Per-Question Pace** | Recommended time per question shown for each section |

---

## 🖥️ Requirements

- **Windows** (Windows 10 / 11 recommended)
- No installation needed — uses `mshta.exe` which is built into Windows

---

## 🚀 Usage

1. Download `GRE_Timer.hta`
2. Double-click the file — it opens as a standalone desktop app
3. Select a GRE section or set a custom time, then press **Start**

> **Note:** If Windows Defender SmartScreen warns you, click *More info → Run anyway*. The file is fully offline and makes no network calls.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `Space` | Start / Pause |
| `1`–`5` | Select GRE section |
| `F` | Full Exam Mode |
| `W` | Stopwatch |
| `Ctrl+R` | Reset (with confirmation) |
| `S` | Toggle sound |
| `T` | Toggle dark/light theme |
| `Alt+E` | Expand / Collapse |
| `Esc` | Dismiss dialog |

---

## 📐 GRE 2024–25 Timing Reference

| Section | Time | Questions |
|---|---|---|
| Analytical Writing | 30 min | 1 essay |
| Verbal Reasoning S1 | 18 min | 12 Q |
| Verbal Reasoning S2 | 23 min | 15 Q |
| Quantitative Reasoning S1 | 21 min | 12 Q |
| Quantitative Reasoning S2 | 26 min | 15 Q |
| **Full Exam** | **1h 58m** | **55 Q** |

---

## 📄 License

MIT — free to use and modify.