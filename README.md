# Personal Portfolio Site

A minimal 4-page portfolio: **About / Experiences / Education / Blog**. Plain HTML + CSS, no build step, so it deploys straight to GitHub Pages.

## Files

```
index.html        About / home (name, bio, nav cards)
experience.html    Work history timeline
education.html     Education timeline
blog.html          List of blog / article links
assets/style.css   Shared styling
```

## Customize

Every spot you need to edit is marked with `<!-- EDIT: ... -->` comments.

1. **index.html** — replace "Your Name" and "yourname", write your one-line bio.
2. **experience.html** — duplicate the `<article class="entry">` block for each role, fill in dates, title, company, description. Most recent first.
3. **education.html** — same pattern, one `<article class="entry">` per degree/school.
4. **blog.html** — replace each `href="#"` with your actual article/LinkedIn post URL, and update the link text.
5. **Page `<title>` tags** — swap "Your Name" for your actual name in all four files.
6. Footer copyright name in all four files.

## Run locally

No build tools needed — just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to "Deploy from a branch".
4. Choose your default branch (e.g. `main`) and folder `/ (root)`, then **Save**.
5. GitHub will give you a URL like `https://yourusername.github.io/your-repo/` within a minute or two.

If you'd rather deploy from a `docs/` folder, move all files into `docs/` and select that folder in the Pages settings instead.
