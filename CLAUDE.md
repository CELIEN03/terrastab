# Contexte projet — TerraStab / BTP Élite

Avant toute production de contenu, de message de prospection ou d'analyse sur ce compte, lire :

- @docs/prompt-systeme-terrastab.md — prompt système de référence (entreprise, équipe, cibles, règles)
- @docs/reunions/2026-09-18-point-terrastab-synthese.md — décisions du dernier point client (amende le prompt système)

La transcription intégrale du point du 18/09/2026 est dans `docs/reunions/2026-09-18-point-terrastab-fathom.md`.

Fiches de référence dans `docs/references/` : méthode de communication Jancovici (le modèle de profil visé pour Philippe), et vérification des personnes et entités citées en réunion.

## Garde-fous permanents

- **Chiffres** : aucune affirmation chiffrée sans source institutionnelle nommée. Tout post contenant des chiffres doit être validé par Philippe Isselin (WhatsApp) avant publication.
- **Sol, jamais fondations** : ne jamais écrire « stabiliser/renforcer les fondations ».
- **Préventif ET curatif** : ne jamais présenter TerraStab comme une solution 100% préventive.
- **Jamais de prix bruts** : uniquement des ratios (« 10x moins cher qu'une reprise en sous-œuvre »).
- **Ne pas vulgariser la solution** TerraStab (le problème RGA, oui).
- **Ne pas nommer publiquement** Didier ni le 4e co-fondateur (encore salariés ailleurs).
- **Confidentiel** : le troisième produit digital évoqué le 18/09/2026 ne doit pas être mentionné publiquement.
- **Profondeur technique** : ne rien publier comparant l'hydrostabilisation à d'autres approches sans cadrage préalable de Philippe et Stéphane (voir le projet MACH/MACH+ du Cerema dans `docs/references/personnes-et-entites-citees-18-09-2026.md`).
- **Tiret cadratin banni** dans les posts LinkedIn de Philippe.
- Tutoiement de Célien, vouvoiement de Philippe.

## Limite d'environnement (vérifiée le 18/09/2026)

La politique d'egress de cette session **bloque tout le web sortant sauf GitHub** : LinkedIn, terrastab.fr, YouTube, Wikipédia, cerema.fr, legifrance.gouv.fr, ccr.fr, georisques.gouv.fr, lemoniteur.fr, theconversation.com renvoient tous un 403 sur le CONNECT du proxy. Chromium et Playwright passent par le même proxy : ils ne contournent rien.

Conséquences :
- **la recherche web fonctionne** (elle ne passe pas par ce proxy) et reste le seul canal d'accès à l'information externe ;
- **aucune source primaire ne peut être ouverte et lue** depuis cette session. Toute vérification de chiffre doit être refaite à la main par un humain avant publication ;
- inutile de retenter : selon le README du proxy, un 403 est une décision de politique, à signaler et non à contourner.

