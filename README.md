# Modèle de dépôt Github pour les standards CNIG

> [!IMPORTANT]
> **Attention** : Le modèle de fichier README débute après ce paragraphe. Dans la suite,
>
> * toutes les consignes en citation, comme cette ligne, doivent être supprimées,
> * tout ce qui est <mark>_surligné_</mark> doit être remplacé.
>
> Vous trouverez l'ensemble des consignes et conseils pour utiliser ce modèle de dépôt sur [cette page de la documentation](https://app.gitbook.com/o/w6D6SnLwCXQaMMSzcTvp/s/weZQRU1RV5So9WzNyxlW/~/changes/19/la-fabrique-des-standards/realisation-du-standard/utiliser-le-modele-de-depot-github). 

---
<!-- Supprimer les trois tirets précédents (qui insèrent une ligne) -->

# Standard Plan départemental des itinéraires de promenade et de randonnée (PDIPR)

Dépôt des documents et travaux du groupe de travail pour la création du standard PDIPR.

<!-- Indiquer le nom du standard à la place de <mark>_Nom_</mark>. Le texte entre les balises "<mark>_" et "_</mark>" apparaît en italique surligné et doit être remplacé dans ce modèle -->

> _Insérer une description du standard et des données concernées en quelques lignes. Ici comme dans la suite, il est recommandé de réutiliser le contenu du mandat du GT ou d'autres documents déjà rédigés. Voici plusieurs exemples pour vous inspirer dans la rédaction :_
>
> * _[standard des opération d'aménagement](https://github.com/cnigfr/schema-operations-amenagement/)_
> * _[standard risques](https://github.com/cnigfr/Geostandards-Risques)._
>
> _Afin de clarifier la lecture de cette description sur le site schema.data.gouv, préciser ici lorsque le standard n'est pas accompagné d'un schéma sur schema.data.gouv:_
>
> [!TIP]
> Ce standard CNIG ne possède pas de schéma de données directement accessible sur schema.data.gouv.fr. 

Davantage de documentation peut être trouvée sur [le site du CNIG](https://cnig.gouv.fr/groupe-de-travail-plans-departementaux-des-a30072.html#H_Introduction).

> Insérer une (ou plusieurs) image(s) pour illustrer la thématique en remplaçant le logo du CNIG ci-dessous.  
<!-- Pour remplacer le logo du CNIG, suivre le modèle "![texte alternatif](lien vers l'image) Les images peuvent être chargées sur le dépôt Github dans un dossier image -->
![logo du CNIG à remplacer par l'image du standard](https://cnig.gouv.fr/IMG/png/cnig2022_geolocalise-petit.png)

## Présentation
Le Groupe de travail a pour objectif de la création d'un standard de données du PDIPR.
Le projet de standard est disponible ici.

## Contexte

Le Plan départemental des itinéraires de promenade et de randonnée (PDIPR) a pour objectif, dans chaque département de France, de protéger les chemins ruraux et d’assurer la continuité des itinéraires ouverts à la randonnée pédestre. Il s’agit d’une compétence départementale obligatoire. Ce plan est établi par le département, après avis des communes intéressées. Il est inclus dans le plan départemental des espaces, sites et itinéraires relatifs aux sports de nature (PDESI).

En 2019, 74 départements étaient engagés dans une démarche PDIPR et une quarantaine de jeux de données PDIPR existent aujourd’hui sur data.gouv.fr, sans que ceux-ci soient homogènes dans leur construction.

## Cadre juridique

[Code de l’environnement  - art. L361-1](https://www.legifrance.gouv.fr/codes/id/LEGIARTI000045212099/2022-02-23) - Modifié par [LOI n°2022-217 du 21 février 2022 - art. 105](https://www.legifrance.gouv.fr/loda/id/LEGIARTI000045199115/2022-02-23)

> ### _Ce que dit la loi :_
> * _Le département établit, après avis des communes intéressées, un plan départemental des itinéraires de promenade et de randonnée._
> * _Les itinéraires inscrits à ce plan peuvent emprunter des voies publiques existantes, des chemins relevant du domaine privé du département ainsi que les emprises de la servitude destinée à assurer le passage des piétons sur les propriétés riveraines du domaine public maritime en application de [l'article L. 121-31 du code de l'urbanisme](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000031210502). Les itinéraires inscrits à ce plan peuvent emprunter les emprises de la servitude de marchepied mentionnée à [l'article L. 2131-2 du code général de la propriété des personnes publiques](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000031065981). Ils peuvent également, après délibération des communes concernées, emprunter des chemins ruraux et, après conventions passées avec les propriétaires intéressés, emprunter des chemins ou des sentiers appartenant à l'Etat, à d'autres personnes publiques ou à des personnes privées. Ces conventions peuvent fixer les dépenses d'entretien et de signalisation mises à la charge du département._
> * _Tout acte emportant la disparition d'un chemin rural susceptible d'interrompre la continuité d'un itinéraire inscrit sur le plan départemental des itinéraires de promenade et de randonnée doit, à peine de nullité, comporter soit le maintien, soit le rétablissement de cette continuité par un itinéraire de substitution. Toute opération publique d'aménagement foncier doit également respecter ce maintien ou cette continuité._
> * _La circulation des piétons sur les voies et chemins inscrits au plan départemental des itinéraires de promenade et de randonnée, ou ceux identifiés pour les chemins privés, après conventions passées avec les propriétaires de ces chemins, par les communes et les fédérations de randonneurs agréées s'effectue librement, dans le respect des lois et règlements de police et des droits des riverains._
> * _Les maires, en vertu de leur pouvoir de police, peuvent, le cas échéant, réglementer les conditions d'utilisation de ces itinéraires._


## Objectif

Création d'un standard de données national afin de :
*	inventorier les itinéraires de randonnée,
*	harmoniser les pratiques entre territoires,
*	faciliter la gestion et la valorisation des données.


## Cas d’usage

> _Présenter ici quelques cas d'usage de données conformes au schéma. Ces cas peuvent exister ou être fictifs._

## Organisation du dépôt

* Le dossier [documentation](documentation) contient les documents utiles pour les utilisateurs du standard ;
* Le dossier [ressources](ressources) contient les documents utiles pour les utilisateurs du standard ;
* Le dossier [groupe_de_travail_CNIG](groupe_de_travail_CNIG) contient les comptes-rendus de réunions et les documents de suivi du groupe de travail ;
* Le dossier [standard](standard) contient le standard ainsi que les documents qui lui sont liés ;
* Le dossier [data_set_PDIPR_Opendata](jeux de données PDIPR - Opendata) contient les jeux de données PDIPR disponibles en Opendata ;

> _A supprimer en l'absence de schéma JSON :_

* Le dossier [schéma](schéma) contient le schéma ainsi que les documents qui lui sont liés.

## Modalités de production des données

> _Dans le cas où la création du standard interviendrait alors que les données sont déjà produites, documenter ici comment leur production a lieu. Dans le cas contraire, cette partie peut être supprimée._

### Données ouvertes

> _Dans le cas où les données sont publiées en open data, sinon, cette partie peut être supprimée._

Les données relatives à <mark>_la thématique_</mark> sont ouvertes et sont à la disposition de tous. Elles seront publiées sur <https://www.data.gouv.fr>

## Informations et participation au groupe de travail

### Méthodologie

> _Cette partie peut être laissée telle quelle. Elle vise à expliquer les modalités d'adoption d'un standard par le CNIG._

La méthodologie des groupes de travail du CNIG repose sur une diversité d'approches complémentaires :

* Construire **une gouvernance ouverte** à l'ensemble des parties prenantes, afin de susciter l’adhésion et de créer le cadre favorable à la pérennité du dispositif ;
* Promouvoir et exploiter **les retours d'expériences** afin d'étudier les diversités d'usages et embarquer les acteurs en les positionnant au centre du processus d’alimentation des référentiels géographiques ;
* Privilégier **l’interopérabilité** entre système d'informations à l’échelle nationale pour favoriser le partage et l’échange de données : éviter les doubles stockages, doubles saisies, etc. ;
* S'appuyer sur les **processus éprouvés** de [standardisation du CNIG](http://cnig.gouv.fr/les-standards-cnig-a18959.html#Etapes-de-creation-d-un-Standard-CNIG) et de modélisation suivant [schema.data.gouv.fr](https://guides.etalab.gouv.fr/producteurs-schemas/).
L’objectif est d'aboutir à terme à un consensus qui se traduise en un standard et un modèle de donnée commun pour la thématique considérée.

### Actualisation

> _Préciser ici la phase d'avancement dans laquelle se trouve le standard selon la terminologie de [la Fabrique des standards](https://guides.data.gouv.fr/guides-de-data.gouv.fr/fabrique-des-standards/la-fabrique-des-standards) (rédaction, validation, déploiement, etc.). Il peut être utile de donner des éléments de calendrier comme la date de passage en commission des standards ou devant le conseil plénier._
> _Indiquer également les évolutions prévues ou prévisibles du standard (en fonction des évolutions réglementaires, des retours des utilisateurs, etc.), ainsi que les évolutions prévues pour les bases de données, logiciels, API, etc. concernées par le standard._

Le projet de standard <mark>_thématique_</mark>, puis le standard une fois validé par le CNIG, évoluera en fonction des évolutions réglementaires et de l'expression des besoins de la communauté des utilisateurs.

Les ressources associées et les bases de données correspondantes seront actualisées conformément au standard CNIG <mark>_thématique_</mark>. Les mises à jour de base de données sont effectuées en modifiant le cas échéant les données qui y figurent déjà.

### Comment contribuer

> _Indiquer ici comment contribuer au standard. Par exemple :_
Vous pouvez contribuer au standard en créant une issue sur cette page (il s'agit d'une fonctionnalité permettant de poser une question, de faire une remarque, une suggestion etc. directement sur github, ce qui en informe automatiquement les responsables du dépôt).

### Nous contacter

Pour contacter le GT CNIG <mark>_thématique_</mark>, écrire à l’adresse cnig[at]cnig.fr.

### Licence

Les travaux du GT CNIG <mark>_thématique_</mark> sont réalisés sous [Licence Ouverte Etalab 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/).
