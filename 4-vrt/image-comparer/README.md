# Instrucciones para ejecutar el comparador de imágenes

## Requisitos

* Haber ejecutado todas las pruebas de Kraken y cypress sobre las 2 versiones de Ghost 5.47.0 y 3.41.1

## Herramientas usadas:
| Programa                        | Versión            |
| ------------------------------- | ------------------ |
| npm                             | 6.14.18            |
| Node                            | 14.21.3            |
| Windows                         | 11                 |
| Ubuntu                          | 22.04              |

## Pasos para la ejecución
1. Abra una consola o terminal y ubíquese en la carpeta donde se encuentra este readme
2. Ejecute 
```shell
npm install
```
3. Ejecute el siguiente comando
```shell
node index.js ../Ghost_5.47.0 ../Ghost_3.41.1
```
Tenga en cuenta que el comando puede variar si no usa sistemas basados en unix a

```shell
node index.js ..\Ghost_5.47.0 ..\Ghost_3.41.1
```
