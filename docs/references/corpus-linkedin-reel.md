# Corpus LinkedIn réel de Philippe Isselin — texte intégral et engagement

Récupéré le 18/09/2026 par Chromium et curl, après ouverture de l'accès réseau.

**Méthode.** La page profil reste bloquée (HTTP 999), mais **les URLs de posts individuels répondent 200**. Le texte intégral, les compteurs de réactions et de commentaires, et les fils de commentaires sont donc accessibles. Le CA du proxy a été ajouté au magasin NSS pour que Chromium valide le TLS ; à aucun moment la vérification n'a été désactivée.

**Profil (chiffres réels) : 4 003 abonnés · 137 posts · 1 article.**

> ⚠️ Ce document **remplace** la section « corpus » de `analyse-linkedin-philippe-isselin.md`, qui était reconstituée. Les analyses de méthode de ce fichier-là restent valables ; son inventaire, non.

---

## 🔴 Correction de méthode : les slugs d'URL mentent

Dans la version précédente, j'avais reconstitué les accroches depuis les slugs d'URL. **C'était faux dans deux cas sur huit** : quand le post partage un lien, LinkedIn construit le slug à partir du **titre de la carte de lien**, pas de la première ligne du post.

| Slug | Accroche réelle |
|---|---|
| `evaluez-vos-facteurs-aggravants` | « **Terrastab lance une application d'auto-diagnostic RGA** pour massifier la prévention. » |
| `terrastab-innovation-rga` (hashtags) | « **🎉 TerraStab à l'honneur dans La Semaine !** » |

La typologie d'accroches de la version précédente était donc bâtie sur du sable pour ces deux posts. Ci-dessous, tout est établi sur le texte réel.

---

## 1. Le corpus

| # | Date | Accroche réelle | Réactions | Comm. |
|---|---|---|---|---|
| 1 | 31/07/2025 | « 🎉 TerraStab à l'honneur dans La Semaine ! » | **74** | 7 |
| 2 | 04/03/2026 | « TerraStab dans la presse BTP » | 8 | 0 |
| 3 | 18/03/2026 | « Terrastab lance une application d'auto-diagnostic RGA pour massifier la prévention. » | 17 | **12** |
| 4 | 03/04/2026 | « À ceux qui me connaissent bien : j'en parle trop… ou pas assez du RGA ? 😅 » | 10 | 4 |
| 5 | 11/04/2026 | « Hier soir, nous étions sur France 3 Lorraine dans le 19/20. » | **34** | 1 |
| 6 | 16/04/2026 | « Votre maison a peut-être 30 ans. Ou 100 ans. Ou 300 ans. » | 11 | 0 |
| 7 | 27/04/2026 | « TerraStab vient d'obtenir le label Solar Impulse Efficient Solution. » | 10 | 0 |
| 8 | 26/06/2026 | « Le RGA représente 70 % des coûts du régime CatNat. » | 25 | **11** |

⚠️ **Limites.** Compteurs visibles en déconnecté, potentiellement partiels. L'audience a grandi sur la période, donc les chiffres ne sont pas strictement comparables dans le temps. Et 8 posts sur 137 ne font pas un échantillon : c'est ce que l'indexation publique laisse voir.

---

## 2. Ce que l'engagement dit, et qui dérange

**Le post le plus réagi du corpus (74) est un remerciement presse avec emoji et hashtags.** Exactement le format que la doctrine interne réprouve : « 🎉 TerraStab à l'honneur dans La Semaine ! Un grand merci à… », suivi de cinq hashtags.

**Le deuxième (34) est le storytelling long sur France 3 Lorraine** — celui qui respecte le mieux les règles éditoriales.

**Les deux textes les mieux écrits du corpus font 11 et 10 réactions** : « Votre maison a peut-être 30 ans. Ou 100 ans. Ou 300 ans. » et le post Solar Impulse.

**Les deux plus commentés sont l'annonce produit (12) et le post à 70 % (11).**

➡️ Le fil conducteur n'est pas la qualité d'écriture : **ce sont les posts qui annoncent un événement ou ouvrent un débat qui font réagir.** Le beau texte sans nouvelle ne déclenche rien.

C'est une nuance importante pour le plan à venir. La note de cadrage de juin et le prompt système poussent vers le storytelling pur ; les données disponibles suggèrent que le storytelling **adossé à une actualité** est ce qui fonctionne. Le post France 3 fait les deux, et c'est le meilleur compromis du corpus.

---

## 3. 🔴 Le post à 70 % : le chiffre est faux, et l'argument a déjà été contredit publiquement

