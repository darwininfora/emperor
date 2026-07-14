EMPEROR EVENT CENTER — WEDDING SITE
====================================

This folder is a complete website. Structure:
  index.html          <- the page
  images/             <- all 12 photos

HOW TO PUT IT ONLINE (pick ONE, all free):

1) NETLIFY DROP  (easiest — no account math, ~2 min)
   - Go to  https://app.netlify.com/drop
   - Drag this ENTIRE folder (emperor-wedding-site) onto the page
   - It gives you a live link instantly, e.g. random-name.netlify.app
   - Free account lets you rename it to emperor-wedding.netlify.app

2) GITHUB PAGES  (best if you want emperoreventcenter.com later)
   - Create a free github.com account
   - New repository -> upload index.html and the images folder
   - Settings -> Pages -> Branch: main -> Save
   - Live at  yourname.github.io/repo-name

3) CLOUDFLARE PAGES  (fast, free, custom domain friendly)
   - dash.cloudflare.com -> Pages -> Upload assets
   - Drag the folder, publish

CUSTOM DOMAIN (emperoreventcenter.com):
   - You already own the domain. In your host (Netlify/Cloudflare/GitHub),
     open Domain settings -> add emperoreventcenter.com, then update the
     DNS records at your domain registrar as they instruct.

TO EDIT LATER:
   - Text is inside index.html (search for the slide title text).
   - To swap a photo, replace the file in images/ keeping the same name.
