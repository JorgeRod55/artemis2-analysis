## 2026-10-25 (Día 1)
- Hecho: VS Code, Git y Python instalados. Análisis en Google Colab, reproducible sin instalar nada.
- Formatos que he encontrado: (pendiente, Día 2)
- Dudas / bloqueos: Data User Guide aún sin localizar.
- Mañana: localizar y leer la guía, anotar bundles y formatos.

## 2026-10-26 (Día 2)
- Hecho: leída la Data User Guide v1.0.
- Bundles: crew_camera, orion_camera, mission_audio (CIS); mission (GEO); spice (NAIF).
- Tabulares: HOBO CSV (hobo1104/1105), transcripciones CSV, OTR JSON, etiquetas XML.
- Hora HOBO en CDT; convertir a UTC.
- Pendiente: comprobar si SPICE está publicado; iPhone sin archivar.
- Mañana: descargar de la página del Geosciences Node el CSV HOBO y el OTR.
- Hecho: correo noreply configurado y historial reescrito antes del primer push.
- readme.txt del bundle mission leído: sin novedades. CSV HOBO son datos crudos (raw), sin calibrar ni limpiar.
- Descargados a data/: 2 CSV HOBO (hobo1104, hobo1105; ~1,6 MB cada uno) y OTR JSON (59 KB).
- Rango real de los HOBO: 26-mar a 21-abr (UTC). El día de inicio del nombre de archivo (086) está desfasado en 1.
- OTR: 39 entradas (30 observación, 9 logística), 10 flags STM; significado de cada STM pendiente de buscar en el Preliminary Report/OSDMP.
- HOBO: 2 loggers, sin huecos ni nulos; se comportan distinto en vuelo y tras amerizaje.
- Hora HOBO validada: CDT = UTC-5, coherente con el nombre de archivo (el día de inicio del nombre está desfasado en 1).
- Notebook 01_inventario probado.
- Fig01 revisada: etiquetas ajustadas para lectura en móvil (v2).
- Preguntas abiertas: por qué el locker D era más frío que el E; causa de las excursiones del 1105 los días 15-16 de abril. La ubicación de cada HOBO figura en la guía (sec. 3.4).
- Guía sec. 3.4: HOBO 1104 en locker E toda la misión; 1105 en locker D hasta el 9-abr (18:00-21:00 UTC), luego locker F. El salto del 1105 empieza a las 18:42 UTC.