# Trading Journal

Journal de trading personal que funciona **fuera de Claude** (no usa tokens). Todo se guarda en tu dispositivo.

## Cómo abrirlo

**PC (Chrome o Edge):** descarga la carpeta `trading-journal` y abre `index.html` con doble clic.
Recomendado: en *Ajustes y respaldo → Elegir carpeta de respaldo* selecciona una carpeta (ej. `Documentos/Respaldo Trading`).
Desde ese momento, cada cambio se copia ahí automáticamente:

- `journal-datos.json` → todos tus datos
- `media/` → tus fotos y videos
- `historial/` → una copia por día

Si el navegador pide permiso al volver a abrir, toca el aviso naranja "Reconectar carpeta".

**Tablet:** lo ideal es publicarlo en GitHub Pages (Settings → Pages del repositorio) y abrirlo desde esa dirección,
luego *Compartir → Agregar a pantalla de inicio*. Así funciona como una app, también sin internet, y el navegador no borra los datos.

## Pasar datos entre PC y tablet
Cada dispositivo guarda sus propios datos. Para sincronizar: *Exportar respaldo completo* en uno
y *Importar y combinar* en el otro.

## Pestañas
Resumen (semáforo de reglas del día, indicadores, calendario) · Plan de negocio (editable, con versiones) ·
Journal real · Backtesting (tabla tipo Excel con riesgo 1 / 1.5 / 2 %) · Tareas de mentoría · Bitácora emocional ·
Análisis IA (rango de fechas, patrones, fortalezas, debilidades, fugas de rentabilidad; queda guardado) · Ajustes.

Cada sección tiene 👁 para ocultarla y ▾ para contraerla. Las pestañas se ocultan en Ajustes.

## IA
El análisis de patrones es local y gratis. Opcional: pegar una clave de API de Anthropic en Ajustes para
conversar con Claude dentro del journal (se cobra por uso en esa cuenta de API), o usar el botón
"Copiar resumen para pegar en Claude".
