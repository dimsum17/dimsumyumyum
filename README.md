# The Order Slip — setup guide

Everything here is free. No credit card, no personal info required beyond a
pseudonymous GitHub account.

## One-time setup (~15 minutes, laptop recommended for this part only)

1. **Create a GitHub account** at github.com using your pseudonym (e.g.
   `dimsum-orderslip`) and a fresh/throwaway email. Don't use your real name
   anywhere in the profile.

2. **Create a new repository**
   - Click the `+` in the top right → "New repository"
   - Name it something like `food-blog` (this becomes part of your URL)
   - Set it to **Public**
   - Do NOT initialize with a README (we already have one)

3. **Upload these files**
   - On the new repo page, click "uploading an existing file"
   - Drag in everything from this folder, **keeping the folder structure**
     (the `.github` folder must stay intact — it may be hidden in your file
     browser since it starts with a dot, so make sure "show hidden files" is
     on, or just drag the whole unzipped folder in)
   - Commit the files

4. **Turn on GitHub Pages**
   - Go to Settings → Pages (left sidebar)
   - Under "Build and deployment", set Source to **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)` → Save
   - After a minute or two, your site will be live at:
     `https://yourusername.github.io/food-blog/`

5. **Confirm Issues are enabled**
   - Settings → General → scroll to "Features" → make sure "Issues" is checked

That's it — the laptop part is done. You'll never need to touch code again.

## Adding a new visit (phone, day-to-day)

1. Open the **GitHub mobile app** (or github.com in your phone browser) and
   sign in with your pseudonymous account
2. Go to your repo → **Issues** tab → **New issue**
3. Pick the **"New Visit"** template — it's a fill-in form
4. Fill in date, restaurant, dishes, rating, location (long-press the spot
   in Google/Apple Maps to copy coordinates), and your notes
5. Paste/attach photos straight from your camera roll into the photos field
6. Submit

Within a minute, a robot (a GitHub Action already set up in this repo)
reads that form, adds it to your site's data file, and closes the issue.
Refresh your site link and the new entry — and its pin on the map — is
there.

## Notes

- Your site URL is the only thing you need to share: `https://yourusername.github.io/food-blog/`
- Nothing personal is exposed — just your pseudonym in the URL and whatever
  you choose to write
- If you ever want a nicer custom domain, that's an optional paid add-on
  later — not required
