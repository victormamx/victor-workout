# Victor Mac Workout

A Progressive Web App (PWA) for Victor's weekly shred training plan. Works offline and installs on iPhone like a native app.

## Features
- Full 6-day split: Chest / Back / Legs / Biceps / Shoulders / Triceps
- Tap exercises to mark them done — progress saves automatically
- Works offline after first load
- Installs on iPhone home screen

## How to deploy (GitHub Pages — free)

1. Create a new GitHub repository (e.g. `victor-workout`)
2. Upload all files keeping the folder structure:
   ```
   index.html
   manifest.json
   sw.js
   icons/icon-192.png
   icons/icon-512.png
   ```
3. Go to **Settings → Pages** in your repo
4. Under **Source**, select **main branch** and click Save
5. Your app will be live at `https://YOUR-USERNAME.github.io/victor-workout/`

## Install on iPhone

1. Open the URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add**

Done — it will appear on your home screen like a native app, full screen, no browser bar.

## Updating the plan
All exercises are in `index.html` inside the `DAYS` array at the top of the script. Edit the names, sets, or reps there and push to GitHub — the app updates automatically.
