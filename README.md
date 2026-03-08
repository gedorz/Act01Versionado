[![Demo CI](https://github.com/gedorz/Act01Versionado/actions/workflows/demo.yml/badge.svg)](https://github.com/gedorz/Act01Versionado/actions/workflows/demo.yml)

## 	Enlace al repositorio de GitHub: https://github.com/gedorz/Act01Versionado

## 	** Explicación breve del flujo de trabajo seguido **

## 1️⃣ Inicialización del repositorio
Se creó un repositorio público en GitHub y se realizó el primer commit con el archivo `README.md`.  
Posteriormente, se añadió la carpeta `evidencias` para documentar todo el proceso realizado durante la práctica.

## 2️⃣ Protección de la rama `main`
Se configuró la protección de la rama `main` con una regla con el mismo nombre
para evitar commits directos.  
Todos los cambios se integraron mediante **Pull Requests**, garantizando un flujo de trabajo controlado y profesional (en este caso no se agrego aprobadores).

## 3️⃣ Trabajo con ramas *feature*
Se crearon ramas independientes para cada funcionalidad:

- `feature/gitignore`
- `feature/suma`
- `feature/resta`
- `feature/ci`

Cada funcionalidad se desarrolló siguiendo el proceso 
sugerido en la actividad y manuales, realizando commits cortos y descriptivos.
se intento hacer siguiendo las buenas prácticas de versionado.

## 	** Descripción de cómo se produjo y resolvió el conflicto e Breve explicación del funcionamiento del workflow de GitHub Actions **

## 1️⃣ Gestión y resolución de conflictos
Se simuló un conflicto entre las ramas `feature/suma` y `feature/resta`.  
El conflicto se resolvió manualmente integrando todas las funciones en el archivo `operations.py`.  
Se documentó el historial utilizando `git log --oneline --graph --all`.

## 2️⃣ Integración continua con GitHub Actions y workflow
Se creó un workflow manual con el nombre de **Demo CI**, que se ejecuta mediante `workflow_dispatch`.  
El workflow recibe como parámetro el nombre y apellidos y los muestra en consola durante su ejecución.  
Se verificó su correcto funcionamiento desde la pestaña **Actions** del repositorio.
Se agregó las correspondientes evidencias. 


**Autor**
German Dario Realpe Zambrano
19/02/2026 al 9/03/2026  Creación de repositorio Github