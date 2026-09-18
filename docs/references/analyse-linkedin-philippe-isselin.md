# Analyse du compte LinkedIn de Philippe Isselin

Analyse menée le 18/09/2026.

> ## ⚠️ Lire d'abord : ce que cette analyse est, et ce qu'elle n'est pas
>
> **Le proxy réseau bloque LinkedIn.** Je n'ai pu ouvrir **aucun post**. Aucun corps de texte, aucune métrique d'engagement, aucun commentaire.
>
> Ce qui suit est reconstitué par méthode indirecte :
> - **les accroches** sont extraites des *slugs* d'URL LinkedIn, qui reprennent les premiers mots du post ;
> - **les dates et heures** sont décodées depuis les identifiants d'activité LinkedIn (les 41 bits de poids fort encodent un timestamp en millisecondes : `date = id >> 22`) ;
> - **le reste** vient de résultats de recherche indexés et de sources publiques (presse, registres).
>
> **La méthode de datation est corroborée trois fois** : le post « label Solar » tombe au 27/04/2026 et la presse date la labellisation d'avril 2026 ; le post « France 3 Lorraine » tombe au 11/04/2026 et France 3 Grand Est a bien couvert TerraStab ; le post reprenant l'article ConstructionBTP tombe au 04/03/2026, l'article est daté du 02/03/2026.
>
> **En revanche l'inventaire est partiel.** Seuls 6 posts sont indexés publiquement, alors que la production est hebdomadaire. Ne jamais lire ce corpus comme exhaustif : il est représentatif de ce que les moteurs retiennent, pas de tout ce qui a été publié.

---

## 1. Le titre du profil pose un problème immédiat

Le titre de son profil (version anglaise) est indexé ainsi :

> *« builds ConTech × ClimateTech solutions that **protect foundations** and preserve home value »*

**C'est une violation directe du garde-fou n°1 du prompt système** : ne jamais écrire « protéger / stabiliser / renforcer les fondations ». Le positionnement juridique de TerraStab repose sur le fait que la solution agit sur **le sol**, jamais sur les fondations, ce qui la maintient hors du périmètre de la garantie décennale.

Et ce n'est pas un post éphémère : c'est **la ligne la plus lue du profil**, celle qui s'affiche sous son nom à chaque commentaire, chaque invitation, chaque apparition dans un fil.

➡️ **Action prioritaire, à remonter à Philippe avant toute autre chose.** Reformulation possible, à valider : *« builds ConTech × ClimateTech solutions that stabilise the ground beneath homes and preserve their value »*.

⚠️ Confiance : élevée sur la formulation (elle remonte de façon identique sur plusieurs requêtes), mais **à vérifier de visu** avant de faire corriger, car je n'ai pas pu ouvrir le profil.

---

## 2. Inventaire des posts identifiés

| # | Date (décodée) | Heure Paris | Accroche reconstituée | Type d'accroche |
|---|---|---|---|---|
| 1 | 31/07/2025 | 19h59 | *(slug réduit aux hashtags)* `#TerraStab #innovation #RGA` | Indéterminé |
| 2 | 04/03/2026 | 08h30 | « [Exclu] Fissures des bâtiments : l'hydrostabilisation… » | Reprise de titre de presse |
| 3 | 18/03/2026 | 09h45 | « Évaluez vos facteurs aggravants » | Injonction / CTA |
| 4 | 11/04/2026 | 18h30 | « Hier soir, nous étions sur France 3 Lorraine… » | **Situationnel** ✅ |
| 5 | 27/04/2026 | 08h00 | « TerraStab vient d'obtenir le label Solar… » | Annonce corporate |
| 6 | 26/06/2026 | 18h00 | « Le RGA représente 70 % des coûts du régime… » | Statistique |

### Ce que ça dit

**Une seule accroche sur six est personnelle ou situationnelle.** La règle éditoriale n°1 du prompt système dit : *« Hook personnel/situationnel, jamais factuel »*. Cinq posts sur six font l'inverse : ils ouvrent sur un titre de presse, une injonction, une annonce corporate ou une statistique.

