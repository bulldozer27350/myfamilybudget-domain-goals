# Release Notes — Silo Objectifs (domain-goals)

Toutes les versions publiées de ce dépôt respectent la spécification [SemVer 2.0.0](https://semver.org/lang/fr/).

---

## [0.0.1] - 2026-11-07

### Type de release
**Version initiale** (mise en place et validation de la structure autonome multi-dépôts)

### Résumé
Première version stable du silo Objectifs (`domain-goals`), regroupant `goals-api` et `goals-core` avec import du BOM centralisé, cycle de build autonome et configuration de déploiement GitHub Packages.

### Changements par composant
- **`goals-api`** : modèles, ports, paramètres (aucun changement métier).
- **`goals-core`** : persistance JPA des tables goal, goal_allocation et objectifs_settings.

### Rétro-compatibilité & Compatibilité binaire
Non applicable : version initiale, aucune version antérieure publiée.
