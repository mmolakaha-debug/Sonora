# Sonora — Stage 01

A first visual and interactive prototype for a personal music library.

## Run it
1. Download and extract `Sonora-Stage-01.zip`.
2. Open the `Sonora` folder.
3. Double-click `index.html` to open it in Firefox, Chrome, or Edge.
4. Click **Add music** or **Choose folder** and select your audio files.
5. Open **Songs**, then click the play icon on a track.

For a better development workflow, open the folder in VS Code and run it with the Live Server extension.

## Included in this stage
- Light, minimal, responsive music-library interface.
- Import multiple audio files or choose a folder.
- Browse Songs, Albums, and Artists.
- Basic filename parsing: `Artist - Track.mp3` becomes artist + track title.
- Audio playback, previous/next, shuffle, repeat, volume, seek bar.
- Download individual tracks or album tracks.

## Important limitation
This is a **local prototype**, not the cloud version yet. Imported audio is held temporarily in browser memory. If you refresh or close the page, re-import the files. Your music has not been uploaded to a server. Stage 02 will add persistent library metadata, and the cloud-storage stage will add secure uploads and access from other devices.

## Privacy
This prototype does not upload audio files anywhere. Files stay in the browser session on your device.
