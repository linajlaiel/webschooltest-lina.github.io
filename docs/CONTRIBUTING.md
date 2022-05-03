# Contribution

## Relecture de code

### Objectifs

**Amélioration** : La MR doit améliorer la base de code.  
D'un point de vue général : la maintenabilité, la lisibilité et la compréhension du code doit être meilleure.

Si le critère précédent n'est pas respecté, aucune situation mis à part une urgence ne peut permettre l'intégration de la MR.

Le relecteur peut apporter des suggestions sur tout ce qu'il pense qui est améliorable.

**Réactivité** : ne pas laisser les MR trop longtemps en suspens sous peine d'engranger un travail de maintenance supplémentaire.

La **MR** est d'une taille raisonnable pour être relue rapidement.

-   Le code est formatté conformément aux standard de formattage du projet
-   Les tests sont conformes au besoin initial
-   Les tests sont efficaces : ils remontent des messages clairs, ils sont en echec si les inputs sont incorrects, ils survivent à un certain degré de refactoring
-   L'analyse statique du code est conforme aux critères de qualité
-   Les messages de commit sont conformes et suivent la convention de nommage

### Qui fait la review ?

On souhaite à minima un relecteur tech lead sur le composant impact.  
Idéalement, on souhaite d'autres relecteurs. Ce sont des personnes :

-   qui veulent apprendre
-   qui veulent apporter un avis extérieur
-   qui se sentent pertinentes sur le sujet
-   qui ont des connaissances fonctionnelles à apporter
-   qui sont appelées par l'auteur

### Qui merge ?

C'est l'auteur de la Merge Request qui merge, ou le lead dev.

### Quand merge-t-on ?

L'auteur de la Merge Request peur merger à partir du moment où une mention _"approved"_ est donnée par un tech lead et qu'un délai raisonnable s'est écoulé pour laisser les contributeurs intervenir.

Une fois que l'ensembles des commentaires sont résolus.

### Qui ferme les commentaires ?

Celui qui a ouvert un commentaire doit approuver la réponse qui y a été apportée.  
L'auteur d'un commentaire est responsable de le marquer comme résolu.

### Comment communiquer les nouvelles MR ?

L'auteur partage le lien vers la merge request dans le canal dédié dans Mattermost ou autre.

Les relecteurs se manifestent en régissant au message (✋, ✔, ❔, ...) pour signaler au reste de l'équipe qu'ils interviennent :

-   :eyes: je regarde
-   :pushpin: intéressé mais j'ai pas le temps pour le moment

Cela permet de :

-   rassurer l'auteur en l'avertissant que quelqu'un prend en charge la relecture

-   de communiquer de manière passive au reste de l'équipe qui se charge de la relecture

-   de marquer son intérêt pour la relecture d'une merge request et ainsi définir le _délai raisonnable_ à laisser avant de merger

### Leviers d'efficacité

Gestion des versions / TAG : https://semver.org/

💡 Utiliser les suggestions Gitlab pour les changements mineurs. Cela permet d'éviter de faire retomber tout l'effort de correction sur l'auteur.

💡 Utiliser la fonction "Start review" pour envoyer les commentaires en une seul bloc. Cela permet d'aller au bout de la relecture et d'obtenir soi-même des réponses à ses propres questions.

❔ Lorsque trop de questions sont soulevées : visio / partage d'écran
