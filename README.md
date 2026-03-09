# 🚀 GRun

> Python script to **run executables in a sandbox** — uses Wine (Linux/macOS) and Docker for Windows/Linux game isolation.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📂 **File Detection** | Detects .exe (Windows), .sh/.bin (Linux), .app (macOS) |
| 🍷 **Wine** | Runs Windows .exe on Linux/macOS |
| 🐳 **Docker** | Sandboxes games in containers (wine:latest, ubuntu:latest) |
| 📋 **Watchdog** | File system observer for auto-run |
| ⚙️ **Auto Install** | Installs Wine/Docker if missing (apt/brew) |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **Python** | 3.x |
| **watchdog** | `pip install watchdog` |
| **Wine** | For running .exe on non-Windows |
| **Docker** | For container sandboxing |

---

## 🚀 Usage

```bash
pip install watchdog
python GRun.py
```

---

<p align="center">
  <sub>🚀 Gorstak Utilities</sub>
</p>
