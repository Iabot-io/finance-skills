---
name: contribution-margin-analysis
description: Calcular márgenes comparables separando costes variables, asignaciones y efecto de devoluciones. En IAbot.io, asígnala a un empleado de análisis económico y aporta ventas netas, costes, devoluciones y criterio de asignación.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Finanzas y control de gestión
---

# Analizar márgenes por producto o servicio

## Uso en IAbot.io

Asigna esta skill a **un empleado de análisis económico** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta ventas netas, costes, devoluciones y criterio de asignación.

**Ejemplo de encargo:** «Calcula el margen de estas líneas y deja visibles los costes comunes que se han repartido.»

**Resultado a revisar:** Tabla de márgenes con definición de coste, fórmula y limitaciones.

## Cuándo usarla y qué necesita

Calcular márgenes comparables separando costes variables, asignaciones y efecto de devoluciones

Trabaja con ventas netas, costes, devoluciones y criterio de asignación. Usa hojas de cálculo, exportaciones contables y supuestos aprobados. Los cálculos no ejecutan pagos, inversiones ni decisiones de financiación.

## Procedimiento

1. Define la unidad analizada y el significado de cada margen antes de calcular.
2. Concilia ventas netas, descuentos y devoluciones con el periodo de costes.
3. Clasifica costes con el criterio aportado y muestra por separado las asignaciones comunes.
4. Calcula margen en importe y porcentaje con bases consistentes, identificando datos faltantes.
5. Compara productos o servicios solo con la misma definición y alcance de coste.

## Comprobación del resultado

- No se denomina beneficio neto a un margen parcial.
- Los costes asignados no se duplican entre líneas.
- El denominador de cada porcentaje está documentado.

## Entrega

Tabla de márgenes con definición de coste, fórmula y limitaciones.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Banco de España, Central de Balances](https://www.bde.es/wbe/es/areas-actuacion/estadisticas/central-balances/)
- [Finanzas para Todos](https://www.finanzasparatodos.es/)
