# FitPro Security — landing page

A single self-contained web page, ready for GitHub Pages. No build step, no
dependencies, nothing to install.

```
index.html          the whole page (HTML + CSS in one file)
images/client-01..04.jpg   the four client transformations, faces blurred
images/og-image.jpg        the preview card shown when the link is shared
```

---

## 1. Put your form link in — do this first

The page has **three** Apply buttons, and all three currently point at a
placeholder. Open `index.html` in any text editor and find and replace:

```
PASTE-YOUR-GOOGLE-FORM-LINK-HERE
```

with your Google Form link (the one from **Send → link icon**, e.g.
`https://forms.gle/xxxxxxxx`). Replace all three. Until you do, the buttons
go nowhere.

## 2. Put it on GitHub Pages

1. Create a GitHub account if you haven't got one.
2. New repository → name it `fitpro-security` → **Public** → Create.
3. On the repo page, click **Add file → Upload files**.
4. Drag in `index.html` **and** the `images` folder. Commit.
5. **Settings → Pages**. Under *Source* choose **Deploy from a branch**,
   branch `main`, folder `/ (root)`. Save.
6. Wait two or three minutes. Your page is live at
   `https://<your-username>.github.io/fitpro-security/`

Any time you want to change wording, edit `index.html` on GitHub and commit —
the live page updates within a minute or two.

## 3. Optional: your own domain

A `.com` or `.co.uk` runs about £10–12 a year from Namecheap, Cloudflare or
similar. Once bought:

- In your domain registrar, add a `CNAME` record pointing `www` to
  `<your-username>.github.io`
- In **Settings → Pages → Custom domain**, enter your domain and tick
  **Enforce HTTPS**

`fitprosecurity.co.uk` reads far better in an Instagram bio than a
`github.io` address, and it costs less than a month of one client.

## 4. Then put the link out

- Instagram bio link, and in your story highlights
- LinkedIn: featured section and your headline
- Any post about the founding cohort

When you paste the link, the preview card uses `images/og-image.jpg`. If you
change the headline on the page, that image won't change by itself — it's a
picture, made separately.

---

## Notes

- **The form lives with Google, not here.** GitHub Pages only serves files;
  it can't receive answers. The Apply buttons link out to your form and
  Google collects the responses. That's a normal setup, not a compromise.
- **The photos are blurred in the files themselves**, not by the page, so
  saving or opening an image directly still shows a blurred face. Bodies,
  tattoos and backgrounds are still recognisable to anyone who knows these
  men — worth having their explicit agreement before the page is public.
- **Prices are in the page** in the founding cohort section. Change them
  there when the founding rate ends.
- The page works down to 320px wide and has no JavaScript, so it loads fast
  on bad signal — which matters for the people you're aiming at.
