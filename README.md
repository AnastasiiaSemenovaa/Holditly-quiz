# Holditly quiz funnel

Quiz funnel with a personalized result, email capture and a paywall (pre-launch "fake door": no real payments are taken).

- `index.html` is the whole funnel (HTML + CSS + JS in one file).
- Edit settings in the `CONFIG` block at the top of the script: Meta Pixel ID, GA4 ID, prices, support email.
- Email and checkout-intent submissions are collected by Netlify Forms (enable form detection in Netlify).
- Add `?debug=1` to the URL to log tracked events in the browser console. `?v=a` / `?v=b` forces an A/B variant.
