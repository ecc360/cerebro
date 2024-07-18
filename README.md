### Repositorio "cerebro"

Este repositorio contiene código relacionado con el proyecto **Cerebro**, diseñado para conectar y administrar índices en Elasticsearch.

**Propósito:**
Cerebro es una herramienta destinada a facilitar la administración de Elasticsearch, permitiendo la conexión y gestión eficiente de índices. Incluye scripts, configuraciones y recursos utilizados para el desarrollo y la administración del sistema.

**Funcionalidades:**
- Conexión fácil a clusters de Elasticsearch.
- Administración de índices, incluyendo creación, eliminación y configuración.
- Monitoreo y visualización de estadísticas de índices.

Este repositorio es útil para aquellos que necesitan una solución robusta para interactuar y administrar datos en Elasticsearch de manera efectiva.

### Construir imagen Docker
```bash
docker build -t cerebro -f Dockerfile .

### Construir contenedor Docker
```bash
docker run -it -p 9000:9000 --name cerebro cerebro

Puedes obtener la imagen directamente desde Docker Hub con:

```bash
docker pull ecc360/cerebro:v1
