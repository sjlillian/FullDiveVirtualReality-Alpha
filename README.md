# FullDiveVirtualReality-Alpha
> **A brain-computer interface (BCI) experiment to control VR with thought.**

This project is my first step toward building a true full-dive VR system — the kind where your **mind controls your avatar**, no keyboard, no body required. Inspired by sci-fi and driven by obsession, this is my raw, open journey to make it real.

---

## Project Goal

Build a working prototype that uses EEG brain signals to control movement in a Unity VR environment.

---

## What This Does (Eventually)

- Reads EEG signals (Muse / OpenBCI)
- Trains a simple ML model to detect intentional mental states
- Sends signals to a Unity VR scene to control an avatar or object
- Blocks real-world movement (motor inhibition logic)


---

## File Structure

fdvr-alpha/
├── data/ ← EEG recordings (.csv, .edf, etc.)
├── models/ ← Trained ML models (.pkl)
├── scripts/ ← Python: signal processing, classification, OSC bridge
├── unity-project/ ← Unity files (Cube scene, movement logic)
├── todo/ ← todo#.md, Braindump, ideas, logs (ADHD-friendly scratchpad)
├── README.md ← You’re reading it
└── LICENSE ← MIT or Creative Commons

---

Commit Style Guide:

- feat: New feature or experiment

- fix: Bug or problem solved

- note: Docs, logs, ideas, or checkpoints
