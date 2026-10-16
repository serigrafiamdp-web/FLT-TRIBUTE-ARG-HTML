# Fairlight Tribute From Argentina — HTML C64 Demo

Exportación web de la demo **Fairlight Tribute From Argentina** para reproducirla en un navegador usando el emulador Commodore 64 incluido en el paquete original.

## Acceso público

Una vez habilitado **GitHub Pages**:

https://serigrafiamdp-web.github.io/FLT-TRIBUTE-ARG-HTML/

## Activación de GitHub Pages

1. Abrir `Settings → Pages` de este repositorio.
2. En **Build and deployment → Source**, seleccionar **Deploy from a branch**.
3. Elegir **main** y **/(root)**.
4. Guardar (**Save**).

## Contenido

- `index.html`: entrada web, pantalla completa.
- `js/content.js`: configuración y PRG de Fairlight incrustado (idéntico al ZIP de origen).
- `js/c64.min.js` y `js/c64.wasm`: motor de emulación.
- `images/`: recursos de los controles.

Los archivos de funcionamiento se alojan dentro del repositorio; la web no necesita servidor de aplicaciones, sólo hosting estático.

## Actualizaciones

Para cambiar la demo, mantener `index.html` como punto de entrada y sustituir `js/content.js` si se genera otra versión de la exportación. El enlace público se mantiene.
