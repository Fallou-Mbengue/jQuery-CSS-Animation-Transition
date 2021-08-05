# jQuery-CSS-Animation-Transition
Atelier 12 : jQuery-CSS-Animation-Transition
1. Que signifie le DOM ? Comment est-il organisé ?

Le Document Object Model (en français modèle d'objets de document), abrégé en DOM, est une interface de programmation normalisée permettant de structurer des documents HTML et XML. ... En raison de la forme de cette structure, cette manière de représenter un projet Web est appelé un DOM-tree (arbre DOM en français).

2. Quelles sont les méthodes permettant d’accéder aux éléments du DOM ?

- document.getElementById(ID)(S'ouvre dans une nouvelle fenêtre)
- Syntax : 
var element = document.getElementById(id);

- document.getElementsByClassName(nomDeClasse)
- Syntax : 
var elements = document.getElementsByClassName(names); // or:
var elements = rootElement.getElementsByClassName(names);

- document.getElementsByTagName(nomDeBalise)
- Syntax : 
var elements = document.getElementsByTagName(name);

- document.querySelector(selecteurCSS)
- Syntax : 
element = document.querySelector(selectors);

- document.querySelectorAll(selecteurCSS)
- Syntax : 
elementList = parentNode.querySelectorAll(selectors);

3. Quels sont les événements en JQuery ? Les événements de Windows ?
- Définition : 
jQuery est la bibliothèque JavaScript la plus utilisée et vous permet de créer des effets dynamiques sur vos pages web comme des changements de couleur, des animations, et des effets de fondu.
Ces méthodes vont porter le nom de l’événement auquel elles réagissent comme 
- click(), 
- mouseenter(), 
- keyup(), 
- change(), etc. et sont en fait des notations raccourcies de la méthode jQuery on() qui va nous permettre de gérer plusieurs événements au sein d’une même fonction gestionnaire d’événements.

4. Quelles sont les méthodes permettant de charger le Javascript et le JQuery ?  et c’est quoi la spécialité de chaque méthode ? 

Pour appeler du code JavaScript depuis votre document HTML, vous aurez besoin de l'élément <script>. Il y a deux méthodes pour utiliser script : une qui sert lorsqu'on souhaite utiliser un script contenu dans un fichier tiers et une qui sert lorsqu'on intègre directement le code du script dans la page web.

Faire référence à un script externe
Généralement, un script est écrit dans un fichier .js à part. Pour exécuter un script depuis un fichier dans la page web, il suffira d'utiliser <script> avec un attribut src pointant vers le fichier du script en utilisant l'URL du fichier :

<script src="chemin/vers/le/script.js"></script>

5. Comment associer un événement à un élément HTML avec Javascript et avec JQuery ? 
La façon la plus simple d’accéder à un élément dans un document va être de la faire en le ciblant avec le sélecteur CSS qui lui est associé.

Deux méthodes nous permettent de faire cela : les méthodes querySelector() et querySelectorAll() qui sont des méthodes du mixin ParentNode et qu’on va pouvoir implémenter à partir des interfaces Document et Element.

La méthode querySelector() retourne un objet Element représentant le premier élément dans le document correspondant au sélecteur (ou au groupe de sélecteurs) CSS passé en argument ou la valeur null si aucun élément correspondant n’est trouvé.

La méthode querySelectorAll() renvoie un objet appartenant à l’interface NodeList. Les objets NodeList sont des collections (des listes) de nœuds.

L’objet NodeList renvoyé est une liste statique (c’est-à-dire une liste dont le contenu ne sera pas affecté par les changements dans le DOM) des éléments du document qui correspondent au sélecteur (ou au groupe de sélecteurs) CSS spécifiés.

Pour itérer dans cette liste d’objets NodeList et accéder à un élément en particulier, on va pouvoir utiliser la méthode forEach(). Cette méthode prend une fonction de rappel en argument et cette fonction de rappel peut prendre jusqu’à trois arguments optionnels qui représentent :

L’élément en cours de traitement dans la NodeList ;
L’index de l’élément en cours de traitement dans la NodeList ;
L’objet NodeList auquel forEach() est appliqué.
Par ailleurs, notez que les deux interfaces Document et Element implémentent leurs méthodes querySelector() ou querySelectorAll() qui vont donc produire des résultats différents selon qu’on les utilise avec des objets de Document ou de Element.

Lorsqu’on utilise querySelector() ou querySelectorAll() avec un objet Document, la recherche se fait dans tout le document. Lorsqu’on utilise l’une de ces méthodes à partir d’un objet Element, la recherche se fait parmi les descendants de l’élément sur lequel on appelle la méthode en question.
  

