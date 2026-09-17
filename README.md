# Mastterly — coaching prise de parole

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `mastterly.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/mastterly.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs mastterly` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@mastterly.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (49 / 119 / 249 €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
Coaching en prise de parole en ligne : entraînement à la prise de parole en public, aux pitchs et présentations professionnelles, aux entretiens et oraux, et à la gestion du trac. Les clients suivent un programme de 4 à 8 semaines avec séances individuelles ou ateliers en petit groupe en visioconférence et analyses vidéo de leurs prises de parole. Les prestations sont vendues sous forme d’abonnements mensuels sans engagement, de 49 € à 249 € par mois, résiliables à tout moment. Aucun produit physique n’est vendu ni expédié. Site : mastterly.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
