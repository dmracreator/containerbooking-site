# containerbooking.com — website

Source of the live site at <https://containerbooking.com>, hosted on GitHub Pages from
<https://github.com/dmracreator/containerbooking-site> (branch `main`, root folder).

## Files
- `index.html` — the whole site (HTML, CSS, JS and graphics inline; no build step).
- `CNAME` — custom domain for GitHub Pages (`containerbooking.com`). Don't remove it.
- `.nojekyll` — tells GitHub Pages to serve the files as they are.

## Update the live site
**Web upload:** on the repo page choose *Add file → Upload files*, drag in the changed
`index.html`, click *Commit changes*. The live site updates within a minute or two.

**Git:** this folder is a clone of the repo.
```bash
cd "~/Documents/Documents/Active websites/Container Booking/website"
git pull
git add -A && git commit -m "Describe the change"
git push
```

## Preview locally
Open `index.html` in a browser.
