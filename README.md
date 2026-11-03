# Finanzas y control de gestión · Skills para empleados IA de IAbot.io

Tesorería, presupuestos, márgenes y escenarios empresariales con cálculos trazables.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Previsión de tesorería](skills/cash-flow-forecast/SKILL.md) | un empleado de tesorería | Previsión de caja con saldo inicial, movimientos, saldo final y supuestos. |
| [Analizar desviaciones presupuestarias](skills/budget-variance-analysis/SKILL.md) | un empleado de control de gestión | Informe por partida con desviaciones, evidencia y acciones propuestas. |
| [Analizar márgenes por producto o servicio](skills/contribution-margin-analysis/SKILL.md) | un empleado de análisis económico | Tabla de márgenes con definición de coste, fórmula y limitaciones. |
| [Comparar escenarios de inversión empresarial](skills/business-investment-scenarios/SKILL.md) | un empleado de planificación financiera | Modelo de alternativas con flujos, indicadores y sensibilidad. |
| [Priorizar seguimiento de cobros](skills/receivables-followup-priority/SKILL.md) | un empleado de cuentas a cobrar | Cartera conciliada, prioridades de revisión y borradores de seguimiento. |
| [Cuadro de gestión para dirección](skills/management-report-pack/SKILL.md) | un empleado de reporting de dirección | Informe ejecutivo, tabla de indicadores y decisiones pendientes. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/finance-skills --list
npx skills add Iabot-io/finance-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Previsión de tesorería:** «Prepara una previsión semanal de caja a trece semanas y marca las semanas con datos incompletos.»
- **Analizar desviaciones presupuestarias:** «Explica las desviaciones de este trimestre y separa hechos demostrados de hipótesis pendientes.»
- **Analizar márgenes por producto o servicio:** «Calcula el margen de estas líneas y deja visibles los costes comunes que se han repartido.»

## Herramientas y límites

Usa hojas de cálculo, exportaciones contables y supuestos aprobados. Los cálculos no ejecutan pagos, inversiones ni decisiones de financiación.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [Banco de España, Central de Balances](https://www.bde.es/wbe/es/areas-actuacion/estadisticas/central-balances/)
- [Finanzas para Todos](https://www.finanzasparatodos.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
