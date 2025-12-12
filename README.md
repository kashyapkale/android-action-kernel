# 📱 Android Use

**The open-source library for controlling native Android apps.**
*Give your AI Agent hands in the physical world.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Status: Public Beta](https://img.shields.io/badge/Status-Public_Beta-orange)]()
[![Twitter Follow](https://img.shields.io/twitter/follow/ethanjlim?style=social)](https://x.com/ethanjlim)

**Android Use** allows LLMs to interact with native Android applications via the Accessibility Tree. It unlocks automation for the "real world" apps that web agents cannot reach—Logistics, Gig Economy, Banking, and Identity.

> **🚧 The Problem:** Web Agents (`Browser Use`) are sandboxed in Chrome. Desktop Agents (`Computer Use`) are trapped on laptops.
>
> **✅ The Solution:** **Android Use** operates on the device where field work actually happens. It bypasses expensive Vision models by reading the XML accessibility tree directly.

---

### ⚡️ Quick Start

#### 1. Install
Since we are in active beta, install directly from source:
```bash
git clone [https://github.com/actionstatelabs/android-action-kernel](https://github.com/actionstatelabs/android-action-kernel)
pip install -e .
# Requires ADB installed and a device/emulator connected

Created by Ethan Lim. Watch the demo video on X https://x.com/ethanjlim/status/1999152070428148108?s=20