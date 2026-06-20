# Bonsai — Desktop

Download the Bonsai desktop app for macOS. (Source code lives in a private repo; this repo hosts the public downloads only.)

## Install

1. Download the latest **`.dmg`** from [**Releases**](https://github.com/Revido-LLC/bonsai-desktop-releases/releases/latest).
2. Open the DMG and drag **Bonsai** to **Applications**.
3. The build is unsigned, so on first launch macOS will warn. Run this once in Terminal:

   ```bash
   xattr -cr /Applications/Bonsai.app
   ```

   (Or: try to open it, then go to **System Settings → Privacy & Security → Open Anyway**.)

4. Launch Bonsai, pair it with your account, and sign in to Bonsai when prompted.

## Updates

The app checks here on launch and shows a banner when a newer version is available — download the new DMG and reinstall over the old one.
