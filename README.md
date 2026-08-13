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

## Status

Awaiting client review and approval before any public launch or listing.
