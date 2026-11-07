# Arrow Out Game - Android APK Builder

This repository contains the **Arrow Out** HTML5 puzzle game configured to be built into an Android APK using **Capacitor** and **GitHub Actions**.

## Project Files
- `index.html`: The complete game code and assets.
- `photo_2026-11-01_00-09-13.jpg`: App icon image source.
- `package.json` & `capacitor.config.json`: Capacitor project configuration.
- `.github/workflows/build-apk.yml`: Automated CI/CD pipeline to build the APK.

## How to Get Your APK via GitHub:
1. Create a new repository on GitHub.
2. Push all files in this folder to your GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Arrow Out game"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
   git push -u origin main
   ```
3. Go to your repository on GitHub and click on the **Actions** tab.
4. You will see the **Build Android APK** workflow running.
5. Once completed successfully, click on the workflow run and download the **app-debug** artifact, which contains your `app-debug.apk` file ready to install on Android!

## App Icon Setup:
The file `photo_2026-11-01_00-09-13.jpg` is included in the root as your app icon source.
