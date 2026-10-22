# Abdallat Law Firm digital card

Static, mobile-first Arabic/English business card for Yazan M. Abdallat, Advocate. No JavaScript, tracking, external font requests, NFC icon, or agency branding on the client page.

## Content sources

- Name, title, firm typography, mobile `0777313113`, office `06-5818081`, and `yazanlaw@yahoo.com`: user-supplied black/platinum card reference, matching the starter archive.
- International dialing format: Jordan `+962`, replacing the local leading zero.
- Maps: user-supplied https://maps.app.goo.gl/7j4jRitHNt4NGCnWA. Opened and verified on 2026-10-22: listing “Adv Yazan Moh. alabdallat”, phone `07 7731 3113`, Amman. No street address or opening hours copied into the card or vCard.

## Hosting

GitHub Pages: deploy `main` from `/ (root)`, with HTTPS enforced. All asset paths are relative so the project URL works. `.nojekyll` enables direct static serving. No build step or dependencies.

## Contacts

`contact.vcf` uses vCard 3.0, UTF-8 without BOM, CRLF line endings, structured name, full name, organization, title, two international phone numbers, and email. The download link uses a `.vcf` filename. Import UI varies by iPhone/Android browser and installed contacts app. Browser download/format checks do not substitute for testing import on physical devices.

## Maintenance

Update visible contact details and `contact.vcf` together. Keep this repository separate from TEVORLI's website. Generate printable QR assets only after the public HTTPS URL has been verified. The mockup's decorative QR is not reused.
