# Secret Code Reveal Page

A simple lock-and-reveal webpage.

## What this does
- Secret code is `open`.
- After unlock, it shows the requested track details:
  - **Artist:** SheandHimOfficial
  - **Song:** I Thought I Saw Your Face Today
- Includes a Play button for local audio playback.

## 1) Add the music file
Place your audio file at:

`assets/i-thought-i-saw-your-face-today.mp3`

> If this file is missing, the page still works but audio playback won't start.

## 2) Run locally (recommended)

```bash
./run.sh
```

Then open:

`http://127.0.0.1:4173`

## 3) Put it on GitHub Pages (so it opens online)

1. Create a new GitHub repo.
2. In this project folder run:

```bash
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git
git push -u origin work
```

3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: `work` and folder `/ (root)`
5. Save and wait 1-2 minutes.
6. Open your live URL from the Pages section.

## Troubleshooting
- If you open with double-click (`file://...`) and it looks broken, use `./run.sh` instead.
- If unlock doesn't work, enter exactly: `open`.
