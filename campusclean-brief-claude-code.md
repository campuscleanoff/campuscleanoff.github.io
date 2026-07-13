# CampusClean — Brief projet pour Claude Code

## Contexte
Service de nettoyage professionnel lancé par **3 étudiants** pour financer leurs études, basé à **Mons, Belgique**. Cible : villas, maisons, appartements, cabinets médicaux, bureaux, commerces, garages.

## Ce qui existe déjà
Un site statique complet a été conçu et livré (HTML/CSS/JS vanilla, sans framework) :
- `index.html` — page unique avec sections ancrées (Hero, Trust badges, Histoire, Services, Pourquoi nous, Stats, Galerie avant/après, Avis, Tarifs, FAQ, CTA, Footer)
- `style.css` — feuille de style complète
- `script.js` — nav mobile, accordéon FAQ, animations au scroll (IntersectionObserver)
- `privacy.html` — page de politique de confidentialité séparée

**Objectif pour Claude Code : reprendre ces fichiers, les héberger (ex. Vercel/Netlify/GitHub Pages), mettre en place un dépôt Git, et permettre des itérations faciles (ajout de vraies photos, vrais avis, mise à jour des tarifs).**

## Identité de marque
- **Nom** : CampusClean
- **Logo** : deux arcs en forme de "C" incomplets qui s'imbriquent (turquoise + marine), symbolisant Campus + Clean, le travail d'équipe et une promesse tenue. Code SVG déjà présent dans les fichiers HTML.
- **Couleurs** :
  - Marine profond `#16233D` (dominante, ~70%)
  - Turquoise `#21A897` (accent interactif, ~15-20%)
  - Menthe `#4FE0C6` (variante turquoise sur fond sombre)
  - Sable doré `#D9B26F` (accent rare uniquement — badges, jamais en aplat)
  - Blanc cassé `#FAFAF8` (fond clair)
- **Typographie** :
  - Space Grotesk (titres, logo) — via Google Fonts
  - Manrope (corps de texte) — via Google Fonts

## Coordonnées réelles (déjà intégrées dans le site)
- WhatsApp : **0470 47 64 26** (lien `https://wa.me/32470476426`)
- Téléphone (appel) : 0455 17 54 53
- Email : campuscleanoff@gmail.com
- Zone d'intervention : Mons et environs

## Ton de marque
Sérieux et professionnel, jamais misérabiliste. Message clé : *"On ne demande pas de la compassion, on gagne la confiance par le travail."* Doit rassurer aussi bien un cabinet médical qu'un particulier.

## À faire / points ouverts avant mise en ligne définitive
1. **Remplacer les avis clients placeholder** par de vrais témoignages (actuellement des emplacements vides marqués "à venir" — ne jamais publier de faux avis).
2. **Ajouter de vraies photos avant/après** dans la section galerie (actuellement des emplacements vides).
3. **Confirmer les tarifs définitifs** (60€ / 90€ sont des exemples indicatifs à ajuster).
4. **Héberger le site** et faire pointer le QR code de la carte de visite vers l'URL finale.
5. Option à discuter : formulaire de contact fonctionnel (actuellement le seul canal est WhatsApp/email/téléphone en liens directs).

## Autres livrables déjà créés (pour référence, pas à recoder)
- Planche d'identité de marque (HTML + PDF, 2 pages) avec toutes les variantes du logo, palette et typographie
- Carte de visite (HTML mockup, recto/verso, avec QR code réel vers le WhatsApp)