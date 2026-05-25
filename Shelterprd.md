# Mockup PRD — FurAndFound Animal Shelter Website
**Version:** 2.0  
**Date:** May 2026  
**Author:** FurAndFound Team  
**Status:** In Progress

---

## Table of Contents
1. Project Overview
2. Target Audience
3. Problem Being Solved
4. User Stories
5. Pages & Sections (with Examples)
6. Design Guidelines
7. Colour & Font Specifications
8. Navigation Structure
9. Button & Link Behaviour
10. External Links Used
11. Accessibility Requirements
12. Mobile & Responsive Design
13. Goals & Success Metrics
14. MVP Ready Check for Lesson 7
15. Testing Checklist
16. Future Features
17. Glossary

---

## 1. Project Overview

**Project Name:** FurAndFound  
*(Other names considered: FureverFriends, PawsUnited, PawsAndClaws)*

**One-Line Description:**  
FurAndFound is a free, public-facing website that connects shelter animals with people who want to adopt, volunteer, donate, or spread awareness — designed to be accessible for kids, adults, and seniors alike.

**Why this project exists:**  
Millions of dogs and cats sit in shelters every year without enough attention or care. Most people don't know how easy it is to help. FurAndFound makes it simple and welcoming for anyone — from a 7-year-old who loves animals to a grandparent looking for a companion — to take action.

**What makes FurAndFound different:**
- It is not a shelter itself — it is a bridge between people and real shelters
- All adopt buttons link to real Petfinder breed searches so they never break
- The lost pet poster maker lets the community help each other
- The share button works without any account or app — just one tap or click
- The design is large, warm, and readable for all ages

---

## 2. Target Audience

| User Type | Age Range | What They Need |
|-----------|-----------|----------------|
| Kids | 6–12 | Fun, visual, easy to understand — sparks empathy |
| Teens | 13–17 | Shareable content, ways to get involved without needing money |
| Adults | 18–64 | Clear info on how to adopt, volunteer, or donate |
| Seniors | 65+ | Large text, simple navigation, calming design |

**Example users:**

- *Mia, age 9* — saw a stray cat and wants to help. She visits the site with her mom and learns what shelters do. She clicks "Browse Breeds" and finds the Tabby card. She asks her mom if they can adopt one.

- *James, age 34* — thinking about adopting a dog for his apartment. He uses "Browse Breeds" to find a Labrador and clicks through to Petfinder. He fills out an adoption application the same day.

- *Margaret, age 71* — wants a quiet cat companion after retirement. She reads the Pet Care page and uses the "How It Works" steps to understand the process before visiting her local shelter.

- *Tyler, age 16* — lost his dog Biscuit in the park. He goes to the Lost Pet page, fills out the form, uploads a photo, and posts it to the community board. His neighbour sees the poster and calls him.

- *Priya, age 42* — doesn't want a pet but loves animals. She clicks the "Share This Site" button and sends the link to three friends. One of them ends up adopting a Beagle.

---

## 3. Problem Being Solved

**The Problem:**  
Dogs and cats in shelters are not receiving enough love, care, or visibility. Many people want to help but don't know where to start or feel overwhelmed by the process.

**Root causes:**
- Shelter websites are often hard to navigate or outdated
- People don't know about breed-based searching on Petfinder
- Lost pet posters are hard to make and share quickly
- Kids have no friendly entry point to learn about animal welfare
- Seniors may find modern websites confusing or too small to read

**The Solution:**  
A simple, friendly, multi-page website that:
- Shows available breeds and links directly to real Petfinder listings
- Explains *why* adoption matters with real statistics
- Teaches *how* to care for a new pet
- Lets people report lost pets and post community notices
- Makes sharing the mission as easy as one button click
- Works on phones, tablets, and computers
- Is readable and navigable for users of all ages

---

## 4. User Stories

User stories describe what a real person wants to do and why. Each one maps to a feature on the site.

