# RTS-Releases
Android APK releases and updates for RTS (realistic C&C-style strategy game).

- `latest.json` - the newest version. The game checks this file on launch and every 10 minutes.
- The APK itself is hosted in Supabase storage (no 100 MB limit); `apkUrl` in latest.json is the download link.

To update: open the game and tap the green **Update ready** button (top right), or open the `apkUrl` link from latest.json
on your phone and tap the downloaded file to install over the old one.
