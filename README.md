# Mixtaped

Remember making mixtapes? Carefully selecting songs, writing out the tracklist, and handing it to someone who needed to hear what you'd been listening to. Mixtaped brings that feeling back for the streaming age thanks to the Spotify Web API.

## Features

- **Grid & Deep Dive views** — See your playlists as album art tiles or detailed cards with descriptions
- **One-tap playback** — Opens directly in Spotify
- **Easy sharing** — Generate a link or code to share your collection
- **Collect from friends** — Save mixtapes others share with you
- **Works offline** — Install as an app on iOS or Android
- **No account required** — Data stays on your device
- **Three themes** — Light, Dark, and Spotify green

## Setup Instructions

Mixtaped is a web app that needs to be hosted online. Here are your options:

### Option 1: GitHub Pages (Free)

1. Create a free [GitHub](https://github.com) account if you don't have one
2. Click the green "Code" button on this repo, then "Download ZIP"
3. Create a new repository on GitHub (click + → New repository)
4. Name it `mixtaped` and make it Public
5. Upload all the files from the ZIP to your new repo
6. Go to Settings → Pages → Source: select "main" branch → Save
7. Your app will be live at `yourusername.github.io/mixtaped` in a few minutes

### Option 2: Netlify (Free, easier)

1. Create a free [Netlify](https://netlify.com) account
2. Drag and drop the unzipped folder onto Netlify's dashboard
3. Your app is instantly live at a random URL (you can customize it)

### Option 3: Any Web Host

Upload all files to any web hosting service (Vercel, your own server, shared hosting, etc.)

## Installing on Your Phone

Once your app is hosted and you have a URL:

### iPhone (Safari only)
1. Open the URL in **Safari** (not Chrome or other browsers)
2. Tap the **Share** button (square with arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add**
5. Open the app from your home screen

### Android
1. Open the URL in **Chrome**
2. Tap the **menu** (three dots)
3. Tap **"Install app"** or **"Add to Home Screen"**
4. Open the app from your home screen

## Files Included

```
index.html                 The app
manifest.json              PWA configuration
favicon.ico                Browser tab icon
favicon-16x16.png          Small favicon
favicon-32x32.png          Standard favicon  
apple-touch-icon.png       iOS home screen icon
android-chrome-192x192.png Android icon
android-chrome-512x512.png Android icon (large)
README.md                  This file
```

## How It Works

Mixtaped uses Spotify's public oEmbed API to fetch playlist titles and artwork. No Spotify login required, but playlists must be set to Public in Spotify.

All data is stored in your browser's localStorage. Nothing is sent to a server. Your playlists, settings, and collected mixtapes stay on your device.

## Limitations

- **Playlists must be public** — Private playlists can't be loaded via the oEmbed API
- **Local storage only** — Clearing browser data resets the app (always save your share code as backup)
- **Short URLs** — The is.gd URL shortener may occasionally be unavailable

## Credits

- Hero images from Unsplash: [@rexcuando](https://unsplash.com/@rexcuando), [@mohammadmetri](https://unsplash.com/@mohammadmetri)
- Icons from [Google Material Symbols](https://fonts.google.com/icons)

## License

© 2025 fromnineteen80. All rights reserved.

This code is provided for personal use. Redistribution or resale is not permitted.

---

**Like this?** [Buy me a coffee](https://buymeacoffee.com/fromnineteen80)
