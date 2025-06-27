---
description: Este procedimiento está diseñado para que un agente de inteligencia artificial pueda analizar recursivamente una función en un código fuente y sus dependencias, identificando posibles vulnerabilidades de seguridad.
---

## Instrucciones para Analizar una Función en Busca de Vulnerabilidades

1. *Identificación Inicial:*
   - *Entrada de la Función:* Recibe como entrada la firma de la función a analizar.
   - *Repositorio de Código:* Asegúrate de tener acceso al repositorio completo donde reside la función a analizar.

2. *Extracción de Dependencias:*
   - *Recorrido del Código:* Identifica todas las llamadas a funciones y metodologías relacionadas dentro de la función dada.
   - *Recursividad:* Para cada función llamada, analiza su definición y extrae de manera recursiva sus dependencias y llamadas a otras funciones.

3. *Análisis de Código:*
   - *Revisión de Vulnerabilidades Comunes:*
     - Inyección de SQL
     - Cross-Site Scripting (XSS)
     - Inyecciones de código
     - Desbordamiento de búfer
     - Manipulación de autenticación y autorización
   - *Patrones Seguros:* Busca la presencia de controles de seguridad como sanitización de entradas, uso de bibliotecas seguras, etc.

4. *Generación de Informes:*
   - *Resumen de Hallazgos:* Genera un informe detallado de las vulnerabilidades detectadas, clasificadas por severidad.
   - *Recomendaciones:* Ofrece recomendaciones sobre cómo podrían mitigarse los problemas de seguridad identificados.

5. *Revisión Manual y Validación:*
   - Sugiere una revisión manual por parte de un experto en seguridad para validar los hallazgos e interpretar contextos específicos donde la IA podría tener limitaciones.