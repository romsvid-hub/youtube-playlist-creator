# YouTube Playlist Creator

A Chrome Extension that automatically curates a personal playlist from your YouTube subscriptions — only new videos, no Shorts, no livestreams.

Instead of scrolling through your feed, you get a clean playlist of up to 20 latest videos from channels you choose. The list updates every 24 hours and lets you manage the order, remove videos, and play them without leaving the extension.

## Features

- **Smart playlist** — up to 20 new videos from selected subscriptions, updated every 24h
- **Filter** — no Shorts, no livestreams, only regular videos
- **New badge** — green dot marks unwatched videos, disappears after viewing
- **Drag & drop** — reorder playlist manually or let it stay chronological
- **Undo delete** — restore removed videos within a 15-minute session
- **Background playback** — audio continues when extension is closed
- **Floating mini player** — play/pause, next, track title without opening the extension
- **Sync with YouTube tab** — if you open a video on YouTube, it syncs with the playlist
- **Persistent settings** — selected channels and preferences are saved between sessions
- **Google auth** — sign in with your existing Google account, silent token refresh

## Installation in Chrome

> The extension is currently in development mode. Follow these steps to install it manually.

1. Download or clone this repository
   ```
   git clone https://github.com/romsvid-hub/youtube-playlist-creator.git
   ```
2. Open Chrome and go to 
3. Enable **Developer mode** (toggle in the top right corner)
4. Click **Load unpacked**
5. Select the folder with the downloaded repository
6. The extension icon will appear in your Chrome toolbar
7. Click the icon → **Sign in with Google** → allow access to YouTube

## Setup

1. Click the extension icon
2. Open the accordion **"Обрати відстеження підписки"**
3. Check the channels you want to track
4. Save — your playlist will appear within seconds

## Tech stack

- Chrome Extension Manifest V3
- YouTube Data API v3
- Google OAuth 2.0
- Vanilla JS / HTML / CSS

## Roadmap

- [ ] Mobile app (separate branch)
- [ ] Custom update time (set playlist refresh hour)
- [ ] Playlist export
- [ ] Multiple playlists

## License

MIT
