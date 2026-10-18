# Tango Dojo

Flashcards for all 894 Minna no Nihongo N5 words (Lessons 1 to 20). Installable on phones, works offline, progress saved on each device.

## Put it online (free)

**GitHub Pages:** create a public repo, upload everything in this folder (keep the `icons` folder), then Settings > Pages > Deploy from branch > `main` / root. Your link is `https://<username>.github.io/<repo>/`.

**Vercel or Netlify:** drag this folder onto https://app.netlify.com/drop, or run `npx vercel` inside it.

It must be served over https for install and offline to work.

## Install on a phone

- iPhone: open the link in Safari, tap Share, then Add to Home Screen.
- Android: open in Chrome, tap Install app (or the menu, then Add to Home screen).

## Updating

Change `index.html`, redeploy, and bump `VERSION` in `sw.js` so phones pick up the new version.
