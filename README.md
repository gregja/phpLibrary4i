# PhpLibrary4i
Documentations PHP pour développeurs IBM i

Ce dossier contient plusieurs documents au format PDF, que j'ai publiés sous licence libre (CC BY NC SA).

Ce sont des documents que j'ai rédigés entre les années 2009 et 2022, et dans lesquels je traite de l'utilisation du langage PHP en environnement IBM i. Chacun de ces documents traite d'un sujet un peu différent, ils se complètent donc plutôt bien.

Vous noterez que le tout premier document de la liste est le seul à avoir bénéficié d'une véritable mise à jour en 2022. Les autres documents sont là plus à titre d'archive, mais ils peuvent être utiles aux développeurs PHP qui ont besoin de comprendre l'écosystème IBM i.

- Livre_blanc_PHP_IBMi_v3.pdf

        Réactualisation en avril 2022 d'un dossier publié initialement sur le site foothing.net (c'était en 2009)
        J'explique dans ce dossier comment utiliser PHP avec DB2 for i, à partir d'un stack PHP situé en dehors de l'IBM i (via une connexion ODBC)
        De nombreux changements intervenus dans les écosystèmes PHP et IBM i rendaient nécessaires une mise à jour de ce document qui pourra, je l'espère, rendre service aux développeurs IBM i amenés à utiliser PHP.

- PHP-et-DB2_Bonnes-pratiques.pdf

        Slide que j'ai présenté lors d'un colloque IBM en avril 2012.
        Contrairement au document précédent, je me focalise dans ce slide sur l'utilisation de PHP à partir d'un stack PHP fonctionnant sur IBM i (sur un stack Zend Server for i).
        Ce mode d'utilisation implique d'utiliser un connecteur DB2 différent de celui évoqué dans le document précédent. 
        Notez que ce document n'a pas fait l'objet d'une réactualisation aussi poussée que le 
        précédent, aussi certains points évoqués en 2012 ne sont plus forcément aussi pertinents en 2022.


- MacaronDB_documentation.pdf

        Documentation du projet MacaronDB
        [https://github.com/gregja/macaronDB](https://github.com/gregja/macaronDB)
        J'avais développé le projet MacaronDB après avoir constaté la difficulté à porter du code PHP d'un stack PHP hors IBM i, vers un stack PHP sur IBM i. Cette difficulté était inhérente au fait que le connecteur DB2 n'était pas le même selon l'environnement d'exécution des scripts PHP. 
         

- MacaronDB_PHP_Toolbox_for_CRUD.pdf

        Slide d'un webinar présenté en partenariat avec Zend France en juin 2012
        Complétant dans une certaine mesure le sujet présenté chez IBM en avril 2012, ce slide m'avait permis de présenter le projet MacaronDB, et d'introduire la notion de CRUD (Create-Read-Update-Delete), avec un exemple à la clé.

- PHPNews_ZendServer_ZRay.pdf

        Slide que j'ai présenté lors d'un colloque IBM en mai 2015. Je présentais plusieurs sujets dans le cadre de ce slide : 
            - nouveautés Zend Server V7 et V8, 
            - arrivée prochain de PHP 7, 
            - utilisation des procédures stockées DB2 externes, 
            - PHP Toolkit, 
            - Process DevOps (CI/CD), 
            - Projet Apigility,
            - etc.

Pour compléter votre information sur l'écosystème IBM i, et en particulier sur la base de données DB2 for i, je vous invite à vous reporter à mon autre dépôt Github, dédié à ce sujet :

[https://github.com/gregja/SQLMasters](https://github.com/gregja/SQLMasters)

