# Kaushal Gohil — Portfolio + Blog

Free to host, no domain required.

## 1. Fill in your content
- `index.html` — replace the bracketed `[...]` placeholders in Education, Clinical
  Experience, Research, and Contact with your real details.
- `blog/first-post.html` — replace with a real post, or delete once you've added
  your own posts.

## 2. Put it on GitHub Pages (100% free, free URL)
1. Create a new **public** repo on GitHub named **exactly** `<your-username>.github.io`
   (replace `<your-username>` with your actual GitHub username — this exact name is
   what makes the free URL work).
2. Push these files to the repo's `main` branch:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages** → under "Build and deployment", set
   **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
4. Within a minute or two, your site is live at:
   ```
   https://<your-username>.github.io
   ```

That's it — no purchase, no DNS, no renewal fees. If you ever want the
kaushalgohil.com domain later, you can add it at any time without rebuilding
anything (see the note at the bottom of this file).

## Adding a custom domain later (optional, not required)
Buy the domain from any registrar, add a `CNAME` file to this repo containing
just `kaushalgohil.com`, add the DNS records GitHub's docs specify, and enter
the domain under Settings → Pages. Everything else stays the same.
