# Bitácora de Perforaciones

Aplicación web para el registro de campo de perforaciones de suelo y ensayos geofísicos:

- Columna estratigráfica con colores de la carta Munsell y achurados por material, incluidos suelos residuales de roca ígnea, metamórfica y sedimentaria.
- Profundidad total calculada con el último estrato.
- Coordenadas MAGNA-SIRGAS Origen Nacional (CTM12) a partir del GPS o de Norte/Este.
- Cota automática: con **Usar mi ubicación** se toma la altura del GPS del celular (funciona sin datos móviles). Si pegas coordenadas, escribes Norte/Este o el celular no da la altura, se consulta en línea el modelo Copernicus GLO-90 en Open-Meteo.
- Tomografía eléctrica (ERT), sondeo eléctrico vertical (SEV), refracción sísmica y MASW, con coordenadas de electrodos, geófonos y disparos.
- Informe PDF por perforación, por línea o del proyecto completo.

Los datos se guardan en el navegador de cada dispositivo. Para pasarlos a otro equipo usa **Respaldo** y luego **Importar**.

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La aplicación |

## Publicar en GitHub Pages

1. En GitHub crea un repositorio público, por ejemplo `bitacora-perforaciones`.
2. Entra al repositorio, elige **Add file → Upload files** y arrastra `index.html` y `README.md`. Pulsa **Commit changes**.
3. Ve a **Settings → Pages**. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
4. En uno o dos minutos la aplicación queda en `https://TU-USUARIO.github.io/bitacora-perforaciones/`.

## Créditos de datos

Modelo de elevación: Copernicus DEM GLO-90, servido por Open-Meteo (open-meteo.com). © DLR e.V. 2010-2014 y © Airbus Defence and Space GmbH 2014-2018, provisto bajo COPERNICUS por la Unión Europea y la ESA; todos los derechos reservados. Las cotas del modelo y del GPS son aproximadas; las del modelo incluyen vegetación y construcciones, y deben verificarse con topografía cuando la obra lo requiera.