| # | As a... | I want to... | So that... |
|---|---------|-------------|------------|
| 1 | Kid | See pictures of cute animals | I feel connected and want to help |
| 2 | Adult | Browse animals by breed | I can find the right match for my home |
| 3 | Adult | Click a breed and go to real listings | I can start the adoption process immediately |
| 4 | Senior | Read large, clear text | I don't need to zoom in or squint |
| 5 | Anyone | Learn why adoption matters | I understand the problem and feel motivated |
| 6 | New pet owner | Read pet care tips | I know how to take care of my new animal |
| 7 | Anyone | Understand the adoption process | The steps don't feel scary or confusing |
| 8 | Pet owner | Make a lost pet poster | I can find my missing animal quickly |
| 9 | Community member | See lost pet posters | I can help reunite pets with their owners |
| 10 | Anyone | Share the site easily | I can spread awareness without needing an account |
| 11 | Volunteer | Find a link to volunteer | I can sign up to help at a real shelter |
| 12 | Donor | Find a link to donate | I can give money to support shelter animals |

---

## 5. Pages & Sections (with Examples)

---

### Page 1 — Home (index.html)
**Purpose:** Welcome visitors and point them in the right direction.

**What it includes:**
- Sticky navigation bar at the top with links to all pages
- Big headline: *"Give a Pet a Second Chance"*
- A short paragraph explaining what the site does and who it is for
- An info note (orange left border) explaining all external links go to real, trusted organizations
- Two buttons: **Browse Breeds** and **Learn Why It Matters**
- A real photo of a Labrador on the right side to create an emotional connection

**Example layout:**
```
┌──────────────────────────────────────────────────────────────────┐
│ 🐾 FurAndFound  Home | Browse Breeds | Why Adopt | Pet Care |    │
│                 How It Works | Lost Pet |      [ Adopt Now ]     │
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│   Give a Pet a                        [ Photo of               ]│
│   Second Chance                       [ friendly Labrador      ]│
│                                       [                        ]│
│   Thousands of dogs and cats                                     │
│   sit in shelters right now...                                   │
│                                                                  │
│   💡 All links go to trusted                                     │
│   real organizations like                                        │
│   Petfinder, Humane Society,                                     │
│   and the ASPCA.                                                 │
│                                                                  │
│   [ Browse Breeds ]  [ Learn Why It Matters ]                    │
│                                                                  │
└──────────────────────────────────────────────────────────────────┘
```

**Design notes:**
- Background: warm gradient from white to light orange `#fde9d4`
- The photo has rounded corners and a soft shadow
- On mobile, the photo moves below the text

---

### Page 2 — Browse Breeds (meet.html)
**Purpose:** Show available animal breeds and link visitors to real adoption listings.

**What it includes:**
- Page heading: "Browse by Breed"
- Subheading: "Explore different dog and cat breeds available for adoption. Click a breed to see real animals waiting for a home near you."
- 6 breed cards arranged in a grid (3 columns on desktop, 1 on mobile)
- Each card has: real breed photo, breed name, tag line, personality description, and an adopt button

**Example breed card:**
```
┌─────────────────────────┐
│  [ Photo of Golden      │
│    Retriever ]          │
│                         │
│  Golden Retriever       │
│  Dog · Friendly ·       │
│  Great with kids        │
│  & seniors              │
│                         │
│  Golden Retrievers are  │
│  gentle, playful, and   │
│  love everyone they     │
│  meet...                │
│                         │
│  [ Adopt a Golden       │
│    Retriever ]          │
└─────────────────────────┘
```

**All 6 breed cards:**

| # | Breed | Type | Tag |
|---|-------|------|-----|
| 1 | Golden Retriever | Dog | Friendly · Great with kids & seniors |
| 2 | Tabby | Cat | Affectionate · Great for apartments |
| 3 | Beagle | Dog | Loyal · Good for all ages |
| 4 | Tuxedo Cat | Cat | Playful · Gets along with other cats |
| 5 | Labrador Retriever | Dog | Calm · Perfect for seniors & families |
| 6 | Grey Shorthair | Cat | Gentle · Best in quiet homes |

