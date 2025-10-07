Place your media assets in these folders:

- assets/images/
  - Put image files here (jpg, png, webp). Example: assets/images/image-1.jpg
  - Recommended sizes: 1200px wide for hero/large images; smaller thumbnails around 600px.

- assets/videos/
  - Put video files here (mp4, webm). Example: assets/videos/video-1.mp4
  - Recommended: H.264 MP4, 720p or 1080p for good compatibility.

Naming guidance:
- Use predictable names like image-1.jpg, image-2.jpg, video-1.mp4.
- If you have versions, append a short suffix, e.g., image-1@2x.jpg for high-res.

Usage:
- Image samples referenced in `spot-ai.html` expect assets/images/image-1.jpg ... image-6.jpg
- Video samples referenced in `spot-ai.html` expect assets/videos/video-1.mp4 ... video-3.mp4

- If a video file is missing, the page will use assets/videos/placeholder-poster.svg as a poster and show a notice. You can replace this poster with your own preview image named placeholder-poster.svg.

Notes:
- Keep file sizes reasonable for the web. Use compression tools for images and videos before adding them.
- If you plan to host assets remotely, update the src paths in `spot-ai.html` to the remote URL.
