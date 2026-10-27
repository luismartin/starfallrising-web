# starfallrising.com

Web pública de **Starfall Rising**: la página del juego, la política de privacidad
(`/privacidad/`) y `app-ads.txt` en la raíz del dominio.

Se publica con GitHub Pages desde la rama `main` (raíz), con el dominio
`starfallrising.com` (`CNAME`). Los DNS están en Cloudflare en modo «DNS only»
(nube gris): las IP del proxy de Cloudflare se bloquean en España durante los partidos.

**La fuente es `site/` del repo del juego** (`luismartin/stellar_assault`, privado), donde
los tests comprueban que la política coincide con `docs/privacidad.md`. Tras cambiar
`site/` allí, se copia aquí tal cual (`tool/sync_site.sh` del juego). No se edita a mano.
