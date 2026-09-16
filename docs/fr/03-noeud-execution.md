# 3. Nœud, consensus et exécution

L’arborescence sépare notamment consensus, mempool, execution, state-sync, storage et network. Ces sous-systèmes coordonnent la réception des transactions, leur ordre, leur exécution et la réplication de l’état.

Pour le développeur de DApp, cette architecture explique pourquoi une transaction a un cycle de vie : soumission, inclusion, exécution puis lecture d’état. Les erreurs d’application et les erreurs de disponibilité ne doivent pas être confondues.

[Chapitre suivant : SDK et intégration](04-sdk-integration.md)
