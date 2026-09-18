# Audit du corpus complet — 97 posts TerraStab

Source : application **Botlan Acquisition** (`app.botlanacquisition.com`), espace client TERRASTAB, onglet Contenu.
Extraction du 18/09/2026. Corpus brut conservé dans `docs/data/posts-terrastab-app-2026-09-18.json`.

**97 posts du 8 avril au 28 septembre 2026** : 91 publiés, 5 à valider, 1 brouillon agence.
Objectif affiché dans l'app : **16 posts/mois**.

> ✅ Ce corpus remplace définitivement les reconstitutions précédentes. C'est la source de vérité.

---

## 🔴 1. Le vrai problème de répétition : l'accroche est toujours un chiffre

Voici les accroches de fin août à fin septembre, dans l'ordre :

> « 58 % des maisons fissurées… » · « 40 000€ de réparations… » · « 474 communes refusées. 107 acceptées… » · « Votre maison pèse entre 80 et 150 tonnes… » · « 7 arrêtés CatNat en 6 mois… » · « 20 milliards d'euros de dégâts… » · « Vous gérez 500 logements. 60 % sont sur sol argileux… » · « 10 centimètres… » · « 60 000€ de micropieux. Ou 6 000€… » · « Arrêté du 12 juin 2026. 107 communes… » · « 10,7 millions de maisons… » · « 200 tonnes… » · « 3,5 milliards d'euros… »

**L'immense majorité des posts ouvre sur un nombre.**

La règle éditoriale n°1 dit : *« Hook personnel ou situationnel — jamais factuel. »* Elle n'est pas enfreinte ponctuellement : **elle est enfreinte systématiquement**, et c'est exactement ce que Philippe ressent quand il dit « toujours la même sémantique, la même prose ».

Ce n'est pas le vocabulaire qui se répète. **C'est la porte d'entrée.** Quatre fois par semaine, le lecteur reçoit le même geste : un chiffre choc, puis le développement. Au bout de trois semaines, le cerveau reconnaît le motif et décroche, quelle que soit la qualité du texte qui suit.

**C'est aussi ce qui explique mécaniquement les erreurs de chiffres.** Si chaque post doit ouvrir sur une donnée neuve, à 16 posts par mois, il faut 16 données neuves par mois. Le réservoir s'épuise, et on finit par arrondir.

### Les accroches qui échappent au motif, et qui sont les meilleures
- 03/08 — « Votre pelouse a jauni en 3 jours cette semaine. Il y a 20 ans, ça prenait 3 semaines. »
- 07/08 — « 800 mètres sous terre. C'est là qu'ils travaillaient. Aujourd'hui, c'est à 50 centimètres sous leurs maisons. » *(les corons)*
- 25/08 — « Il pleut. Vous pensez que c'est bon pour votre sol. C'est souvent le contraire. »
- 04/09 — « Couper un arbre pour sauver sa maison peut aggraver les fissures. »
- 08/09 — « Vendredi dernier, un propriétaire m'a demandé : "Mais concrètement, comment vous savez que mon sol bouge ?" »
- 23/09 — « Un arbre en zone argileuse fait exactement l'inverse la nuit de ce qu'il fait le jour. »

Ce sont des accroches **situationnelles ou contre-intuitives**. Ce sont aussi, d'après le prompt système, celles dont les performances sont les meilleures (l'arbre à 91K impressions, les 10 cm à 224K).

---

## 🔴 2. Prix bruts publiés — dont un faux

Huit occurrences de montants en euros. **Il faut distinguer deux cas.**

**✅ Légitime — citer le coût d'une réparation tierce ou une donnée officielle :**
| Date | Montant | Nature |
|---|---|---|
| 23/07, 31/07 | 40 000€ | coût de réparation subi |
| 27/07 | 70 000€ | idem |
| 24/08 | 16 500€ | coût moyen d'un sinistre (Cour des comptes) |
| 03/09 | 60 000 € | coût de reprise |
| 21/09 *(à valider)* | 76 000 € | le post « voisin » |

**🔴 Non conforme — annoncer un prix TerraStab :**
> **01/09/2026, publié** : « **60 000€ de micropieux. Ou 6 000€ d'hydrostabilisation.** Pour le même problème. »

Deux problèmes cumulés :
1. C'est un **prix brut de la solution**, interdit depuis juillet 2026 : la règle impose un ratio.
2. **Le chiffre est faux.** Le prompt système établit que la solution installée démarre **à environ 10 000 € minimum**. Annoncer 6 000 € promet un prix qui n'existe pas.

➡️ **Post à corriger en priorité.** Formulation conforme : « Les micropieux, c'est un ordre de grandeur dix fois supérieur. »

---

## 🔴 3. Incohérence interne : 10,7 millions contre 12,1 millions

| Post | Chiffre | Formulation |
|---|---|---|
| **07/09/2026**, publié | **10,7 millions de logements** | « Un logement sur trois. […] C'est la cartographie officielle du BRGM, aujourd'hui, en 2026. » |
| 11 autres posts, dont le 28/09 à valider | **12,1 millions de maisons individuelles** | « (BRGM, janvier 2026) » |

