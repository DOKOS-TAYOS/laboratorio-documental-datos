# Laboratorio documental: datos públicos

Datos completamente ficticios de Nexo Industrial para comparar tres estructuras documentales. Los archivos están **sin comprimir en la rama main** y pueden consultarse individualmente, sin descargar ZIP ni iniciar sesión.

## Documentación por versión

- [V1 · Caótica](v1_caotica/): 108 PDF en sus carpetas originales, sin índice añadido.
- [V2 · Indexada](v2_indexada/): 100 PDF, índices y CSV. [Índice general](v2_indexada/INDICE_GENERAL.md) · [CSV de documentos](v2_indexada/indice_documentos.csv).
- [V3 · Markdown y chunks](v3_markdown/): 100 documentos Markdown, índices, 300 chunks y SQLite. [Índice general](v3_markdown/INDICE_GENERAL.md) · [Chunks JSON](v3_markdown/chunks.json).

## Correos, tickets y proyectos

Los ejemplos son comunes a las tres versiones y se publican una sola vez en la raíz:

| Archivo | Registros | Lectura directa |
|---|---:|---|
| [correos.json](correos.json) | 20 | [JSON sin formato](https://raw.githubusercontent.com/DOKOS-TAYOS/laboratorio-documental-datos/main/correos.json) |
| [tickets.json](tickets.json) | 25 | [JSON sin formato](https://raw.githubusercontent.com/DOKOS-TAYOS/laboratorio-documental-datos/main/tickets.json) |
| [proyectos.json](proyectos.json) | 10 | [JSON sin formato](https://raw.githubusercontent.com/DOKOS-TAYOS/laboratorio-documental-datos/main/proyectos.json) |

[Índice V3 sin formato](https://raw.githubusercontent.com/DOKOS-TAYOS/laboratorio-documental-datos/main/v3_markdown/INDICE_GENERAL.md) · [Chunks V3 sin formato](https://raw.githubusercontent.com/DOKOS-TAYOS/laboratorio-documental-datos/main/v3_markdown/chunks.json).

Para obtener otro archivo sin formato, utiliza el botón **Raw** de GitHub. También puedes añadir su ruta relativa a `https://raw.githubusercontent.com/DOKOS-TAYOS/laboratorio-documental-datos/main/`.

## Uso con asistentes

Proporciona el enlace del repositorio y pide consultar los archivos de main directamente, sin descargar ni extraer ZIP. Los Markdown, CSV y JSON son texto; los PDF y SQLite requieren herramientas capaces de leer esos formatos. No todos los asistentes pueden recorrer automáticamente un repositorio: facilita enlaces a archivos concretos si es necesario.

Para comparar las versiones, utiliza las mismas preguntas y conserva los resultados separados. No se incluyen respuestas de evaluación, correspondencias internas ni código de la aplicación.

[Explorar la web de Streamlit](https://laboratorio-documental-empresa-chatgpt.streamlit.app/).

## ZIP opcionales · v1.0.0

Los paquetes originales siguen disponibles como edición fija, con los ejemplos incluidos en cada ZIP:

- [V1 · Caótica](https://github.com/DOKOS-TAYOS/laboratorio-documental-datos/releases/download/v1.0.0/laboratorio_v1_chatgpt.zip)
- [V2 · Indexada](https://github.com/DOKOS-TAYOS/laboratorio-documental-datos/releases/download/v1.0.0/laboratorio_v2_chatgpt.zip)
- [V3 · Markdown](https://github.com/DOKOS-TAYOS/laboratorio-documental-datos/releases/download/v1.0.0/laboratorio_v3_chatgpt.zip)

## Licencia

Contenido sintético creado para este laboratorio. Licencia MIT; ver LICENSE.
