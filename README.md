# Spotify-Last.fm Integration Script

## Usage Instructions

### 1. Prerequisites

#### Spotify Developer Account
Ensure you have registered an app in the Spotify Developer Dashboard and obtained `SPOTIPY_CLIENT_ID` and `SPOTIPY_CLIENT_SECRET`.

#### Last.fm API Account
Register on Last.fm API and obtain `LASTFM_API_KEY` and `LASTFM_API_SECRET`.

### 2. Environment File (.env)
Create a `.env` file in the project directory with the following keys:


```env
SPOTIPY_CLIENT_ID=your_spotify_client_id
SPOTIPY_CLIENT_SECRET=your_spotify_client_secret
LASTFM_API_KEY=your_lastfm_api_key
LASTFM_API_SECRET=your_lastfm_api_secret
```

### 3. Script Capabilities
This script integrates Spotify and Last.fm APIs to:

- Retrieve user's top tracks, top artists, and saved tracks from Spotify.
- Fetch similar tracks for a given track or artist using Last.fm API.
- Create a Spotify playlist with recommendations based on Last.fm's similar track suggestions.
- Edit playlist information such as name, description, cover image, collaboration status, and public status.