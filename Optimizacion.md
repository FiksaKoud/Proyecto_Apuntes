# Optimización del código
La **optimización de código** es el proceso de mejorar un programa para que sea más eficiente, sin alterar su funcionalidad. Esto puede implicar hacerlo más rápido, consumir menos memoria, reducir el uso de CPU, o hacerlo más legible y mantenible

---

## Hediondez del código

- También llamado **code smell** en inglés.
- Es un síntoma en el código fuente que indica posiblemente un problema más profundo.
- Usualmente no son bugs (errores de ejecución): no impiden que el programa funcione, pero...
- Indican deficiencias en el diseño que pueden:
  - Ralentizar el desarrollo.
  - Aumentar el riesgo de errores o fallos a futuro.
- Son una razón importante para realizar refactorización.
- [Leer más en Wikipedia](https://es.wikipedia.org/wiki/Hediondez_del_c%C3%B3digo)

---

## Análisis de código

### Tipos:

- **Análisis dinámico**: mediante pruebas unitarias (unit tests).
- **Análisis estático**: mediante linters (analizadores de código sin ejecutar el programa).

---

## Análisis estático de código

- Uso de analizadores estáticos llamados **linters**.
- También puede hacerse desde plataformas online de inspección continua (**Continuous Inspection**).
- Recurso: [GitHub: Introducción a los linters (en inglés)](https://github.com/mcandre/linters)

---

## Linters (Analizadores estáticos)

| Lenguaje    | Linter             |
|-------------|--------------------|
| C           | `lint`             |
| Java        | `sonar`            |
| JavaScript  | `JSLint`, `ESLint` |

---

## Continuous Inspection / Continuous Analysis

### Plataformas populares de inspección de código:

#### Scrutinizer

- Soporta PHP, Python y Ruby.
- 14 días de prueba gratuita.
- **Precios (Dic. 2017):**
  - Basic: 49 € / mes
  - Professional: 99 € / mes
  - Unlimited: 199 € / mes

---

#### SonarQube


- Soporta más de 20 lenguajes.
- **Precios (Dic. 2017):**
  - Open Source: 0 $
  - Private Projects: Desde 5 $ / mes

---

## Refactorización

- Reestructuración del código sin cambiar su comportamiento externo.
- Mejora la legibilidad, mantenibilidad y escalabilidad.
- Técnicas comunes:
  - Renombrar variables.
  - Extraer funciones para eliminar duplicación.
  - Eliminar código inalcanzable.
  - Eliminar redundancias.
  - Eliminar código muerto.

---

