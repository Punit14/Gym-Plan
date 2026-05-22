# Media Folder – Gym Machine Photos & Videos

Drop photos and videos here. The app auto-detects them by filename — no code changes needed.

## Naming convention

Files must be named after the exercise, lowercased, with hyphens instead of spaces, plus a `-1`, `-2` number suffix.

| Exercise name          | File(s)                                              |
|------------------------|------------------------------------------------------|
| Chest Press            | `chest-press-1.jpg`, `chest-press-2.jpg`, …         |
| Lat Pulldown           | `lat-pulldown-1.jpg`, `lat-pulldown-1.mp4`, …       |
| Doorway Chest Stretch  | `doorway-chest-stretch-1.jpg`                        |
| Warm-up                | `warm-up-1.jpg`                                      |

**Rules:**
- Always start at `-1` (there is no un-numbered version)
- Numbers must be sequential with no gaps (`-1`, `-2`, `-3` — not `-1`, `-3`)
- The app tries up to `-6` per exercise; stop there or add more by changing `MEDIA_MAX` in `index.html`

## Supported formats
- **Images:** `.jpg` / `.jpeg` → save/export as JPG
- **Videos:** `.mp4` → convert MOV → MP4 if needed (AirDrop from iPhone converts automatically when sent to a Mac)

## Example folder layout
```
media/
  chest-press-1.jpg
  chest-press-2.jpg
  chest-press-1.mp4
  lat-pulldown-1.jpg
  leg-press-1.jpg
  leg-press-2.jpg
```

## What happens with no media
If no files exist for an exercise, the thumbnail strip is hidden automatically — the card looks exactly as before.
