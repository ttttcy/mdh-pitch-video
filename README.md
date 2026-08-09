# Media Detective Hub — Pitch Video

Public playback page for the UNESCO Youth Hackathon 2026 pitch video.

The public player uses one complete, full-length 1920×1080 H.264 HD file hosted
as a GitHub Release asset. It is not split or cropped, and there are no alternate
quality choices. A prominent download button links directly to the untouched
556 MB original 4K MP4.

Play/pause and sound/mute each use one state-driven SVG inside one button. This
avoids the duplicate-icon issue caused by mobile Safari handling `hidden` on
inline SVG elements inconsistently.

The downloadable 4K MP4 was Fast Start optimized by relocating its `moov` atom;
its audio and video streams were not re-encoded. A mild display-only brightness
adjustment is applied in the web player and does not alter the media files.

Submitted by Media Literacy Science Popularization Base, SWUPL.
