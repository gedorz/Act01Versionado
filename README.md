[![Demo CI](https://github.com/gedorz/Act01Versionado/actions/workflows/demo.yml/badge.svg)](https://github.com/gedorz/Act01Versionado/actions/workflows/demo.yml)

## 	** 7.1.	Enlace al repositorio de GitHub: https://github.com/gedorz/Act01Versionado **

## 	** 7.2.	Explicación breve del flujo de trabajo seguido **

## Inicialización del repositorio

Se crea un repositorio con acceso público en GitHub web y se realiza el primer commit con el archivo README.md después se añade a la carpeta ‘evidencias’ para documentar el proceso realizado.

## Protección de la rama `main`

Se crea una configuración para protección de la branch ‘main’ agregando una regla de validación con el nombre de ‘main’ en la misma rama, esto evita que se pueda hacer commit directo sobre la rama ‘main’, de esta forma todos los cambios futuros se integraran mediante **Pull Requests**, garantizando un flujo de trabajo controlado, en este caso no se agregó aprobadores.

## Trabajo con ramas *feature*
Se crearon ramas independientes para cada funcionalidad:

- `feature/gitignore [Se agrega configuración para .log y cache de pyton]`
- `feature/suma [se agrega dos funciones info y suma]`
- `feature/resta [se agrega dos funciones info y resta]`
- `feature/ci [se agrega un workflow simple de nombre y apellido]`

Cada funcionalidad se desarrolló siguiendo el proceso sugerido en la actividad y manuales, realizando varios commit cortos y descriptivos. se intentó hacer siguiendo las buenas prácticas de versionado

## 	** 7.3.	Descripción de cómo se produjo y resolvió el conflicto. **

## Gestión y resolución de conflictos
Se simula un conflicto entre las ramas [feature/suma] y [feature/resta] agregando una idéntica función llamada info() en las dos ramas. 
El conflicto se resolvió editando el código manualmente y manteniendo todas las funciones en el mismo archivo operations.py. 
Se documentó el historial utilizando el comando ‘git log --oneline --graph –all’ y colocando en un archivo de eivdencias del tipo txt.

## ** 7.4.	Breve explicación del funcionamiento del workflow de GitHub Actions
Se creó un workflow de ejecución manual con el nombre de ‘Demo CI’, el cual crea una maquina Ubuntu para luego ejecutar una instrucción de comado **echo** todo esto es controlado de forma manual mediante un workflow_dispatch que es ejecutado desde github basado en la configuración de un archivo yml. 
El workflow recibe como parámetro el nombre y apellidos y posteriormente se muestra en la consola durante su ejecución, se verificó su correcto funcionamiento desde la pestaña ‘Actions’ del repositorio. 
Se agregó las correspondientes evidencias de texto como de imagenes.

## Integración continua con GitHub Actions y workflow
Se creó un workflow manual con el nombre de **Demo CI**, que se ejecuta mediante `workflow_dispatch`.  
El workflow recibe como parámetro el nombre y apellidos y los muestra en consola durante su ejecución.  
Se verificó su correcto funcionamiento desde la pestaña **Actions** del repositorio.
Se agregó las correspondientes evidencias. 

**Autor**
German Dario Realpe Zambrano
19/02/2026 al 9/03/2026  Creación de repositorio Github