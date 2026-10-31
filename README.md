# 2D UCN fan game

A fan game inspired by Five Nights at Freddy's: Ultimate Custom Night.

## Layout

- `www/index.html` - the whole game (all JavaScript and styles in one file)
- `www/audio/` - sounds and music (keep next to `index.html`)
- `www/icons/` - web icons
- `android-icons/` - Android launcher icons made from the logo
- `capacitor.config.json` and `package.json` - app name and build settings
- `.github/workflows/build-apk.yml` - builds the APK on GitHub

## Get the APK

1. Upload everything in this folder to a GitHub repository (keep the `.github` folder).
2. Open the repository's **Actions** tab. The **Build APK** workflow runs on every push, or tap **Run workflow** to start it by hand.
3. When it finishes (about 5-10 minutes), open the run and download **2D-UCN-fan-game-apk** from the Artifacts section. It is a zip containing `app-debug.apk`.
4. Unzip it, open the APK on your phone and allow installs from unknown sources when asked.

## Maintenance Panel terminal

Open the MAINTENANCE PANEL button in the office, type `?` and press Enter to see every command.
