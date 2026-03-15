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

---

## Disclaimer

**NO WARRANTY.** THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

**Limitation of Liability.** IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
