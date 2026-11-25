# Rare Diseases with Dr. Hans

Website for Dr. Hans (infectious and rare diseases): podcasts, documentaries, contact. Built and maintained by Ray Wolters / KWB Media.

## How it's built
- Plain static site, four pages: `index.html`, `podcasts.html`, `documentaries.html`, `contact.html`. Shared styles in `styles.css`.
- Images sit in the repo root (`LOGO.JPEG`, `background.png`, `Website background6.png`, `meet-dr-hans.JPG`, `contact-dr-hans.JPG`). Filenames have spaces and uppercase extensions, so match them exactly.
- Videos are YouTube embeds (the documentary currently uses `vgIAD5osLLw`). Swap the video ID rather than committing video files.

## Hosting
Ray keeps hosting lean across his sites (he's at his Vercel plan limit). Don't add services or big files.

## Standing order: keep this file current (Ray asked for this permanently)
- Whenever you commit work in this repo, update the "Current state / where we left off" section below **in the same commit**: what changed, what's half-done, what's next. Don't wait to be asked.
- If anything above goes stale (new page, new game, hosting change, new gotcha), fix it in that commit too.
- Keep the "where we left off" section to the last few sessions; trim older lines so the file stays short.
- Ray works on two computers. At the start of a session, `git pull` before touching anything; push when done.

## Current state / where we left off
- Last change: replaced the documentary video with `vgIAD5osLLw`.
