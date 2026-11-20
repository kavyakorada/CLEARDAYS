# ClearDays — natural food plan for fewer migraine days

Quiz funnel website: quiz → personal 28-day food plan → Razorpay payment → member area.

## Put it live on GitHub Pages
1. Sign in at github.com → **New repository** → name it `cleardays` → **Public** → Create.
2. Click **uploading an existing file**, drag in ALL the files from this folder (including `.nojekyll`), then **Commit changes**.
3. Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main**, folder **/ (root)** → Save.
4. Wait 1–2 minutes. Your site is live at `https://<your-username>.github.io/cleardays/`.

## Before going live
- Fill every yellow [PLACEHOLDER] in about, contact, terms, privacy, refund and shipping pages.
- Paste your Razorpay Payment Page links into `index.html` (search for "STEP 1").
- Razorpay redirect after payment: `https://<your-username>.github.io/cleardays/#thank-you`
- Optional: paste your Meta Pixel code where `index.html` says "STEP 4".

## Your own domain (optional)
Settings → Pages → Custom domain → enter e.g. `cleardays.in`, then add the DNS records GitHub shows at your domain provider. Tick **Enforce HTTPS**.