C'est **exactement le reproche que Philippe nous a fait le 18/09** — « toujours la même sémantique, la même prose ». Le problème n'est pas seulement le phrasé à l'intérieur du post. Il est **dans la porte d'entrée** : on entre presque toujours par l'institution ou par le chiffre, jamais par une situation.

Et c'est cohérent avec ce que le prompt système note lui-même sur la performance : le post « voisin », qui ouvre sur une personne (*« Mon voisin a une toute petite retraite »*), reste la référence absolue. Les accroches administratives et macro-statistiques sous-performent.

**Le passage du post 6 mérite une attention particulière.** *« Le RGA représente 70 % des coûts du régime… »* : c'est une accroche statistique, sur un chiffre qui n'est **cohérent avec aucune de nos sources** (voir § 4). Un post publié en juin 2026 avec un chiffre invérifiable : c'est précisément le carton rouge de septembre.

---

## 3. Rythme, horaires et formats

**Cadence.** Six posts indexés entre juillet 2025 et juin 2026, avec un trou de sept mois entre le post 1 et le post 2. ⚠️ Cette cadence est un artefact d'indexation, pas la réalité : la production est hebdomadaire. Mais **ce que les moteurs retiennent est ce que les moteurs retiennent** : hors de LinkedIn, l'empreinte de Philippe est très faible et très discontinue. Pour quelqu'un qui doit devenir « le pompier du RGA », c'est un point faible réel.

**Horaires.** La règle interne est une publication planifiée à 8h par Lauriane. Sur les six posts : **un seul est à 8h00** (le 27/04). Les autres tombent à 19h59, 08h30, 09h45, 18h30 et 18h00. Soit le process de planification n'est pas appliqué de façon systématique, soit les posts du soir sont publiés à la main par Philippe en réaction à l'actualité. **À clarifier avec Lauriane** : ce n'est pas anodin, l'inconstance horaire dilue la régularité que l'algorithme récompense.

**Formats.** Deux des six posts sont des reprises d'actualité extérieure (article ConstructionBTP, passage France 3). Le prompt système pose « posts natifs uniquement, pas de reshare ». ⚠️ **Impossible de trancher sans ouvrir les posts** : un commentaire natif sur un article de presse est légitime, un reshare ne l'est pas. À vérifier.

**Le sujet « facteurs aggravants » n'est pas neuf.** Le post 3 du 18/03/2026 s'intitule « Évaluez vos facteurs aggravants ». Or au point du 18/09, ce territoire est présenté comme à ouvrir. **Il a donc été ouvert il y a six mois, puis abandonné.** Avant de le relancer, il faut savoir comment ce post a performé : si c'est un échec, on répète une erreur ; si c'est un succès, on a laissé un filon.

---

## 4. ⚠️ Contradictions relevées entre le prompt système, les posts publiés et les sources publiques

Ce sont les points les plus importants de cette analyse. **Aucun ne doit être tranché par nous : ils remontent tous à Philippe.**

### 4.1 Le chiffre « 70 % des coûts du régime CatNat »

| Source | Valeur |
|---|---|
| Post LinkedIn de Philippe, 26/06/2026 | **70 %** des coûts du régime |
| Prompt système TerraStab | **42 %** des dommages assurés au titre CatNat |
| Cerema / Ighil Ameur | **54 %** de sinistralité cumulée sur 10 ans |
| Cerema, autre indicateur | passage de **37 % à 60 %** sur 2016-2021 en charge financière cumulée |

Quatre valeurs pour une notion voisine. Les périmètres diffèrent probablement (dommages assurés / charge financière / sinistralité sur 10 ans), mais **un post qui affiche 70 % sans préciser le périmètre ne se défend pas ligne à ligne en commentaire**. C'est le cas d'école de ce que Philippe veut éliminer.

### 4.2 L'histoire fondatrice ne correspond pas à celle du prompt système

Le prompt système dit : la maison **de Didier** fissurée il y a onze ans est le déclencheur fondateur, et Didier est un **ami d'enfance**.

