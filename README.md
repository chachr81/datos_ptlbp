# Catálogo Geo PTLBP

Este repositorio contiene un notebook para acceder a los servicios de almacenamiento de datos geoespaciales de la Plataforma Tecnológica Línea de Base Pública (PTLBP).

## Contenido

- **Notebook**: `notebook/servicios_geoespaciales.ipynb`
  - Acceso a servicios WFS.
  - Listado de capas disponibles.
  - Descarga de datos geoespaciales en formatos como GeoJSON, Shapefile y GeoPackage.

- **Requisitos**: Archivo `requirements.txt` con las dependencias necesarias.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/catalogo_geo_ptlbp.git
   cd catalogo_geo_ptlbp
   ```

2. Crea y activa un entorno virtual:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Navega al directorio del notebook:
   ```bash
   cd notebook
   ```

2. Inicia Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Abre el archivo `servicios_geoespaciales.ipynb` y sigue las instrucciones.

## Estructura del Proyecto

- `notebook/`: Contiene el notebook principal.
- `data/`: Directorio para almacenar datos descargados.
- `.venv/`: Entorno virtual (ignorado por Git).
- `requirements.txt`: Lista de dependencias.

## Contribuciones

Si deseas contribuir, por favor abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.