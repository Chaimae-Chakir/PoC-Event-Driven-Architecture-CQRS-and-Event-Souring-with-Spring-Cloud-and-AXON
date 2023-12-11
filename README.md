## les patterns CQRS et Event Sourcing.

## Démonstration de PoC (Proof Of Concept)
-j'ai réalisé une démonstration de Proof Of Concept (PoC) visant à illustrer comment séparer la partie Commande de la partie Query au sein de deux microservices distincts dans un projet Spring Boot composé de 3 modules.

### Modules du Projet

1. **Core-API (Kotlin)**
    - Implémentation des commandes, events, DTO, queries, etc.

2. **Partie Commande**
    - Module responsable de la gestion des commandes du système.

3. **Partie Query**
    - Module dédié à la gestion des requêtes pour récupérer des données du système.

Cette démonstration vise à montrer aux étudiants comment concevoir un système modulaire, où les responsabilités de la manipulation de données (Commande) et de la récupération de données (Query) sont traitées de manière indépendante, favorisant ainsi la scalabilité et la maintenabilité du projet.

Pour plus de détails, consultez le code source dans les répertoires respectifs des modules.

### Captures d'écran de la Démo

https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture.PNG
https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture8.png
https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture1.png
https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture2.png
https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture3.png
https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture4.png
https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture5.png
https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture6.png
https://github.com/Chaimae-Chakir/PoC-Event-Driven-Architecture-CQRS-and-Event-Souring-with-Spring-Cloud-and-AXON/blob/main/captures/Capture7.png

