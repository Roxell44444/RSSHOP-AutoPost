# RSSHOP AutoPost

Aplicación Android para organizar anuncios, campañas y publicaciones asistidas de RSSHOP LAS TUNAS.

## Compilación Android
El repositorio usa Capacitor y GitHub Actions para generar un APK de depuración. Cada push a `main` o `android-build` y cada ejecución manual genera el artefacto `RSSHOP-AutoPost-debug-apk`. El APK se puede instalar en Android para pruebas.

## Funciones incluidas
- Añadir y gestionar grupos de Facebook.
- Crear campañas con texto, fotos y vídeos.
- Crear una tarea por grupo seleccionado.
- Copiar el anuncio, abrir el grupo y marcar la publicación como completada.
- Guardar los datos en el dispositivo y exportar/importar respaldos.

## Límites
La app no publica automáticamente en grupos. Meta no ofrece una API oficial disponible para automatizar publicaciones en grupos. Esta compilación tampoco está conectada todavía a una aplicación de Meta ni a un servidor de publicación para Páginas. La automatización de una Página requiere un servidor HTTPS, una app de Meta, permisos aprobados y la autorización del administrador.

## Instalación
Descarga el APK debug desde el artefacto de la ejecución de GitHub Actions. Es una compilación de prueba; al reinstalar una compilación firmada con otra clave puede ser necesario desinstalar la anterior. Los datos locales pueden perderse al desinstalar la app; exporta un respaldo antes.
