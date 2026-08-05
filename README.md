# Media Detective Hub — Pitch Video

Public playback page for the UNESCO Youth Hackathon 2026 pitch video.

The videos are distributed as GitHub Release assets. The HTML5 player defaults
to a 1080p network-optimized H.264/AAC copy and offers an in-page switch to the
untouched 4K original. It loads only metadata initially, supports native seeking
and fullscreen playback, and keeps a direct 4K-file fallback link.

The 4K MP4 was Fast Start optimized by relocating its `moov` atom; its audio and
video streams were not re-encoded. A mild display-only brightness adjustment is
applied in the web player and does not alter either media file.
