# blocklists

A collection of blocklists for use with [Pi-hole](https://pi-hole.net/) and other DNS-based blockers.

## Available Blocklists

### Spotify

| File | Description |
|------|-------------|
| [spotify/video.txt](spotify/video.txt) | Blocks Spotify video content (Canvas loop videos, video podcasts) in the Spotify app |

## Usage with Pi-hole

1. Go to **Settings → Blocklists** in your Pi-hole admin interface.
2. Add the raw URL of the desired blocklist file, e.g.:
   ```
   https://raw.githubusercontent.com/twentythree-ch/blocklists/main/spotify/video.txt
   ```
3. Click **Save and Update**.

## Blocklist Format

Each file contains one domain per line. Lines starting with `#` are comments and are ignored by Pi-hole.
