# Proyecto DevOps - Evaluación Parcial 1

## Integrante: Carlos Moil Alvarado

La finalidad de este repositorio es implementar un flujo de trabajo
colaborativo y automatizado.

## Estrategia de Ramificación

Se decidió utilizar el método Trunk-Based Development ya que:

- Es recomendado para proyectos de corto alcance y pocos archivos (como es este caso).
- Permite trabajar de manera simple, ágil y directa sobre la rama `main`.

### Convenciones de Commits

- Mensajes claros y en tiempo real.
- Prefijos según el tipo de cambio:

  - `feat:` → para nuevas funcionalidades.
  - `hot:` → para correcciones.
  - `docs:` → documentación.

## Flujo de Merge

- Se trabaja en las ramas `feature/ejemplo` o `hotfix/ejemplo`.
- Se realiza Pull Request hacia `develop`.
- Al tener una versión estable, se hace Pull Request desde `develop`
  hacia `main`.

## Naming de Ramas

- `feature/ejemplo` → nuevas características.
- `hotfix/ejemplo` → correcciones urgentes.

## Estrategias de Revisión

- Todos los cambios pasarán por Pull Request.
- Cada Pull Request debe ser revisado antes de hacer merge.

## Declaración uso de IA

Se utilizó ChatGPT para corregir errores de indentación en archivos `.md` 
y mejorar la redacción de los documentos.

## Reflexión individual

Este proyecto fue muy entretenido, ya que me permitió entender mejor 
el uso de comandos en Git y la gestión de ramas. 

Aprendí la importancia de trabajar con versiones controladas y de no realizar 
cambios directamente a la rama principal. 
Además, reforcé buenas prácticas en la documentación 
y el flujo de trabajo colaborativo.