**Petfinder links used:**
- Golden Retriever → petfinder.com/search/dogs-for-adoption/ca/on/northyork/?breed=Golden Retriever
- Tabby → petfinder.com/search/cats-for-adoption/ca/on/northyork/?breed=Tabby
- Beagle → petfinder.com/search/dogs-for-adoption/ca/on/northyork/?breed=Beagle
- Tuxedo Cat → petfinder.com/search/cats-for-adoption/ca/on/northyork/?breed=Domestic Short Hair
- Labrador → petfinder.com/search/dogs-for-adoption/ca/on/northyork/?breed=Labrador Retriever
- Grey Shorthair → petfinder.com/search/cats-for-adoption/ca/on/northyork/?breed=Domestic Short Hair

---

### Page 3 — Why Adopt (why.html)
**Purpose:** Educate visitors on why shelter adoption matters using real facts.

**What it includes:**
- 4 stat cards with real numbers sourced from the ASPCA
- An awareness box with a share button (no account required)

**Example stat cards:**
```
┌──────────────┐  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐
│    6.3M      │  │    920K      │  │   2 Lives    │  │     25%      │
│              │  │              │  │              │  │              │
│ Animals      │  │ Animals      │  │ Every        │  │ Of shelter   │
│ enter U.S.   │  │ euthanized   │  │ adoption     │  │ dogs are     │
│ shelters     │  │ annually in  │  │ saves two    │  │ purebreds.   │
│ every year.  │  │ shelters.    │  │ lives at     │  │ No breeder   │
│ That is one  │  │ Most are     │  │ once.        │  │ needed.      │
│ every 5 sec. │  │ healthy.     │  │              │  │              │
└──────────────┘  └──────────────┘  └──────────────┘  └──────────────┘
```

**Awareness box example:**
```
┌─────────────────────────────────────────────┐
│  🌍 Help Spread Awareness                   │
│                                             │
│  You don't have to adopt to help.           │
│  Sharing this page, talking to a neighbour, │
│  or posting about shelter animals on        │
│  social media can inspire someone else      │
│  to act. Every voice counts.                │
│                                             │
│  [ 🔗 Share This Site with a Friend ]       │
│                                             │
│  ✅ Link copied! Paste it and send it       │
│     to a friend or family member 🐾         │
└─────────────────────────────────────────────┘
```

**Share button behaviour:**
- On mobile/tablet: opens the device's native share sheet (same as sharing a photo)
- On desktop: copies the page URL to clipboard and shows the green confirmation message for 3 seconds
- No Twitter, no accounts, no app downloads needed

---

### Page 4 — Pet Care (care.html)
**Purpose:** Help new and future pet owners know what to do after adopting.

**What it includes:**
- 6 tip cards in a grid layout
- Each card has an emoji icon, a title, and 2–3 sentences of practical advice

**All 6 tip cards in detail:**

```
🍖 Feeding
Feed your pet at the same times each day.
Use vet-recommended portions and always
keep fresh, clean water available.

🏃 Exercise & Play
Dogs need at least one walk a day.
Cats need 15–20 minutes of interactive
play. Movement keeps them happy and healthy.

🩺 Vet Visits
Book a checkup within the first week.
Keep up with vaccinations, flea prevention,
and yearly wellness exams.

❤️ Building Trust
New pets need time to settle in.
Give them a quiet space, be patient,
and let them come to you. Trust grows slowly.

🎓 Training
Use positive reinforcement — treats, praise,
and play. Reward good behaviour.
Never punish or yell. Short daily sessions work best.

🛏️ A Safe Space
Set up a cozy bed or crate that belongs
just to your pet. A calm corner helps them
feel secure in their new home.
```

---

### Page 5 — How It Works (how.html)
**Purpose:** Walk visitors through the adoption process step by step.

**What it includes:**
- 4 numbered steps connected by arrow connectors
- A final call-to-action box with three real external links

**Step breakdown:**

