# 3. Preuves zkEVM et prover

Scroll vise une équivalence de bytecode avec Ethereum : le prover transforme l’exécution EVM en témoins compatibles avec les circuits zkEVM. Le dossier prover-bin et les crates libzkp exposent la génération, le découpage et la vérification des tâches.

Les tâches peuvent être organisées par chunks, bundles et batches. Cette hiérarchie permet de paralléliser le calcul et de suivre les versions de circuit et de codec.

Le coordinator distribue les tâches aux provers et conserve les états utiles à leur reprise. Une preuve n’est exploitable que si elle correspond au bon lot, au bon circuit et aux bonnes données.

Suite : [coordinator et base](04-coordinator-base.md).
