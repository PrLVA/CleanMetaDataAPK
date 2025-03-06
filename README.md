# MetadataCleaner (Android)

Una aplicación Android escrita en Kotlin para eliminar metadatos de imágenes (JPEG, PNG) y PDFs, con verificación posterior para confirmar que los metadatos han sido eliminados. Ideal para proteger la privacidad al compartir archivos.

## Características
- **Formatos soportados**: JPEG, PNG y PDF.
- **Interfaz gráfica**: Botones simples para seleccionar y limpiar archivos.
- **Procesamiento local**: Todo se realiza en el dispositivo, sin necesidad de internet.
- **Verificación**: Comprueba si los metadatos (EXIF para imágenes, /Info para PDFs) se eliminaron correctamente.
- **Almacenamiento**: Guarda los archivos limpios en `cleaned_files` dentro del directorio privado de la app.

## Requisitos
- **Android**: API 29 (Android 10) o superior.
- **Dependencias**:
  - AndroidX (Core KTX, AppCompat, Activity, ConstraintLayout)
  - Material Components
  - iTextPDF (para PDFs)
- **Herramientas**: Android Studio.