```
[ 1 Browse ] ──── [ 2 Apply ] ──── [ 3 Meet ] ──── [ 4 Welcome Home! ]

1. Browse
   Look through breeds and find one that
   feels right for your home and lifestyle.

2. Apply
   Fill out a short adoption form so the
   shelter can match you with the right pet.

3. Meet
   Visit the shelter to spend time with
   your potential new companion.

4. Welcome Home
   Once approved, your new pet comes home.
   Your furever journey begins!
```

**Call-to-action box at the bottom:**
```
┌──────────────────────────────────────────────┐
│  Ready to take the first step?               │
│                                              │
│  Every pet is waiting — not for a perfect    │
│  home, just for a loving one.                │
│                                              │
│  [ Start Your Adoption ]                     │
│  [ Volunteer ]   [ Donate ]                  │
└──────────────────────────────────────────────┘
```

---

### Page 6 — Lost Pet Poster Maker (lost.html)
**Purpose:** Help people whose pets are lost create a poster and share it with the community.

**Form fields:**

| Field | Type | Required | Example |
|-------|------|----------|---------|
| Pet Name | Text input | Yes | Biscuit |
| Animal Type | Dropdown | Yes | Dog |
| Breed | Text input | No | Beagle |
| Colour | Text input | No | Brown & white |
| Last Seen Location | Text input | Yes | High Park, Toronto |
| Date Last Seen | Date picker | No | May 8, 2026 |
| Description | Text area | No | Red collar, very friendly |
| Reward Amount | Number (with $ prefix) | No | 150 |
| Contact Info | Text input | Yes | 647-555-0192 |
| Pet Photo | File upload | No | biscuit.jpg |

**Example filled-in form:**
```
Pet Name: Biscuit          Animal Type: Dog
Breed: Beagle              Colour: Brown & white
Last Seen: High Park, Toronto    Date: May 8, 2026
Description: Wearing a red collar. Very friendly with strangers.
             Will come to you if you call his name.
Reward: $150               Contact: 647-555-0192
Photo: [ biscuit.jpg uploaded ✓ ]
```

**Example generated poster:**
```
┌──────────────────────────────┐
│        LOST DOG              │
│                              │
│          Biscuit             │
│     Beagle · Brown & white   │
│                              │
│   [ Photo of Biscuit ]       │
│                              │
│  Last seen: High Park        │
│  Date: May 8, 2026           │
│                              │
│  Wearing a red collar.       │
│  Very friendly with          │
│  strangers. Will come        │
│  to you if called.           │
│                              │
│     💰 $150 REWARD           │
│                              │
│      📞 647-555-0192         │
└──────────────────────────────┘
```

**Poster action buttons:**
- 🖨️ **Print Poster** — prints only the poster, hides the rest of the page
- 📌 **Post to Community Board** — adds a card to the board below so other visitors can see it

**Community board card example:**
```
┌────────────────────────┐
│  LOST DOG              │
│  [ Photo of Biscuit ]  │
│  Biscuit               │
│  Beagle · Brown & white│
│  Last seen: High Park  │
│  on May 8, 2026        │
│  💰 $150 Reward        │
│  📞 647-555-0192       │
└────────────────────────┘
```

---

## 6. Design Guidelines

**Overall feel:** Warm, friendly, approachable — like a cozy animal shelter, not a cold government website.

**Principles:**
- Keep it simple — one main idea per page
- Use large text so seniors and kids can read it easily
- Use warm orange to create energy and friendliness without being aggressive
- Every section should have enough white space so it doesn't feel crowded
- Buttons should be big, rounded, and easy to tap on a phone

---

## 7. Colour & Font Specifications

| Element | Value | Notes |
|--------|-------|-------|
| Primary orange | `#d9601a` | Buttons, highlights, active nav links |
| Dark orange (hover) | `#b84e12` | Button hover state |
| Light orange bg | `#fdf7f0` | Alternatinfg section backgrounds |
| Light orange accent | `#fdebd8` | Pet tags, info boxes |
| Dark text | `#1a1a1a` | Headings |
| Body text | `#555` | Paragraphs |
| Muted text | `#888` | Subtitles, breed tags |
| White | `#ffffff` | Cards, nav bar |
| Dark footer | `#1a1a1a` | Footer background |
| Font family | Segoe UI, Tahoma, Geneva, Verdana, sans-serif | System fonts — no download needed |
| Base font size | 18px | Larger than average for readability |
| Heading size (h1) | 3.2rem | Big and impactful on home page |
| Heading size (h2) | 2.2rem | Clear section titles |
| Border radius (cards) | 16–18px | Soft, friendly corners |
| Border radius (buttons) | 32px | Pill-shaped buttons |

