# Media Detective Hub — Pitch Video

Public playback page for the UNESCO Youth Hackathon 2026 pitch video.

Desktop browsers default to the 1080p network-optimized H.264/AAC Release asset.
Phones default to a full-length 960×540 H.264/AAC MP4 served directly by GitHub
Pages with a standard `video/mp4` response, avoiding the attachment MIME type
that can prevent inline playback in mobile Safari. The player also offers an
in-page switch to the untouched 4K original and keeps a direct 4K fallback link.

Play/pause and sound/mute each use one state-driven SVG inside one button. This
avoids the duplicate-icon issue caused by mobile Safari handling `hidden` on
inline SVG elements inconsistently.

The 4K MP4 was Fast Start optimized by relocating its `moov` atom; its audio and
video streams were not re-encoded. A mild display-only brightness adjustment is
applied in the web player and does not alter either media file.
