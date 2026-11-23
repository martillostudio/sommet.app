# Producto

**SOMMET es un entrenador de rodillo, no un simulador.** Plan, entrenos estructurados y rodaje libre, controlando el Kickr Core 2 con los dos Zwift Click V2.

Objetivo inmediato: entrenar este invierno para no perder la forma y llegar a la primavera preparado para salidas más largas y exigentes.

## Para quién

Para mí ahora, sin cerrar la puerta a que ayude a otros: **«para mí, lista para cualquiera»**.

- Perfil, bici y dispositivos configurables; nada «cableado» a un equipo concreto.
- Sin cuentas ni servidor propio: datos en el dispositivo + iCloud.
- Publicar más adelante sería empaquetar (Apple Developer Program, 99 €/año; comprobar la marca «Sommet»), no rehacer.

Si se abre, el hueco sería: ciclistas con rodillo inteligente y mandos Click que entrenan en MyWhoosh y quieren un plan estructurado sin pagar Zwift o TrainerRoad, con un diseño cuidado.

## Plataformas

Nativa de Apple. Safari en iPhone/iPad no tiene Web Bluetooth, así que una web no podría hablar con el rodillo.

| Plataforma | Papel |
|---|---|
| Mac | Pantalla de rodaje (a la par con el iPad); donde se desarrolla y prueba |
| iPad | Pantalla de rodaje (a la par con el Mac), en horizontal |
| iPhone | Hoy, Plan, Historial; rodaje compacto si no hay otra pantalla |
| Web | Solo página del proyecto, si se abre |
| Apple Watch, Android, Windows | Fuera de alcance |

## Base técnica

- Swift 6 + SwiftUI, una sola app para Mac, iPad e iPhone.
- Paquete `SommetKit` (= `CicloKit` de taylor-zwift migrado): protocolos, física, entrenos, plan y cálculos, con tests sin hardware.
- SwiftData + iCloud. La app funciona entera sin red.
- intervals.icu (API con clave personal): subir cada sesión en `.fit` y leer salidas exteriores.
- Componentes de marca SOMMET en SwiftUI (Geist, colores por estación, cifra en Geist Pixel, modo noche) antes que cualquier pantalla.
