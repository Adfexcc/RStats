# RStats · Melilla Ciudad del Deporte

Web de estadística avanzada para el cuerpo técnico del Melilla Ciudad del Deporte (Segunda FEB 2026/27, Grupo A).
Datos actualizados tras la **jornada 8** (Getafe y SBA con 7 partidos: su partido se aplazó).

## Contenido

- `index.html`: la web completa en un solo archivo. Funciona sin conexión: se abre con doble clic en cualquier navegador.
  Pestañas: Resumen, Esta semana, Próximo rival (scouting de Getafe), Grupo A, Grupo B, Actas, Jugadores, Fichas y Fuentes.
- `datos/`: los datos de partida en CSV.
  - `grupoA_jornada8.csv`: totales de los 14 equipos (contrastados con la tabla de medias por equipo de la FEB).
  - `resultados.csv` y `clasificacion.csv`: resultados por jornada y clasificación (J1–J4 oficiales; J5–J8 calculadas con los resultados).
  - `melilla_partidos.csv`: partidos de Melilla.
  - `jugadores_melilla_liga.csv`: estadísticas acumuladas de liga de los jugadores de Melilla.
  - `grupoB_jornada8.csv`: totales de los 14 equipos del Grupo B tras la jornada 8 (referencia).

## Publicarla como página web (GitHub Pages)

Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)`.
Ojo: una página de GitHub Pages es **pública** aunque el repositorio sea privado (salvo en planes Enterprise).

## Fuentes

Estadísticas, resultados y actas oficiales de la FEB (feb.es / baloncestoenvivo.feb.es). Fotos de jugadores: web del Club Melilla Baloncesto.
Métricas: Dean Oliver (*Basketball on Paper*), John Hollinger y Basketball-Reference.
