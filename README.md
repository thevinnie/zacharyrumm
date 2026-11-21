# zacharyrumm.org

A memorial site for Zachary Rumm. It goes with the platypus bench placed in his memory at the Columbus Zoo in Columbus, Ohio, near the Australia exhibit. Visitors who find the bench can come here to learn who Zach was.

Live at <https://zacharyrumm.org>.

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: one page |
| `css/site.css` | All styling. The colors at the top are taken from the bench's paint |
| `img/` | The bench photo and three photos of Zach |
| `404.html` | Shown for mistyped addresses; points back to the home page |
| `favicon.svg`, `apple-touch-icon.png` | Browser tab and phone home-screen icons |
| `CNAME` | Tells GitHub Pages the site's domain. Don't delete it |
| `.nojekyll` | Tells GitHub Pages to publish the files as they are |

There is no build step, no JavaScript and nothing to install.

## Making a change

1. Edit `index.html` (the words and photos) or `css/site.css` (the look).
2. Preview it: run `python3 -m http.server` in this folder and open <http://localhost:8000>. Opening the file directly also works, except that the video shows an error.
3. Commit and push to `master`. The live site updates in about a minute.

## How it's hosted

- **GitHub Pages** publishes the `master` branch of this repository.
- **Cloudflare** manages the domain's DNS, sits in front of the site, and redirects `http` to `https` ("Always Use HTTPS").
- Mail to `info@zacharyrumm.org` is forwarded by Cloudflare Email Routing.

## Things worth knowing

- The Donate buttons link to the Columbus Zoo's general Zoo Fund page. If the Zoo changes that address, update the link in `index.html`; it appears three times.
- The video is hosted on YouTube, and the "Stay Connected" links point to Zach's own accounts on Facebook, YouTube, Twitter and Blogger. If one of those disappears, remove or replace its link.

## Rights

The words and photographs belong to Zach's friends and family. Please don't reuse them without asking: <info@zacharyrumm.org>.
