# Portfolio site

A single page portfolio for my independent AI security and cyber security contracting work. Plain HTML and CSS, no build step, hosts anywhere static.

## Publish on GitHub Pages

The quickest route is a user site, which serves at the root of your GitHub domain.

1. Create a new public repository named `annamenikou.github.io`.
2. Upload everything in this folder, `index.html`, `og-image.png`, `favicon.svg` and `.nojekyll`, to the root of that repository.
3. Open Settings, then Pages, and set the source to the `main` branch and the root folder.
4. Wait a minute or two, then visit `https://annamenikou.github.io`.

If you would rather keep it inside a project repository, that also works. The site will then live at `https://annamenikou.github.io/REPO-NAME`. In that case add the repo name to the two share image URLs and the page URL in the head of `index.html`, otherwise the link preview image will not load.

## Before you go live

The second report needs a link. Open `index.html` and find the LASR Market Insights Report card. Replace `href="#report-2"` with the real URL and remove the word `pending` from that link's class so it becomes an active link like the other one. Both edit points are marked with comments so they are easy to spot.

The supply chain paper currently points at the Cisco blog about the white paper. Swap that href if you have a link you prefer.

## Files

- `index.html` is the whole site, including the embedded favicon.
- `og-image.png` is the preview card that shows when the link is shared.
- `favicon.svg` is the same mark as a standalone file, used for the iOS home screen icon.
- `.nojekyll` tells GitHub Pages to serve the files as they are.

## Notes

The fonts load from Google Fonts, so the page needs an internet connection to look exactly right. Everything else is self contained.
