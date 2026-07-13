# The Art of Recovery — Brand & Build Guide
Use this so the website and the companion app stay perfectly consistent.

## Colors (from Issue One)
- Deep navy (signature page): #0A1535
- Background black-navy: #05080f / #070d18
- Gold: #c9a14a · Light gold: #ecd591 · Deep gold: #9c7a2e
- Cream (text): #f3eee2 · Muted text: rgba(243,238,226,.55)
- Gold gradient: linear-gradient(135deg,#f0dd9b 0%,#c9a14a 38%,#8f6c25 72%,#e7cd84 100%)

## Typography (Google Fonts, same as Issue One)
- Display / headlines: Playfair Display
- Small caps / labels / nav: Cinzel (wide letter-spacing, uppercase)
- Body: Cormorant Garamond
- Script accent ("something you feel.", "Be the Artist."): Great Vibes

## Voice
Tagline: "Something you don't just read, *something you feel.*"
Sign-off: "Be the Artist."

## Structure
index.html (Cover) · current-issue.html · archive.html · contributors.html ·
about.html · press.html · submit.html (Submit + Contact) · subscribe.html ·
issue-01.html (the complete Premiere Issue, untouched) · assets/ · styles.css

## Contacts
- Admins / co-founders: mike@theartofrecoverymag.com, grace@theartofrecoverymag.com
- Submissions: Submissions@theartofrecoverymag.com
- Media kit: https://recovery-ad-deck.emergent.host
- Socials: Instagram @artofrecoverymagazine · Facebook "The Art of Recovery" · YouTube @theartofrecoverymagazine

## Before launch (important)
1. SUBSCRIBE PAGE: DONE — wired to Stripe Payment Link
   https://buy.stripe.com/9B67sLd7Ac8q5NXcA36Zy00
   After the domain is live, set the payment link's confirmation page in
   Stripe to redirect to https://theartofrecoverymag.com/welcome.html
   Periodically shorten the trial days in Stripe so new signups' first
   charge stays near 12/01/2026.
2. SUBMIT PAGE: currently opens the reader's email app pre-addressed to
   Submissions@theartofrecoverymag.com. Can be upgraded to a hosted form
   (Formspree/Basin/own backend) that emails the editor directly and
   accepts file uploads.
3. Facebook URL confirmed: https://www.facebook.com/artofrecoverymag/
4. About page: replace the three "Bio coming soon." placeholders when ready.

## The app
Build the app (React Native / Expo recommended) from these same tokens:
same 8 sections as the nav, same colors, fonts, logo, and one shared
subscriber database with the website (same Stripe customer = access on both).
