# MobiWholesale

The spare-parts trade network — an installable web app (PWA) for mobile spare-parts wholesalers and retailers.

**Two apps in one:**
- **Wholesaler** — billing, inventory, credit limits, trust scores, KYC, returns, reports (cash / online / credit breakdowns).
- **Retailer** — supplier dues & payments, live supplier stock, own inventory, and a same-city retailer-to-retailer marketplace.

Works offline. Installs to the home screen and opens fullscreen like a native app.

---

## Files
| File | Purpose |
|------|---------|
| `index.html` | The whole app (UI + logic) |
| `manifest.json` | App name, icon, colors, fullscreen settings |
| `sw.js` | Service worker — enables offline use & install |
| `icon.svg` | App icon |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

---

## How to publish it on GitHub (free hosting + installable)

### 1. Create a GitHub account
Go to https://github.com and sign up (free).

### 2. Create a new repository
- Click the **+** (top-right) → **New repository**.
- Repository name: `mobiwholesale` (any name is fine).
- Set it to **Public**.
- Click **Create repository**.

### 3. Upload these files
- On the new repo page, click **uploading an existing file** (or **Add file → Upload files**).
- Drag in **all** of these: `index.html`, `manifest.json`, `sw.js`, `icon.svg`, `.nojekyll`.
- Click **Commit changes**.

> Note: `.nojekyll` starts with a dot. If your phone/computer hides it, that's okay — the app still works without it, it just helps.

### 4. Turn on GitHub Pages
- In the repo, go to **Settings** (top menu).
- Left sidebar → **Pages**.
- Under **Source**, choose **Deploy from a branch**.
- Branch: **main**, folder: **/ (root)** → click **Save**.
- Wait ~1 minute. The page will show a link like:
  `https://YOUR-USERNAME.github.io/mobiwholesale/`

### 5. Open & install on your phone
- Open that link in **Chrome** (Android) or **Safari** (iPhone).
- **Android:** menu (⋮) → **Install app** / **Add to Home screen**.
- **iPhone:** Share button (↑) → **Add to Home Screen**.
- A MobiWholesale icon appears on your home screen. Tap it — it opens fullscreen, no browser bar.

That's it. Anyone you send the link to can install it the same way.

---

## Demo login
This is a demo — at the OTP screen, enter **any 4 digits** to continue.

## Updating the app later
Edit the files in your repo (or re-upload), commit, and GitHub Pages updates automatically in about a minute.
