# Registro de decisiones

| Fecha | Decisión |
|---|---|
| 2026-11-23 | SOMMET se replantea desde cero como **entrenador de rodillo**, no simulador. Fuera 3D, avatares y multijugador. |
| 2026-11-23 | Público: para mí ahora, construida «lista para cualquiera» (sin cuentas ni servidor). |
| 2026-11-23 | Nativa de Apple (Swift 6 + SwiftUI). Web descartada: Safari en iOS/iPadOS no tiene Web Bluetooth. |
| 2026-11-23 | Modo rodaje para **Mac e iPad por igual**; iPhone para consulta y rodaje compacto. |
| 2026-11-23 | El **plan vive dentro de la app** (generado por fases, carga calculada en la app). intervals.icu solo recibe las sesiones. |
| 2026-11-23 | Datos en SwiftData + iCloud; la app funciona sin red. |
| 2026-11-23 | Repo nuevo `martillostudio/sommet.app`. `taylor-zwift` queda como laboratorio; su Bluetooth se migra como `SommetKit` en la Fase 2. |
| 2026-11-23 | Cuestionario: mínimo 3 días/semana, sesiones de ~1 h o más; prioridad no lesionarse; objetivo forma y salidas más largas sin fecha; FTP ~185 W. |
| 2026-11-23 | Plan **adaptativo**; las salidas exteriores (Garmin vía intervals.icu) cuentan en la carga y reajustan el plan. |
| 2026-11-23 | Pulsómetro de banda Bluetooth. Sesiones: ERG, rutas SIM, fuerza/baja cadencia y rodaje libre con propósito. |
| 2026-11-23 | Vista minimizada para ver series: se prueban ventana flotante (Mac), PiP (iPad) y barra fina, y se decide probando. |
| 2026-11-23 | Avisos sonoros/voz desactivables, perfil restante, comparar con sesiones anteriores. Paisaje/vídeo de ruta, más adelante. |
| 2026-11-23 | En ERG, +/− ajustan la intensidad ±5 %. Mapeo de mandos: +/− marchas, A pausa, B saltar, Y/Z dato, cruceta menús. |
| 2026-11-23 | Sin cuenta Apple de pago por ahora: Mac como plataforma principal y sin sincronizar; iCloud preparado para activarse. |
| 2026-11-23 | Licencia GPL-3.0. Diseño de pantallas en el lienzo de diseño de Claude. |
| 2026-11-23 | Tras el MVP, primero el plan adaptativo. Días fijos: lunes a viernes rodillo, fines de semana salidas en exterior que cuentan en la carga. |
| 2026-11-23 | Enviar entrenos estructurados al Garmin Edge. Montaje variable: el modo rodaje se adapta a cualquier tamaño. App en español. |
| 2026-11-23 | Notificaciones: recordatorio del entreno del día y resumen semanal. |
| 2026-11-23 | Motor del plan con reglas legibles que explican cada cambio; sensaciones antes de la sesión y esfuerzo percibido (1–10) al terminar. |
| 2026-11-23 | Exportación completa en formatos abiertos (.fit por sesión + archivo con todo). |
| 2026-11-23 | **intervals.icu es el puente:** SOMMET sube sesiones (.fit) y copia el plan a su calendario por API (clave personal); intervals.icu envía los entrenos de la semana a Garmin Connect y de ahí al Edge. |
| 2026-11-23 | Strava no se integra directamente: su API exige suscripción de pago desde el 1-jun-2026. |
| 2026-11-23 | Garmin Connect: la API personal es solo lectura; SOMMET exporta el .fit para importarlo a mano. |
| 2026-11-23 | Puertos precargados: perfiles generados con OpenStreetMap (ODbL, con atribución) + relieve Copernicus GLO-30. Fase 5. |
| 2026-11-23 | Marca SOMMET: sin conflicto evidente en una búsqueda rápida; registro formal (EUIPO/OEPM) antes de publicar. |

## Pendiente (cierra la Fase 0)

- [ ] Garmin Connect: ¿vale importar a mano el .fit de cada sesión, o basta con intervals.icu?
- [ ] Antes de publicar: consultar SOMMET en el registro de marcas (EUIPO/OEPM).
