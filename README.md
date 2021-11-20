# How to create monorepo with npm Workspaces

Guide from: https://ruanmartinelli.com/posts/npm-7-workspaces-1

# Resume
```shell
# Ejecutar npm run en todos los packages
npm run test --workspaces
npm run test -ws
# Ejecutar run test solo en el package-a 
npm run test --workspace package-a
# instalar el package-b en el package-a
npm i package-b  --workspace package-a
# instalar lodash en el package-a
npm i lodash --workspace package-a
```
