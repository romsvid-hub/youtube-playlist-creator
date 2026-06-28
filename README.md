# YouTube Playlist Creator

A Chrome Extension that automatically curates a personal playlist from your YouTube subscriptions — only new videos, no Shorts, no livestreams.

## The problem it solves

Keeping up with YouTube subscriptions takes time. To build a watchlist manually, you'd need to visit each channel, find recent videos, and repeat for every subscription you care about. The more channels you follow — the more time it wastes.

YouTube Playlist Creator eliminates that entirely. Instead of searching, you get a ready playlist of the latest videos from the channels you choose — automatically, every day. One click opens it as a queue in YouTube. You skip straight to watching.

## Features

- **Auto-curated playlist** — up to 20+ new videos from selected subscriptions, updated every 24h
- **No Shorts, no livestreams** — only regular videos
- **New badge** — green dot marks unwatched videos, disappears after viewing
- **Drag & drop** — reorder playlist manually or keep it chronological
- **Undo delete** — restore removed videos within a 15-minute session
- **Open in YouTube** — one click sends the full playlist as a queue to YouTube
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
5. Select the downloaded folder
6. The extension icon will appear in your Chrome toolbar
7. Click the icon → **Sign in with Google** → allow access to YouTube

## Setup

1. Click the extension icon
2. Open **"Обрати відстеження"** accordion
3. Check the channels you want to track
4. Save — your playlist will appear within seconds
5. Click **▶ Відкрити в YouTube** to start watching

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
