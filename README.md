# 🕵️ Advanced Python Keylogger & System Monitor

> **A comprehensive system monitoring tool that captures keystrokes, mouse activity, audio, screenshots, and system metadata.**

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Educational-orange?style=for-the-badge)

## 📄 Overview

This project is a multi-functional surveillance tool developed in Python. Unlike standard keyloggers that only capture text, this tool acts as a full system monitor. It is designed to capture a wide array of user interactions and environment data, automatically reporting them via email at set intervals.

**⚠️ Ethical Disclaimer:** This software is for **educational purposes and authorized security testing only**. Using this tool to monitor devices without the owner's explicit consent is a violation of privacy laws. The developer assumes no liability for misuse.

## ✨ Key Features

* **⌨️ Key Logging:** Captures all keystrokes, including special characters (Space, Esc, etc.).
* **🖱️ Mouse Tracking:** Logs mouse movements, clicks, and scrolling behavior.
* **🎤 Audio Surveillance:** Records microphone input (saved as `.wav`) to capture ambient sound.
* **📸 Visual Surveillance:** Takes periodic screenshots of the user's desktop.
* **💻 System Fingerprinting:** Collects internal IP, processor type, OS version, and machine architecture.
* **📧 Auto-Reporting:** Sends collected logs and media files via SMTP (Email) at defined intervals.
* **🧹 Self-Destruct:** Includes logic to attempt self-deletion after execution (OS dependent).

## 🛠️ Dependencies

This project relies on several powerful Python libraries:

* `pynput` (Input
