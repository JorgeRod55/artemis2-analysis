## 2026-10-25 (Día 1)
- Hecho: VS Code + Git + Python 3.14.9 instalados. Smart App Control bloquea pandas en local, así que trabajo en Google Colab (funciona).
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
- PENDIENTE antes del primer push: cambiar user.email al correo noreply de GitHub y reescribir el historial.
- readme.txt del bundle mission leído: sin novedades. CSV HOBO son datos crudos (raw), sin calibrar ni limpiar.
- Descargados a data/: 2 CSV HOBO (hobo1104, hobo1105; ~1,6 MB cada uno) y OTR JSON (59 KB).
- Rango en nombres de archivo: día 086 a 111 (27-mar a 21-abr). Comprobar contra las fechas internas.
- OTR: 39 entradas (30 observación, 9 logística), 10 flags STM; significado de cada STM pendiente de buscar en el Preliminary Report/OSDMP.
- HOBO: 2 loggers, sin huecos ni nulos; se comportan distinto en vuelo y tras amerizaje.
- Hora HOBO validada: CDT = UTC-5, coherente con el nombre de archivo (el día de inicio del nombre está desfasado en 1).
- Notebook 01_inventario probado.
- Fig01 revisada: etiquetas ajustadas para lectura en móvil (v2).
- Preguntas abiertas: por qué el locker D era más frío que el E; causa de las excursiones del 1105 los días 15-16 de abril. La ubicación de cada HOBO figura en la guía (sec. 3.4).