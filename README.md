# TrabajoColaborativo
Trabajo colaborativo del funcionamiento de github para el uso de proyectos
# Proyecto Calculadora Simple

## Integrantes:
- Gomez Aitana
- Granda Paula
- Guaña Karla
- Palacios Aaron

## Descripción:
Proyecto base para simular trabajo colaborativo con ramas en Git.

Cada integrante trabajará en su propia rama para agregar una función.

## Funciones asignadas:

- Karla: suma
- Paula: resta
- Aaron: multiplicación
- Aitana: división

---

## Flujo de trabajo recomendado:

1. Cada integrante crea su rama desde main:
   - git checkout -b karla-feature
   - git checkout -b Paula-feature
   - git checkout -b Aaron-feature
   - git checkout -b Aitana-feature

2. Cada uno modifica `main.c` para agregar su función y la llamada en `main()`.

3. Hacen al menos 2 commits por integrante con mensajes claros.

4. Suben su rama al remoto: `git push origin <tu-rama>`

5. Desde main, se van fusionando las ramas con `git merge <rama>`.

6. En caso de conflicto, se resuelve manualmente en `main.c`.

7. Finalmente, se sube el `main` actualizado al remoto.
