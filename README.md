# Documentation coverage

Here we use [Storybook](https://storybook.js.org/) and [Compodoc](https://compodoc.app/)

## Add Storybook:

1. npx storybook init
2. disable telemetry
   ".storybook/main.js
   core: {
   disableTelemetry: true, // 👈 Disables telemetry
   }"

## Add Compodoc:

1. npm install --save-dev @compodoc/compodoc
2. add tsconfig.doc.json
3. add "compodoc": "npx compodoc -p tsconfig.doc.json" to package.json scripts
