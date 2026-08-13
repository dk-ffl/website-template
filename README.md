# TapNorth Website — Build Log

The TapNorth marketing site was built and is hosted on Higgsfield's website
platform (per the client's request to use the Higgsfield connector), not in
this repository. This repo tracks the build request and its status.

## Live preview

**https://tapnorth-nfc.higgsfield.app**

Draft only — not listed on Higgsfield's public community feed, and not yet
approved by the client for launch.

## What was built (V1)

- Dark/black + blue premium theme, mobile-first, animated scroll-driven hero
  ("signal → circuit → ring" abstract film — never a fabricated product
  render).
- Real, unaltered client assets throughout: TapNorth logo, the all-in-one NFC
  keychain (hero), and product photos for the Google Review, Social Media,
  and Wi-Fi NFC stands. No AI-generated stand-ins for the products or logo.
- Sections: Hero, How It Works, Products, Pricing (extensible list), Why
  TapNorth, Businesses We Serve, FAQ, and a real Contact/Order form (persisted
  to a database, no payment processing).
- No invented phone numbers, emails, social handles, testimonials, or
  addresses — placeholders used where information wasn't supplied.
- SEO: per-route meta, canonical tags, Organization/WebSite/FAQPage JSON-LD.

## V2 update

Targeted edit pass, same design/animations/layout — no redesign:

- Hero featured visual swapped from the keychain photo to a second real
  TapNorth logo (brand-first opening impression); headline unchanged ("One
  Tap. Better Business."); scroll-scrub film and blue/black aesthetic
  untouched.
- Pricing rewritten: **NFC Stand — $50 CAD each**, **NFC Keychain — $10 CAD
  each**, "Bulk and business orders — Contact for pricing" kept. Old $40/$60
  tiers removed.
- Products section expanded from 3 to 7 real products, all using client
  photos: Google Review, Social Media, Wi-Fi, Menu, Appointment Booking, and
  Airbnb/Guest Stay stands ($50 CAD each), plus the All-in-One Keychain ($10
  CAD, positioned as the lower-priced add-on, not the featured product). Grid
  updated to fit the larger catalog; card component and CTA pattern reused
  for visual consistency.
- Descriptions for the two brand-new products (Menu, Appointment) and the
  Airbnb/Guest Stay card were written in-house (short, factual, no invented
  claims) since no client copy was supplied for those — worth a client
  read-through.
- Navigation unchanged; `Products` link verified to still route to the
  expanded catalog.

## V3 refinement

Brand positioning, copy accuracy, and product-data pass — no redesign:

- Hero now leads with a "Premium NFC Solutions" eyebrow above the existing
  headline, subhead expanded to mention menus and bookings; logo remains the
  main hero visual.
- All QR-code language removed sitewide (copy, FAQ, meta/JSON-LD) — TapNorth
  is presented as NFC-only for now.
- Product descriptions tightened to final client wording across all 7 items;
  pricing ($50 CAD/stand, $10 CAD/keychain, contact for bulk) made consistent
  everywhere it appears.
- Added material + dimensions to every product card: acrylic stands (130mm W
  x 180mm H, 50mm base, kept as distinct figures, never summed), epoxy
  keychain (40mm x 40mm).
- How It Works, Why TapNorth, FAQ (expanded to 9 Q&As), and the Pricing
  section rewritten to match the brief; contact form's product dropdown
  confirmed to list all 7 products.
- Found and fixed a real bug: the hero animation and the contact form
  briefly shared the same section anchor, so "Order This Stand" / "Contact
  for pricing" buttons were landing mid-hero instead of the form. Every CTA
  now verified to reach the actual form.
- Mobile and desktop layouts reviewed section-by-section; no functional
  horizontal-scroll issue found (a decorative background glow extends past
  the viewport edge but doesn't affect scrolling).

## V4 cleanup

Product-lineup and layout cleanup pass — no redesign:

- Removed the standalone Pricing section and its nav/footer links (prices
  still shown on each product card); adjacent sections rebalanced so there's
  no gap left behind.
- Businesses We Serve: removed the Airbnb/Guest-Stay product image, left that
  side empty per instruction, and rebalanced the section to a full-width
  layout so it still reads as intentional.
- Products reordered with the All-in-One NFC Keychain first, then the Google
  Review NFC Stand, followed by the five remaining stands (Social, Wi-Fi,
  Menu, Appointment, Airbnb/Guest Stay).
- Only the Keychain and Google Review Stand are marked available (real price,
  active order CTA, stronger visual emphasis). The other five stands now
  carry a premium "Coming Soon" badge, no purchasable price shown, and a
  disabled CTA — photos and descriptions kept so visitors can still see
  what's coming.
- Order form's product dropdown trimmed to the two available products (plus
  the existing "Other" catch-all) — coming-soon products can't be submitted.

## V5 fix

Small follow-up to V4's Coming Soon cards, which repeated "Coming Soon"
three times (badge, price slot, button):

- Each Coming Soon stand card now shows exactly one "COMING SOON" badge at
  the top, its real "$50 CAD" price restored (styled the same as the
  available Google Review Stand's price), and no bottom button at all.
- The two available products (Keychain, Google Review Stand) were untouched.

## V6 fix

Hero cleanup, nothing else touched:

- Removed the large TapNorth logo card that sat between the hero's
  supporting paragraph and the "Shop TapNorth" / "See How It Works" CTAs —
  no replacement image added, that space is now empty.
- CTAs moved up to sit directly under the paragraph.
- Header logo, eyebrow, headline, and the animated hero background were not
  touched.

## Status

Awaiting client review and approval before any public launch or listing.
