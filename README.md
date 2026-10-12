# Halcyon Past Homebrew Tap

Official Homebrew Tap for [Byakugan Scan](https://byakugan-scan.aritro.cloud) and utilities by [@halcyon-past](https://github.com/halcyon-past).

---

## 📦 Available Casks

| Cask | Description | Command |
| :--- | :--- | :--- |
| **`byakugan-scan`** | Instant on-device OCR, QR code, and barcode scanner for macOS. | `brew install --cask halcyon-past/tap/byakugan-scan` |

---

## 🚀 Installation & Usage

### 1. Direct Install
You can install Byakugan Scan directly in a single command without explicitly tapping:
```bash
brew install --cask halcyon-past/tap/byakugan-scan
```

### 2. Tap First, Then Install
```bash
# Add tap
brew tap halcyon-past/tap

# Install cask
brew install --cask byakugan-scan
```

### 3. Brewfile
Add this to your `Brewfile`:
```ruby
tap "halcyon-past/tap"
cask "byakugan-scan"
```

---

## 🔄 Updates

Byakugan Scan includes native in-place auto-updates, but you can also update via Homebrew:
```bash
brew update && brew upgrade --cask byakugan-scan
```
