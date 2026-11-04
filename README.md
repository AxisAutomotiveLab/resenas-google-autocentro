# Reseñas de Google – Autocentro

## Enlace del dashboard
[Abrir dashboard de reseñas](https://axisautomotivelab.github.io/resenas-google-autocentro/?key=cd0cb8eb15be4d34)

Dashboard de reseñas de Google de Autocentro:
Toyota, Nissan, Chrysler, AC+ San Juan y AC+ Guaynabo.

## Cómo funciona
- Las reseñas se sincronizan cada hora desde la API de Google Business Profile
  (Apps Script "Sync Reseñas Google") hacia las hojas de cada marca.
- Esta página no guarda datos: al abrirla, los pide en vivo al Apps Script.
- Es solo de lectura. Las respuestas a reseñas se hacen en Google Business Profile.
- Para entrar se necesita el enlace completo con la clave de acceso
  (pídelo al equipo de BDC).

## Contenido
- **Filtros:** periodo, estrellas, estado y búsqueda.
- **Indicadores:** total, promedio, % positivas, tasa y tiempo de respuesta, pendientes.
- **Visuales:** comparación por marca, distribución de calificaciones y tendencia.
- **Reseñas:** tabla con respuestas, pestaña de pendientes y exportación a CSV.

## Mantenimiento
- `index.html` es la versión para GitHub del archivo `Dashboard.html` de Apps Script.
  Si cambia el diseño, hay que volver a subir `index.html`.
- Si se cambia el código de Apps Script, hay que publicar una nueva versión
  en la misma implementación para que el enlace no cambie.