**Texte de l'accroche :**
> « Le RGA représente 70 % des coûts du régime CatNat. Il est cartographié. Récurrent. Prévisible. À quel moment on arrête d'appeler ça une catastrophe ? »

Le chiffre est faux : le rapport annuel CCR du 23/06/2026 donne **53,1 %** (voir `verification-chiffres-sources.md`).

**Et un commentateur a attaqué l'argument central en public :**

> **JACQUES ROBERT** — « Non cela ne fonctionne pas de cette façon. L'aléa ne constitue qu'un indicateur statistique à grande échelle. Avez-vous programmé la date de vos funérailles sur la base d'une espérance départementale de vie en affirmant la prévisibilité de votre décès ? J'en doute ! »

Le commentaire a recueilli des réactions. **C'est précisément le scénario que Philippe redoute** : un post qu'on ne peut pas défendre ligne à ligne en commentaire.

**À sa décharge, le reste du post est excellent.** Il accumule des signaux faibles — Cour des comptes sur la soutenabilité, interrogation du Sénat, fonds de prévention argile, élargissement de la carte, arrêt de la Cour de cassation exigeant la preuve de mesures préventives — puis retourne : « Le RGA est en train de passer d'un sujet d'indemnisation à un sujet d'assurabilité. » C'est du très bon travail.

➡️ **Ne pas supprimer ce post : le corriger.** Remplacer 70 % par 53,1 % avec attribution au rapport CCR du 23/06/2026, et remplacer « Prévisible » par « **de plus en plus anticipable** », ce qui désamorce l'objection de M. Robert sans rien perdre de la force de l'argument.

---

## 4. Conformité du texte réel aux garde-fous

**🔴 Post 5 (France 3), à corriger :**
> « Notre technologie existe. Elle est brevetée. Elle est **10 fois moins chère** qu'une réparation. **Elle empêche les fissures d'apparaître.** »

Le ratio est conforme ✅. Mais « empêche les fissures d'apparaître » est du **100 % préventif**, ce que la règle actuelle interdit. C'est le symptôme direct de la note de cadrage de juin, qui impose « préventif, jamais curatif ».

**✅ Emploi de « fondations » — conforme partout dans le corpus.** Tous les emplois relevés décrivent le problème, jamais l'action de TerraStab : « les fondations ne suivent plus », « les fondations d'hier ne sont pas faites pour les sols d'aujourd'hui », « des fondations travaillent ». C'est correct. Le problème reste circonscrit au titre du profil (« protect foundations ») et à la vidéo du Drive.

**✅ Sourcing déjà pratiqué.** Le post 3 cite nommément « les travaux de la **Mission Risques Naturels (MRN)** » et « le **guide RGA publié par le Cerema** ». La bonne habitude existe déjà, elle est juste irrégulière.

**⚠️ Registre corporate sur les posts 1 et 2** : remerciements nominatifs, emojis, hashtags en pied. C'est le registre que Philippe juge lassant — et c'est aussi celui qui performe le mieux. Contradiction à porter devant lui plutôt qu'à trancher nous-mêmes.

---

## 5. 💎 Un actif trouvé dans les commentaires

Sous le post 3, une géotechnicienne valide publiquement le principe de TerraStab :

> **Karine Lebas** — « En tant que géotechniciens nous intervenons trop souvent post-sinistre sur les maisons individuelles […] peu de propriétaires sont conscients que le maintien de l'état hydrique du sol sous les fondations ne demande pas la mise en place de protections onéreuses au regard du coût d'un confortement. Soyez vigilant à ce que vos études de conception géotechniques (notamment dans le cadre de la loi Elan/G1/G2) intègrent des préconisations constructives adaptées aux ouvrages. »

➡️ **Caution technique tierce, spontanée, publique.** Bien plus crédible qu'une affirmation de TerraStab sur soi-même. À valoriser avec son accord, et à recontacter : c'est aussi un prospect ou un prescripteur.

Laurent Charlemaine et Stéphane Giloppé commentent également ce post. ⚠️ À noter pour la stratégie d'engagement : les commentaires internes gonflent les compteurs mais ne valent pas caution externe.

---

## 6. Suite possible

Le profil compte **137 posts**. La méthode fonctionne : dès qu'on a l'URL d'un post, on récupère texte, compteurs et commentaires. Il manque un moyen d'énumérer les URLs — la page d'activité et la page entreprise redirigent vers l'authentification.

Deux voies :
1. **Célien ou Lauriane exportent la liste des URLs** depuis leur session LinkedIn connectée. Je fais le reste automatiquement sur les 137.
2. On continue à en découvrir par moteur de recherche, ce qui plafonne vite.

La voie 1 permettrait enfin la vraie corrélation accroche / performance sur l'ensemble du corpus.