Les sources publiques disent autre chose : **Philippe** a acheté une longère ancienne qui s'est fissurée, diagnostiquée RGA, et il cite *« C'est le combat de Didier depuis 10 ans qui m'a poussé à chercher une solution »*, **Didier Rovel** étant présenté comme son **cousin**.

Les deux récits sont conciliables (deux maisons fissurées, deux déclencheurs), mais ils ne sont pas interchangeables. ⚠️ **Le storytelling d'humanisation prévu par Lauriane ne peut pas démarrer tant que la version canonique n'est pas fixée.** Publier une version qui contredit France 3, c'est offrir la contradiction en commentaire.

### 4.3 Didier est déjà nommé publiquement

Le prompt système interdit de nommer Didier publiquement. Mais **Didier Rovel est nommé dans la presse régionale et apparaît dans les registres d'entreprise comme cofondateur**.

➡️ La règle n'est peut-être plus opérante, ou elle ne concerne que LinkedIn. **À reclarifier avec Philippe** : elle bloque aujourd'hui tout le volet technique de la communication, alors que Didier est précisément celui qui porte la connaissance des sols (travaux publics, 30 ans).

### 4.4 Autres écarts

| Élément | Prompt système | Source publique |
|---|---|---|
| Création de TerraStab | 2024 | Registres et presse : **2025**. Philippe DG au 25/09/2025, Président au 22/12/2025 |
| Formation de Philippe | « EDEC Lille » | LinkedIn : **EDHEC Business School**. « EDEC » est vraisemblablement une coquille |
| Ratio de coût | « 10x moins cher » | Communication publique / presse : **« 5 à 15 fois moins coûteuse »** que pieux béton ou reprise en sous-œuvre |
| Implantation | non mentionnée | **Essey-lès-Nancy (54270)**, SIREN 988609350. Identité « start-up nancéienne » assumée dans la presse |
| Presse | article Le Moniteur à venir | **Le Figaro Immobilier**, juin 2026, Philippe sollicité comme voix experte. Non mentionné dans le prompt système |

Sur le ratio : **« 5 à 15 fois » est plus prudent et mieux défendable que « 10x »**, parce que c'est une fourchette. Si c'est la formulation déjà validée en public, c'est elle qu'il faut utiliser partout.

---

## 5. Ce que le compte fait déjà bien

Pour ne pas donner une lecture uniquement critique :

- **Le positionnement « voix experte » fonctionne.** Le Figaro Immobilier, ConstructionBTP et France 3 le sollicitent comme expert, pas comme fournisseur. C'est précisément le socle du rôle de « pompier du RGA » : il est déjà légitime auprès des médias, il ne l'est pas encore auprès de son audience LinkedIn.
- **Les angles juridiques sont bons.** Il a posté sur l'absence de norme nationale définissant les « mesures de prévention usuelles » en matière assurantielle. C'est un angle clivant, défendable, et que personne d'autre ne tient. C'est de la matière première pour la suite.
- **Le site porte déjà un corpus.** `terrastab.fr/rga-news` publie des analyses (refus CatNat, dossier technique de recours, sécheresse comme risque n°1). **C'est le socle long que Jancovici a et que nous n'exploitons pas.** Il est écrit, il est en ligne, il n'est pas décliné sur LinkedIn.

---

## 6. Recommandations

1. **Corriger le titre du profil** (« protect foundations »). Priorité absolue, à remonter aujourd'hui.
2. **Faire arbitrer les cinq contradictions du § 4** avant de produire le plan de contenu. Le storytelling d'humanisation en dépend entièrement.
3. **Basculer les accroches sur du situationnel.** Cinq sur six sont institutionnelles. C'est la cause racine du reproche de Philippe, davantage que le phrasé.
4. **Récupérer les statistiques d'engagement des six posts** auprès de Philippe ou de Lauriane. Sans elles, cette analyse reste structurelle et aveugle sur la performance.
5. **Décliner `terrastab.fr/rga-news` sur LinkedIn.** Le socle existe. C'est le gisement le moins cher et le plus rapide.
6. **Clarifier le process de publication de 8h** avec Lauriane : il n'est appliqué que sur un post sur six.

---

## 7. Ce qu'il me faut pour faire la vraie analyse

