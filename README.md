# IPTV World Bangla — বিশ্ব সংবাদ চ্যানেল প্লেলিস্ট

World news IPTV playlist built from **iptv-org/iptv**.

- **Original repo:** https://github.com/iptv-org/iptv (144k+ stars — collection of publicly available IPTV channels from all over the world)
- **This repo:** a small, checked playlist — not the giant 10,000-channel index.

## কী আছে / What is inside

`playlist_world.m3u8` — 10 world news channels:

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

## যা ঠিক করা হয়েছে / What was fixed

- The upstream `index.m3u` lists thousands of channels, many dead. This playlist keeps **only 10 streams that were live-checked on 2026-11-23** — each returned HTTP 200 and a real `#EXTM3U` playlist.
- **Dropped:** Sky News via `dash4.antik.sk` — listed upstream but unreachable (connection failed), so it is not in this file.
- Euronews redirects once (302) — use a player that follows redirects (VLC/MPV do).

## ব্যবহার / How to use

1. Open VLC → Media → Open Network Stream → paste one stream URL from `playlist_world.m3u8`, or
2. Media → Open File → select `playlist_world.m3u8` to load all 10 channels.
3. Or open the raw file URL in any IPTV player app.

## সতর্কতা

Streams belong to their broadcasters and can change or go offline. If a channel stops, check the upstream list at https://iptv-org.github.io/iptv/ for a new URL.
