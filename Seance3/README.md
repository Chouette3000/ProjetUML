# UML SEANCE 3 : Diagramme de classes

## À quoi sert le Diagramme de classes ?
<p>Le diagramme de classe représente le comportement d’une classe et les relations entre les classes</p>
<p>une classe est un modèle qui permet de fabriquer des objets partageant les mêmes états (attributs) et comportements (méthodes)</p>
<p>Ce diagramme est utile pour les design pattern et pour cette raison, il est beaucoup utilisée en ingénierie logicielle orientée objet</p>
<h2>Comment passer du diagramme de cas d’utilisation au diagramme de classe ? </h2>
<p>On part du diagramme de cas d'utilisation. En effet, pour pouvoir réaliser le diagramme de classe, il faut analyser la description du cas
d’utilisation, c'est ce texte qui permettra de trouver les classes à faire apparaitre sur le diagramme. Ainsi, un verbe correspondra souvent à une
méthode, un chiffre ou une valeur sera souvent un attribut. (Tandis qu'une logique ou un acteur sera une classe.)
<h2> Notation UML pour les classes</h2>
<p>En UML, une classe comprend 3 parties : </p>
<ul>
<li>le nom de la classe</li>
<li>les attributs</li>
<li>les méthodes</li>
</ul>

<h2>Visibilités</h2>
<p>les méthodes et attributs peuvent avoir différents niveaux d'accessibilité (appelés visibilités) : </p>

<table>
<tr>
<td>+</td>
<td>public : accessible de partout</td>
</tr>
<tr>
<td>#</td>
<td>protected : accessible uniquement depuis la classe contenante ou les classes filles</td>
</tr>
<tr>
<td>-</td>
<td>private : accessible uniquement par la classe contenante</td>
</tr>

</table>

<p>Par défaut, en Kotlin, tout est public (pas nécessaire de le préciser) </p>

<h2>Relations entre les classes</h2>
<p>Les classes peuvent avoir plusieurs types de relations, notamment</p>

<table>
<tr>
<td>l'Association</td>
<td><img src="../img/association.png" alt="association"></td>
</tr>
<tr>
<td>l'Héritage (Généralisation et Spécialisation)</td>
<td><img src="../img/heritage.png" alt="heritage"></td>
</tr>
<tr>
<td>l'Agrégation</td>
<td><img src="../img/agregation.png" alt="agregation" ></td>
</tr>
<tr>
<td>la Composition </td>
<td><img src="../img/composition.png" alt="compositon"></td>
</tr>
<tr>
<td>la Dépendance</td>
<td><img src="../img/dependance.png" alt="dependance"></td>
</tr>
</table>
<p>Les relations peuvent être unidrectionnelle ou birectionnelle mais, il est préférable de se limiter à un seul sens (relation unidirectionnelle)</p>

<h2>Diagramme de classe du domaine (énoncé Sens Critique)</h2>

<img src="../img/diagDomaine.png" alt="diagramme de classe" >