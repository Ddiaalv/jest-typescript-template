# Typescript + Jest

Plantilla muy básica para crear rápidamente un entorno de desarrollo orientado a ejecutar tests mediante TS y Jest.

## Tecnologías

| Nombre                                                 | Detalles                                                                   |
| ------------------------------------------------------ | -------------------------------------------------------------------------- |
| 🌐[Typescript](https://www.typescriptlang.org/)        | Lenguaje de programación                                                   |
| 👁️[ESlint](https://eslint.org/)                        | Linter para controlar errores en nuestro código                            |
| 🦋[Prettier](https://prettier.io/)                     | Formatea nuestro código                                                    |
| 🧪[Jest](https://jestjs.io/)                           | Framework de testing                                                       |
| 🐺[Husky](https://www.npmjs.com/package/husky)         | Comprueba errores en nuestro código para evitar errores en nuestros commit |
| 🚫[Lint-staged](https://github.com/okonet/lint-staged) | Ejecuta los linters para evitar errores antes de hacer un commit           |
| 🧾[Hygen](https://www.hygen.io/)                       | Generador de código                                                        |

## Scripts de npm

| Comando      | Detalles                                                                   |
| ------------ | -------------------------------------------------------------------------- |
| `ts:watcher` | Ejecuta el watcher del compilador de Typescript                            |
| `lint`       | Comprueba errores de sintaxis                                              |
| `format`     | Formatea nuestro código TS                                                 |
| `test`       | Ejecuta test                                                               |
| `precommit`  | Comprueba si hay errores en los staged changes antes de realizar un commit |
| `new:f`      | Genera una carpeta con una funcción y un test para ésta                    |
