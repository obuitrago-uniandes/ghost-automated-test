# RIPuppet
Una librería NodeJS para GUI Ripping en aplicaciones web.

## Pasos para ejecutar

1. Configure el archivo `config.json` teniendo en cuenta la siguiente información:

| Campo | Descripción |
| -- | -- |
| url | La url donde se encuentra el administrador de ghost Tenga en cuenta que los selectores están configurados para la versión 3.41.1 |
| headless | Activar el modo headless |
| depthLevels | Nivel de profundidad |
| inputValues | Si se activa el ingreso de valores de entrada específicos |
| values | un objeto con los valores de entrada para los identificadores dados (aqui coloque las credenciales de acceso a ghost) |
| browsers | un arreglo de los navegadores para realizar la prueba |

2. Abra un terminal al mismo nivel de este readme instale las dependencias

```shell
npm install
```

3. Luego ejecute el GUI Ripping con 

```shell
node index.js
```

