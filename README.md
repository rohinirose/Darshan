# Darshan's Midnight Birthday Website 🖤🌙

A responsive black-and-white birthday website with:
- A welcome question and a playful moving **NO** button
- **YES** opens a live countdown to November 24, 2026 (midnight, India time)
- The birthday surprise stays locked until the countdown reaches zero
- A birthday letter and cinematic photo gallery with tap-to-enlarge previews
- Monochrome starry background, soft transitions, and mobile-friendly layout

## Add your photos

Open the `images` folder and add your own photos with these exact names:
- `darshan-cover.jpg`
- `darshan-1.jpg`
- `darshan-2.jpg`
- `darshan-3.jpg`
- `darshan-4.jpg`

Use JPG photos for the simplest setup. If your images are PNG, either convert them to JPG or change the filenames in `index.html` to match your image extensions.

## Preview on your computer

Double-click `index.html`. It should open in your browser. The photo areas will be empty until you add the images above.

## Publish it with GitHub Pages

1. Sign in at https://github.com
2. Create a new **Public** repository, for example `darshan-birthday`.
3. Open the repository and choose **Add file → Upload files**.
4. Upload `index.html`, `README.md`, and the `images` folder (with your photos inside).
5. Click **Commit changes**.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, select **Deploy from a branch**.
8. Choose branch **main** and folder **/(root)**, then click **Save**.
9. Wait a little and refresh the Pages section. GitHub will show your public website URL.

## Important notes

- The site is designed for a birthday on **November 24, 2026**, using India Standard Time.
- GitHub Pages websites are public. Anyone who has the link may view the site.
- The countdown is a front-end experience, not a secure privacy lock. A technically curious visitor could inspect the website files. Don't put private or sensitive information on it.
- The Google Fonts import needs an internet connection; the page still works if the fonts cannot load.


## Photo display update

The cover photo is also shown on the first welcome screen. Photo areas use `object-fit: contain` so the full photo stays visible instead of being cropped. A photo cannot become genuinely HD if the original file has low resolution; use the original full-resolution photos from the phone/camera for the sharpest result.
