# ImageMasterExe

ImageMaster es una aplicación de escritorio (empaquetada en un ejecutable) desarrollada en Python que permite convertir, comprimir, eliminar transparencias, remover el fondo y redimensionar imágenes en múltiples formatos. Además, incluye una funcionalidad básica para la actualización automática mediante la consulta de lanzamientos en GitHub.

Funcionalidades
Conversión de imágenes:
Permite convertir imágenes entre diferentes formatos:

PNG a JPG y viceversa.
AVIF a PNG o JPG.
WEBP a PNG o JPG.
Conversión a ICO (genera iconos en múltiples tamaños).
Compresión de imágenes:
Optimiza imágenes PNG y JPG sin pérdida apreciable de calidad, guardando el resultado con el sufijo _comprimed.

Incluir o quitar transparencia:

Al convertir imágenes, se puede elegir incluir transparencia (por ejemplo, para PNG o ICO) mediante la opción "Incluir Transparencia".
También se puede quitar la transparencia existente y generar una imagen sin canal alfa.
Remover el fondo:
Permite quitar el fondo de las imágenes convirtiendo los píxeles de un color (configurable con tolerancia) en completamente transparentes. Se agrega el sufijo _nofondo a los archivos resultantes.

Redimensionar imágenes:
Permite cambiar el tamaño de las imágenes a dimensiones especificadas por el usuario (ancho y alto), ya sea de forma individual o en lote. El resultado se guarda con el sufijo _resized.

Actualización automática:
La aplicación consulta la API de GitHub para detectar si existe una nueva versión publicada en los Releases. Si hay una actualización disponible, se ofrece al usuario la descarga e instalación del nuevo ejecutable.
