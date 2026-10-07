# Noah's Air Conditioning and Heating

Single-page sample site for an HVAC contractor in Lancaster, California
(Antelope Valley). Built as a free sample for a warm SMS lead.

## Business details

| | |
|---|---|
| Business | Noah's Air Conditioning and Heating |
| Owner | Filmon Findlay (per BBB) — **not named on the site**, see below |
| Phone shown | **(661) 436-8945** — the local Antelope Valley number from his Google listing |
| Other number | (571) 354-1503 — the Virginia-area number CSLB has on file |
| Location shown | Lancaster, CA |
| Google listing | https://maps.google.com/?cid=4733530750011959100 |
| LLC | Noah's Air Conditioning & Heating LLC (CA #202463319691) |

## ⚠️ The licence is currently SUSPENDED — read this first

Checked against the CSLB database on **2026-10-07** (data current as of
10/7/2026 11:40 AM), licence **#1124510**:

- Issued 07/31/2024, expires 07/31/2028, classification **C-20**
- Bond: **$25,000** with Jet Insurance Company (#JT009062), effective 07/02/2024
- Workers' comp: Employers Compensation Insurance Company, policy #EIG606617900,
  **effective 08/11/2025 — expired 08/11/2026**
- **License Status: "License is under suspension for failure to comply with
  Workers Comp."**

The brief described this as "WC Susp Pending". It is no longer pending — the
suspension has taken effect.

**This is why the site contains no licence, bond or insurance claims at all.**
A suspended California contractor cannot legally contract for work over $500,
and under B&P 7031 cannot collect payment for work performed while suspended.
Advertising "licensed, bonded and insured" today would be false, trivially
checkable at cslb.ca.gov, and would expose him rather than help him.

Every other HVAC site in this collection leans on a licensing section as its
main trust block. This one deliberately does not. A grep for
`licen|bonded|insured|CSLB` over `index.html` returns nothing, by design.

**It is retroactively fixable.** CSLB states the suspension lifts retroactively
to the coverage date once a certificate or exemption statement is processed. He
renews with Employers Comp (or files an exemption if he no longer has
employees), and the licence returns to active.

**When it clears, add a licensing section** — C-20 #1124510, $25,000 Jet
Insurance bond, workers' comp carried. That is a 10-minute edit and it is the
single biggest upgrade available to this page.

He was told about the suspension by SMS on 2026-10-07, framed as a heads-up
rather than a problem with the sample.

## The review — real, and used carefully

His Google listing shows **5.0 stars from exactly one review**. The brief said
"5.0 stars"; the count matters, so the site states it plainly.

> "Mr Filman is totally professional, fast, reliable, friendly, honest, and a
> man of his word. He do his utmost to save you money."
> — **Todd Rodger**, 2 years ago

Genuine: Todd Rodger is an established Google account (13 reviews, 3 photos) and
Filmon replied to it at the time. It is quoted verbatim apart from trimming
"Mr Filman is" to start the sentence, attributed by name, and followed by a line
saying it is the only review so far with an invitation to leave more. Nothing is
inflated into "5-star rated contractor".

## Phone number and address decisions

- **(661) 436-8945 is shown.** For an Antelope Valley contractor, a local 661
  number is far better than the 571 Virginia area code. Confirm with him.
- **"Lancaster, CA" only.** Three addresses exist across his records:
  8844 Avoca Ct (CSLB/BBB — his home), 2355 Westwood Blvd #969 Los Angeles
  (a mailbox, and what Google Maps currently shows), and 4083 W Ave L #147.
  None belongs on the site: one is his home, one is a mailbox 70 miles away that
  makes a Lancaster business look like an LA operation. City only, as with every
  other site here.
- **The owner is not named.** "Filmon Findlay" comes from BBB, and phone lookups
  show "Filmon T" — the two do not agree, and he has not published a name
  himself. The site says "you get the owner" without naming him.

## What was deliberately not built

- No licence/bond/insurance section (see above).
- No years-in-business claim — the licence dates to July 2024 and the LLC to 2024.
- No "24/7" or response-time promises — nothing supports them.
- No fabricated testimonials to pad the single real review.
- No service-hours claim beyond "open until 5pm" from the Google listing.

## Images

`img/` — four stock photos (Unsplash). He has **no** photos anywhere: the Google
listing has none, there is no website, and no Facebook, Instagram or Yelp
presence. Stock use is disclosed in a caption under the gallery and in the footer.

Job photos are the second-biggest improvement available after the licence fix;
he was asked for them in the same SMS.

## Design

Deliberately distinct from the other HVAC sites here (GSW, Marcus Air, Brilliance):

- Desert palette — sand `#FAF6EF`, dusk blue `#1F3A4D`, sun orange `#D9742B`,
  chosen for the Antelope Valley rather than borrowed from another site.
- Barlow Condensed (display, uppercase) + Barlow (body) — a different type voice
  from the Outfit/Source Sans used on Brilliance.
- Inline SVG sun/dial logo mark — he has no logo of his own.
- Eight sections: hero, stats strip, services, review, service areas, why us,
  work gallery, contact.
- Full dark mode (system preference plus explicit `data-theme`), sticky header,
  `scroll-margin-top` anchors, reduced-motion respected, inline CSS, no build step.

## Open questions for the client

1. **Clear the workers' comp suspension** — everything else is secondary.
2. **Which number** to show — 661 or 571.
3. **Job photos** — even phone pictures of installs.
4. **Service area** — confirm the eight communities listed are right.
5. **Hours** — the listing says "closes 5 PM"; confirm actual hours.
6. **Add the website to his Google listing** once live. The listing currently
   says "Add website", so the single review and the 5.0 rating have nowhere to
   send anyone. That is the whole pitch.
