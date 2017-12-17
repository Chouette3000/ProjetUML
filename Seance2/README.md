# UML SEANCE 2 : Diagramme de cas d'utilisation

## Qu'est ce qu'un diagramme de cas d'utilisation ?

<p>Le diagramme de cas d’utilisation permet de déterminer les services rendus par le système aux utilisateurs.</p>
<p>Il définit les différents acteurs et leurs interactions avec le système. Les acteurs externes sont également définis.</p>
<p>Les acteurs peuvent être des personnes physiques mais également ou d’autres systèmes ou ressources.</p>

<h2>Description du cas d'utilisation</h2>
<p>Un cas d’utilisation correspond à un service rendu par le système</p>
<p>Il est important de faire la description du cas d'utilisation pour l'analyse et la réalisation d'autres diagrammes (diagramme de séquence etc.)</p>
<p>La description explique les différentes étapes que contient le cas d'utilisation</p>
<p>Pour chaque cas d’utilisation, il y a plusieurs scénarii possibles : </p>
<ul>
<li>Scénario nominal : Déroulement normal</li>
<li>Scénarios alternatifs : Déroulement différent du scénario nominal</li>
<li>Scénario d'exception : Déroulement lorsqu'une erreur se produit</li>
</ul>

## Sens Critique

<p>Plusieurs énoncés ont été proposé et l'énoncé "Sens critique" a été choisi</p>
<p>Ce système permet à des utilisateurs de pouvoir noter et émettre une critique sur des films et séries</p>

<h2>Réponses aux question relatives à l'énoncé</h2>
<p><b>1. Quels sont les acteurs ?</b></p>
<p>Administrateur, Critiqueur et utilisateur</p>
<p><b>2. Quelles sont les relations entre les acteurs ?</b></p>
<p>Il y a plusieurs relations d'héritage : "Critiqueur" hérite d’ "utilisateur", et "administrateur" hérite de "critiqueur".</p>

<p><b>Quels sont les cas d'utilisation ?</b></p>
<p>Voir le diagramme correspondant (plus bas)</p>
<p><b>Que peut faire un administrateur</b></p>
<p>Il peut gérer les critiqueurs et mettre en avant des oeuvres</p>
<p><b>Quels acteurs interviennent dans ces différents cas d'utilisation ?</b></p>
<p>Sur le diagramme, les acteurs intervenant dans un cas d'utilisation sont reliés à celui-ci par une flèche, (voir diagramme plus bas)</p>
<p><b>Que visualise le cadre autour des cas d'utilisation?</b></p>
<p>Ce cadre représente le système</p>
<p><b>Qu'exprime les cardinalités?</b></p>
<p>Elles expriment le nombre minimal et maximal d'instance dans une classe</p>
<p><b>A quoi sert un diagramme de cas d'utilisation ?</b></p>
<p>Il sert à représenté les services rendus par le systèmes aux différents acteurs</p>

## Diagramme de cas d'utilisation

<p>à partir de cet énoncé, voici le diagramme de cas d'utilisation réalisé : </p>
<img src="../img/diagUc.svg" alt="useCase">

## Conclusion de la séance

<p>Cette séance a permis de revoir les diagrammes de cas d'utilisation en théorie et en pratique sur 2 énoncés car nous avons débuté avec l'énoncé
donné en exemple <a href="https://mbf-iut.i3s.unice.fr/doku.php?id=2016_2017:s2:td:td_use_cases">ici</a> avant de réaliser celui de sens critique</p>
<p>Il faut faire attention au sens des flèches <i><b>"include"</i></b> et <i><b>"extend"</i></b> car il aisé de les confondre</p>