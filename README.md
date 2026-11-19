# Kandhavi Aari Designs – gallery website

Live site: https://rajarajan133.github.io/kandhavi-aari/

## Files
- `index.html` – the gallery page (no need to edit)
- `photos.json` – shop details and the list of designs (edit this)
- `photos/` – put your aari work photos here
- `logo.jpg`, `favicon.jpg` – logo and browser icon

## Add a new design
1. Upload the photo into the `photos/` folder (e.g. `peacock-bridal-blouse.jpg`).
   Use short file names with no spaces. Keep photos under about 1 MB.
2. Open `photos.json`, and add one entry inside `"photos": [ ... ]`:

```json
{ "file": "peacock-bridal-blouse.jpg", "name": "Peacock bridal blouse", "type": "Bridal blouse", "date": "2026-11-19", "note": "Zardosi and pearl work" }
```

- `type` must match one of the names in `"categories"`
- `date` is YYYY-MM-DD; the newest date shows first and gets a "New" tag for 3 weeks
- `note` is optional
- Put a comma between entries, but not after the last one

3. Commit. The site updates in 1–2 minutes.

## Shop details
In `photos.json` → `"shop"`:
- `whatsapp`: number with country code, digits only, e.g. `919876543210`
- `phone`, `instagram` (username only), `location`, `tagline`, `about`

Leave any field as `""` to hide it.
