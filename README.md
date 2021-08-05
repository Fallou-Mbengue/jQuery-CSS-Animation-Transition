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

