# Concepts avancés

- [Chargement possible des ressources via RequireJS](https://jamesward.com/2014/02/19/official-support-for-requirejs-in-webjars/) avec `RequireJS.getSetupJavaScript`, helper fourni par `webjars-locator`. Peu documenté, et les essais ne sont pas toujours couronnés de succès…
- Chargement depuis un CDN [jsDelivr](http://www.jsdelivr.com/) en préfixant l'URL avec `//cdn.jsdelivr.net/webjars/{groupId}` (e.g. `/webjars/jquery/2.1.0/jquery.js` → `//cdn.jsdelivr.net/webjars/org.webjars/jquery/2.1.0/jquery.js`).