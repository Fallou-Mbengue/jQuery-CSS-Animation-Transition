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
