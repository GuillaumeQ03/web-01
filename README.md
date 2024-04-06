## RENDU FINAL TP WEB - Guillaume QUINTIN & Augustin DENIS

### Question 1 :
Le fichier package-lock.json sert à conserver une trace de l'arbre des dépendances de l’application.

### Question 2 :
Version sémantique.

### Question 3 :
Une devDependency définissent les dépendances utilisées uniquement lors du développement. La différence avec une dépendance classique est que les devDependencies ne sont pas nécessaires pour l'exécution du code en production.

### Question 4 :
Une closure est une fonction JavaScript auto-exécutante qui encapsule le contexte dans lequel elle est définie. Elle était utilisée pour créer des scopes privés avant l'introduction des modules dans ES6. Les modules ES6 ont remplacé en grande partie l'utilisation des closures pour cet usage.

### Question 5 :
`import * from './utils'` importe toutes les fonctions et objets exportés par le module utils, tandis que `import { parseUrl } from './utils'` importe seulement la fonction `parseUrl` depuis le module utils. Importer tout le module peut entraîner un surcroît de poids et d'exécution.

### Question 6 :
En Java classes, la surcharge d'opérateurs et les destructeurs ne sont pas possibles, tandis qu'en ES6 classes, ils le sont.

### Question 7 :
let permet de déclarer des variables dont la portée est limitée à celle du bloc dans lequel elles sont déclarées.  var permet de définir une variable globale ou locale à une fonction.

### Question 8 :
`.bind(this)` permet de définir la valeur de this pour une fonction. Si vous supprimez `.bind(this)`, le contexte de `this` sera déterminé par la manière dont la fonction est appelée. Les fonctions fléchées en ES6 capturent le contexte lexical, donc `.bind(this)` n'est généralement pas nécessaire lors de leur utilisation.

### Question 9 :
Le symbole "@" dans "@babel/***" signale un décorateur Babel..

### Question 10 :
Les avantages des Promises est la gestion plus propre des opérations asynchrones, la facilité de composition des opérations asynchrones.

### Question 11 :
ECMAScript 2017 (ES8).

### Question 12 :
La programmation orientée composant pour le web est plus maintenable grâce à la réutilisabilité des composants.

### Question 13 :
La programmation fonctionnelle est un paradigme de programmation basé sur le concept de fonctions pures.

### Question 14 :
La fonction map() applique une fonction à chaque élément d'un tableau et retourne un nouveau tableau contenant les résultats de l'application de cette fonction.

### Question 15 :
La fonction filter() crée un nouveau tableau contenant uniquement les éléments d'un tableau qui satisfont à une condition spécifique définie dans une fonction de filtrage.

### Question 16 :
La fonction reduce() applique une fonction de réduction à chaque élément d'un tableau pour réduire le tableau à une seule valeur.

### Question 17 :
`.then()` est utilisé pour gérer les promesses de manière asynchrone en JavaScript, tandis que l'async/await permet d'écrire du code asynchrone de manière plus synchrone avec `async` et `await`.

### Question 18 :
Le préfixe `_` sur un fichier Sass indique souvent qu'il s'agit d'un fichier partiel qui ne sera pas compilé individuellement en CSS.
