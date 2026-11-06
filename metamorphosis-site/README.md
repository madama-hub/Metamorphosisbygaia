# Metamorphosis by Gaia

A responsive, buildless editorial website for Gaia's love and relationships brand. Edit the files in `dist/` directly; no dependencies or build step are required.

## Local preview

Run `python3 -m http.server 4173 --directory dist --bind 127.0.0.1` from this folder, then open http://127.0.0.1:4173.

## Content and behavior

- Primary action: open Gaia's existing free-guide destination.
- Secondary actions: her existing newsletter and Spotify podcast.
- Real Instagram reel previews link to their corresponding posts.
- Accessible mobile navigation, keyboard focus styles, skip link, native FAQ disclosures, and reduced-motion support.
- No forms, analytics, payments, fabricated services, or client testimonials.

## Verified sources

Profile reviewed November 6, 2026: https://www.instagram.com/metamorphosisbygaia/

The profile identifies Gaia's focus as love, relationships, mixed signals and situationships, and lists:

- Your Metamorphosis Podcast: https://open.spotify.com/show/0DXfoGt6TypJ0vLody10QE
- Cheat Codes to Love newsletter: https://tinyurl.com/CHEATCODES-TO-LOVE
- Unf*ck Your Love Life free PDF: https://tinyurl.com/metamorphosisbygaia

These destinations were transcribed from the profile. The shortened links' destination pages were not inspected because browser approval review reported a usage limit; confirm them before a public launch. The website uses the existing published links, rather than claiming to deliver or collect anything itself.

The three reel thumbnails are copied from the public profile and stored locally. The user supplied two 1086 × 724 portraits: `dist/assets/gaia-beach.jpg` appears in the opening section and `dist/assets/gaia-city.jpg` accompanies the about section. Both files are unchanged copies; responsive crops are applied only through CSS. The original files remain untouched.

Brand copy, butterfly mark, guide presentation, envelope, record, and podcast typography are original proposed creative direction. The typographic resource illustrations are decorative, not reproductions of the actual PDF or podcast cover. No episode titles or guide contents have been invented.

The previous AI-generated still life is retained as `dist/assets/hero.jpg` but is no longer displayed. See `ART-DIRECTION.md` for its prompt and provenance. The current hero uses the user-supplied beach portrait.

## Hosting

The exact Sites project ID is persisted in `.openai/hosting.json`. Keep it when updating this site. Deployment is owner-private by default; changing the audience requires an explicit request.
