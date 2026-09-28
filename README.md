# M3U Editor (Playlist Bench)

A single self-contained HTML page for editing IPTV M3U playlists in your browser — no install, no server, no build step. Open `Playlist Bench — M3U Editor.html` and load a playlist from a local file, a URL, or an Xtream Codes portal.

## Features

- **Channel editing** — search/filter, multi-select (Shift-click, Ctrl/Cmd+A), drag-and-drop reordering, bulk find/replace on names, bulk group assignment, bulk stream URL http/https scheme fix, and an auto-clean-names cleanup.
- **Groups/categories** — drag-and-drop reordering, with up/down controls for mobile.
- **Logo matching** — fuzzy-matches channel names against a GitHub-hosted logo folder, with manual picks, hover-to-zoom preview, and a "needs review" filter so re-matching an edited playlist doesn't force you to re-check everything.
- **EPG (XMLTV) matching** — supports multiple EPG sources per playlist, combined into one now/next view; sources are remembered and can be re-fetched individually.
- **Logo resizer** — batch resize, pad, recolor the background, and convert format for logos, including pulling them straight from the loaded playlist.
- **Loading playlists from URL/Xtream** — when a direct fetch is blocked by CORS, the tool explains the download-then-upload workaround.
- **Per-playlist settings memory** — GitHub logo URL, Xtream credentials, load URL, and resize defaults are remembered per playlist filename (stored in your browser's local storage — nothing leaves your machine).
- **Light/dark theme** and **English/Portuguese language toggle**.
- **Built-in help** — click the "?" button in the app for a full walkthrough.

## Usage

Just open `Playlist Bench — M3U Editor.html` in a modern browser (Chrome or Firefox recommended). Everything runs client-side; no data is sent to any server except the playlist/EPG/logo sources you explicitly load.

## License

MIT — see [LICENSE](LICENSE).
