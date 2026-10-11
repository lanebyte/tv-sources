# tv-sources

Merged IPTV live-source playlist for FongMi / TVBox, regenerated from public
upstream lists.

## Use

Add this URL as a **live source** (设置 → 直播 → 直播源):

    https://lanebyte.github.io/tv-sources/merged.m3u

## What it is

`merged.m3u` is generated, not hand-written. Upstreams are
`best-fan/iptv-sources`, `iptv-org/iptv` and `Guovin/iptv-api`; every line was
downloaded and its first media segment pulled and measured before being kept.

Channels are grouped by genre via `group-title`, and each channel keeps at most
two lines. Repeated names inside a group are intentional — the same channel
carried by different upstreams is what the player's source switching falls back
through.
