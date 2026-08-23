# Putting the Command Center on GitHub — click-by-click

No command line needed. This takes about 10 minutes. I can't log into your
GitHub from here, so these steps are yours to click through — but they're simple.

You'll decide one thing first:

| If you want… | Choose | Result |
|---|---|---|
| A safe online backup + version history | a **Private** repo | Only you can see the code. No live link. |
| A live web link you can open on any device | a **Public** repo + Pages | The *app code* is public at a URL. **Your data is still private** — it never leaves your browser. |

Either way, **none of your household data ever goes to GitHub.** The file only
contains the app itself; your numbers live in your browser on your device.

---

## Part 1 — Create the repository

1. Go to **https://github.com** and sign in (or click **Sign up** if you don't
   have an account — it's free).
2. Click the **+** in the top-right corner → **New repository**.
3. **Repository name:** `provision-house` (or any name you like).
4. **Description** (optional): `The Provisioned Household — CFO Command Center`.
5. Choose **Private** or **Public** (see the table above).
6. Leave everything else as-is and click **Create repository**.

---

## Part 2 — Upload the files

1. On your new empty repo page, click the link **“uploading an existing file”**
   (or the **Add file** button → **Upload files**).
2. Drag these three files into the box (or click **choose your files**):
   - `index.html`
   - `README.md`
   - `GitHub-Setup-Guide.md`
   *(You can also add `provisionedhousehold.html` if you want the original name too.)*
3. Scroll down and click the green **Commit changes** button.

That's it — your Command Center is now on GitHub. To update it later, open the
repo, click **Add file → Upload files**, drop in the newer `index.html`, and
**Commit changes** again.

---

## Part 3 (optional) — Get a live web link with GitHub Pages

Do this only if you chose a **Public** repo and want to open the app from any
device by visiting a link.

1. In your repo, click **Settings** (top menu).
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Under **Branch**, pick **main** and the **/(root)** folder, then click **Save**.
5. Wait about a minute, then refresh. GitHub shows a link like:
   `https://YOUR-USERNAME.github.io/provision-house/`
6. Open it — that's your live Command Center. Bookmark it on your phone.

**Reminder:** the live page is the *app*. Each device keeps its own data in its
own browser. If you enter your budget on your laptop, it won't appear on your
phone automatically — use **Back up my data** on one device and **Restore backup**
on the other to move it. (Meal PDFs are stored per-device and aren't included in
that backup file.)

---

## A note on privacy

- A **Private** repo keeps the code visible only to you.
- A **Public** repo (needed for a free live link) makes the *code* visible to
  anyone with the link — but the code has no personal data in it. Your household
  numbers, goals, and PDFs never touch GitHub; they stay in your browser.
- If you'd rather not have any public link, keep the repo **Private** and just
  open the `index.html` file from your own computer by double-clicking it.

Questions on any step? Tell me which part number you're on and I'll walk you through it.
