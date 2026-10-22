# Abdallat Law Firm - single NFC card and desk stand

This package supersedes the prior PAPER card package. Quantity: ONE NFC card, ONE desk stand. No purchase or order has been placed.

## Approved source
Reference: APPROVED_REFERENCE.png supplied by the user in the previous chat. Front: name and Advocate only; no NFC icon, no front scales. Back: scales inside QR and the two approved telephone numbers. Arabic/English firm identity is retained on the contact page and stand. Typeface is a reconstruction using Baskerville Old Face, not the unidentified exact font in the image. Black/silver material texture requires a physical proof.

Approved contact data: Yazan M. Abdallat / Advocate; 0777313113 (+962777313113); 06-5818081 (+96265818081); yazanlaw@yahoo.com. No address invented. User supplied map: https://maps.app.goo.gl/7j4jRitHNt4NGCnWA .

## Permanent payload for BOTH NFC tags and ALL QR codes
https://ahmadabdallatt11.github.io/abdallat-digital-card/

Encode a single NFC Forum NDEF URI record, HTTPS URI prefix 0x04 followed by `ahmadabdallatt11.github.io/abdallat-digital-card/`. Do not store the .vcf itself on the chip. Do not use a paid dynamic-QR service or an intermediate shortener. Do not rename/delete the GitHub account, repository, or Pages path after manufacture.

Use NFC Forum Type 2 / genuine NTAG213 or equivalent, with a vendor-matched antenna. This short URI fits NTAG213. Use a proper NFC card inlay, not an ordinary paper card with an unprotected adhesive chip. Keep tags writable during proofing. After owner verification on both phones, optionally make read-only; permanent locking is irreversible and needs owner approval.

## NFC card
Finished size 85.6 x 54 mm (standard NFC card format), nominal 0.76 mm PVC/PET laminate; black core or fully opaque black skins; matte/satin protective finish compatible with the supplier's NFC lamination process. Vendor to confirm actual thickness, corner radius (target 3.18 mm), and antenna template before production. This replaces the previous inferred 85 x 45 mm paper-card size.

PDF MediaBox 91.6 x 60 mm, TrimBox 85.6 x 54 mm, 3 mm bleed each side. Critical art safe inset 4 mm. Border inset 4 mm. PDFs are upright front then back; no mirroring. SVGs have the same bleed extent. Use the vector PDF for production; don't print the photograph.

01_NFC_CARD_COMPOSITE.pdf is the two-sided vector composite. 02_NFC_CARD_SILVER_PLATE.pdf is a positive black separation for the silver-look ink, NOT an instruction to apply metallic foil. Spot name SILVER_NONCONDUCTIVE_INK in the composite. All English type is outlined. Use opaque, NONCONDUCTIVE cool-gray/silver-look ink; on black PVC it may require a vendor-created white underbase registered beneath the visible marks. Avoid exposed white halos. QR uses opaque nonmetallic white; background uses CMYK 60/40/40/100 as a starting value only. Vendor must profile for the actual process and total ink limit.

Card provisional antenna center x=42.8,y=27 mm measured from top-left. Manufacturing drawing's 36 mm disk is a provisional keep-out, not the final inlay CAD. Actual antenna vendor may require a much larger area. All silver-look marks in this version must therefore be nonconductive. No metallized film, real silver foil or metal substrate across the antenna. If real satin silver foil is desired outside the antenna area, vendor must supply the actual antenna map and demonstrate read performance before any change. No visible NFC icon.

## Desk stand
Finished face 100 x 150 mm portrait. Material: opaque black cast acrylic 3 mm, polished edges, slightly eased corners. Front surface UV printing, silver-look nonconductive ink and opaque white QR; do not reverse-print through opaque black acrylic. PDF MediaBox 106 x 156 mm; TrimBox 100 x 150 mm; bleed 3 mm; safe inset 5 mm. It is a face artwork, not a laser-cut toolpath.

Suggested base: black acrylic 100 x 60 x 8 mm, polished; slot centered across width, 90 mm long, nominal 3.2 mm wide, 4 mm deep, approximately 10 degrees rearward tilt. Fabricator must measure actual sheet thickness and make a slot test coupon before cutting the final base. Slot dimensions are provisional fabrication guidance, not a guaranteed interference fit. Avoid metal fasteners and magnets. Use a compatible acrylic adhesive if needed; do not drill through an NFC antenna.

Stand tag: nominal 25-30 mm antenna, mounted at rear center x=50,y=101 mm (behind QR). Antenna faces front through 3 mm acrylic; protect rear with a thin black nonmetallic cover. For use near a metal base/backing or on-metal variant, use a vendor-rated ferrite-backed on-metal tag. Stack from viewer: acrylic, antenna, ferrite, metal. Ferrite belongs between antenna and metal, never between phone and antenna. A metal card requires a purpose-designed on-metal/window antenna; attaching a standard tag to metal is not acceptable. Test read range through the final assembled stand; don't promise a distance from chip specification alone.

## QR
The primary QR preserves the reference: opaque WHITE modules on BLACK, with scales in the center. It is NOT silver foil. Card total square 32 mm; stand 44 mm. Version 6, error correction H; 41 x 41 modules plus four quiet-zone modules on every edge = 49 units total. Quiet zone is solid black for this inverted treatment. Do not crop, round modules, add a frame, stretch or add artwork inside this zone. Module pitch: 0.653 mm card, 0.898 mm stand. No spot UV, metallic ink, gloss or reflective foil over QR. Inverted QR needs actual camera proof; digital decoding with inversion is not proof every camera accepts it. If a phone fails, switch to the included standard black-on-white backup after client review.

## Printer handoff and release
Vector PDFs include trim/bleed boxes; no crop marks are printed on the finished face. Arabic is an embedded subset in the stand PDF; SVG Arabic remains editable text and must be outlined before using that SVG for manufacture. PDF is the primary production master. Files are not certified PDF/X and have no printer-specific ICC OutputIntent. The printer must convert to its accepted PDF/X profile, preserve separations and trim/bleed, and produce a physical proof. Do not claim certified PDF/X from this package.

The stand uses a silver spot channel plus ordinary white QR. Vendor makes the separate white-underbase pass from the composite according to its machine. The card silver mask intentionally renders black as a positive plate.

Release checklist: verify spellings and both printed phone numbers; measure trim; scan both QR codes with normal Camera on iPhone and Android in office lighting; tap each assembled item on both phones; confirm exact HTTPS URL; tap each tel/mail/maps control; import .vcf and verify both phone numbers and email; remove test contact. Do not approve mass production from an on-screen image alone.

## Sources and costs
QR margin: https://www.qrcode.com/en/howto/code.html/index.html
Metal/ferrite guidance: https://www.nxp.com/docs/en/application-note/AN13219.pdf and https://www.st.com/content/st_com/en/support/learning/essentials-and-insights/connectivity/nfc/nfc-touchpoints.html
Chip: https://www.nxp.com/products/NTAG213_215_216

No purchases or paid services initiated. Existing GitHub Pages URL is reused; no domain or QR subscription purchased. Physical cost is unquoted and requires the local fabricator's price for 1 NFC card, 1 acrylic face/base, 1 on-metal-capable tag, printing, and a sample. Do not treat this as a supplier quote.

