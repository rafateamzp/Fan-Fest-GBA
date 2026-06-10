# 🗺️ Pantallas Gigantes del Mundial - Gran Buenos Aires

Un mapa interactivo desarrollado en **R** utilizando la librería **Leaflet**, que muestra la ubicación de las pantallas gigantes donde se podrán ver los partidos del Mundial de Fútbol en el Gran Buenos Aires.

## ⚽ Características del Mapa

- **Interactivo:** Zoom y navegación fluida.
- **Estilo Nocturno:** Diseño moderno con fondo oscuro (`CartoDB DarkMatter`).
- **Detalles al Clic:** Al hacer clic en cada marcador de pelota de fútbol, se despliega información detallada:
  - Nombre del lugar
  - Barrio / Zona
  - Dirección exacta
  - Estado de confirmación del evento. Algunos sitios no se confirman como oficial ya que esta sujeto a condiciones meteorológicas.

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** R
- **Librerías:** `leaflet`, `readxl`, `dplyr`, `htmlwidgets`
- **Despliegue:** GitHub Pages
- **Datos:** Coordenadas geográficas proporcionadas por Google Maps.

## 🚀 Cómo usar

Para visualizar el mapa, simplemente haz clic en el archivo `index.html` o visita el enlace desplegado.

Si deseas **actualizar** o generar nuevos datos:
1. Asegurarse de tener las columnas: `Latitud`, `Longitud`, `Nombre`, `Barrio`, `Dirección`, `Estado`.
2. Ejecutar el script de R actualizado.
3. Generar un nuevo `index.html`.
4. Reemplazar el archivo en este repositorio y hacer *Commit*.

## 📍 Datos Cubiertos

Actualmente incluye [12] ubicaciones en el Gran Buenos Aires. Los puntos se actualizan constantemente según confirmación de eventos.

---
## Autoría
*Desarrollado con ❤️ y R *
* Rafael Zerpa / GeckoGIS *
