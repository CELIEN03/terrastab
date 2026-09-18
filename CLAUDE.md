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

## Accès réseau (mis à jour le 18/09/2026)

L'environnement cloud est passé en **accès réseau « Complet »**. Le web ouvert est accessible **via curl dans Bash**. ⚠️ L'outil WebFetch garde la politique figée au démarrage de la session et refuse encore les domaines externes : dans une session ouverte avant le changement, **utiliser `curl` plutôt que WebFetch**.

Restent inaccessibles quelle que soit la politique réseau :
- **LinkedIn** — répond HTTP 999 aux requêtes non authentifiées (blocage anti-robot). Le texte des posts et les métriques doivent venir d'un export manuel.
- **Légifrance** — 403 sur curl (pare-feu applicatif). Passer par le portail CCR.

Les connecteurs (Gmail, Drive, Fathom, Notion, Canva, Apollo, Agenda) n'ont jamais été concernés : leur trafic passe par les serveurs Anthropic, pas par le réseau de la session.
