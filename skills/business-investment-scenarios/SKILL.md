---
name: business-investment-scenarios
description: Comparar inversiones operativas mediante escenarios y sensibilidad de supuestos documentados. En IAbot.io, asígnala a un empleado de planificación financiera y aporta alternativas, desembolsos, flujos previstos, horizonte y criterios de evaluación.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Finanzas y control de gestión
---

# Comparar escenarios de inversión empresarial

## Uso en IAbot.io

Asigna esta skill a **un empleado de planificación financiera** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta alternativas, desembolsos, flujos previstos, horizonte y criterios de evaluación.

**Ejemplo de encargo:** «Compara estas alternativas de maquinaria y muestra cómo cambia el resultado al variar ventas y plazo.»

**Resultado a revisar:** Modelo de alternativas con flujos, indicadores y sensibilidad.

## Cuándo usarla y qué necesita

Comparar inversiones operativas mediante escenarios y sensibilidad de supuestos documentados

Trabaja con alternativas, desembolsos, flujos previstos, horizonte y criterios de evaluación. Usa hojas de cálculo, exportaciones contables y supuestos aprobados. Los cálculos no ejecutan pagos, inversiones ni decisiones de financiación.

## Procedimiento

1. Define alternativas y horizonte común incluyendo desembolso, mantenimiento, capacidad y valor residual aportados.
2. Separa flujos de caja de gastos contables y aclara tratamiento de inflación, impuestos y financiación.
3. Calcula los indicadores pedidos con fórmulas visibles y tasa de descuento justificada por el usuario.
4. Evalúa escenarios adversos y sensibilidad de los supuestos dominantes, conservando restricciones no monetarias.
5. Entrega comparación para decisión; no recomienda instrumentos financieros ni ejecuta una inversión.

## Comprobación del resultado

- Las alternativas comparten moneda y convención temporal.
- Una tasa nominal no se mezcla sin ajuste con flujos reales.
- Los resultados no se presentan como rendimientos garantizados.

## Entrega

Modelo de alternativas con flujos, indicadores y sensibilidad.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Banco de España, Central de Balances](https://www.bde.es/wbe/es/areas-actuacion/central-balances/)
- [Finanzas para Todos](https://www.finanzasparatodos.es/)
