# Cuerpo Sublevado · Inspiración y documentación

Materiales estratégicos y visuales para una marca de humor gráfico y productos sobre dolor crónico, fatiga y discapacidad invisible. La marca no se limita a un diagnóstico: trabaja con experiencias compartidas, comentarios invalidantes, planes que cambian y el absurdo cotidiano.

## Archivos de esta carpeta

- **`Proyecto_marca_dolor_cronico_y_prompt_Claude_v2.pdf`** — guía de marca, dirección artística, paleta, voz, territorios narrativos, frases de ejemplo y prompt de producción.
- **`muestra_librov2.pdf`** — libro para colorear A4: portada y seis láminas originales vectoriales.
- **`generar_pdfs_cuerpo_sublevado.py`** — código fuente para generar los dos PDF y validar su firma y número de páginas.
- **`muestra_librov1_CORRUPTO_OBSOLETO.pdf`** — nombre previsto para conservar el archivo anterior corrupto como referencia histórica, si se desea.
- **`referencias_visuales/`** — referencias e inspiración gráfica, cuando esta carpeta esté presente.

## Dirección artística

- Humor cotidiano y absurdo: el cuerpo tiene sus propios planes y no respeta la agenda.
- Sarcasmo y zascas dirigidos a comentarios invalidantes, clichés y barreras; nunca a la persona que vive con dolor.
- Personajes expresivos y situaciones que transmitan cansancio, incredulidad, rabia o ironía.
- Para productos: color, contraste y una idea visual clara.
- Para colorear: línea negra sobre fondo blanco, sin grises ni grandes masas negras, con áreas amplias y margen de seguridad.

## Regenerar y validar

Requiere Python 3, ReportLab y pypdf:

```bash
python -m pip install reportlab pypdf
python generar_pdfs_cuerpo_sublevado.py
```

El script genera los dos PDF junto a sí mismo y comprueba su firma y el número de páginas. Además, se debe revisar visualmente el resultado: márgenes, legibilidad, ortografía, líneas cortadas y aspecto a tamaño real. No se debe declarar un archivo listo para impresión profesional sin esa revisión final.

**Versión preparada:** v2 · octubre de 2026.