Cette analyse porte sur **la structure**, pas sur **le contenu**. Pour aller au bout il me faut, de la part de Célien ou de Lauriane :

- l'**export des 20 à 30 derniers posts** (copier-coller du texte intégral, ou captures) ;
- les **impressions, réactions et commentaires** de chacun ;
- une **capture du profil** (titre, section « Infos », bannière) ;
- si possible les **commentaires reçus** sur les posts chiffrés, pour voir si quelqu'un a déjà contesté un chiffre en public.

Avec ça je sors la vraie grille : longueur moyenne, structure des paragraphes, tics de langage récurrents, position des chiffres, nature des clôtures, corrélation accroche/performance.

---

## 8. Sources

- [Philippe Isselin — profil LinkedIn](https://fr.linkedin.com/in/philippe-isselin/en)
- [Post du 31/07/2025 — #TerraStab #innovation #RGA](https://fr.linkedin.com/posts/philippe-isselin_terrastab-innovation-rga-activity-7356745347127250944-Pdp3)
- [Post du 04/03/2026 — « [Exclu] Fissures des bâtiments : l'hydrostabilisation… »](https://fr.linkedin.com/posts/philippe-isselin_exclu-fissures-des-b%C3%A2timents-lhydrostabilisation-activity-7434862710363955200-oFVO)
- [Post du 18/03/2026 — « Évaluez vos facteurs aggravants »](https://fr.linkedin.com/posts/philippe-isselin_evaluez-vos-facteurs-aggravants-activity-7439955039856685056-dx8b)
- [Post du 11/04/2026 — « Hier soir, nous étions sur France 3 Lorraine »](https://fr.linkedin.com/posts/philippe-isselin_hier-soir-nous-%C3%A9tions-sur-france-3-lorraine-activity-7448769335910830080-wOCI)
- [Post du 27/04/2026 — « TerraStab vient d'obtenir le label Solar… »](https://fr.linkedin.com/posts/philippe-isselin_terrastab-vient-dobtenir-le-label-solar-activity-7454409135842000896-1Fo2)
- [Post du 26/06/2026 — « Le RGA représente 70 % des coûts du régime… »](https://fr.linkedin.com/posts/philippe-isselin_le-rga-repr%C3%A9sente-70-des-co%C3%BBts-du-r%C3%A9gime-activity-7476303313194422272-cTkv)
- [France 3 Grand Est — Maisons fissurées : une solution abordable développée par une start-up nancéienne](https://france3-regions.franceinfo.fr/grand-est/meurthe-et-moselle/nancy/maisons-fissurees-une-solution-abordable-developpee-par-une-start-up-nanceienne-3334745.html)
- [ConstructionBTP, 02/03/2026 — L'hydrostabilisation comme alternative durable aux micropieux](https://www.constructionbtp.com/batiment/article/2026/03/02/155081/exclu-fissures-des-batiments-hydrostabilisation-comme-alternative-durable-aux-micropieux)
- [TerraStab — Le Figaro Immobilier sollicite TerraStab comme expert RGA](https://terrastab.fr/en/terrastab-figaro-expertise-rga)
- [TerraStab — RGA News](https://www.terrastab.fr/rga-news)
- [TerraStab — Sécheresse et CatNat : seulement 1 sinistré sur 4 est indemnisé](https://www.terrastab.fr/rga-solidarite-nationale-25-victimes-indemnisees)
- [TerraStab — Refus CatNat RGA : constituez un dossier technique solide](https://www.terrastab.fr/rga-refus-catnat-dossier-technique)
- [TERRASTAB — Solar Impulse, Alliance mondiale pour des solutions efficaces](https://solarimpulse.com/entreprises/terrastab)
- [TERRASTAB — societe.com (SIREN 988609350, Essey-lès-Nancy)](https://www.societe.com/societe/terrastab-988609350.html)
- [TB TERRASTAB — Pappers](https://www.pappers.fr/entreprise/tb-terrastab-988609350)
- [TerraStab — La French Tech Est](https://lafrenchtechest.fr/startup/terrastab-1ld5/)
