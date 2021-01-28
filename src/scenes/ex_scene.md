Dans le dossier scenes, il y a des assemblages de composant pour créer des views, c’est-à-dire un ensemble d’éléments (balises JSX, composants réutilisables, …) qui forment une page. Une scène est généralement accessible par une unique route.

Comme précédemment, il est possible que ces scènes aient besoin d’un composant qui sera non réutilisable, dans ce cas il peut vivre dans un dossier components à l’intérieur d’une scène. Comme, dans l’exemple suivant, où notre scène Index, qui correspond à la page d’accueil, est la seule à avoir une barre latérale.

EX: components/
    scenes/
        Index/
            components/
                Sidebar/
                    Sidebar.js      
                    Sidebar.scss
                Index.js
                Index.scss
        Login/
            Login.js
            Login.scss
        NotFound/
            NotFound.js
            Notfound.scss
        Unauthorized/
            Unauthorized.js
            Unauthorized.scss