---

## 8. Navigation Structure

Every page shares the same sticky navigation bar at the top.

```
[ 🐾 FurAndFound ]   Home | Browse Breeds | Why Adopt | Pet Care | How It Works | Lost Pet | [ Adopt Now ]
```

**Nav behaviour:**
- Stays at the top of the screen as you scroll (sticky)
- The current page's link is highlighted in orange with an underline
- "Adopt Now" is styled as a filled orange pill button (links to petfinder.com)
- On mobile, nav links wrap into two rows

**Page map:**
```
index.html      → Home
meet.html       → Browse Breeds
why.html        → Why Adopt
care.html       → Pet Care
how.html        → How It Works
lost.html       → Lost Pet
petfinder.com   → Adopt Now (external)
```

---

## 9. Button & Link Behaviour

| Button | Action | Opens in |
|--------|--------|----------|
| Browse Breeds (home) | Goes to meet.html | Same tab |
| Learn Why It Matters | Goes to why.html | Same tab |
| Adopt a [Breed] | Goes to Petfinder breed search | New tab |
| Adopt Now (nav) | Goes to petfinder.com | New tab |
| Share This Site | Copies link or opens share sheet | No navigation |
| Start Your Adoption | Goes to petfinder.com | New tab |
| Volunteer | Goes to humanesociety.org/volunteer | New tab |
| Donate | Goes to aspca.org/donate | New tab |
| Generate Poster | Renders poster preview | No navigation |
| Print Poster | Opens print dialog | Print dialog |
| Post to Community Board | Adds card to board on page | No navigation |

---

## 9B. Technical Button Specifications

This section describes exactly how every button on the site looks, what happens when you hover over it, and the CSS values behind it.

---

### Button Types

There are 5 distinct button styles used across the site. Each has a specific purpose and visual appearance.

---

#### Type 1 — Primary Button (`.btn-primary`)

Used for the most important action on a page — e.g. "Browse Breeds", "Start Your Adoption".

```
┌──────────────────────────────┐
│       Browse Breeds          │   ← white text, bold
└──────────────────────────────┘
  background: #d9601a (orange)
  border-radius: 32px (fully rounded / pill shape)
  padding: 14px top/bottom, 32px left/right
  font-size: 1rem
  font-weight: 700 (bold)
  color: white (#ffffff)
  no border
```

**Hover state:**
```
background changes to: #b84e12 (darker orange)
button lifts up: transform: translateY(-2px)
transition speed: 0.2 seconds
cursor: pointer (hand icon)
```

**Visual example:**
```
Normal:   [ Browse Breeds ]      ← solid orange, white text
Hover:    [ Browse Breeds ]      ← darker orange, slightly raised
```

---

#### Type 2 — Secondary Button (`.btn-secondary`)

Used for the second-most important action — e.g. "Learn Why It Matters". Less visually heavy than primary.

```
┌──────────────────────────────┐
│    Learn Why It Matters      │   ← orange text, bold
└──────────────────────────────┘
  background: transparent (see-through)
  border: 2px solid #d9601a (orange outline)
  border-radius: 32px
  padding: 14px top/bottom, 32px left/right
  font-size: 1rem
  font-weight: 700
  color: #d9601a (orange text)
```

**Hover state:**
```
background fills in: #d9601a (solid orange)
text color changes to: white
button lifts up: transform: translateY(-2px)
transition speed: 0.2 seconds
```

**Visual example:**
```
Normal:   [ Learn Why It Matters ]   ← transparent bg, orange border & text
Hover:    [ Learn Why It Matters ]   ← solid orange bg, white text
```

