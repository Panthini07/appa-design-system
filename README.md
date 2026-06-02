# Appa Design System · v2.0

The full design system for **Appa**, a calming procrastination-productivity app.
Teal-led, pink accent, calm on entry, joyful on exit, never overwhelming.

## 🔗 Visual link (the rendered design system to review)

### 👉 https://panthini07.github.io/appa-design-system/appa-design-system.html

This is the live, **visual** version. Open it to see everything below in context.
(The bare repo URL serves only the older color-only palette.)

---

## What changed from Rucha's review

**Typography**
- The three smallest text sizes were bumped (Body SM 14 → 15, Caption 12 → 13, Micro floor 11) so nothing forces a squint.
- Tightened the lowercase rule: lowercase is only for the wordmark "appa", type-codes (p-avoidant) and hashtags. UI actions stay capitalised ("Skip").
- "See all" and "Show more" are now the same size, differing only in colour.

**Buttons & colour**
- Outline buttons are the default; a solid fill is reserved for the one key action per view.
- Primary CTAs trimmed to a calmer size (44px).
- Full-strength teal is reserved for actions; ambient and high-frequency elements use lighter tints.
- Form borders sit at a dark neutral by rest, teal only on focus.
- Topic tags are outline-only; status tags keep a light tint fill.
- The "sent" chat bubble was softened to light teal with dark text.

**Shape, icons, motion**
- Added a named circle radius for circular breathe prompts.
- Larger icon tiers, plus a profile-avatar tier (80 / 96 / 120).
- The radius section now leads with the element-to-radius table (easier to read than raw pixels).
- Hover reveals use an intent delay (slow in, fast out) so an accidental swipe does not pop things up.
- Micro-interaction demos were slowed for a calmer feel.

**Illustration & tone**
- Illustration colour split: functional art stays on-brand; celebrations open up to bright, solid colours (no dull colours).
- Tone Do / Don't lists rewritten as clear imperatives.

---

## What's new in v2.0

**New components:** modal & bottom sheet (with a dimmed scrim), toast / snackbar, selection controls (switch · checkbox · radio), progress, tabs & segmented control, nudge / tip / coach-mark, empty states, skeleton loaders, badges · list items · avatar groups, and dark-mode component previews.

**New sections:** Content & UX Writing (voice examples + emoji rules), Data Visualization (Insights charts), Logo & app icon, Safe areas & responsive behaviour, and Rules for DIY.

**Foundations:** the copy-paste token reference is fully synced, a new `--overlay` scrim token was added, and the real Appa logo is now used throughout.

---

## House rules (baked in)

- No em dashes (use the `·` separator).
- No horizontal lines or dividers; no arrows on buttons.
- White tile backgrounds, colour on the border only, never fill.
- First-person copy.

---

## Still open (picking up next)

- The **Data Visualization** charts use placeholder sample data. They become real once we confirm what Insights actually tracks (metrics, time ranges, chart type per metric, any comparison).

---

## Files in this repo

- `appa-design-system.html` · the full design system (the visual link above).
- `index.html` · the older color-only palette.
- `logo.png` · the Appa logo.
