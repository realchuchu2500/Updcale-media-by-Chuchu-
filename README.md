# UpscaleMedia - App Android 4K

## 🚀 Cómo generar el APK desde tu móvil Android (sin PC)

### 1. Subir el proyecto a GitHub
- Crea un repositorio nuevo en GitHub desde tu móvil.
- Descomprime `upscalemedia_github_bundle.zip` y sube todos los archivos.
- O sube el ZIP completo y descomprímelo desde GitHub.

### 2. Añadir el workflow de GitHub Actions
- Crea la carpeta `.github/workflows/` en el repositorio.
- Sube el archivo `workflow.yml` exactamente como está.

### 3. Compilar el APK
- Ve a la pestaña **Actions** del repositorio.
- Selecciona el workflow **Build Android APK**.
- Clic en **Run workflow** → **Run workflow**.
- Espera 3-5 minutos hasta que termine.

### 4. Descargar el APK
- En la pestaña **Actions**, abre el workflow que corrió.
- Ve a **Artifacts** → `app-debug-apk`.
- Descarga el archivo `app-debug.apk`.

### 5. Instalar en tu Android
- En tu móvil, ve a **Ajustes → Seguridad → Permitir apps de fuentes desconocidas**.
- Abre el APK descargado y da **Instalar**.
- Listo: la app UpscaleMedia está instalada.

## 📱 Qué hace la app
- Upscale de videos a **4K** (manteniendo relación de aspecto).
- Upscale de imágenes a **4K** (mejora tipo foto de estudio).
- Mejora visual cinematográfica (denoise + nitidez).
- Todo procesado **localmente** en tu móvil.
- Interfaz en español.

## 🔧 Si hay error
- Verifica que el workflow termine con ✅.
- Revisa los logs de Actions.
- Asegúrate de que el repositorio tenga el archivo `workflow.yml` correcto.

## 📲 Instalación en Android
- **Mínimo Android 7.0** (API 24).
- Permisos: acceso a galería y fotos.

¡Listo! Tu app UpscaleMedia ya está funcionando en tu móvil.
