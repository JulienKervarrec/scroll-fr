# 4. Coordinator, tâches et persistance

Le coordinator joue le rôle de planificateur entre le rollup et les workers de preuve. Il attribue les tâches, suit les tentatives et récupère les résultats.

La base de données conserve les blocs L1/L2, les lots, les chunks, les messages et les tâches de prover. Les migrations montrent l’évolution des index, des métadonnées de blob, des hashes de challenge et des statistiques.

Cette persistance rend les reprises possibles, mais elle impose des identifiants stables et une gestion claire des états intermédiaires. Un opérateur doit surveiller les tâches bloquées et les versions incompatibles.

Suite : [pont L1/L2](05-pont-l1-l2.md).
