# FF4D experiments

A static website with a homepage and a **DPO Validation** tab.

The validation page contains ten synchronized comparison videos. Panels are ordered:

1. Before DPO
2. DPO update 100 with the pre-DPO layout
3. DPO update 100

## Preview locally

Run `python3 -m http.server 8000` from the repository root, then open
`http://localhost:8000/`.

## GitHub Pages

Serve the `main` branch from `/ (root)` in **Settings → Pages**. The site uses
relative links and includes the video files, so no build step is needed.
