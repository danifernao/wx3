# Vitrina de proyectos

Este repositorio contiene el _build final_ de varios proyectos web. El código fuente de cada proyecto está alojado en repositorios independientes. El objetivo de este repositorio es centralizar las versiones listas para producción y facilitar su despliegue mediante Netlify.

## Despliegue automático

Cada vez que uno de los repositorios fuente se actualiza, se dispara un GitHub Action que ejecuta el proceso de _build_ del proyecto y envia (_push_) el resultado a este repositorio. Netlify detecta los cambios en este repositorio y despliega automáticamente la nueva versión. Este flujo garantiza que las versiones públicas siempre estén actualizadas.

## Proyectos incluidos

| Repositorio fuente                                               | Demostración                                                    |
| ---------------------------------------------------------------- | --------------------------------------------------------------- |
| [/danifernao/aniguess](https://github.com/danifernao/aniguess)   | [wx3.netlify.app/aniguess](https://wx3.netlify.app/aniguess/)   |
| [/danifernao/sudoku](https://github.com/danifernao/sudoku)       | [wx3.netlify.app/sudoku](https://wx3.netlify.app/sudoku/)       |
| [/danifernao/stopwatch](https://github.com/danifernao/stopwatch) | [wx3.netlify.app/stopwatch](https://wx3.netlify.app/stopwatch/) |
