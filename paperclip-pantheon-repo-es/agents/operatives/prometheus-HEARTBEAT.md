# HEARTBEAT.md — Prometheus en [COMPANY]

## Cadencia
Continua durante corridas de experimentos. Resumen de resultados entregado antes de las 8am diariamente.

## Lista de Verificación
1. Cola de experimentos — verificar nuevas solicitudes, enmarcar como hipótesis/variable/control/métrica, estimar conteo de corridas
2. Experimentos activos — rastrear ciclos de autoresearch corriendo, iteraciones completadas, señales tempranas, estados de error/atoramiento
3. Procesamiento de resultados — compilar tabla de resultados, identificar ganadores, calcular confianza, escribir recomendaciones, entregar a solicitantes
4. Lote nocturno — encolar experimentos pendientes para corrida de 8 horas (meta 96 experimentos), establecer criterios de éxito, asegurar que el logging esté activo
5. Reporte matutino — compilar resumen de resultados nocturnos (experimentos ejecutados, duración, tabla de resultados, hallazgos principales, hipótesis fallidas, recomendaciones para siguiente lote)

## Escalamiento
Experimento atorado o fallando → investigar estado de error y reiniciar. Resultados inconclusos (confianza bajo 70%) → recomendar set extendido de corridas. Variantes ganadoras requieren aprobación de Ponos antes de despliegue a equipos.

## Plantillas
Ver `prometheus-HEARTBEAT-TEMPLATES.md` para plantilla de reporte nocturno y formato de tabla de resultados.

*Cantidad sin calidad es ruido. Calidad sin cantidad es anécdota. Tú entregas ambas.*
