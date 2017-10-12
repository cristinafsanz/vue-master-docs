# vue-master-docs

Repositorio creado a partir de la [demo de Jose Dongil](https://github.com/jdonsan/charla-aprendiendo-vuejs) y la [guía](https://github.com/cristinafsanz/vuejs-primeros-pasos) que hice a partir de ella.

El propósito del repositorio es cambiar Webpack para generar los ficheros de producción en la carpeta /docs y habilitar GitHub Pages para que lo publique desde ese directorio.

## Instrucciones:

- El artículo [Documenting your VueJS project with Github pages](http://blog.toast38coza.me/documenting-your-vuejs-project-with-github-pages/) lo explica muy bien:

	- Editar config/index.js y cambiar ../dist a ../docs.

	- Cambiar assetsPublicPath: assetsPublicPath: './'

	- npm install

	- npm run build

- Se habilita GitHub Pages en /docs.

- El resultado se puede ver en https://cristinafsanz.github.io/vue-master-docs/.
