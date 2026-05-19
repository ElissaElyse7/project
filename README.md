# Version Control Workflow – Figma Collaboration

## Project: [ELYSE GROUP]

**Team Members**
- 1 Murengerantwari Elyse
- 2 UMURINGA NUCQUESSE
- 3 IRASUBIZA GABIN HERTIER
- 4 UMUHOZA HENRIETTE
- 5 TETA CHANCELLINE
- 6 UMUGWANEZA JOY

---

## 1. Branching Strategy (Figma File Organization)

We will use **separate pages** inside the same Figma file as “branches”:

| Page Name | Owner | Purpose |
|-----------|-------|---------|
| `main` | All (read-only for most) | Final approved version |
| `dev` | Elyse + Nucquesse | Active working ground |
| `feature/homepage` | Gabin | Homepage redesign |
| `feature/auth` | Henriette | Login/signup screens |
| `feature/dashboard` | Chancelline | Dashboard UI |
| `feature/settings` | Joy | Settings/profile page |

> 🔁 Each feature page is merged into `dev` after review, then `dev` is merged into `main` after weekly approval.

---

## 2. Change Tracking (No Git for Figma, but this replaces it)

Use **Figma’s version history** + **this convention**:

- Every time you finish a task → **Name the version** in Figma:  
  `[YourName] - FeatureName - Date`  
  Example: `Nucquesse - auth buttons - 2026-05-19`

- Add a **short changelog** in this MD file:

### Changelog

| Date | Author | Page/Section | Change description | Version name in Figma |
|------|--------|--------------|-------------------|------------------------|
| May 19 | Elyse | dev | Added nav bar | Elyse-navbar-19May |
| May 20 | Joy | feature/settings | Created settings layout | Joy-settings-20May |

---

## 3. Conflict Prevention Rules

✅ **Only one person edits a page at a time** – announce in group chat before working.  
✅ Every morning → **copy latest `main` into your feature page** before starting work.  
✅ Do NOT delete others’ frames without asking.  
✅ Use **Figma comments** (@mention team members) for feedback – not just chat.

---

## 4. Merge Process (When a feature is done)

1. **Owner** posts in group chat: “`feature/auth` ready for review”
2. At least **2 other members** must review and add ✅ in Figma comments.
3. One reviewer **duplicates** the page content into `dev` (overwriting conflicts carefully).
4. **Weekly leader** (rotating) merges `dev` → `main` and creates a **named version** in Figma.

---

## 5. Rollback Plan

If something breaks:
- Go to Figma → **File > Show version history**
- Restore last stable version (named `main - before [bad change]`)
- Notify team in chat: “Rolled back to [version name]”

---
## 6. OUR FIGMA PROTOTYPE
-  [FIGMA FIRST LINK](https://www.figma.com/files/team/1616716552661280953/recents-and-sharing?fuid=1616716550900246154)
- [FIGMA EXPORT](https://www.figma.com/design/xxcivW5nmCobVxym2eUA9D/EduMentor-AI?node-id=0-1&p=f&t=H7QmIHok3ZBuCLFo-0)

## 7. Tools we use

- **Figma** (design + version history + comments)
- **WhatsApp / Telegram / Discord** (quick sync)
- **This MD file** (changelog + rules)
- **Google Sheets** (optional: task tracker)

---


---

**Last updated:** May 19, 2026  
**Maintainer this week:** Murengerantwari Elyse