---

#### Type 3 — Adopt Button (`.btn-adopt`)

Used on every breed card. Smaller than primary, sits inside a card.

```
┌───────────────────────────────┐
│   Adopt a Golden Retriever    │   ← white text, bold
└───────────────────────────────┘
  background: #d9601a (orange)
  border-radius: 28px
  padding: 11px top/bottom, 26px left/right
  font-size: 0.95rem (slightly smaller than primary)
  font-weight: 700
  color: white
  display: inline-block (sits inline with card content)
  width: fit-content (only as wide as the text needs)
```

**Hover state:**
```
background changes to: #b84e12 (darker orange)
no lift effect (stays flat inside the card)
transition speed: 0.2 seconds
```

**Visual example (inside a breed card):**
```
┌─────────────────────────┐
│  Golden Retriever       │
│  Dog · Friendly · ...   │
│  Golden Retrievers are  │
│  gentle and playful...  │
│                         │
│  [ Adopt a Golden    ]  │  ← adopt button at bottom of card
│  [    Retriever      ]  │
└─────────────────────────┘
```

---

#### Type 4 — White Button on Coloured Background (`.btn-white`)

Used inside the orange CTA sections where the background is already orange. The button flips to white so it stands out.

```
┌──────────────────────────┐
│    Start Your Adoption   │   ← dark orange text on white bg
└──────────────────────────┘
  background: white (#ffffff)
  color: #d9601a (orange text)
  border-radius: 32px
  padding: 14px top/bottom, 32px left/right
  font-size: 1rem
  font-weight: 700
  no border
```

**Hover state:**
```
background changes to: #f5ede6 (very light orange tint)
button lifts up: transform: translateY(-2px)
```

---

#### Type 5 — Outline White Button (`.btn-outline-white`)

Used alongside Type 4 on orange backgrounds. Less important than the main action.

```
┌────────────────┐
│   Volunteer    │   ← white text, white border
└────────────────┘
  background: transparent
  border: 2px solid white
  border-radius: 32px
  padding: 14px top/bottom, 32px left/right
  font-size: 1rem
  font-weight: 700
  color: white
```

**Hover state:**
```
background fills in: white
text color changes to: #d9601a (orange)
button lifts up: transform: translateY(-2px)
```

---

### Nav Button (`.nav-btn`)

The "Adopt Now" button in the top navigation bar. Smaller than page buttons, pill-shaped.

```
  background: #d9601a
  color: white
  padding: 10px top/bottom, 22px left/right
  border-radius: 30px
  font-size: 1rem
  font-weight: 500
```

**Hover state:**
```
background: #b84e12
```

---

### Generate Poster Button (`.generate-btn`)

Full-width button at the bottom of the lost pet form.

```
  width: 100% (stretches the full width of the form)
  background: #d9601a
  color: white
  padding: 16px (tall, easy to tap)
  border-radius: 32px
  font-size: 1.1rem (slightly larger than normal)
  font-weight: 700
  border: none
```

**Hover state:**
```
background: #b84e12
button lifts up: transform: translateY(-2px)
```

---

### Print & Post Buttons (`.btn-print`, `.btn-copy`)

Two side-by-side buttons that appear below the poster preview after it is generated.

**Print Poster (`.btn-print`):**
```
  background: #d9601a
  color: white
  padding: 13px
  border-radius: 28px
  font-size: 0.95rem
  font-weight: 700
  flex: 1 (takes up half the row)
```

**Post to Community Board (`.btn-copy`):**
```
  background: transparent
  border: 2px solid #d9601a
  color: #d9601a
  padding: 13px
  border-radius: 28px
  font-size: 0.95rem
  font-weight: 700
  flex: 1 (takes up the other half)
```

**Visual layout:**
```
┌──────────────────┬──────────────────────────────┐
│  🖨️ Print Poster │  📌 Post to Community Board   │
│  (orange filled) │  (orange outline, white bg)   │
└──────────────────┴──────────────────────────────┘
```

---

### Share Button

