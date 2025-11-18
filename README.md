# 🌋 Difz25x Universal Bypasser

> **Advanced Multi-Platform URL Bypass Tool with Real-time Progress Tracking**

A powerful Electron-based application that automatically bypasses URL shorteners and access control systems across 15+ platforms with an elegant checkpoint tracking interface.

[![Version](https://img.shields.io/badge/version-1.0.6-beta1-orange.svg)](https://github.com/Difz25x/auto-bypass)
[![Electron](https://img.shields.io/badge/electron-latest-green.svg)](https://www.electronjs.org/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 📋 Overview

Difz25x Bypasser is a universal bypass tool that supports multiple URL shortening and access control platforms. Built with Electron and Puppeteer, it features smart detection, intelligent caching, and real-time progress tracking through a beautiful checkpoint system.

**Key Highlights:**
- 🎯 **15+ Supported Platforms** - From simple API bypasses to complex multi-stage systems
- ⚡ **Dual Bypass Methods** - Fast API-based or advanced browser automation
- 💾 **Smart Caching** - Instant retrieval for previously bypassed URLs
- 🎨 **Modern UI** - Real-time checkpoint tracker with 5-stage progress visualization
- 🔄 **Auto-Detection** - Automatically identifies and applies the correct bypass method

---

## 🌐 Supported Platforms

### ✅ API-Based Bypasses (Fast - Sub-second)

| Platform | Type | Cache Support |
|----------|------|---------------|
| **Rekonise.com** | Social unlock | ✓ |
| **Mboost.me** | URL shortener | ✓ |
| **Sub2unlock.com** | Social gate | ✓ |
| **Sub4unlock.com** | Link redirect | ✓ |
| **Pastefy.app** | Paste service | ✓ |
| **Pastebin.com** | Paste service | ✓ |
| **Pastes.io** | Paste service | ✓ |
| **GitHub.com** | Raw file fetch | ✓ |
| **Subnise.com** | URL shortener | ✓ |

### 🌐 Browser-Based Bypasses (Advanced - 30-180s)

| Platform | Type | Complexity |
|----------|------|------------|
| **Volcano.wtf** | Multi-checkpoint | High |
| **Work.ink** | Social unlock | High |
| **Sub2unlock.io** | Button unlock | High |
| **Link4sub.com** | Social gate | High |
| **Scriptpastebin.com** | Code extraction | High |
| **Scriptpastebins.com** | Code extraction | High |
| **Paste-drop.com** | Paste service | High |
| **Sub4unlock.co** | Link redirect | High |
| **Link2unlock.com** | Social unlock | High |

---

## 📊 Performance Metrics

### Speed Comparison

| Platform Type | First Access | Cached Access | Success Rate |
|---------------|--------------|---------------|--------------|
| **API-Based** | 0.3s - 1.0s | 0.1s - 0.2s | 99% |
| **Browser-Based (Simple)** | 30s - 60s | N/A | 95% |
| **Browser-Based (Complex)** | 120s - 180s | N/A | 92% |

### Platform-Specific Performance

| Platform | Avg. Time | Cache Hit Rate | Reliability |
|----------|-----------|----------------|-------------|
| Rekonise | 3s | 95% | ⭐⭐⭐⭐⭐ |
| Mboost | 3s | 90% | ⭐⭐⭐⭐⭐ |
| Pastefy | 4 | 98% | ⭐⭐⭐⭐⭐ |
| Pastebin | 4s | 97% | ⭐⭐⭐⭐⭐ |
| GitHub | 4s | 95% | ⭐⭐⭐⭐⭐ |
| Sub2unlock.io | 6s | 0% | ⭐⭐⭐⭐ |
| Link4sub | 5s | 0% | ⭐⭐⭐⭐ |
| Scriptpastebin | 2s | 0% | ⭐⭐⭐⭐⭐ |
| Volcano.wtf | 160s | 0% | ⭐⭐⭐⭐ |

**Notes:**
- ⚡ API-based bypasses are near-instant with caching
- 🌐 Browser-based bypasses require full automation (captcha, buttons, etc.)
- 💾 Cache dramatically improves performance for repeated URLs
- 🔄 Success rates may vary based on platform changes

---

## 🚀 Quick Start

### Usage

1. Launch the application
2. Paste your URL into the input field
3. Click "Start Bypass"
4. Monitor progress via checkpoint tracker
5. Copy the result when complete

### Supported URL Formats

```
✓ https://key.volcano.wtf/?hwid=YOUR_HWID
✓ https://rekonise.com/abc123
✓ https://pastefy.app/xyz789
✓ https://mboost.me/short-code
✓ https://sub2unlock.io/link-id
✓ And more...
```

---

## 🎯 Features

### ✨ Core Features
- **Smart URL Detection** - Automatically identifies platform type
- **Dual Bypass Engine** - API-based (fast) or Browser-based (advanced)
- **Real-time Progress** - 5-stage checkpoint visualization
- **Intelligent Caching** - Stores results for instant re-access
- **Error Recovery** - Automatic retry with smart fallback
- **Modern UI** - Dark theme with animated backgrounds

### 🔥 Technical Features
- **Anti-Detection** - Browser fingerprint spoofing
- **Captcha Handling** - Cloudflare Turnstile solver
- **Ad-Block Bypass** - Custom extension injection
- **Context System** - Unified handler communication
- **Performance Timer** - Track bypass duration

---

## ⚙️ Configuration

### Checkpoint System

Visual progress tracking through 5 stages:

```
[STARTING] → [PHASE 1] → [PHASE 2] → [PHASE 3] → [COMPLETED]
    🟡         🟡          🟡         🟡           🟢
```

### Cache System

- **Location:** `data/data.json`
- **Format:** Key-value pairs (URL slug → Result)
- **Benefits:** Instant retrieval, offline access
- **Clear Cache:** Delete `data/data.json`

---

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Browser won't launch | Install Chromium dependencies |
| Timeout errors | Increase timeout values |
| Cache not working | Check data directory permissions |
| Volcano stuck | Clear cache and retry |

---

## 📝 Credits

**Created by:** Difz25x  
**Based on work by:** ducknovis
**Technologies:** Electron, Puppeteer, Node.js

---

## ⚠️ Disclaimer

This tool is for **educational purposes only**. Use responsibly and respect platform Terms of Service. The authors are not responsible for misuse.

---

## 📄 License

MIT License - See LICENSE file for details

---

**Version:** 1.0.1
**Last Updated:** 2025  
**Status:** Active Development
