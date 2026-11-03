---
name: cash-flow-forecast
description: Preparar previsiones de caja distinguiendo compromisos, estimaciones y escenarios. En IAbot.io, asígnala a un empleado de tesorería y aporta saldos, vencimientos, cobros, pagos previstos y supuestos del negocio.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Finanzas y control de gestión
---

# Previsión de tesorería

## Uso en IAbot.io

Asigna esta skill a **un empleado de tesorería** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta saldos, vencimientos, cobros, pagos previstos y supuestos del negocio.

**Ejemplo de encargo:** «Prepara una previsión semanal de caja a trece semanas y marca las semanas con datos incompletos.»

**Resultado a revisar:** Previsión de caja con saldo inicial, movimientos, saldo final y supuestos.

## Cuándo usarla y qué necesita

Preparar previsiones de caja distinguiendo compromisos, estimaciones y escenarios

Trabaja con saldos, vencimientos, cobros, pagos previstos y supuestos del negocio. Usa hojas de cálculo, exportaciones contables y supuestos aprobados. Los cálculos no ejecutan pagos, inversiones ni decisiones de financiación.

## Procedimiento

1. Fija fecha de corte, cuentas, moneda y saldo conciliado; no sumes transferencias internas como ingresos nuevos.
2. Distribuye cobros y pagos por fecha prevista distinguiendo vencimiento contractual y expectativa.
3. Separa partidas comprometidas, recurrentes y estimadas y conserva fuente de cada supuesto.
4. Calcula saldo final por periodo y escenarios con cambios explícitos de plazo o importe. Si falta un tipo de cambio, conserva la partida en su moneda y etiqueta el agregado convertido como parcial; no presentes ese subtotal como caja final completa.
5. Entrega necesidades potenciales de caja y datos pendientes sin ejecutar movimientos financieros.

## Comprobación del resultado

- Saldo final de un periodo coincide con el inicial del siguiente.
- Las transferencias internas no duplican caja consolidada.
- Los escenarios mantienen las mismas unidades y moneda.

## Entrega

Previsión de caja con saldo inicial, movimientos, saldo final y supuestos.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Banco de España, Central de Balances](https://www.bde.es/wbe/es/areas-actuacion/central-balances/)
- [Finanzas para Todos](https://www.finanzasparatodos.es/)
