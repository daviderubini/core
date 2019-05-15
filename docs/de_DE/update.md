Beschreibung 
===========

<<<<<<< HEAD
Das **Update Center** ermöglicht es Ihnen, alle Funktionen von Jeedom zu
aktualisieren, einschließlich Kernsoftware, Plugins, Widgets usw.. Weitere
Funktionen zur Verwaltung von Erweiterungen sind verfügbar (Löschen,
Neuinstallieren, Prüfen usw.).
=======
Le **centre de mise à jour** permet de mettre à jour toutes les
fonctionnalités de Jeedom, incluant le logiciel de base (core), les
plugins, les widgets, etc. D’autres fonctions de gestion des extensions
sont diponibles (supprimer, réinstaller, vérifier, etc.)
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7

Die Update Center Seite
================================

<<<<<<< HEAD
Sie ist über das Menü **Administration → Update Center**
erreichbar.

Sie finden auf der linken Seite alle Funktionen von Jeedom und auf der rechten Seite den **Informations**-Teil, in dem angezeigt wird, was passiert wenn ein ein Update gestartet wird.
=======
Elle est accessible par le menu **Administration → Centre de mise à
jour** et se composent de 3 onglets et une partie haute.
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7

Die Funktionen oben auf der Seite.
---------------------------------

<<<<<<< HEAD
In oberem Teil der Tabelle befinden sich die Schaltflächen. Jeedom
verbindet sich regelmäßig mit dem Markt um zu sehen, ob Updates
verfügbar sind (das Datum der letzten Prüfung wird am oberen Rand auf der
linken Seite der Tabelle angezeigt). Wenn Sie eine manuelle Überprüfung
durchführen möchten, klicken Sie die Schaltfläche "Nach Updates suchen" an.

Die Schaltfläche **Updaten** wird verwendet, um das Jeedom Paket zu aktualisieren. Sobald Sie darauf klicken, erhalten Sie diese verschiedenen Optionen :
=======
En haut de la page,indépendant de l'onglet, se trouvent les boutons de commande. 
Jeedom se connecte périodiquement au Market pour voir si des mises à jour
sont disponibles (la date de dernière vérification est indiquée en haut
à gauche de la page). Si vous voulez réaliser une vérification manuelle,
vous pouvez appuyer sur le bouton "Vérifier les mises à jour".

Le bouton **Mettre à jour** permet de mettre à jour l’ensemble de
Jeedom. Une fois que vous avez cliqué dessus, on obtient ces différentes
options :
-   **Pré-update** : Permet de mettre à jour le script de mise à jour avant
    applicatifs des nouvelles mises à jour.
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7

-   **Vorher speichern** : Führt vor dem Update eine Jeedom-Sicherung 
    durch.

-   **Plugins aktualisieren** : Ermöglicht Plugins im Update zu
    integrieren.

-   **Kern aktualisieren** : Ermöglicht Ihnen, den Jeedom-Kernel in das
    Update aufzunehmen.

<<<<<<< HEAD
-   **Zwangsbetrieb** : Führt das Update im erzwungenen Modus durch, das
    heißt, selbst wenn ein Fehler auftritt, fährt Jeedom fort und wird das Backup
    nicht wiederherstellen.
=======
-   **Mode forcé** : Effectue la mise à jour en mode forcé, c’est-à-dire
    que, même s’il y a une erreur, Jeedom continue et ne restaurera pas
    la sauvegarde. (Ce mode désactive la sauvegarde !)
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7

-   **Update wieder anwenden** : Ermöglicht es Ihnen, ein Update erneut zu
    installieren. (Hinweis : Nicht alle Updates können erneut angewendet werden.)

> **Wichtig**
>
>Vor der Aktualisierung wird Jeedom standardmäßig eine Sicherungskopie
> erstellen. Bei Problemen beim Anwenden eines Updates wird Jeedom
> automatisch die zuvor erstellte Sicherung wiederherstellen. Dieses Prinzip
> gilt natürlich nur für Jeedom Updates, nicht für Plugins.

> **Tipp**
>
> Sie können ein Update von Jeedom erzwingen, auch wenn es Ihnen nicht
> angeboten wird.

<<<<<<< HEAD
Die Tabelle der Aktualisierungen
---------------------------

