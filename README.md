# 🍄 mushroom steam

Rooms for you and your friends — gameplay streaming, a voice lounge and chat — brought
together by **your own small server**, with everything flowing **peer-to-peer**.

Someone creates a room and gets a permanent code like `MUSH-7Q2K4-9XB3M`; friends enter it
once and the room stays in their list. Whenever members have the app open they are linked
directly to each other: streams, voice and chat never pass through the server, which only
introduces people (and relays as a last resort when a strict NAT blocks a direct path).

**This repository holds the downloads and the documentation.** The app and server source
live in a separate repository.

## Download

**Windows:** get `mushroom-steam-Setup-X.Y.Z.exe` from the
[Releases page](https://github.com/Zachary-work/mushroom-steam/releases/latest) and run it
once (per user, no admin needed). After that the app checks this page when it starts and
offers newer versions: *Install now* downloads and restarts into them.

You also need a server to point the app at: see the setup guide.

## Documentation

- **Guides:** https://zachary-work.github.io/mushroom-steam/ (also in [`docs/`](docs/))
  - [Get started · App](https://zachary-work.github.io/mushroom-steam/client.html)
  - [Get started · Server](https://zachary-work.github.io/mushroom-steam/server.html) — a Raspberry Pi is plenty
  - [Settings](https://zachary-work.github.io/mushroom-steam/settings.html)

The guides currently show the 0.4 app; the server steps are unchanged for 0.5. Each
release's notes list what changed.

## What's in a release

| Feature | |
|---|---|
| Rooms | permanent code, saved on your server; members come and go freely |
| Streaming | 720p–4K, 30/60/120 fps, 1–100 Mbps; VP9, H.264 (GPU) or AV1; change quality, screen or window while live; one direct stream per viewer |
| Voice lounge | mic noise suppression (RNNoise or DeepFilterNet3), speaking rings, mute/deafen, device pickers with a level meter |
| Chat | stored on members' PCs and shared between them; nothing on the server |
| Game audio | only the shared window's own sound (Windows), or the whole desktop's |

## License

MIT — see [LICENSE](LICENSE).
