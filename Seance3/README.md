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
<th>Relation</th>
<th>Contexte</th>
<th>Représentation UML</th>
</tr>
<tr>
<td>Association</td>
<td>Une instance d'une classe utilise une instance d'autre classe</td>
<td><img src="../img/association.png" alt="association"></td>
</tr>
<tr>
<td>Héritage (Généralisation et Spécialisation)</td>
<td>Une classe hérite d'une autre (dispose au moins des mêmes attributs et méthodes)</td>
<td><img src="../img/heritage.png" alt="heritage"></td>
</tr>
<tr>
<td>Agrégation</td>
<td>Une classe contient une autre classe mais la durée de vie du contenu n'est pas lié à celle du contenant</td>
<td><img src="../img/agregation.png" alt="agregation" ></td>
</tr>
<tr>
<td>Composition </td>
<td>Une classe contient une autre classe et le celle contenue est détruit en même temps que celle contenante</td>
<td><img src="../img/composition.png" alt="compositon"></td>
</tr>
<tr>
<td>Dépendance</td>
<td>Une classe a besoin d'une autre à un moment donné (ex: lors de l'exécution d'une méthode précise)</td>
<td><img src="../img/dependance.png" alt="dependance"></td>
</tr>
</table>
<p>Les relations peuvent être unidrectionnelle ou birectionnelle mais, il est préférable de se limiter à un seul sens (relation unidirectionnelle)</p>

<h2>Diagramme de classe du domaine (énoncé Sens Critique)</h2>
<p>En analysant le diagramme de UC, voici le diagramme de classe de domaine que nous avons produit. </p>

<img src="../img/diagDomaine.png" alt="diagramme de classe" >

<h2>Conclusion de la séance</h2>
<p>Ce diagramme est utile pour modéliser les classes nécessaires au système et les relations entre ces 
classes. Il permet également de comparer les classes pour pouvoir optimiser le codage en utilisant 
au mieux l'orienté objet : modéliser des classes abstraites en utilisant l'héritage, réflechir au type de relation le plus adéquat etc.
</p>
