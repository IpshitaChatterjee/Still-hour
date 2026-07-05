# Stillhour

A minimal, single-file meditation timer. Set a duration, upload your own track, and it fades out smoothly right as the timer ends.

## Use it

Open `index.html` in any modern browser (desktop or mobile). No build step, no server required.

## Features

- Pick a session length (5–30 min, via quick-select chips)
- Upload any audio file (MP3, M4A, MP4 audio) to play during the session — loops for the full duration
- Smooth 10-second fade-out timed to the end of the session
- Pause / resume / reset
- Calm, minimal interface with a breathing-ring animation

## Host it for free (GitHub Pages)

Once this repo is pushed to GitHub:

1. Go to the repo's **Settings → Pages**
2. Under "Build and deployment," set **Source** to `Deploy from a branch`
3. Choose the `main` branch and `/ (root)` folder
4. Save — GitHub will give you a URL like `https://yourusername.github.io/stillhour/`

That URL works on your phone too — no app install needed, just bookmark it or add it to your home screen.

## Notes

- The uploaded track is only held in memory for that browser session — it's not saved anywhere, so you'll re-upload it each time you open the page fresh.
