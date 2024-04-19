# Proyecto Final: Desarrollo de un Servicio

## Parte 1

### Desarrollo del Servicio y publicación

**Objetivo**

- Crear un servicio API REST o un servidor web con al menos 2 endpoints o páginas según corresponda.

- Utilizar un marco de desarrollo para la implementación del servicio.
Documentar claramente la API, especificando los endpoints, métodos HTTP permitidos y el formato de los datos de solicitud y respuesta.


### Container y Publicación

- Crear una o varias imagenes Docker del servicio desarrollado.
- Publicar la imagen en Google Cloud Artifact Registry.
  

### Implementación del Pipeline

**Objetivo**

- Crea con Terraform la cuenta de servicio para habilitar al Pipeline para interactuar con la nube seleccionada.

- Crear un pipeline que automatice el proceso de construcción, almacenamiento y despliegue del servicio.

- Configurar el pipeline para ejecutarse automáticamente cuando se realicen cambios en el repositorio del proyecto.

- Definir un flujo de trabajo para integrar nuevos features. Se recomienda [feature-branch](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)


### Parte 2

Integrar al proyecto:

- Controles de calidad
- Logging GCP y Queries
- Gestión ambientes Staging y Producción


### Parte 3

Integrar al proyecto:

- Métricas, análisis, Alarmas y Paneles
- Agrega con Terraform y el módulo [google_monitoring_dashboard](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/monitoring_dashboard) el dashboard principal de tu proyecto.


¡Éxito!
