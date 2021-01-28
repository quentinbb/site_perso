Dans le dossier services, on définit tous les services de notre application comme api, security, stores…

EX: src/
        components/
        scenes/
        services/
            security/
                hasRoles.js
                isAuth.js
            stores/
                themeStore.js

Nous aurions également pu y mettre notre fichier de configuration des routes mais nous avons préféré le mettre à la racine du dossier src car il s’agit d’un élément central dans notre application et il sera plus aisé de le positionner à la racine de notre projet.