Der Tabelle besteht aus zwei Registerkarten :

-   **Kern und Plugins** : Enthält die Basissoftware von Jeedom und 
    die Liste der installierten Plugins.
=======
Onglets Core et Plugins et l'onglet Autre
-----------------------------------------

Ces deux onglets similaires, secomposent d'un tableau :

-   **Core et Plugins** : Contient le logiciel de base de Jeedom (core) et la
    liste des plugins installés.
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7

-   **Andere** : Enthält Widgets, Skripte usw.

Hier finden Sie folgende Informationen: * **Status** : OK oder NOK. Zeigt den
aktuellen Status des Plugins an. * **Name** : Sie sehen die Quelle des
Elements, den Typ des Elements und seinen Namen. * **Version** : Gibt die
genaue Version des Elements an. * **Optionen** : Aktivieren Sie dieses
Kontrollkästchen, wenn das Element während des allgemeinen Updates
nicht aktualisiert werden soll (Schaltfläche **Updaten**).

> **Tipp**
>
<<<<<<< HEAD
> Für jede Tabelle können Sie in der ersten Zeile nach dem Status, den
> Namen oder der Version des vorhandenen Elemente filtern.
=======
> Pour chaque tableau, la première ligne permet de filter suivant
> le nom des éléments présents.
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7

In jeder Zeile können Sie  für jedes Element die folgenden Aktionen vdurchführen :

-   **Neu installieren** : Erzwingt eine Neuinstallation.

-   **Löschen** : Ermöglicht das Elemente zu löschen.

-   **Prüfen** : Überprüft die Update-Quelle, um herauszufinden, 
    ob ein neues Update verfügbar ist.

-   **Update** : Ermöglicht das Element zu aktualisieren (wenn ein 
    Update verfügbar ist).

-   **Änderungsprotokoll** : Bietet Zugriff auf die Liste der Änderungen der 
    Updates.

> **Wichtig**
>
<<<<<<< HEAD
> Wenn das Änderungsprotokoll leer ist, aber Sie noch ein Update haben,
> bedeutet dies, dass die Dokumentation aktualisiert wurde. Es ist daher
> nicht notwendig, vom Entwickler die Veränderungen zu verlangen, da es
> nicht unbedingt notwendig ist. (Dies ist oft ein Update der Dokumentations > Übersetzung.)
=======
> Si le changelog est vide mais que vous avez tout de même une mise à
> jour, cela signifie que c’est la documentation qui a été mise à jour.
> Il n’est donc pas nécessaire de demander au développeur les
> changements, vu qu’il n’y en a pas forcément. (c’est souvent une mise
> à jour de la traduction, de la documentation)
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7

> **Tipp**
>
> Beachten Sie, dass "core : jeedom" "Aktualisierung der Jeedom
> Kernsoftware" bedeutet.

<<<<<<< HEAD
Update in der Kommandozeile
=======
Onglet Logs
-----------

Onglet vers lequel vous êtes automatiquement basculé en cas d'installation
de mise à jour, il vous permet de suivre tout ce qui se passe durant la mise
à jour du core, comme des plugins.


Mise à jour en ligne de commande 
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7
================================

Es ist möglich, Jeedom direkt in SSH zu aktualisieren. Sobald die Verbindung
hergestellt ist, folgt der folgende Befehl :

    sudo php /var/www/html/install/update.php

Die möglichen Parameter sind :

-   **`mode`** : `force`, um ein Update im erzwungenen Modus zu starten (be
    rücksichtigt keine Fehler).

-   **`version`** : gefolgt von der Versionsnummer, um Änderungen von 
    dieser Version erneut anzuwenden.

<<<<<<< HEAD
Im Folgenden finden Sie eine Beispielsyntax für eine erzwungene
Aktualisierung durch erneutes Anwenden des Updates von Version 1.188.0 :
=======
Voici un exemple de syntaxe pour faire une mise à jour forcée en
réappliquant les changements depuis la 3.2.14 :
>>>>>>> 370b7e805d7368b83ea9dce02286fd4ec4f466d7

    sudo php  /var/www/html/install/update.php mode=force version=3.2.14

Achtung nach einem Update in der Komandozeile müssen Sie die Rechte an
den Jeedom Ordner erneut anwenden :

    chown -R www-data:www-data /var/www/html
