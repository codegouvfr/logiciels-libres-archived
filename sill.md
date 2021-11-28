---
title: Présentation du socle interministériel de logiciels libres
toc: false
---

# Table des matières

-   [Comment ajouter un logiciel libre dans le SILL ?](#comment-ajouter-un-logiciel-libre-dans-le-SILL)
-   [Les critères d’entrée d’un logiciel dans le SILL](#les-critres-dentre-dun-logiciel-dans-le-sill)
-   [Que signifie être « référent » d’un logiciel ?](#que-signifie-tre-rfrent-dun-logiciel)
-   [Les groupes MIM qui construisent le SILL](#les-groupes-mim-qui-construisent-le-sill)
-   [Présentations partagées dans les groupes MIM](#prsentations-partages-dans-les-groupes-mim)
-   [[Archive] Les documents de construction du SILL 2020](#orgdcb8fd9)
-   [Licence du SILL et de ce dépôt](#licence-du-sill-et-de-ce-dpt)

Le socle interministériel de logiciels libres (SILL) est le catalogue
de référence des logiciels libres recommandés par l’Etat.

Il est construit de façon collaborative par des communautés d’agents
informaticiens de la fonction publique d'État et de la fonction
publique hospitalière, ci-après « référents SILL ».

-   La page d'accueil du SILL : <https://sill.etalab.gouv.fr>
-   La page d'accueil des groupes MIM : [www.mim-libre.fr](https://www.mim-libre.fr/)

Pour toute question, écrire à [logiciels-libres@data.gouv.fr](mailto:logiciels-libres@data.gouv.fr) (le pôle
logiciels libres d'Etalab) ou à [mim-noyau@listes.etalab.gouv.fr](mailto:mim-noyau@listes.etalab.gouv.fr)
(l'équipe d'animation des groupes MIM.)


<a id="comment-ajouter-un-logiciel-libre-dans-le-SILL"></a>

# Comment ajouter un logiciel libre dans le SILL ?

**Attention**: pour qu’un logiciel entre dans le SILL, il faut qu’un agent
public se porte volontaire pour en être le *référent* et que le logiciel
corresponde bien aux critères d'entrée - voir ci-dessous pour ces deux
points.

Pour proposer un nouveau logiciel dans le SILL, envoyez un mail à
[sill-mainteneurs@groupes.renater.fr](mailto:sill-mainteneurs@groupes.renater.fr) en précisant :

-   de quel logiciel libre il s'agit ;
-   quel usage en est fait dans votre administration ;
-   le lien vers le code source et la licence ;
-   si vous acceptez d'en être le référent ;
-   quelle version minimale est recommandée.

Notez que si vous êtes une entreprise et que votre logiciel libre est
utilisé par une ou plusieurs administrations publiques, vous devrez
d'abord trouver dans cette administration un agent public volontaire
pour être le référent de votre logiciel.


<a id="les-critres-dentre-dun-logiciel-dans-le-sill"></a>

# Les critères d’entrée d’un logiciel dans le SILL


## Prérequis : le code source doit être publié sous licence libre sans délai entre le code source et la version exécutable

Le code source du logiciel doit être publié sous l'une des licences
libres reconnues par la [Free Software Foundation](https://www.gnu.org/licenses/license-list.fr.html) *et* l'[Open Source
Initiative](https://opensource.org/licenses).

La licence ne doit contenir aucun ajout ou modification risquant d'en
altérer le caractère libre.  En cas de doute sur une licence, le
groupe noyau qui coordonne l'ensemble du SILL est libre de refuser un
logiciel.

D'autre part, il ne doit y avoir aucun délai de publication entre le
code source et la version exécutable du logiciel.


## Deux critères obligatoires pour les logiciels recommandés

-   **Il existe un référent SILL**, un agent public de la fonction publique
    d'État ou hospitalière pour ce logiciel libre, qui accepte d'être
    inscrit à la liste `sill-mainteneurs@groupes.renater.fr`.

-   **Le logiciel est significativement utilisé** dans un organisme public
    de la fonction publique d'État ou hospitalière.  « Utilisé » veut
    dire que le logiciel est *installé* dans le système d'information ou
    sur des postes de travail des agents : les logiciels libres utilisés
    en *Software as a Service* par un prestataire ne sont pas éligibles à
    la recommandation dans le SILL, les prestataires ou éditeurs sont
    invités à les référencer dans le catalogue [GouvTech](https://catalogue.numerique.gouv.fr/).


## Plusieurs logiciels aux fonctionnalités similaires sont admissibles

Le SILL aide les administrations à s'y retrouver dans les logiciels
libres dont elles doivent considérer l'utilisation.

Plusieurs logiciels aux fonctionnalités similaires peuvent figurer
dans le SILL (voir par exemple ces [éditeurs de texte](https://sill.etalab.gouv.fr/fr/software?id=174), ou ces [systèmes
de gestion de contenus](https://sill.etalab.gouv.fr/fr/software?id=36)) : les référents SILL travaillent à faire
évoluer le SILL de façon à ce que ce catalogue aide à choisir entre
ces solutions multiples.


## D’autres informations optionnelles

D'autres informations sont accessibles aux référents SILL sans être
affichées publiquement :

-   Le logiciel est **mûr et actif** : la longévité est constatée, il y a de
    bonnes garanties sur la pérennité et il existe une communauté
    dynamique ainsi qu’une feuille de route.

-   Le logiciel est **performant**, il a une bonne couverture fonctionnelle
    par rapport au besoin.

-   Pour les outils de bureautique, le **logiciel est multiplateforme**.

-   Si pertinent, le **logiciel respecte des normes et des standards**,
    notamment ceux du [RGI](http://references.modernisation.gouv.fr/interoperabilite) et du [RGAA](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/).

-   Le logiciel propose des **facilités d'exploitation** : supervision,
    administration, configuration, sauvegarde, existence d'installeurs,
    d'outils de configuration et de déploiement.

-   Le logiciel est **adapté aux besoins des organismes publics** français :
    intégration dans les SI, traduction en français, besoins spécifiques
    aux grands comptes.

-   L’un des organismes publics utilisateur ayant un usage significatif
    du logiciel a **publié des informations sur cet usage**.


<a id="que-signifie-tre-rfrent-dun-logiciel"></a>

# Que signifie être « référent » d’un logiciel ?


## Vous souhaitez être référent ?

Pour cela, demandez à être inscrit sur la [liste de discussion des
référents](https://listes.etalab.gouv.fr/listinfo/sill-mainteneurs) en envoyant un mail à `logiciels-libres@data.gouv.fr`.


## Qui peut être « référent SILL » ?

Tout agent public travaillant dans un organisme public de la fonction
publique d'État ou hospitalière peut être référent d’un logiciel libre
dont il connaît l’usage au sein de son administration.


## Quels sont les tâches du référent ?

**Le référent :**

1.  atteste de l’usage d’un logiciel libre dans son administration ;
2.  collecte les informations pertinentes (de la version utilisée à des cas d’usage complets) sur le logiciel ;
3.  remonte ces informations aux mainteneurs du [dépôt SILL](https://git.sr.ht/~etalab/sill) géré par la DINUM - s’il peut, il met à jour ce dépôt directement ;
4.  participe une fois par an à l’une des réunions du groupe MIM pertinent (MIMO ou MIMDEVOPS) ;
5.  participe aux discussions entre mainteneurs sur la liste [sill-mainteneurs](https://groupes.renater.fr/sympa/info/sill-mainteneurs) ;
6.  cherche un référent pour le remplacer s’il vient à ne plus pouvoir être référent.

**Le référent n’est pas :**

-   un contact de support pour l’ensemble de l’administration ;
-   obligé de rester référent toute l’année ;
-   obligé de publier son identité ou delà du groupe des référents.


<a id="les-groupes-mim-qui-construisent-le-sill"></a>

# Les groupes MIM qui construisent le SILL

Le préfixe `MIM` signifie « Mutualisation interministérielle ».

Le SILL est rédigé par deux groupes : le groupe **MIMO** qui se consacre
aux outils de bureautique et le groupe **MIMDEVOPS** dédié aux outils de
développement et de production.

Chaque groupe se réunit en présentiel et échange régulièrement par
messagerie ; un groupe « noyau » assure la coordination de l'ensemble.


<a id="prsentations-partages-dans-les-groupes-mim"></a>

# Présentations partagées dans les groupes MIM

-   27/11/2019 (MIMO) : [Présentation Management Poste de travail](https://speakerdeck.com/bluehats/presentation-management-poste-de-travail)
-   27/11/2019 (MIMO) : [Firefox for Entreprise](https://speakerdeck.com/bluehats/firefox-for-enterprise)
-   27/11/2019 (MIMO) : [La gestion du poste de travail temps réel](https://speakerdeck.com/bluehats/la-gestion-du-poste-de-travail-temps-reel)
-   27/11/2019 (MIMO) : [Nextcloud - Le cloud alternatif aux GAFAM](https://speakerdeck.com/bluehats/nextcloud-le-cloud-alternatif-aux-gafam)


<a id="orgdcb8fd9"></a>

# [Archive] Les documents de construction du SILL 2020

Les documents de construction du SILL 2020 sont disponibles via
l'espace de partage <https://groupes.mim-libre.fr>.  Si vous êtes
référent, vous pouvez obtenir un compte sur cet espace.

Une fois connecté sur cet espace, les documents de préparations sont
accessibles ici :

-   [MIMO](https://cloud.mim-libre.fr/apps/files/?dir=/Partage%20MIM/MIMO/SILL&fileid=10858)
-   [MIMDEV](https://calc.mim-libre.fr/MIMDEV/edit)
-   [MIMPROD](https://calc.mim-libre.fr/MIMPROD/edit)


<a id="licence-du-sill-et-de-ce-dpt"></a>

# Licence du SILL et de ce dépôt

Le SILL est publié par les groupes de mutualisation interministérielle
sous [licence Ouverte 2.0](https://github.com/etalab/Licence-Ouverte/blob/master/LO.md).

Ce dépôt est publié sous [licence Ouverte 2.0](https://github.com/etalab/Licence-Ouverte/blob/master/LO.md).

