# Conventions

- GroupId en `org.webjars`&nbsp;: construit à façon via un projet Maven, notamment pour pouvoir gérer la déclaration de dépendances transitives (e.g. `org.webjars:Bootstrap` qui dépend de `org.webjars:popper.js`) et d'autres subtilités avancées,
- GroupId en `org.webjars.npm`&nbsp;: provient directement d'un packaging automatique via http://www.webjars.org d'une lib issue de https://www.npmjs.com.

Convention de nommage plus détaillée sur la page d'accueil de http://www.webjars.org.