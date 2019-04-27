Se informa a todas las tareas de aplicaciones que se ejecutan en el Jeedom
servidor. Este menú es utilizar a sabiendas, o
solicitar soporte técnico.

> **Importante**
>
> En caso de mal manejo de esta página, cualquier solicitud
> Soporte puede ser negado.

Pour y accéder, il faut aller dans **Administration → Moteur de tâches**
:

# Cron

En la parte superior, a la derecha, tienes:

-   **Désactiver le système cron** : un bouton pour désactiver ou
    réactiver toutes les tâches (si vous les désactivez toutes, plus
    nada será funcional con su Jeedom)

-   **Rafraîchir** : un bouton pour rafraîchir le tableau des tâches

-   **Agregar** : un botón para agregar una tarea cron

-   **Enregistrer** : un bouton pour enregistrer vos modifications.

En-dessous, vous avez le tableau de toutes les tâches existantes
(attention, certaines tâches peuvent lancer des sous-tâches, il est donc
vivement recommandé de ne jamais modifier d’informations sur cette
page). Dans ce tableau, on retrouve :

-   **\#** : ID de la tâche, peut être utile pour faire le lien entre un
    proceso que gira y lo que realmente hace

-   **Action** : un bouton pour lancer ou arrêter la tâche en fonction
    de son statut et un bouton pour voir le cron dans le détail (tel que stocké en base)

-   **Actif** : indique si la tâche est active (peut être lancée
    por Jeedom) o no

-   **PID** : indica el proceso ID actual

-   **Deamon** : si esta casilla es "sí", la tarea siempre debe
    être en cours. A côté, vous retrouvez la fréquence du démon, il est
    aconsejado de no tocar nunca este valor y sobre todo nunca
    disminuirla

-   **Unique** : si c’est à "oui" alors la tâche se lancera une fois
    y se eliminará

-   **Classe** : classe PHP appelée pour exécuter la tâche (peut
    estar vacío)

-   **Fonction** : fonction PHP appelée dans la classe appelée (ou non
    si la clase esta vacia)

-   **Programmation** : la programmation de la tâche au format CRON

-   **Timeout** : durée maximale de fonctionnement de la tâche. Si la
    tarea es un deamon por lo que se detendrá automáticamente y
    reiniciado al final del timeout

-   **Último lanzamiento** : fecha de lanzamiento de la última tarea

-   **Dernière durée** : dernière durée pour accomplir la tâche (un
    démon sera toujours à 0s, il ne faut pas s’inquiéter d’autres tâches
    puede estar en 0s)

-   **Statut** : état actuel de la tâche (pour rappel, une tâche démon
    todavía está en "run")

-   **Suppression** : permet de supprimer la tâche


# Listener

Les listeners sont juste visibles en lecture et permettent de voir les fonctions appelées sur un évenement (mise à jour d'une commande...)
