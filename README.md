# AACURA Custom Theme (`theme_llslim`)

This repository contains the custom **Moodle Theme** design for **AACURA** (AAC Understanding & Reflective Assistant). It styles the frontpage layout, login pages, and core course/activity wrapper elements.

---

## 🎨 Design Features
* Sleek, high-contrast user interface tailored for teaching tools.
* Custom responsive login page templates with high-resolution background assets.
* Harmonious styling matching the AACURA activity modules.

---

## 📥 Installation Guide

### Option A: Install via Composer (Recommended)
Add the repository to your Moodle project's root `composer.json` and require it:

```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/llslim/moodle-theme_llslim.git"
    }
],
"require": {
    "llslim/moodle-theme_llslim": "dev-dev"
}
```

Then run:
```bash
composer update
```

### Option B: Manual Installation
1. Download the latest release or ZIP from [llslim/moodle-theme_llslim](https://github.com/llslim/moodle-theme_llslim).
2. Install via Moodle Administration:
   ```
   Site Administration → Plugins → Install Plugins → Install plugin from ZIP file
   ```
   Or clone directly to Moodle's `theme/` directory:
   ```bash
   git clone https://github.com/llslim/moodle-theme_llslim.git theme/llslim
   ```

---

## 🏷️ Version History & Git Tagging Log

For the semantic version log of the theme commits mapped according to our tagging policy, see **[version_history.md](version_history.md)**.
