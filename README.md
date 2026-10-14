# InfyCredit · Consultoría

Aplicativo estático para organizar entidades, tareas, cronogramas, checklist, notas, actas y compromisos.

## Uso

Abre `index.html` o la dirección de GitHub Pages. El espacio inicia vacío: pulsa **Nueva entidad** y guarda su ficha. Los demás accesos se encuentran debajo del selector de entidad.

- Ficha técnica editable; permite información pendiente.
- Tareas por estado y cronograma con gráfica, duraciones y desplazamiento opcional.
- Plantilla de actividades disponible para cronogramas vacíos; sus fechas se generan desde el inicio de la entidad y deben revisarse.
- Checklist seccionado: Sí y No aplica suman con igual peso.
- Importación local de FOTSC-03 `.xlsx`, vista del original, conversión horizontal y exportación CSV.
- Botones con iconos y texto.

## Almacenamiento y límites

Los datos se guardan únicamente en el almacenamiento del navegador y los originales en IndexedDB. No se envían a GitHub ni a Drive. Borrar los datos del navegador puede eliminar el expediente. No hay autenticación, colaboración entre usuarios, seguridad multi-entidad de servidor ni sincronización. Usa datos de prueba mientras no exista un backend autorizado para información confidencial.

El repositorio contiene solo el aplicativo y esta guía, sin credenciales, registros de entidades, adjuntos ni documentos de referencia. Las plantillas contienen nombres genéricos de actividades.

## GitHub Pages

En Settings → Pages elige Deploy from a branch, rama `main`, carpeta `/ (root)`, y guarda. El sitio no requiere compilación ni dependencias.
