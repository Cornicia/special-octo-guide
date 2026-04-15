# Gestionnaire de Tickets IT — Eliot Group

Application console Java pour la gestion des incidents IT
internes d'une entreprise multi-sites.

## Prérequis
- Java 17+
- Maven 3.8+

## Installation
```bash
git clone https://github.com/africatech/ticket-manager.git
cd ticket-manager
mvn compile
```

## Lancer l'application
```bash
mvn exec:java -Dexec.mainClass="com.africatech.tickets.Main"
```

## Lancer les tests
```bash
mvn test
```

## Fonctionnalités
- Créer, lister, rechercher un ticket
- Filtrer par statut et priorité
- Assigner un technicien
- Gérer les transitions de statut
- Import / Export CSV
- Statistiques

## Structure du projet
C:\Users\elied\Downloads\Gestion de Ticket IT
├── model/      → Ticket, enums
├── manager/    → TicketManager
├── util/       → CsvUtil
└── Main.java   → Point d'entrée
