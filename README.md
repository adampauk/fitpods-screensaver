# fitpods-screensaver

Media feed for the FitPods pod TVs (Aerial Views screensaver).

## How to change what the pod TVs show
1. Upload images/videos into the `media/` folder (drag & drop on github.com).
2. Edit `feed.csv` — one full URL per line.
3. Commit. Every pod picks up the new list at its next screensaver activation.

No ADB, no visiting the pods.

## URL entered on each box
Aerial Views -> Media sources -> Custom feeds -> Feed URLs:

https://raw.githubusercontent.com/adampauk/fitpods-screensaver/main/feed.csv

## Rules
- Images: JPG/PNG, 1920x1080 landscape, under ~2 MB each.
- Video: MP4 (H.264/HEVC), 1920x1080, keep short.
- Images and videos can be mixed freely in one feed.
- Images show ~30 s each; videos play through.
- `feed.csv` = full https:// URLs, one per line. No quotes, no header row.
