# Evren MUD

Evren MUD is a text-based multiplayer online role-playing game built on the **DikuMUD → Merc → ROM → Anatolia 3.0** codebase.  
The project aims to bring the nostalgic Anatolia 3.0 code up to date for modern compilers and continue its legacy with new content over time.

---

## 📜 Overview

- **Base:** Anatolia 3.0 (ROM MUD derivative)
- **Language:** C
- **Status:** Early stage (Anatolia 3.0 code adapted for GCC 11.4 with zero warnings or errors)
- **Platform:** Linux (other POSIX-compatible systems should work as well)
- **License:** Inherits the original Anatolia 3.0 license terms

---

## 🚀 Features

- **Full GCC 11.4 compatibility**: Clean compile without warnings.
- **Classic Anatolia 3.0 mechanics**: All original commands, spells, races, and classes are intact.
- **Authentic MUD feel**: Telnet connection, ANSI color support etc.

---

## 🛠️ Compilation & Setup

### Requirements
- Linux or POSIX-compatible OS
- `gcc` 11.4 or newer
- `make`
- `libcrypt` library (usually included by default on Linux systems)

### Build
```bash
git clone https://github.com/username/evren-mud.git
cd evren-mud/src
make
