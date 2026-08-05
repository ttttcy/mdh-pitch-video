# Media Detective Hub — Pitch Video

Public playback page for the UNESCO Youth Hackathon 2026 pitch video.

The public player uses only the untouched 3840×2160 4K original. There are no
alternate quality choices. A prominent download button links directly to the
full 556 MB MP4 so visitors can save the original when their browser or network
cannot play the large file inline.

Play/pause and sound/mute each use one state-driven SVG inside one button. This
avoids the duplicate-icon issue caused by mobile Safari handling `hidden` on
inline SVG elements inconsistently.

The 4K MP4 was Fast Start optimized by relocating its `moov` atom; its audio and
video streams were not re-encoded. A mild display-only brightness adjustment is
applied in the web player and does not alter either media file.
