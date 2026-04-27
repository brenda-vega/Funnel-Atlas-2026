# Funnel Atlas

Herramienta de toma de decisiones para selección de funnels de marketing. No es un catálogo — es un sistema que cruza tres variables de tu situación actual y devuelve la combinación de funnels recomendada, el orden de ejecución, la lógica detrás, y lo que no debes hacer en ese contexto.

## Para qué sirve

Evita el error más frecuente en marketing digital: elegir tácticas por referencia o por intuición en lugar de por contexto. La herramienta responde: *dado dónde estás ahora, qué combinar y en qué orden.*

## Cómo funciona

La recomendación cruza tres variables:

| Variable | Opciones |
|---|---|
| **Etapa del negocio** | Sin audiencia / Crecimiento / Madurez / Escala |
| **Temperatura del tráfico** | Frío / Tibio / Caliente / Cliente activo |
| **Objetivo inmediato** | Generar leads / Nutrir / Convertir / Filtrar / Retener |

Cada resultado incluye:
- **Funnels con roles** — Core (trabajo principal), Soporte (amplifica), Opcional (si tienes capacidad)
- **Flujo operativo** — el orden real de ejecución
- **Rationale** — por qué esta combinación y no otra en este contexto
- **Warning** — qué no combinar ni hacer antes de ejecutar

## Estructura de archivos

```
funnel_atlas_v6.html     — Sistema principal (motor de decisiones + atlas de tarjetas)
funnel_atlas_miniguia.html  — Guía de uso embebible (qué es y cómo leer los resultados)
README.md
```

## Limitaciones conocidas

**La matriz no es exhaustiva.** Cubre los escenarios más frecuentes, no todas las combinaciones posibles. Si seleccionas una combinación de variables que no existe en la matriz, el sistema lo indica explícitamente — no es un error, es un hueco intencional. En ese caso, consulta directamente la tarjeta del funnel más cercano a tu objetivo en el atlas.

**La temperatura del tráfico requiere diagnóstico previo.** La herramienta no puede saber si tu tráfico es frío, tibio o caliente — eso lo defines tú antes de usarla. Seleccionar la temperatura incorrecta produce una recomendación correcta para el contexto incorrecto. Ver guía de uso para criterios de diagnóstico.

**Las combinaciones multi-funnel asumen capacidad de ejecución.** Los funnels de soporte y opcional son el sistema ideal, no el mínimo. Si tienes recursos limitados, ejecuta el core primero y agrega soporte cuando esté funcionando.

## Versiones

| Versión | Cambio |
|---|---|
| v6 | Estado vacío explícito cuando la combinación de variables no tiene resultado en la matriz |
| v5 | Motor de decisiones, dark mode, búsqueda en tiempo real, filtrado por recomendación |

## Contexto de uso

Diseñado para uso personal como herramienta de consulta rápida en la fase de diagnóstico y planeación estratégica. No reemplaza el criterio — da el marco correcto para decidir.

---

*Brenda Vega — San Luis Potosí, MX*
