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

(cqrs-evs-microservice-model/captures/Capture.png)
(cqrs-evs-microservice-model/captures/Capture8.png)
(cqrs-evs-microservice-model/captures/Capture1.png)
(cqrs-evs-microservice-model/captures/Capture2.png)
(cqrs-evs-microservice-model/captures/Capture3.png)
(cqrs-evs-microservice-model/captures/Capture4.png)
(cqrs-evs-microservice-model/captures/Capture5.png)
(cqrs-evs-microservice-model/captures/Capture6.png)
(cqrs-evs-microservice-model/captures/Capture7.png)

