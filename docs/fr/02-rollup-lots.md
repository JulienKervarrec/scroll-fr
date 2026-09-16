# 2. Rollup, blocs et lots

Le service rollup observe les blocs L2, construit les lots et prépare les données à publier sur Ethereum. Les fichiers de test et de configuration montrent des étapes de récupération, de traçage et de soumission.

Un lot regroupe plusieurs blocs afin de réduire le coût de publication. Les métadonnées de lot, les blobs et les versions de codec sont persistés pour permettre au prover et aux services aval de retrouver exactement les entrées.

L’ordre, le numéro de bloc et le hash des données sont des invariants de coordination. Une reprise doit distinguer un lot en attente, publié, prouvé ou finalisé.

Suite : [preuves zkEVM](03-preuves-zkevm.md).
