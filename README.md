# The SMBC Muslim Guide to MIT & Boston

A guide to prayer spaces, masjids, halal butchers and restaurants across Greater Boston, for Muslims at MIT Sloan.

Maintained by **MIT Sloan Muslims in Business Club (SMBC)**. Published at <https://smbc-sloan.github.io/guide/>.

## Deploying

This is a GitHub **project site**: the repo is `smbc-sloan/guide`, so it serves from `/guide/` on the club domain. GitHub Pages is set to deploy from `main` / `(root)`, and pushes go live within a minute or so. There is no build step — what's in the repo is what's served.

## What's here

| File | What it is |
|---|---|
| `index.html` | The whole guide — one self-contained page, no build step, no dependencies |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Editing it

`index.html` is plain HTML with the styles inline at the top. Open it in any editor, change the text, commit. GitHub Pages redeploys automatically within a minute or so.

Every address is a Google Maps search link of the form:

```
https://www.google.com/maps/search/?api=1&query=<url-encoded name and address>
```

These resolve by name and address rather than by place ID, so they keep working even if a business moves or Google changes its internal IDs.

## Annual review checklist

Roughly a third of this content goes stale within two years. Each year, the board should check:

- [ ] **Jummah time and location** — confirm with the MSA; it has moved before
- [ ] **W11 overnight access hours** — the 1 AM–4 AM lock window has changed in past years
- [ ] **Campus prayer rooms** — confirm E52-112 and E51-050 are still designated
- [ ] **MSA contact + mailing list link** — boards turn over every year
- [ ] **Restaurant closures** — several entries on the source list have closed since it was compiled
- [ ] **Halal status of chains** — especially Dave's Hot Chicken, which varies by franchise
- [ ] **SMBC contact details** in the quick-reference section

## Restaurant tiering

Restaurants carry one of three tiers. This distinction is deliberate and should not be flattened into a single list — some entries serve pork, or have only one halal item.

| Tier | Meaning |
|---|---|
| 1 | Fully halal — the whole menu |
| 2 | Partially halal — specific items only; the note says which |
| 3 | Safe to eat — no halal meat, but vegetarian/vegan/seafood options |

## Credit

The restaurant and butcher research draws on the community-maintained *"Halal & Masjid Boston"* Google Maps list compiled by **Habibah Agianda**, which carries its own standing caveat: *"halal or safe to eat — always ask for zabiha / cross-contamination."*

Prayer space and Jummah information comes from the [MIT Muslim Students Association](https://msa.mit.edu) and the MIT Division of Student Life. Masjid addresses were cross-checked against [The Revert Project](https://therevertproject.org/masjidboston) and each masjid's own site.

Nothing in this guide is official MIT policy.
