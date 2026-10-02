# Overview media provenance

Updated on 2026-10-02 from the website's refreshed real-app overview.

- `dev-workbench-overview.mp4`: 35 seconds, 2880 × 1750, H.264 at 60 fps,
  silent, Fast Start, 2,401,096 bytes.
- `dev-workbench-overview.gif`: the complete MP4 converted to a looping GIF,
  35 seconds, 960 × 583, 10 fps, 350 frames, 2,685,595 bytes. Conversion uses
  Lanczos scaling, a generated palette, and Sierra dithering.
- MP4 SHA-256: `613bdb6a630ebb67dde3d9aaab5502b9e01b5730cf10e8fab4eb9ce24ac69b9e`.
- GIF SHA-256: `b5f707ca2d1222e233556a34a3273eda22f4aa251b604ce567021af4c58ca031`.

The opening five seconds use the original small synthetic JSON example in
the current Release 1.0 (build 2) UI, with Pro verified before capture. The
remaining JSON/YAML, cURL, Text Diff, Log Analyzer, and Local Data footage is
preserved from the earlier Release 1.0 (build 1) overview. All segments retain
their normal speed and order. The existing WebP depicts a retained scene.

The original masters, capture provenance, and previous support-repository
deliveries remain in the external `workbench-demo` media archive. The website
repository's `docs/media-capture.md` records the underlying capture and edits.
Reviewed footage uses synthetic data; no private values were introduced by
this conversion. GIF timing, dimensions, frame count, and decode were checked;
sampled frames cover all six workflows. GIF visual acceptance remains pending.
