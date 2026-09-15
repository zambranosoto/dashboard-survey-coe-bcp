# Dashboard COE BCP V1.2 - GitHub Pages

## Estructura requerida

```text
/
├── index.html
└── data/
    └── actions.json
```

## Publicacion inicial

1. Sube `index.html` a la raiz del repositorio.
2. Crea la carpeta `data` y sube dentro `actions.json`.
3. Haz commit de ambos archivos.
4. GitHub Pages leera `data/actions.json` cada vez que se abra el dashboard.

## Actualizar el plan de accion

1. Abre la pagina publicada.
2. Marca/desmarca `Prioridad maxima` y/o agrega nuevas acciones.
3. Los cambios se guardan como borrador local en ese navegador.
4. Pulsa `Exportar actions.json`.
5. En GitHub, abre la carpeta `data` y reemplaza `actions.json` por el archivo exportado.
6. Haz commit.
7. Tras el despliegue de GitHub Pages, todos los usuarios veran esa version. Puedes pulsar `Recargar publicada` en el dashboard para forzar la lectura del JSON nuevo.

## Importante

GitHub Pages es estatico: el navegador puede leer `actions.json`, pero no puede escribirlo directamente en el repositorio sin un backend/autenticacion. Por eso la publicacion de cambios requiere reemplazar el JSON y hacer commit.
