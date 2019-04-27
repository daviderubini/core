Le sous-menu Gestion des plugins permet de manipuler les plugins, à
savoir : les télécharger, les mettre à jour et les activer,etc.​

Plugin de gestión
===================

Puede acceder a la página de complementos de gestión de plugins →
plugins. Una vez que se hace clic, la lista de encontrar
plugins en orden alfabético y un enlace para el mercado. plugins
personas con discapacidad se atenúan.

> **Tip**
>
> Al igual que en muchos lugares en Jeedom, poner el ratón mientras la izquierda
> Para que aparezca un menú de acceso rápido (se puede
> Su perfil en dejar la siempre visible). A continuación, el menú
> Para obtener la lista de plugins ordenados por categorías.

En cliquant sur un plugin, vous accédez à sa configuration. En haut, vous
retrouvez le nom du plugin, puis entre parenthèses, son nom dans Jeedom
(ID) et enfin, le type de version installée (stable, beta).

> **Important**
>
> Lors du téléchargement d’un plugin, celui-ci est désactivé par défaut.
> Il faut donc que vous l’activiez par vous-même.

Arriba a la derecha, un par de botones:

-   ** ** Documentación: Permite el acceso directo a la página
    documentación para plugins

-   ** ** Cambios: Para ver el plugin si hay cambios

-   ** ** Enviar en el mercado: enviar el plugin en el mercado
    (Sólo está disponible si usted es el autor)

-   ** ** Detalles: recupera la página del plugin en el mercado

-   **Supprimer** : Supprime le plugin de votre Jeedom. Attention, cela
    También elimina de forma permanente todas las instalaciones de este plugin

Abajo a la izquierda, hay una zona estado con :

-   ** ** Estado: muestra el estado del plugin (activo / inactivo)

-   ** ** Versión: la versión del plug-in instalado

-   **Acción** : Permite activar o desactivar el plugin

-   **Versión Jeedom** : Versión Jeedom mínima requerida
    para el funcionamiento del plugin

-   **Licence** : Indique la licence du plugin qui sera généralement
    AGPL

A droite, on retrouve la zone Log et surveillance qui permet de définir 

-   le niveau de logs spécifique au plugin (on retrouve cette même possibilité dans
Administation → Configuration sur l’onglet logs, en bas de page)

-   de ver los logs del plugin

-   Heartbeat : toutes les 5 mins, Jeedom regarde si au moins un équipement du plugin a communiqué dans les X dernières minutes (si vous voulez désactiver la fonctionnalité, il suffit de mettre 0)

-   Redémarrer démon : si le Heartbeat tombe en erreur alors Jeedom va redémarrer le démon

Si le plugin possède des dépendances et/ou un démon, ces zones
supplémentaires s’affichent sous les zones citées ci-dessus.

Dependencias :

-   **Nombre** : normalmente será local

-   **Statut** : vous dira si les dépendances sont OK ou KO

-   **Instalación**: instalará o reinstalará los
    dépendances (si vous ne le faites pas manuellement et qu’elles sont
    KO, Jeedom s’en chargera de lui-même au bout d’un moment)

-   **Dernière installation** : date de la dernière installation des
    dependencias

Daemon :

-   ** Nombre** : normalmente será local

-   **Estado**: le dirá si el deamon es OK o KO

-   **Configuration** : sera OK si tous les critères pour que le démon
    tourne sont réunis ou donnera la cause du blocage

-   **(Re)Démarrer** : permet de lancer ou relancer le démon

-   **Parar**: permite detener al deamon (solamente en el caso de
    la gestión automática está desactivada)

-   **Gestión automática** : permite de activar o desactivar la gestión
    automatique (ce qui permet à Jeedom de gérer lui même le démon et le
    relancer si besoin. Sauf contre indication, il est conseillé de
    dejar la gestión automática activa)

-   **Dernier lancement** : date du dernier lancement du démon

> **Tip**
>
> Certains plugins ont une partie configuration. Si tel est le cas, elle
> apparaîtra sous les zones dépendances et démon décrites ci-dessus.
> Dans ce cas, il faut se référer à la documentation du plugin en
> question pour savoir comment le configurer.

En dessous, on retrouve une zone fonctionnalités. Celle-ci permet de voir
si le plugin utilise une des fonctions core Jeedom tel que :

