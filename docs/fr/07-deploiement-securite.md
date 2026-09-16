# 7. Déploiement, composants et sécurité

Le monorepo combine Go, Rust, contrats Solidity et services Docker. Les configurations décrivent des rôles distincts : rollup, coordinator, prover, base de données et API d’historique.

Cette modularité facilite l’exploitation mais élargit la surface de confiance. Il faut protéger les clés de publication, limiter les accès aux RPC et vérifier les images, paramètres et versions déployés.

Les preuves réduisent la confiance dans l’exécuteur, sans supprimer les risques de disponibilité, de mauvaise configuration, de pont ou de gouvernance.

Suite : [limites et périmètre](08-limites.md).
