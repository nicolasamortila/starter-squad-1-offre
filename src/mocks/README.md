# Mocks des contrats des autres squads

Ces modules simulent les contrats **v0** des squads dont la squad 1 · Offre dépend, pour développer et tester
sans attendre leur implémentation. Ils suivent les contrats du Context Nexus en version 0.1.0.

Quand une autre squad publie sa v1 (ou qu'un contrat change pendant le Develop), mettez le mock à jour **avec** la spec :
demandez à Claude « Aligne le mock <nom> sur la nouvelle version du contrat ».

| Mock | Contrat simulé |
|---|---|
| `regle-prix.ts` | Règle de prix v0 (squad Prix) |
