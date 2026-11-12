# ANMUC — sitio institucional

Página de inicio estática, adaptable a computadoras y celulares. No requiere instalar dependencias ni ejecutar comandos para publicarse.

## Publicación en GitHub Pages

1. Descomprime el ZIP. Crea un repositorio público bajo la cuenta u organización institucional de ANMUC, por ejemplo `anmuc-web`.
2. En el repositorio selecciona **Add file → Upload files** (o el enlace de carga inicial). Sube `index.html`, `assets/`, `documentos/` y `README.md` en la raíz, conservando las carpetas. Incluye `.nojekyll` si aparece; es opcional para este sitio. No subas el ZIP como archivo único.
3. Guarda los cambios con **Commit changes** en la rama `main`.
4. En **Settings → Pages**, selecciona **Deploy from a branch**, rama `main`, carpeta `/(root)` y pulsa **Save**.
5. Abre **Visit site** cuando esté disponible. Una URL habitual de proyecto es `https://<organizacion>.github.io/anmuc-web/`.

## Vista local

Abre `index.html` en Chrome o Safari conservando las carpetas junto al archivo. Las imágenes y PDF están incluidos. Montserrat (Google Fonts) y los enlaces externos requieren internet; hay fuentes alternativas locales.

## Dominio anmuc.org

No se incluye un archivo CNAME ni se cambia el DNS todavía. Comprueba primero el sitio de prueba. Después configura el dominio personalizado siguiendo la documentación oficial de GitHub Pages y las instrucciones del proveedor DNS. Conserva Wix hasta verificar el nuevo sitio. No borres ni modifiques los registros MX, SPF, DKIM o DMARC del correo institucional.

Documentación: https://docs.github.com/es/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Contenido y revisión previa a publicación

- Contacto institucional: asociacion@anmuc.org. Los botones abren el correo; no existe backend, formularios ni procesamiento de pagos.
- Femengineer: enlaces directos a Spotify y Apple Podcasts; no depende de un reproductor incrustado.
- Cifras de contexto: INEGI, ENOE 2019 y EAEC 2024 (publicada en 2025); se enlazan las fuentes originales. No son resultados del trabajo de ANMUC.
- Los cuatro programas se presentan como parte de la teoría de cambio; las universidades se describen como parte de su trayectoria. Confirmar actividad vigente, cifras de impacto y donaciones antes de ampliar la información.
- La visión pública se presenta hacia 2030 por indicación de la solicitante; el documento interno de planeación tiene horizonte 2032. Confirmar alineación institucional.
- Confirmar derechos de publicación de fotos y documentos. La planeación estratégica y los archivos originales de trabajo no se incluyen.
- Antes de sustituir Wix, revisar el blog y las URL anteriores para preservar publicaciones y enlaces difundidos.
