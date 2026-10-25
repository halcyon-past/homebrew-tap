# Halcyon Past Homebrew Tap

Official Homebrew Tap for macOS applications and utilities crafted by [@halcyon-past](https://github.com/halcyon-past).

---

## 📦 Available Casks

| Cask | Description | Direct Install |
| :--- | :--- | :--- |
| **[`sutrakey`](https://sutrakey.aritro.cloud)** | Shift + Select radial media and document downloader | `brew install --cask halcyon-past/tap/sutrakey` |
| **[`byakugan-scan`](https://byakugan-scan.aritro.cloud)** | Instant on-device OCR, QR code, and barcode scanner | `brew install --cask halcyon-past/tap/byakugan-scan` |

---

## 🚀 Installation

### 1. Direct Install (Recommended)
Install any app directly without explicitly tapping first:
```bash
brew install --cask halcyon-past/tap/<cask-name>
```

For example:
```bash
brew install --cask halcyon-past/tap/sutrakey
brew install --cask halcyon-past/tap/byakugan-scan
```

### 2. Tap Once, Then Install
Add the tap to your Homebrew installation once:
```bash
brew tap halcyon-past/tap
```

Then install any available cask by name:
```bash
brew install --cask sutrakey
brew install --cask byakugan-scan
```

### 3. Brewfile
Add the tap and desired casks to your `Brewfile`:
```ruby
tap "halcyon-past/tap"

cask "sutrakey"
cask "byakugan-scan"
```

---

## 🔄 Updates

All applications include native, in-place background auto-updates. You can also update them anytime via Homebrew:

```bash
# Update Homebrew and check for outdated casks
brew update

# Upgrade a specific cask
brew upgrade --cask sutrakey
brew upgrade --cask byakugan-scan

# Or upgrade all casks
brew upgrade --cask
```

---

## 🛠️ Troubleshooting & Uninstallation

To cleanly remove an application along with its caches and configuration:
```bash
brew uninstall --zap --cask <cask-name>
```

To remove the tap:
```bash
brew untap halcyon-past/tap
```

---

## 📄 License & Privacy

- All applications in this tap are 100% free, open source, and respect privacy with **zero telemetry** and strictly on-device processing.
- Distributed under the [MIT License](https://github.com/halcyon-past/homebrew-tap/blob/main/LICENSE).
