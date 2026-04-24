# Nab Landing Page Handoff

This is the clean source document to use when building the separate Nab landing page repo.

## What To Carry Over From This Repo

These are the pieces worth reusing directly or nearly directly:

- **App name:** `Nab`
- **Core concept:** swipe-based restaurant reservation discovery
- **Short positioning:** browse available reservations one at a time instead of running a normal search loop
- **Support email:** `nabreservations@gmail.com`
- **Legal links:**
  - Privacy Policy: `https://nrtattrie.github.io/nab-legal/privacy.html`
  - Terms of Service: `https://nrtattrie.github.io/nab-legal/terms.html`
- **Brand assets:**
  - App icon: [assets/icon.png](/Users/nathantattrie/Developer/reservation_tinder/assets/icon.png)
  - Favicon: [assets/favicon.png](/Users/nathantattrie/Developer/reservation_tinder/assets/favicon.png)
  - Splash mark: [assets/splash-icon.png](/Users/nathantattrie/Developer/reservation_tinder/assets/splash-icon.png)
- **Possible screenshot sources:**
  - [screen_grabs/Screenshot 2026-03-02 at 5.11.41 PM.png](/Users/nathantattrie/Developer/reservation_tinder/screen_grabs/Screenshot%202026-03-02%20at%205.11.41%E2%80%AFPM.png)
  - [screen_grabs/Screenshot 2026-03-02 at 6.05.16 PM.png](/Users/nathantattrie/Developer/reservation_tinder/screen_grabs/Screenshot%202026-03-02%20at%206.05.16%E2%80%AFPM.png)

## What Not To Copy Raw

These docs are useful for understanding the product, but they are not landing-page copy:

- `docs/architecture.md` because it is implementation-facing
- `docs/phases.md` because it is planning-facing
- `docs/topics/api-strategy.md` because it includes internal technical/legal nuance that should not be public-site marketing copy

Use those docs as source material only. The website should stay simple, public-facing, and non-technical.

## Recommended Site Structure

For the first version, one page is enough:

1. Hero
2. Short “How it works”
3. Why Nab
4. Screenshot strip
5. FAQ
6. Support / feedback / legal links

If the App Store URL is not live yet, use a placeholder CTA like `Coming soon to the App Store` or `Join the beta`.

## Ready-To-Use Landing Page Copy

### Hero

**Headline**

Nab your next reservation.

**Subheadline**

Nab makes finding a table feel less like a search and more like discovery. Swipe through real restaurant options and jump into a live booking when something looks right.

**Primary CTA**

Download on the App Store

**CTA fallback if the app is not live yet**

Coming soon to the App Store

### Short Product Description

Nab is a restaurant reservation app built for people who would rather browse than filter. Instead of opening OpenTable and digging through lists, you swipe through restaurant options one at a time and jump into booking when one clicks.

It is designed for spontaneous nights out, last-minute plans, and the kind of dinner decisions that usually turn into too many tabs and too much overthinking.

### How It Works

**1. Set your plan**

Pick your date, time, party size, and neighborhood.

**2. Swipe through options**

Browse restaurants one at a time instead of sorting through a giant search results page.

**3. Book the one you want**

When a spot looks right, continue into the live reservation flow and lock it in.

### Why Nab

- Less filtering, more discovering
- Built for spontaneous dinner plans
- Mobile-first and fast to use
- A simpler way to stumble into a great reservation

## FAQ Copy

### What is Nab?

Nab is an iPhone app that helps you discover restaurant reservations with a swipe-based experience.

### Is Nab a reservation platform?

No. Nab helps you discover restaurants and move into the booking flow, but it does not own restaurant inventory itself.

### Where is Nab available?

Nab is currently built for iPhone.

### How do I get support?

Email `nabreservations@gmail.com`.

### Where can I read the privacy policy and terms?

Privacy Policy: `https://nrtattrie.github.io/nab-legal/privacy.html`

Terms of Service: `https://nrtattrie.github.io/nab-legal/terms.html`

## Feedback Section Copy

Have an idea, found a bug, or want to request a feature? Send feedback to `nabreservations@gmail.com`.

If you later choose a dedicated feedback board, replace this with that link and keep the email as a fallback.

## Footer Copy

Nab

Restaurant reservation discovery for iPhone.

Support: `nabreservations@gmail.com`

Privacy Policy

Terms of Service

## Suggested Metadata

**Title tag**

Nab | Restaurant Reservation Discovery

**Meta description**

Nab helps you discover restaurant reservations with a swipe-first iPhone experience. Browse, decide faster, and jump into a live booking flow.

## Practical Build Notes

- Start from the existing `nab-legal` GitHub Pages setup if possible
- Keep the first version static and cheap
- Reuse the current Nab icon and screenshots rather than inventing new marketing art
- Do not make claims that Nab guarantees a reservation or owns reservation inventory
- Keep the wording non-technical; the public site does not need internal OpenTable or WebView details

## My Recommendation

Do not copy and paste from the repo docs directly into the landing page.

Use this file as the starting copy instead. It is cleaner, safer, and already trimmed down to what a public-facing Nab site should say.
