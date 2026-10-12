---
description: Create a polished, separate veterinary clinic prospect demo from the KingVet Animal Clinic mother template. Use only when the user asks to create a new veterinary prospect site or baby demo from this template.
---

# Create a veterinary prospect demo

Invoke this skill manually:

```text
/create-vet-demo Barkeley and Mao Veterinary Clinic
```

If the user supplies a short project name, treat it as the target slug. The Barkeley target slug is **barkeley-mao-vet**.

## Non-negotiable safeguards

- KingVet is the **mother template**. Do not edit, rename, move, overwrite, commit changes to, or deploy its existing site files while creating a child demo.
- Create the child in a separate target directory and, if GitHub is in scope, a separate repository. For Barkeley, use `barkeley-mao-vet` for the target directory, GitHub repository, and proposed preview-project name.
- If that destination already exists, inspect it first and ask before overwriting anything.
- Do not publish, deploy, create a live booking integration, or connect forms to an external service unless the user explicitly approves it.
- Treat social-media screenshots as reference material only. Do not crop, reuse, or download post photos, videos, testimonials, logos, or other assets unless the user separately supplies them for website use.
- Never invent clinical claims, fees, promotions, credentials, staff bios, opening hours, contact details, reviews, ratings, or addresses. Mark unverified fields as demo placeholders.

## First response: plan before changes

Before creating the child project, give a concise plan that states:

1. The source: KingVet mother template.
2. The separate target: the clinic name and slug.
3. The build: a static, WordPress-ready front-end that retains the existing multi-page structure and replaces only the clinic brand, content, and imagery.
4. Why it remains separate: the source template stays reusable for future prospects.
5. The missing business facts or assets that will remain clearly marked as placeholders.

Wait for confirmation if the plan requires a meaningful design or technical decision beyond the supplied reference material.

## Barkeley and Mao Veterinary Clinic preset

When the clinic or slug matches Barkeley, begin with this approved brief:

- **Clinic name:** Barkeley and Mao Veterinary Clinic
- **Project/URL slug:** `barkeley-mao-vet`
- **Positioning/tagline:** “Happiness Starts with a Healthy Pet”
- **Brand direction:** Warm, upbeat, approachable, pet-first; use a soft cream base with cheerful pink, coral, and mint/teal accents inspired by the supplied Facebook cover. Recreate this direction in the interface; do not copy the cover artwork.
- **Visible service themes to feature:** Health checks and vaccination, laboratory, surgery, grooming and boarding, and X-ray/ultrasound or diagnostic imaging.
- **Conversion goal:** Guide a pet owner from services to a low-friction contact or appointment request.

### Barkeley facts still needing confirmation

Keep these as clearly labelled demo placeholders until the user supplies them:

- Exact address, service area, hours, phone, email, Messenger link, booking route, and emergency policy.
- Active promotions, discounts, prices, or package terms.
- Clinicians, credentials, team bios, testimonials, review ratings, and consented photos.
- A transparent logo file (PNG or SVG) and any original brand files.

Do not turn a time-sensitive promotional graphic into evergreen website copy without current written approval.

## Build workflow

1. Inspect the mother template and inventory its pages, shared CSS, JavaScript, navigation, forms, and assets.
2. Copy it into the separate target. Preserve the source untouched.
3. Create a Barkeley-specific content map before editing:
   - Home
   - Services
   - Laboratory & Diagnostics
   - About
   - Team
   - Testimonials
   - Contact / Location
   - Appointment
4. Replace all inherited KingVet or placeholder clinic naming and calls to action in the child only.
5. Use original, licensed, or clearly labelled placeholder visuals. Do not use Facebook post imagery by default.
6. Keep the site responsive and make every main CTA lead to service information, contact, or the demo appointment page.
7. Make contact and appointment forms visibly demo-only unless a real service has been explicitly approved.
8. Add basic local-SEO structure without inventing location facts: accurate title hierarchy, descriptive page titles, service keywords grounded in the approved brief, and pending-data markers where local details are missing.
9. Run a complete quality pass: every route, navigation link, CTA, image path, mobile/tablet/desktop layout, console errors, and form behaviour.
10. Report the child-project path, changed files, verification results, remaining placeholders, and whether it is ready for static hosting. Do not deploy until asked.

## Definition of done

A finished child demo is visibly distinct from KingVet, uses only approved facts and assets, is presentation-ready on mobile and desktop, retains no unapproved source-client copy, and is isolated from the mother template.
