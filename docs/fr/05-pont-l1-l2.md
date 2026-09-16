# 5. Pont L1/L2 et messages

Le pont relie les dépôts et retraits entre Ethereum et Scroll. Le monorepo contient les services et interfaces qui suivent les événements des deux couches et construisent l’historique des dépôts et retraits.

Un retrait doit être associé à un message, à un bloc source et à une preuve attendue. L’API bridge-history sert à reconstituer ces relations et à préparer les preuves de retrait.

Les messages inter-couches doivent rester ordonnés et idempotents. Une application ne doit pas considérer un événement observé comme final avant d’avoir vérifié le niveau de finalité requis.

Suite : [RPC et observabilité](06-rpc-observabilite.md).
