---
description: Revisión de cambios en código (`git diff`)
---

Hola, tengo un archivo de diferencias que contiene el resultado de `git diff`, con los cambios recientes introducidos a mi código. Quiero que lo analices como si fueras un revisor técnico senior o un lintern de calidad de software con criterio amplio. Te pido que:

---

## Análisis de buenas prácticas

- Verificá si el código respeta principios como **KISS**, **DRY**, **YAGNI**, **SOLID** y otras buenas prácticas del lenguaje correspondiente.
- Identificá patrones de diseño correctos o mal implementados.

---

## Calidad del código

- Evaluá la **legibilidad** general: claridad de lógica, estructura, modularidad, cohesión y separación de responsabilidades.
- Señalá oportunidades claras de **refactorización**: simplificación de lógica, extracción de funciones, reducción de duplicación, etc.
- Indicá si hay **comentarios innecesarios, faltantes o mal usados**.

---

## Errores y problemas potenciales

- Detectá **errores lógicos, omisiones, edge cases no contemplados o condiciones mal manejadas**.
- Indicá cualquier comportamiento que podría generar **bugs en tiempo de ejecución**.

---

## Performance

- Identificá problemas de **ineficiencia algorítmica** o mal uso de estructuras de datos.
- Comentá si hay operaciones innecesarias en loops, consultas redundantes, accesos repetidos a recursos costosos, etc.

---

## Seguridad

- Buscá posibles **vulnerabilidades**, como manejo inseguro de datos, sanitización insuficiente, uso de funciones inseguras o exposición de información sensible.
- Si corresponde, señalá prácticas inseguras en manejo de errores, autenticación/autorización o dependencias externas.

---

## Mantenibilidad y escalabilidad

- Evaluá si el código puede **escalar bien** o si podría generar **deuda técnica**.
- Comentá si hay señales de **acoplamiento excesivo** o falta de abstracción que dificulten su evolución.

---

## Testing

- Señalá si faltan **tests unitarios, de integración o de regresión** para los cambios introducidos.
- Identificá **casos borde** que no parecen estar contemplados.
- Sugerí, si aplica, qué tests serían convenientes agregar.

---

## Nomenclatura

- Observá si los nombres de **variables, funciones, clases o archivos** son descriptivos, consistentes y en inglés.
- Sugerí nombres más claros si encontrás alguno ambiguo o genérico.

---

## Formato de respuesta

- Estructurá tu respuesta por secciones si lo considerás conveniente.
- Usá ejemplos concretos o fragmentos del diff para fundamentar tus observaciones.
- En caso de cambios triviales, podés agrupar comentarios. En casos críticos, sé detallado.

---

Analizá el contenido completo del archivo antes de responder, incluso si es extenso.  
El objetivo es obtener una revisión exhaustiva y de alto valor técnico.  
¡Gracias!
