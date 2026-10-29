# Photography portfolio

A one-page gallery site. No build step, no dependencies.

## 1. Add your photos

1. Create a folder named `photos` next to `index.html`.
2. Copy your original image files into it (JPG, PNG, WebP all work).
3. Open `index.html` and edit the block at the top of the `<script>`:
   - your name, tagline, bio
   - email / Instagram links
   - the `photos` list: one line per file, in the order you want them shown

The first photo in the list becomes the full-screen cover.

## 2. Keep the quality

The site never re-compresses or crops your gallery photos. It shows the exact files you upload, and the viewer opens the same file, scaled down only to fit the screen.

So the quality depends on the files you upload:
- Upload the exported JPGs, not screenshots or WhatsApp copies (WhatsApp and Instagram compress heavily).
- GitHub allows files up to 100 MB and recommends repos under 1 GB. A set of 10 to 20 full-resolution JPGs fits easily.
- If the page loads slowly on weak Wi-Fi, export at about 2500 to 3000 px on the long edge at JPEG quality 90 or higher. That still looks sharp on any screen.

## 3. Host it on GitHub Pages

1. Create a new public repository on GitHub, for example `photo-portfolio`.
2. Upload `index.html` and the `photos` folder (drag and drop works on the repo page: **Add file > Upload files**).
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then Save.
5. After a minute or two your site is live at `https://<your-username>.github.io/photo-portfolio/`.

Put that link in the RAW induction form.

## Troubleshooting

- A dashed box saying "Photo not found" means the file name in `index.html` doesn't match the file in `photos`. Names are case sensitive on GitHub (`IMG_01.JPG` is not `img_01.jpg`).
- Changes can take a minute or two to appear after you upload.
- To preview locally, just double-click `index.html`.
