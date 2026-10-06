# Boulder-dash

Jeu Boulder Dash en Java, dans la continuité du projet `BoulderProject`.

## Contenu

Le projet se trouve dans `JPU-BlankProject/BoulderDash/`, découpé en modules Maven :

- `contract/` : interfaces du modèle, de la vue et du contrôleur
- `controller/` : contrôleur du jeu
- `entity/` : entités
- `main/` : point d'entrée
- `diagram/` : diagrammes de conception

## Stack

Java, Maven multi-modules, Swing pour l'affichage.

## Compiler et lancer

```bash
cd JPU-BlankProject/BoulderDash
mvn clean install
```

## Contexte

Exercice d'école (2022) sur l'architecture MVC et les modules Maven. Le dépôt `BoulderProject`
porte la version la plus complète.
