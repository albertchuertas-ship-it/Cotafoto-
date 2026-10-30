COTAFOTO ISOMÉTRICA — PROYECTO ANDROID

Este paquete envuelve el prototipo web CotaFoto en una aplicación Android nativa sencilla mediante WebView.

PARA GENERAR EL APK:
1. Instala Android Studio en una computadora (Windows, macOS o Linux).
2. Descomprime CotaFoto_Android_Studio.zip.
3. En Android Studio, elige Open y selecciona la carpeta CotaFoto_Android_Studio.
4. Espera a que termine la sincronización de Gradle. Se necesita conexión a Internet la primera vez para descargar las herramientas de compilación.
5. Ve a Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Android Studio generará el APK en:
   app/build/outputs/apk/debug/app-debug.apk
7. Copia ese APK a tu Android, ábrelo y autoriza la instalación desde esa fuente si Android lo solicita.

REQUISITOS:
- Android Studio actualizado.
- JDK 17 (Android Studio normalmente incluye uno).
- Android SDK Platform 35 y Build Tools instalados desde SDK Manager.

ESTADO:
- Proyecto Android preparado.
- Este entorno no tiene Android SDK ni Gradle instalados, por eso no puedo compilar ni adjuntar un APK binario ya construido desde aquí.
- La aplicación contiene el prototipo CotaFoto Isométrica: cámara/galería, cotas táctiles, anotaciones, calibración simple y exportación PNG.

NOTA TÉCNICA:
La calibración de una sola distancia no corrige la perspectiva de todos los ejes de una foto isométrica. Comprueba las dimensiones físicas antes de fabricar una pieza.
