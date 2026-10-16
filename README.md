# Occurrence

Squarespace site for [occurrence.ca](https://occurrence.ca/), a Montreal contemporary art space (espace d’art et d’essai contemporains).

This repo tracks **site customizations you can version outside the CMS**. Page content, images, menus, and Style Editor tweaks live in Squarespace.

## Stack

- Squarespace **7.1** (Fluid Engine)
- Template ID `5c5a519771c10ba3470d8101`
- Site ID `6679bc54d1d9b14b57134c58`
- Primary language: `fr-CA`
- DNS via Cloudflare (proxied to Squarespace)
- Optional: Weglot (multilingual)

## Structure

```
README.md
custom.css    Source for Design → Custom CSS
```

Squarespace compiles Custom CSS on save. Keep `custom.css` here as the editable source; paste it into the dashboard when deploying CSS changes.

## Site map (nav folders)

Top-level folders on the live site:

| Folder | Examples |
|--------|----------|
| Infos | Mandat et historique, Équipe, Appels de dossiers, Pour nous joindre |
| Programmation | Expositions, Les inéluctables, CONSTELLATIONS, International, National, Événements, Studios et vitrines d'été |
| Archives | Season archives (`/archives-YYYY-YYYY`, …) |
| Médiation culturelle | Visites et ateliers, Point Bleu, Portraits d'artistes |
| Publications | Publications, Livres en vente |
| Locations | Nos espaces, Nos équipements, Plan de la galerie |
| (link) | Campagnes de financement |

Homepage collection: `/` (Accueil).

## Custom CSS

Live Custom CSS is minimal and homepage-scoped (`#collection-6717a70670c4897ffa9575a6`): heading margins, link color, paragraph spacing.

1. Edit `custom.css` in this repo.
2. Copy the rules into Squarespace → **Design → Custom CSS**.
3. Save and verify on [occurrence.ca](https://occurrence.ca/).

Do not commit Squarespace’s compiled one-line output; keep the readable source in git.

## What is not in this repo

- CMS pages, blog/event collections, and uploaded media
- Style Editor / theme tweaks (colors, fonts, spacing)
- Code Injection (header/footer) unless you add files here later
- Weglot dashboard config

## Access

Edit the live site in the Squarespace admin for this site (identifier `octopus-raccoon-m97m`). Contact: `info@occurrence.ca`.
