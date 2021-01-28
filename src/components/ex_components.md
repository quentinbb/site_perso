Le dossier component contient tous les coposants réutilisables.

-> regroupera les fichier lié au menu :
EX: components/
        Menu/
            Menu.js
            Menu.css
            Menu.test.js



Si le composant Menu est composé de plusieurs composants MenuItem qui ne sont pas réutilisables dans toute l’application mais seulement dans le composant Menu, alors:
EX: components/
        Menu/
            components/
                MenuItem/
                    MenuItem.js
                    MenuItem.css
                    MenuItem.test.js
        Menu.js
        Menu.css
        Menu.test.js

Ainsi la règle de la structure est qu’un composant à la racine du dossier components est réutilisable dans toute l’application mais les composants enfants d’un composant(MenuItem) sont utilisables seulement par le composant parent (Menu).