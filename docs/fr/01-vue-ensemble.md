# 1. Vue d’ensemble de Scroll

Scroll est un zkRollup compatible avec le bytecode EVM. Le monorepo rassemble le rollup, le nœud, les contrats, le prover, le coordinator, la base de données et les outils d’intégration.

Le dépôt décrit une séparation entre la chaîne L1 qui reçoit les lots et la chaîne L2 qui exécute les transactions. Les circuits zkEVM produisent des preuves de validité pour cette exécution.

Le parcours suit le flux d’un bloc : collecte, exécution, compression en lots, génération de preuve, publication et vérification.

Suite : [rollup et lots](02-rollup-lots.md).
