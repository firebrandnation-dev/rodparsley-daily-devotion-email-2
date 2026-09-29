# Rod Parsley Daily Devotion Email Version 2

This repository contains the light, editorial version of the September 29 Daily Devotion email.

The design follows the supplied revision brief:

- clean white and warm cream backgrounds
- deep burgundy for headings, buttons, and small accents
- gold used sparingly
- Calibri throughout the email
- the supplied original Rod Parsley Podcast artwork
- the approved devotional and latest-episode content from version 1
- Apple Podcasts, Spotify, YouTube, Facebook, and X links with image icons
- World Harvest Church calls to action linked to `https://whc.life/`

Files:

- `index.html` - responsive, table-based HTML email with inline core styling and public HTTPS image URLs
- `plain-text.txt` - matching text-only fallback
- `campaign-notes.txt` - subject, preheader, links, and send notes
- `assets/` - devotion hero, original podcast artwork, episode thumbnail, and icons

The core layout is inline-styled and table-based for Gmail, Outlook, Apple Mail, and common campaign tools. Rounded corners degrade to square corners in older Outlook versions without breaking alignment or content. Images use public HTTPS URLs from this repository, so the rendered template can be copied into an email editor without rewriting asset paths.