-   **Interac** : interacciones específicas

-   **Cron**: un cron por minuto

-   **Cron5** : un cron cada 5 minutos

-   **Cron15** : un cron cada 15 minutos

-   **Cron30** : un cron cada 30 minutos

-   **CronHourly** : un cron cada hora

-   **CronDaily** : un cron diario

> **Tip**
>
> Si le plugin utilise une de ces fonctions, vous pourrez spécifiquement
> lui interdire de le faire en décochant la case "activer" qui sera
> présente à côté.

Enfin, on peut retrouver une section Panel qui permettra d’activer ou
désactiver l’affichage du panel sur le dashboard ou en mobile si le
plugin en propose un.

Instalación de un plugin

Pour installer un nouveau plugin, il suffit de cliquer sur le bouton
"Market" (et que Jeedom soit relié à Internet). Après un petit temps de
chargement, vous obtiendrez la page.

> **Tip**
>
> Vous devez avoir saisi les informations de votre compte du Market dans
> l’administration (Configuration→Mises à jour→Onglet market) afin de
> retrouver les plugins que vous avez déjà achetés par exemple.

En la parte superior de la ventana, tienes filtros:

-   **Gratuit/Payant** : permet d’afficher uniquement les gratuits ou
    los de pago.

-   **Oficial/Aconsejado** : permite mostrar solamente los plugins
    oficiales o recomendados

-   **Instalado/No instalado** : permite mostrar solamente los plugins
    instalados o no instalados

-   **Menu déroulant Catégorie** : permet d’afficher uniquement
    algunas categorías de plugins

-   **Rechercher** : permet de rechercher un plugin (dans le nom ou la
    descripción de este)

-   **Nom d’utilisateur** : affiche le nom d’utilisateur utilisé pour la
    connexion au Market ainsi que le statut de la connexion

> **Tip**
>
> La petite croix permet de réinitialiser le filtre concerné

Une fois que vous avez trouvé le plugin voulu, il suffit de cliquer sur
celui-ci pour faire apparaître sa fiche. Cette fiche vous donne beaucoup
d’informations sur le plugin, notamment :

-   S’il est officiel/recommandé ou s’il est obsolète (il faut vraiment
    evitar la instalación de plugins obsoletos)

-   4 acciones :

    -   **Instalar estable** : permite instalar el plugin en su
        versión estable

    -   **Installer beta** : permet d’installer le plugin dans sa
        versión beta (solo para probadores beta)

    -   **Installer pro** : permet d’installer la version pro (très
        poco utilizado)

    -   **Supprimer** : si le plugin est actuellement installé, ce
        botón permite borrarlo

En dessous, vous retrouvez la description du plugin, la compatibilité
(si Jeedom détecte une incompatibilité, il vous le signalera), les avis
sur le plugin (vous pouvez ici le noter) et des informations
complémentaires (l’auteur, la personne ayant fait la dernière mise à
jour, un lien vers la doc, le nombre de téléchargements). Sur la droite
vous retrouvez un bouton "Changelog" qui vous permet d’avoir tout
l’historique des modifications, un bouton "Documentation" qui renvoie
vers la documentation du plugin. Ensuite vous avez la langue disponible
et les diverses informations sur la date de la dernière version stable.

> **Importante**>>
 No es recomendable poner un plugin beta en
>> Jeedom no beta, muchos problemas operativos pueden aparecer

>> **Importante**
>
> Algunos plugins son de pago, en este caso será indicado en la pagina de presentación del plugin que os propondrá comprarlo.
>> Una vez hecho esto, tienes que esperar mas o menos diez minutos (tiempo de validación del pago), luego tienes que regresar en  la pagina de presentación del plugin para instalarlo normalmente.

> **Consejo**
>>
> También puedes agregar un plugin a Jeedom desde un archivo o
> desde un repositorio Github. Para ello, es necesario, en la configuración de
> Jeedom, activar la función apropiada en la sección "Actualizaciones y
> archivos". Entonces, poniendo el ratón
> a la izquierda y mostrando el menú de la página plugin, de hacer un clic
> en "Agregar desde otra fuente". A continuación, puedes elegir la > fuente "Archivo". Atención, si agregas un archivo zip, el nombre de este zip debe ser el mismo que el ID del plugin y desde >  la apertura del ZIP en una carpeta plugin\_info debe ser presente.