Les deux sont attribués au BRGM, à la même période, et présentés comme officiels. Les périmètres diffèrent peut-être (logements vs maisons individuelles), mais **« un logement sur trois » et « 61,5 % du parc de maisons individuelles » ne se recoupent pas**, et rien dans les posts ne l'explique.

Un lecteur attentif qui suit le compte voit les deux chiffres à deux semaines d'intervalle. ➡️ **Trancher avec Philippe et n'en garder qu'un.**

---

## 🔴 4. Le post du 18 septembre est marqué publié avec ses notes internes

Le post daté du **18/09/2026**, statut **Publié**, commence littéralement par :

> « **DEUX VERSIONS POUR CE POST : 1 -** Avant d'être un aléa climatique, le RGA est un aléa minéralogique… »

⚠️ **À vérifier de toute urgence sur LinkedIn.** Soit c'est un statut mal renseigné dans l'app et rien n'est parti, soit un post contenant des instructions de production interne a été publié sous le nom de Philippe. Dans le second cas, c'est l'incident le plus grave du corpus.

Le texte lui-même est excellent par ailleurs : l'argile comme empilement de feuillets de moins d'un nanomètre, variations de volume de 10 à 40 %, « une matière qui respire ».

---

## ✅ 5. Deux de mes alertes précédentes étaient des faux positifs

**« 70 % » du 06/08 : faux positif.** Le passage dit « Aujourd'hui, 55 % du territoire est en zone exposée au RGA. En 2050, ce sera probablement 70 % ». C'est une projection territoriale, pas la part des coûts CatNat. Rien à corriger, hors le fait que la projection 2050 mériterait une source.
**Seul le post du 26/06 porte le « 70 % des coûts du régime ».**

**« Fondations » du 15/05 : faux positif, et c'est même exemplaire.**
> « Il y a un ordre logique. D'abord **stabiliser le sol**. Ensuite, si nécessaire, **conforter les fondations**. Et seulement après, réparer les fissures. […] Notre technologie agit sur la première étape. »

La distinction sol / fondations est explicite, et le confortement des fondations est attribué à une autre étape que celle de TerraStab. **C'est la formulation de référence à réutiliser.**

**Reste une seule violation réelle du garde-fou préventif/curatif :** le post du **11/04** (France 3) — « Elle empêche les fissures d'apparaître ».

---

## ✅ 6. Le sourcing existe et progresse

Sources nommées dans le corpus : **BRGM (6 posts)**, **CCR (6)**, **Sénat (5)**, **Cour des comptes (4)**, **Cour de cassation (3)**, France Assureurs (2), MRN (2), Solar Impulse (2), Cerema (1), Géorisques (1), rapport Lavarde (1), rapport Ledoux (1).

Le brouillon agence en attente porte un bloc de sources complet destiné aux commentaires — exactement le standard réclamé par Philippe. **La pratique existe, elle est juste irrégulière.**

---

## 7. Format : le post court n'existe pas

| | |
|---|---|
| Longueur médiane | **1 031 caractères** |
| Moyenne | 1 128 |
| Minimum | 596 |
| Maximum | 3 348 |
| Posts de moins de 400 caractères | **0** |

La note de cadrage de juin prévoit un format « **court et percutant — 3-4 lignes, un chiffre, une chute. Idéal pour tester de nouveaux angles.** »

**Ce format n'a jamais été produit.** Sur 96 posts, aucun ne descend sous 596 caractères. Un levier de variété entier est resté inutilisé, alors qu'il est le moins coûteux à produire.

---

## ✅ 8. Question résolue : l'Université Gustave Eiffel, c'est eux

Post du **20/08/2026** : « On recrute un(e) chercheur(se) pour résoudre un problème à 500 milliards d'euros. Avec l'Université Gustave Eiffel… »

L'offre de post-doctorat sur le comportement hydrique des sols argileux gonflants que j'avais repérée en veille **est celle de TerraStab**. Ce n'était pas un concurrent, c'est leur propre partenariat de recherche. À valoriser comme tel dans le pilier « crédibilité tech ».

---

## 9. Actions, par ordre de rentabilité

| | Action | Échéance |
|---|---|---|
| 1 | **Vérifier le post du 18/09** — publié avec ses notes internes ? | Aujourd'hui |
| 2 | **Corriger le post du 28/09 avant publication** : 42 % → 53,1 % (rapport annuel CCR, 23/06/2026) | Avant le 28/09 |
| 3 | **Corriger le post du 01/09 en ligne** : retirer « 6 000€ », passer au ratio | Aujourd'hui |
| 4 | **Corriger le post du 26/06 en ligne** : 70 % → 53,1 %, et « Prévisible » → « de plus en plus anticipable » | Aujourd'hui |
| 5 | **Trancher 10,7 M vs 12,1 M** avec Philippe | Cette semaine |
| 6 | **Corriger le titre du profil LinkedIn** (« protect foundations ») | Cette semaine |
| 7 | **Casser le motif de l'accroche chiffrée** : viser une accroche situationnelle ou contre-intuitive sur au moins 2 posts sur 4 | Plan à un mois |
| 8 | **Introduire le format court** (3-4 lignes), inutilisé depuis juin | Plan à un mois |
| 9 | **Remplir l'onglet Statistiques** de l'app, vide depuis l'origine | Mensuel |
