# Datos

**La app es dueña de lo que mide y del plan; intervals.icu recibe una copia de cada sesión.** La app funciona entera sin red y sincroniza cuando hay conexión.

| Dato | De dónde viene | Dónde vive | A dónde sale |
|---|---|---|---|
| Perfil: peso, FTP, FC máx, zonas | Usuario, test de FTP | App + iCloud | FTP a intervals.icu |
| Equipo: bici, desarrollos, rodillo, mandos, pulsómetro | Usuario, emparejamiento | App + iCloud | — |
| Muestras por segundo: potencia, cadencia, FC, velocidad, pendiente, marcha | Kickr y pulsómetro | Archivo de sesión | `.fit` |
| Resumen de sesión: tiempo, km, NP, IF, TSS, kJ, FC media | Calculado en la app | App + iCloud | intervals.icu |
| Entrenos: bloques con duración, % FTP y cadencia | Biblioteca propia, `.zwo` | App | — |
| Plan y calendario | Planes de SOMMET (por fases, ajustables) | App + iCloud | — |
| Rutas: perfil de pendiente desde GPX | Archivo GPX (o cursos de Garmin) | App | — |
| Forma y carga: CTL, ATL, TSB | Calculado en la app (con salidas exteriores) | App + iCloud | — |
| Salidas exteriores | Garmin → intervals.icu | Solo lectura | — |
