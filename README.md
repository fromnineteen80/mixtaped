# MIXTAPED

Remember making mixtapes? Carefully selecting songs, writing out the tracklist, and handing it to someone who needed to hear what you'd been listening to. Mixtaped brings that feeling back for the streaming age thanks to the Spotify Web API.

**[Try the demo →](https://fromnineteen80.github.io/mixtaped)**

## Features

- **Quick Access** — Your favorite Spotify playlists, one tap away
- **Share** — Send your entire collection with a single code
- **Collaborate** — Build mixtapes with friends
- **Grid & Deep Dive views** — See your playlists as album art tiles or detailed cards with descriptions
- **Inline editing** — Edit playlists directly in Grid or Deep Dive view without switching pages
- **Embedded player** — Preview playlists without leaving the app (tablet/desktop)
- **Works offline** — Install as an app on iOS or Android
- **No account required** — Data stays on your device
- **Three themes** — Light, Dark, and Spotify green

## What's New

- **GitHub Gist backup** — Store your backup in a GitHub Gist for easy restore across devices
- **Inline edit mode** — Toggle edit mode to add, remove, or modify playlists without leaving your current view
- **Playlist edit modal** — Click any playlist tile in edit mode to update URL, name, or description
- **Occasion tags** — Label mixtapes with occasions like Road Trip, Workout, Dinner Party, and more
- **Smart name display** — Long names like "Jack Smith" automatically display as "Jack S."
- **Welcome popup** — First-time visitors see a quick intro to the three key features
- **Mobile navigation** — Top tray for switching between your mixtapes and collaborations, bottom tray for main actions
- **Full backup system** — Back up everything: your playlists, curated mixtapes, and collected collaborations
- **Embedded Spotify player** — Listen to playlists directly in the app on larger screens
- **Responsive design** — Collapsible sidebar with tooltips on desktop, optimized trays on mobile

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

## Backup Your Data

Go to your **Profile** to back up your data. You have two options:

### GitHub Gist (Recommended)
1. Create a [GitHub Gist](https://gist.github.com) with any placeholder text
2. Click "Raw" on your gist and copy that URL
3. Paste the raw URL in the Backup section of your Profile
4. Click "Save" to copy your backup code
5. Paste the code into your gist and save it
6. On any device, enter your gist URL and click "Restore from Gist"

### Manual Backup
1. Click "Generate Backup Code" in your Profile
2. Copy the code and save it somewhere safe (Notes app, email, [notepad.cc](https://notepad.cc))
3. To restore, paste the code and click "Restore"

Your backup includes:
- Your main playlist collection
- Saved mixtapes with occasions
- Collected mixtapes from friends
- Profile information

## Limitations

- **Playlists must be public** — Private playlists can't be loaded via the oEmbed API
- **Local storage only** — Clearing browser data resets the app. Use GitHub Gist backup for persistent storage across devices
- **Short URLs** — The is.gd URL shortener may occasionally be unavailable

## Credits

- Hero images from Unsplash: [@rexcuando](https://unsplash.com/@rexcuando), [@mohammadmetri](https://unsplash.com/@mohammadmetri)
- Icons from [Google Material Symbols](https://fonts.google.com/icons)

## License

© 2025 fromnineteen80. All rights reserved.

This code is provided for personal use. Redistribution or resale is not permitted.

---

**Like this?** [Buy me a coffee](https://buymeacoffee.com/fromnineteen80)
