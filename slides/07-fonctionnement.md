# Comment ça marche&nbsp;?

- S'appuie très simplement sur le mécanisme de **chargement de ressources à partir du classpath**,
- Intégré à certains frameworks pour permettre le chargement via des URL raccourcies (exemple Spring Boot&nbsp;: `/webjars/**` est mappé sur `classpath:/META-INF/resources/webjars`),
- Possibilité d'[omettre la version précise de la lib dans les URL](https://www.webjars.org/documentation#springboot) des resources avec `webjars-locator-core` (e.g. `href='/webjars/bootstrap/css/bootstrap.min.css'` au lieu de `href='/webjars/bootstrap/3.1.0/css/bootstrap.min.css'`),
- **Attention&nbsp;:** Les dépendances transitives sont récupérées automatiquement dans le projet, mais doivent être spécifiées explicitement dans la page Web (e.g. nécessité de charger les ressources Bootstrap & Popper pour que Boostrap fonctionne).