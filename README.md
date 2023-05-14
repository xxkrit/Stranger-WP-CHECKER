# Stranger WP Checker
```text
███████╗████████╗██████╗  █████╗ ███╗   ██╗ ██████╗ ███████╗██████╗ 
██╔════╝╚══██╔══╝██╔══██╗██╔══██╗████╗  ██║██╔════╝ ██╔════╝██╔══██╗
███████╗   ██║   ██████╔╝███████║██╔██╗ ██║██║  ███╗█████╗  ██████╔╝
╚════██║   ██║   ██╔══██╗██╔══██║██║╚██╗██║██║   ██║██╔══╝  ██╔══██╗
███████║   ██║   ██║  ██║██║  ██║██║ ╚████║╚██████╔╝███████╗██║  ██║
╚══════╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝
          [ STRANGER SYSTEM - BYPASS THE LIMITS ]
```
**Stranger WP Checker** is an automated WordPress reconnaissance tool designed for
bulk scanning of WordPress installations. It prioritizes speed and accuracy in
detecting sensitive endpoints such as `wp-login.php` and `xmlrpc.php` across
large target lists.

---

## Features

- **Bulk Scanning** — Multi-threaded engine capable of processing thousands of
  URLs simultaneously.
- **Accurate Detection** — Reliably identifies `wp-login.php` presence as well
  as custom login page implementations.
- **Log Management** — Organizes and persists scan results in structured `.txt`
  log files.
- **Code Protection** — The core logic is protected to prevent unauthorized tampering and to secure internal operational parameters.
---

## Installation

1. **Clone the repository:**

```bash
   git clone https://github.com/xxkrit/Stranger-WP-CHECKER.git
```

2. **Navigate to the project directory:**

```bash
   cd Stranger-WP-CHECKER
```

3. **Create a virtual environment** *(optional but recommended)*:

```bash
   python -m venv venv

   # Linux & macOS
   source venv/bin/activate

   # Windows
   venv\Scripts\activate
```

4. **Install dependencies:**

```bash
   pip install -r requirements.txt
```

5. **Run the tool:**

```bash
   python3 main.py
```

---

## Usage

### 🛠 Modules & Features
- **[01] WP-Login Validator** — Bulk verification for WordPress login endpoints
- **[02] XML-RPC Scanner** — Detect enabled XML-RPC interfaces on targets
- **[03] Performance Configuration** — Adjust concurrent threads & scan performance
- **[04] Exit Application** — Safely terminate the current session
---

## 📘 WP-Login Format Requirement

Gunakan salah satu format berikut di dalam file `.txt`:

```txt id="aqxv3l"
site.com/wp-login.php#user@pass
site.com/wp-login.php;user;pass
site.com/wp-login.php:user:pass
```
---

### **Quick Start Guide**
1. Prepare a list of targets in a text file (one URL per line).
2. Select **Option 1** or **2**.
3. When prompted, input the filename (e.g., `list.txt`) and press **Enter**.
4. Results are automatically exported to the `results/` directory.


---

## Disclaimer

This tool is intended **solely for educational purposes and authorized security
testing**. Any use of this tool against systems without explicit prior permission
from the system owner is strictly prohibited and may violate local, national, or
international law. The developers assume no liability and are not responsible for
any misuse, damage, or legal consequences arising from the use of this software.

**Use responsibly. Hack ethically.**

---

## License

Copyright © 2023 Stranger System. All rights reserved.