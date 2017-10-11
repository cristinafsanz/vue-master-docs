# vue-master-docs

Repositorio creado a partir de la [demo de Jose Dongil](https://github.com/jdonsan/charla-aprendiendo-vuejs) y la [guía](https://github.com/cristinafsanz/vuejs-primeros-pasos) que hice a partir de ella.

El propósito del repositorio es cambiar Webpack para generar los ficheros de producción en la carpeta /docs y habilitar GitHub Pages para que lo publique desde ese directorio.

## Instrucciones:

- Se han cambiado las rutas en config/index.js: 

    index: path.resolve(__dirname, 'index.html'),
    assetsRoot: path.resolve(__dirname, 'docs'),
    assetsSubDirectory: 'static',
    assetsPublicPath: '/vue-master-docs/docs/',

- npm install

- npm run build