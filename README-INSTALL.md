# Intuitex AI Solutions — Production GitHub Pages Site

Target GitHub account / organization:
`intuitexaisolutions`

Target repository:
`intuitexaisolutions.github.io`

Expected public website:
`https://intuitexaisolutions.github.io/`

## Upload

This ZIP is designed for the ROOT of an empty `intuitexaisolutions.github.io` repository.

Upload every file and folder from the ZIP root directly into the repository.

Do NOT upload it as:
`intuitexaisolutions.github.io/intuitex-ai-solutions-production-site/...`

## Enable GitHub Pages

Repository → Settings → Pages

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`
- Save
- Keep HTTPS enabled

## Final production URLs

Publisher:
`https://intuitexaisolutions.github.io/`

Apps:
`https://intuitexaisolutions.github.io/apps/`

AI Essay Writer & Chat:
`https://intuitexaisolutions.github.io/apps/ai-essay-writer/`

Privacy Policy:
`https://intuitexaisolutions.github.io/apps/ai-essay-writer/privacy/`

Terms & Conditions:
`https://intuitexaisolutions.github.io/apps/ai-essay-writer/terms/`

Support:
`https://intuitexaisolutions.github.io/apps/ai-essay-writer/support/`

Publisher Privacy:
`https://intuitexaisolutions.github.io/privacy/`

Publisher Terms:
`https://intuitexaisolutions.github.io/terms/`

Publisher Support:
`https://intuitexaisolutions.github.io/support/`

AdMob app-ads.txt:
`https://intuitexaisolutions.github.io/app-ads.txt`

## Google Play listing

Package:
`com.intuitex.ai.writer`

App:
`https://play.google.com/store/apps/details?id=com.intuitex.ai.writer`

Developer profile:
`https://play.google.com/store/apps/developer?id=Intuitex+AI+Soultions`

Current Google Play support email:
`intuitexaisolutions@gmail.com`

Legal developer:
`INTUITEX AI SOLUTIONS (SMC-PRIVATE) LIMITED`

Address:
`Office S-142, Malikabad Plaza, Near 6th Road Flyover, Rawalpindi 46300, Pakistan`

Phone:
`+92 349 8940985`

## app-ads.txt

Included at repository root:

`google.com, pub-2683875379511234, DIRECT, f08c47fec0942fa0`

IMPORTANT:
This uses the same AdMob publisher line you have been using on the other publisher sites.
Before using it for Intuitex, confirm that `pub-2683875379511234` is the AdMob publisher account actually monetizing `com.intuitex.ai.writer`.
If Intuitex uses a different AdMob account, replace ONLY the publisher line in `app-ads.txt` with the exact line shown by that AdMob account.

## Google Play Console migration

After the site is deployed and tested:

Developer website:
`https://intuitexaisolutions.github.io/`

Privacy Policy:
`https://intuitexaisolutions.github.io/apps/ai-essay-writer/privacy/`

Use app support page where a website support destination is appropriate:
`https://intuitexaisolutions.github.io/apps/ai-essay-writer/support/`

Keep the old Blogger privacy page available until Google Play is updated and the new URL is confirmed live.

Old privacy page:
`https://intuitexprivacypolicy.blogspot.com/2026/08/ai-essay-writer.html`

## Search Console

After GitHub Pages is live:

1. Add URL-prefix property:
   `https://intuitexaisolutions.github.io/`
2. Choose HTML file verification.
3. Upload the exact Google verification `.html` file to repository root.
4. Wait for Pages deployment.
5. Open the exact verification URL.
6. Click Verify in Search Console.
7. Leave the verification file in the repository.

## CRITICAL Play Data Safety audit

The current Google Play listing says:
- No data shared with third parties
- No data collected

The current privacy policy states:
- prompts / chat messages are sent to OpenAI;
- AdMob may process advertising identifiers;
- essay/chat history is stored locally;
- Google UMP is used for advertising consent;
- Firebase Remote Config is used.

Before the next Play update, review the Data Safety declaration against the actual release AAB and current Google Play definitions.

Audit:
- OpenAI/API request path and retention behavior;
- AdMob SDK;
- Google UMP;
- Firebase modules actually bundled;
- local Essay History / chat history;
- any Analytics / Crashlytics not mentioned in the old policy;
- support flow;
- encryption in transit;
- deletion controls.

Do not keep a “No data collected / No data shared” declaration unless it is actually correct under Google Play’s current Data Safety definitions.

## Website tracking

The publisher website itself:
- does not install Google Analytics;
- does not install Google Ads/AdSense;
- does not place web advertising;
- does not intentionally set first-party tracking cookies.

Google Play outbound links preserve:
- utm_source
- utm_medium
- utm_campaign
- utm_term
- utm_content
- gclid
- gbraid
- wbraid

A local `dataLayer` event is emitted on Google Play clicks:
`google_play_outbound_click`

No GA/Google Ads tag is installed until you intentionally provide a measurement/conversion ID.

## Production characteristics

- Fully responsive desktop / tablet / mobile.
- Premium Intuitex blue/cyan/indigo visual system.
- Local copies of current Google Play app icon and screenshots.
- Publisher homepage + app landing page.
- App-specific Privacy, Terms and Support.
- General publisher Privacy, Terms and Support hubs.
- App-specific AI and academic-integrity disclaimers.
- SEO metadata, canonical URLs and JSON-LD.
- robots.txt.
- sitemap.xml.
- site.webmanifest.
- custom 404.
- app-ads.txt.
- reduced-motion accessibility.
- no web ads on legal/support pages.