Styled the same as `.btn-primary` but is an HTML `<button>` element instead of a link, because it runs JavaScript instead of navigating.

```
  Same visual style as Type 1 (Primary Button)
  Uses onclick="sharesite()" JavaScript function
  Text: "🔗 Share This Site with a Friend"
  After clicking on desktop: text changes to "✅ Copied!" for 3 seconds
  After 3 seconds: text resets to original
```

---

### Button Spacing Rules

- On desktop, buttons next to each other have a gap of `14px` between them
- Buttons never touch the edge of the screen — minimum side padding of `24px` on mobile
- On mobile, buttons in a row stack vertically with `12px` gap between them
- All buttons have a minimum height of `44px` to be easy to tap on touchscreens

---

### Summary Table — All Buttons at a Glance

| Button Name | Background | Text Color | Border | Border Radius | Font Size | Hover Effect |
|-------------|------------|------------|--------|---------------|-----------|--------------|
| Primary | #d9601a orange | White | None | 32px | 1rem | Darker + lift |
| Secondary | Transparent | #d9601a orange | 2px orange | 32px | 1rem | Fills orange, white text + lift |
| Adopt | #d9601a orange | White | None | 28px | 0.95rem | Darker |
| White CTA | White | #d9601a orange | None | 32px | 1rem | Light tint + lift |
| Outline White | Transparent | White | 2px white | 32px | 1rem | Fills white, orange text + lift |
| Nav Adopt Now | #d9601a orange | White | None | 30px | 1rem | Darker |
| Generate Poster | #d9601a orange | White | None | 32px | 1.1rem | Darker + lift |
| Print Poster | #d9601a orange | White | None | 28px | 0.95rem | Darker |
| Post to Board | Transparent | #d9601a orange | 2px orange | 28px | 0.95rem | Light orange tint |
| Share | #d9601a orange | White | None | 32px | 1rem | Darker + lift |

---

## 10. External Links Used

| Button | Destination | Why This Site |
|--------|-------------|---------------|
| Adopt Now / Browse Breeds | petfinder.com | Largest pet adoption database in North America |
| Volunteer | humanesociety.org/volunteer | Trusted national animal welfare organization |
| Donate | aspca.org/donate | One of the most recognized animal charities |
| Share This Site | Device clipboard / share sheet | No third-party service — built into the browser |

**Note:** All external links open in a new tab (`target="_blank"`) and include `rel="noopener"` for security. The home page displays a notice explaining that these links go to real, trusted, humane organizations.

---

## 11. Accessibility Requirements

| Requirement | How It Is Met |
|------------|--------------|
| Large readable text | Base font size is 18px across all pages |
| Colour contrast | Dark text on light backgrounds throughout |
| Image alt text | Every image has a descriptive alt attribute |
| Keyboard navigation | All links and buttons are standard HTML elements |
| No autoplay | No videos or audio that play automatically |
| Simple language | Written at a reading level accessible to kids and seniors |
| Clear labels | Every form field has a visible label above it |

---

## 12. Mobile & Responsive Design

The site is fully responsive — it adjusts automatically for phones, tablets, and computers.

| Screen Size | Layout Changes |
|------------|----------------|
| Desktop (1000px+) | Two-column hero, 3-column pet grid, steps in a row |
| Tablet (600–999px) | Two-column pet grid, steps wrap |
| Mobile (under 600px) | Single column everything, nav wraps, photo stacks below text |

**Key mobile rules:**
- All buttons are large enough to tap with a thumb (minimum 44px height)
- The nav bar wraps into two rows on small screens
- Pet cards stack into one column
- The lost pet form and poster preview stack vertically on mobile

---

## 13. Goals & Success Metrics

| Goal | How We Measure It |
|------|------------------|
| Increase awareness | Number of times the share button is used |
| Drive adoptions | Number of clicks on breed adopt buttons |
| Educate visitors | Time spent on Pet Care and Why Adopt pages |
| Help lost pets | Number of posters posted to the community board |
| Reach all ages | Site is tested with a kid, adult, and senior before launch |

---

