# Au pays du Père Noël – Simulation en C#

Projet universitaire réalisé en binôme en L2 Informatique à l'Université de Poitiers.

## Le projet
Simulation en mode console de l'atelier du Père Noël. Les lettres des enfants arrivent heure par heure ; les lutins fabriquent les jouets, les nains les emballent, puis les elfes les chargent dans les traîneaux et les livrent sur chaque continent.

## Fonctionnalités
- Simulation heure par heure ou jusqu'au jour suivant
- Répartition des lettres entre lutins, nains et elfes
- Chargement et livraison des traîneaux par continent, avec stockage en entrepôts
- Gestion du personnel : mise au repos et rappel des lutins et des nains, avec délais à respecter
- Calcul des coûts, indicateurs et bilan de la simulation

## Notions utilisées
- C# et .NET 8
- Programmation orientée objet
- Structures de données génériques : listes chaînées, piles, files

## Répartition du code
- **Fournis par l'enseignant** : l'architecture du programme, les classes, les structures de données (`MyList`, `MyStack`, `MyQueue`) et les menus
- **Écrits par le binôme** : le moteur de la simulation (`AvancerUneHeure`, `AvancerJusquaJourSuivant`), la gestion du personnel (`ModifierNombreLutins`, `ModifierNombreNains`) et les méthodes du traîneau

## Lancer le projet
- Avec le SDK .NET 8 : `dotnet run`
- Ou ouvrir `ProjetAP2.sln` avec Visual Studio

## Auteurs
- Folawe SABINO
- Salimatou BARRY
