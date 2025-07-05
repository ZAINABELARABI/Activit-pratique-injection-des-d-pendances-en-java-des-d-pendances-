# Projet Injection de Dépendances et Mini Framework

## Objectif
Ce projet a pour but de comprendre et mettre en œuvre le principe d'injection de dépendances en Java, en utilisant différentes techniques : instanciation statique, dynamique, et avec le framework Spring (XML et annotations).  
En deuxième partie, développement d’un mini-framework d’injection des dépendances similaire à Spring IOC.

## Partie 1 : Interfaces et Implémentations
- Création des interfaces `IDao` et `IMetier`.
- Implémentations respectives avec couplage faible.
- Tests d’injection statique et dynamique.

## Partie 2 : Injection avec Spring Framework
- Configuration XML avec `applicationContext.xml`.
- Configuration par annotations avec `@Component` et `@Autowired`.

## Partie 3 : Mini Framework d’Injection des Dépendances
- Conception d’un conteneur IoC simple.
- Support de configuration via fichier XML (par JAXB).
- Support d’annotations personnalisées pour l’injection.
- Possibilité d’injection via constructeur, setter, et attribut.

## Gestion Git
- Réalisation de commits et push toutes les 30 minutes.
- Utilisation du fichier README.md pour documenter les étapes.
- Dernier commit à la fin de chaque séance.
