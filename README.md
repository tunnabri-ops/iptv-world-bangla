# 📺 IPTV World Bangla

**A checked playlist of 10 world news channels, plus a small player that runs in your browser.**

## ✨ Features

- 10 world news channels, each live-checked — every stream returned HTTP 200 and a real playlist.
- `index.html` — a small Bangla player: pick a channel, watch it in the browser.
- `playlist_world.m3u8` — the playlist file, ready for VLC, MPV, or any IPTV app.

| Channel | Country |
|---|---|
| Al Jazeera English | Qatar |
| DW English | Germany |
| Euronews English | Europe |
| Sky News Arabia | UAE |
| NDTV 24x7 | India |
| Al Arabiya English | Saudi Arabia |
| TRT World | Türkiye |
| WION | India |
| NHK World-Japan | Japan |
| CNBC UK | UK |

## 🚀 How to use

**In the browser:** open `index.html` and click a channel.

**In VLC:**

1. Media → Open File → select `playlist_world.m3u8` to load all 10 channels, or
2. Media → Open Network Stream → paste one stream URL from the playlist.

## ⚠️ Honest limits

- Streams belong to their broadcasters — a channel can change address or go offline at any time.
- Euronews redirects once (HTTP 302) — use a player that follows redirects (VLC and MPV do).
- One candidate stream was tested and dropped because it was unreachable, so it is not in this playlist.

## 🇧🇩 বাংলা

**আইপিটিভি ওয়ার্ল্ড বাংলা — বিশ্ব সংবাদ চ্যানেলের যাচাই করা প্লেলিস্ট।**

- ১০টা বিশ্ব সংবাদ চ্যানেল, প্রতিটা লাইভ যাচাই করা
- ব্রাউজারে চালানোর জন্য ছোট প্লেয়ার (`index.html`)
- VLC/MPV বা যেকোনো IPTV অ্যাপে `playlist_world.m3u8` খুললেই চলবে

## 📄 License

MIT — use it however you like.
