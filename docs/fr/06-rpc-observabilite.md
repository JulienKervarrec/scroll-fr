# 6. RPC, synchronisation et observabilité

Les utilitaires communs fournissent des clients RPC, des fonctions de simulation, des journaux, des métriques de version et des outils de traçage. Ils sont partagés par les services qui lisent L1 et L2.

La synchronisation doit gérer les erreurs RPC, les blocs manquants, les délais et les réorganisations. Les traces servent à diagnostiquer un écart entre le bloc exécuté et le lot envoyé au prover.

Les versions de prover et de codec sont exposées comme des données opérationnelles : elles doivent être contrôlées avant de mélanger des tâches.

Suite : [déploiement et sécurité](07-deploiement-securite.md).
