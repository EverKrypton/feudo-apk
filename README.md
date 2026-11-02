# FEUDO — descarga (Android)

Repo **público** de distribución de **FEUDO**, un juego de granja, crafteo y señorío medieval.
Acá viven el **APK** y la **página de descarga**. El **código fuente** está en un repo privado.

## Página de descarga

**https://everkrypton.github.io/feudo-apk/**

Desde ahí bajás el APK y ves la versión, el tamaño y el SHA-256.

## Instalar

1. Descargá **FEUDO.apk** (desde la página o directo: `FEUDO.apk` en este repo).
2. Al abrirlo, Android pedirá permitir **instalar apps desconocidas** (Chrome o Archivos). Aceptá.
3. Tocá **Instalar**. Si ya tenías FEUDO, se actualiza **sin perder el progreso**.

> ¿Dice «paquete no válido»? Casi siempre es una descarga incompleta o el navegador interno de
> WhatsApp/Instagram. Descargá desde la página con Chrome y comprobá el SHA-256.

## Actualización automática

La app busca novedades en `update.json` (servido por GitHub Pages en este repo) y ofrece la
actualización in-app. No hay que reinstalar a mano.

## Archivos

- `index.html` — página de descarga.
- `FEUDO.apk` — última versión (nombre estable).
- `FEUDO-<versión>.apk` — copia versionada.
- `update.json` — manifiesto de actualización (versión, tamaño, SHA-256, URL).

---

FEUDO · hecho con Phaser + Capacitor.
