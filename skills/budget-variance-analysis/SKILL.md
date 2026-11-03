---
name: budget-variance-analysis
description: Comparar presupuesto y realidad explicando diferencias de alcance, volumen, precio y calendario. En IAbot.io, asígnala a un empleado de control de gestión y aporta presupuesto, datos reales, mapa de cuentas y criterio de periodificación.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Finanzas y control de gestión
---

# Analizar desviaciones presupuestarias

## Uso en IAbot.io

Asigna esta skill a **un empleado de control de gestión** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta presupuesto, datos reales, mapa de cuentas y criterio de periodificación.

**Ejemplo de encargo:** «Explica las desviaciones de este trimestre y separa hechos demostrados de hipótesis pendientes.»

**Resultado a revisar:** Informe por partida con desviaciones, evidencia y acciones propuestas.

## Cuándo usarla y qué necesita

Comparar presupuesto y realidad explicando diferencias de alcance, volumen, precio y calendario

Trabaja con presupuesto, datos reales, mapa de cuentas y criterio de periodificación. Usa hojas de cálculo, exportaciones contables y supuestos aprobados. Los cálculos no ejecutan pagos, inversiones ni decisiones de financiación.

## Procedimiento

1. Alinea periodos, moneda, unidades y mapa de cuentas entre presupuesto y datos reales.
2. Calcula desviaciones absolutas y porcentuales, tratando por separado bases cero o negativas.
3. Descompón efectos de volumen, precio, mezcla y calendario solo cuando los datos permiten hacerlo.
4. Relaciona explicaciones con evidencia y conserva hipótesis que aún necesitan confirmación.
5. Prioriza revisiones por materialidad acordada y presenta acciones sin modificar el presupuesto aprobado.

## Comprobación del resultado

- Las partidas conciliadas suman el total del origen.
- Una diferencia temporal no se presenta como ahorro permanente.
- Los porcentajes con base cero no se calculan como cifras normales.

## Entrega

Informe por partida con desviaciones, evidencia y acciones propuestas.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Banco de España, Central de Balances](https://www.bde.es/wbe/es/areas-actuacion/central-balances/)
- [Finanzas para Todos](https://www.finanzasparatodos.es/)
