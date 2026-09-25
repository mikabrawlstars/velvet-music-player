# Velvet


**Your music. Every word in focus.**


Velvet is a desktop music player for Windows, built around a unified music library and expressive, synchronized lyrics. It brings local music and supported music providers together in a clean, focused listening experience.


> **Currently in development.** Features, provider integrations, and availability may change as Velvet evolves.


## One library, multiple sources


Velvet treats a song as a single track, even when it is available from more than one source. Local files and supported provider connections can belong to the same track, keeping favorites, playlists, and listening history together when the playback source changes.


The provider-based design supports integrations such as Spotify Connect and TIDAL catalog search, with room for additional services in the future. Playback capabilities depend on the provider; catalog access does not necessarily include streaming playback.


## Lyrics that move with the music


Synchronized lyrics are at the heart of Velvet. TTML support enables precise word-by-word highlighting, smooth line transitions, and a focused lyrics view. Lyrics follow the playback position when pausing, resuming, or seeking. Line-synchronized and static lyrics are supported as well.


## Development status


Velvet is actively being developed, with a focus on reliable playback, a consistent library across providers, and a polished desktop experience.


This repository is the public project overview. It contains documentation only; the Velvet application source code and private configuration are not published here.

## Privacy / Datenschutz

The German privacy policy for **Velvet: Music Player** is available at:

**[Datenschutzerklärung](https://mikabrawlstars.github.io/velvet-music-player/privacy/)**

It describes the current local-backend development version. No public Velvet
account or cloud backend is currently operated. Review and update the policy
before a public app release or any cloud rollout, including complete controller
contact information and the actual hosting, retention and deletion arrangements.

## Documentation website

GitHub Pages publishes the static `docs/` directory from `main`.
In **Settings → Pages**, use **Deploy from a branch → main → /docs**.
The `.nojekyll` marker disables Jekyll processing; no dependencies, build workflow,
external fonts or client scripts are required.

- Project page: `docs/index.html`
- Privacy policy: `docs/privacy/index.html`
- Shared styles: `docs/assets/site.css`

Keep this repository documentation-only. Never add application source code,
private configuration, credentials, user databases or personal library exports.
