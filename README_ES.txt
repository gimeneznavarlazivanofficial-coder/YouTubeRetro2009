YOUTUBE RETRO 2009 — Proyecto Android

Compatibilidad prevista: Android 6.0 o posterior; preparado para compilar con SDK 35.
El Redmi Note con Android 15 debería poder instalar la APK compilada.

QUÉ INCLUYE
- Aplicación Android sencilla con WebView.
- Interfaz propia inspirada en YouTube de 2009.
- Búsqueda que abre resultados reales en YouTube móvil.
- Sin inicio de sesión propio ni recopilación de datos por esta app.

IMPORTANTE
- Este ZIP contiene el CÓDIGO FUENTE, no una APK ya compilada.
- La experiencia de YouTube puede cambiar y algunas funciones se abren en YouTube actual.
- No es una app oficial ni está afiliada a Google/YouTube.
- No introduzcas contraseñas en páginas que no sean dominios oficiales de Google.
- La reproducción integrada puede estar limitada por YouTube; la búsqueda se abre en YouTube móvil.

CÓMO COMPILAR UNA APK
1. En un ordenador, instala Android Studio desde la web oficial de Android Developers.
2. Descomprime este ZIP.
3. Android Studio > Open > selecciona la carpeta YouTubeRetro2009.
4. Acepta la sincronización de Gradle e instala Android SDK Platform 35 si lo solicita.
5. Menú Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Cuando termine, pulsa Locate. La APK de depuración suele estar en:
   app/build/outputs/apk/debug/app-debug.apk
7. Pasa esa APK al Redmi Note.
8. En el móvil, abre el archivo y autoriza temporalmente la instalación para la app
   que lo abre (por ejemplo, Archivos), si Android lo solicita.
9. Instala y abre “YouTube Retro 2009”.

Si Android Studio informa de un error de versión de Gradle/JDK, usa el JDK integrado de Android Studio
y vuelve a sincronizar el proyecto.

COMPILACIÓN EN LA NUBE (SIN ORDENADOR)
El ZIP incluye .github/workflows/build-apk.yml para GitHub Actions.
Necesitas una cuenta de GitHub y subir el contenido del proyecto a un repositorio.
Al ejecutar la acción "Build YouTube Retro 2009 APK", GitHub compila el proyecto y guarda
el APK como artefacto descargable en la ejecución. GitHub puede pedir verificar la cuenta
o aceptar sus condiciones. No compartas tokens ni contraseñas con nadie.