## 14. MVP Ready Check for Lesson 7

- [x] My page opens in the browser
- [x] My title and intro are clear
- [x] I have at least 3 pet breed cards (we have 6)
- [x] I have at least 2 adoption facts (we have 4)
- [x] I have at least 2 pet care tips (we have 6)
- [x] I have a final call to action
- [x] All nav links work and go to the right pages
- [x] All external buttons go to real websites
- [x] The lost pet poster maker fills in and generates a poster
- [x] The community board shows posted posters
- [x] The share button works without needing an account
- [x] The site looks good on a phone

**Status: ✅ MVP Complete — all Lesson 7 requirements met**

---

## 15. Testing Checklist

Before showing the site to a teacher or presenting it, check every item below.

**Navigation:**
- [ ] Click every nav link — does it go to the right page?
- [ ] Does the current page highlight in orange in the nav?
- [ ] Does the logo link back to the home page?

**Home Page:**
- [ ] Does the hero image load?
- [ ] Do both buttons work?
- [ ] Is the info note visible?

**Browse Breeds:**
- [ ] Do all 6 breed photos load?
- [ ] Does each adopt button open Petfinder in a new tab?
- [ ] Does Petfinder show the correct breed when the button is clicked?

**Why Adopt:**
- [ ] Do all 4 stat cards display correctly?
- [ ] Does the share button copy the link on desktop?
- [ ] Does the share button open the share sheet on mobile?
- [ ] Does the confirmation message appear and disappear after 3 seconds?

**Pet Care:**
- [ ] Do all 6 tip cards display?
- [ ] Do the emoji icons show on all devices?

**How It Works:**
- [ ] Do all 4 steps display in a row on desktop?
- [ ] Do the 3 CTA buttons link to the correct external sites?

**Lost Pet:**
- [ ] Can you fill out the form and click Generate Poster?
- [ ] Does the poster preview appear correctly?
- [ ] Does the Print button open the print dialog?
- [ ] Does Post to Community Board add a card to the board?
- [ ] Does the board show "No lost pet posters yet" when empty?

**General:**
- [ ] Does the site look good on a phone?
- [ ] Does the footer appear on every page?
- [ ] Are there any broken images?
- [ ] Are there any links that go nowhere?

---

## 16. Future Features (Not in MVP)

These features were considered but are not included in the current version. They could be added in a future lesson or project.

| Feature | Description | Why Not Yet |
|---------|-------------|-------------|
| User accounts | Save lost pet posters permanently across sessions | Requires a backend/database |
| Map of nearby shelters | Show a Google Map with local shelters | Requires Google Maps API key |
| "Which breed is right for me?" quiz | Answer questions and get a breed recommendation | Needs more development time |
| Donation tracker | Show how much the community has raised total | Requires payment integration |
| Pet reunion stories | A page where people share happy endings | Needs user-submitted content system |
| Dark mode | A darker colour scheme for nighttime browsing | Low priority for MVP |
| Multiple languages | French, Spanish, and other languages | Would require translations |
| Email notifications | Get an email when someone sees your lost pet poster | Requires email service |

---

## 17. Glossary

| Term | Definition |
|------|------------|
| MVP | Minimum Viable Product — the simplest working version of the site |
| PRD | Product Requirements Document — this document |
| Petfinder | A real website (petfinder.com) that lists animals available for adoption across North America |
| ASPCA | American Society for the Prevention of Cruelty to Animals — a major animal welfare charity |
| Humane Society | A national organization that works to protect animals and reduce suffering |
| Responsive design | A website that automatically adjusts its layout to fit any screen size |
| Sticky nav | A navigation bar that stays at the top of the screen as you scroll |
| Alt text | A written description of an image, used by screen readers and shown if the image fails to load |
| Breed search | A Petfinder feature that filters adoptable animals by their breed |
| Community board | The section of the Lost Pet page where posted posters are displayed publicly |
| Call to action | A button or message that encourages the visitor to do something (adopt, donate, share) |
| Positive reinforcement | A training method that rewards good behaviour instead of punishing bad behaviour |
