# shutter kif. — portfolio site

A single-page, scrolling portfolio: hero, about, a PSP-style console
for browsing work (photos or videos), and contact — with a light/dark
"invert" toggle and background music you can turn on/off.

## Preview it
Just double-click `index.html` to open it in a browser. No build step,
no dependencies — it's plain HTML/CSS/JS.

## Customize it
Open `index.html` and search for the word `EDIT:` — every comment
marked that way is a spot to swap in your own name, bio, email,
Instagram handle, or images.

- **Photos / video** — replace the files in `assets/img/` and
  `assets/work/` with your own (keep the filenames, or edit the
  `gallery` array near the bottom of `index.html`). To add a video,
  use an entry like:
  ```js
  { type: "video", src: "assets/work/my-clip.mp4",
    poster: "assets/work/my-clip-poster.jpg", title: "Reel" }
  ```
- **Music** — drop an `.mp3` file at `assets/audio/music.mp3`. See the
  README in that folder.
- **Colors / fonts** — the CSS variables at the top of the `<style>`
  block in `index.html` control the whole palette.

## Publish it (GitHub Pages)
1. Create a new GitHub repo and push this whole folder to it.
2. In the repo settings, turn on GitHub Pages for the main branch.
3. Your site will be live at `https://<username>.github.io/<repo>/`.

## What's inside
```
index.html            the whole site (HTML + CSS + JS, one file)
assets/img/            about + contact placeholder photos
assets/work/           six placeholder images for the console gallery
assets/audio/          put your music.mp3 here
```

The placeholder photos are abstract grain/gradient generated images —
swap every one of them out for your own photography before publishing.
