# Jhanna's 21st Birthday

A self-contained Gothic birthday experience for GitHub Pages. The page uses plain HTML, CSS, and JavaScript in `index.html`; it needs no build step, libraries, or server.

## Add your photos and music

Put your own photos and audio beside `index.html` before publishing:

- `1.png`, `2.png`, `3.png`, and onward for the album. Use consecutive numbers with no gaps. The page displays up to 24 photos and stops at the first missing number.
- `music1.mp3` for the optional background music. The music button can start and pause it.

The album has four layouts: Nocturne, Film Strip, Scrapbook, and Moonlight. If you have not added photos yet, it shows a reminder in the album.

## Publish with GitHub Pages

1. Unzip this folder and place `index.html`, `README.md`, your numbered photos, and `music1.mp3` at the top level of your GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the branch and root folder that contain `index.html`, then save.
4. Open the Pages URL after the deployment finishes.

The birthday key is checked in the browser using a SHA-256 digest; the key itself is not written into this package. GitHub Pages is static hosting, so the check is only a playful entrance screen. Anyone who can inspect the public page can bypass a client-side gate, and a short numeric key can be guessed. Do not use it to protect private photos or sensitive information.

## Personalize the letter

Open `index.html` in a text editor and edit the paragraphs inside `<article class="letter">` to make the message your own. The page is English-only as requested.
