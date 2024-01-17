# Proyecto Final: Desarrollo de un Servicio

## Parte 1

### Desarrollo del Servicio y publicación

**Objetivo**

- Crear un servicio API REST o un servidor web en Python con al menos 2 endpoints o páginas según corresponda.

- Utilizar un marco de desarrollo como Flask o FastAPI para la implementación del servicio.
Documentar claramente la API, especificando los endpoints, métodos HTTP permitidos y el formato de los datos de solicitud y respuesta.
Integración con GCP:

- Crear un script Bash que utilice la CLI gcloud para consultar la lista de usuarios (o principals) del proyecto "curso-devops" en GCP.
Guardar el resultado en formato CSV en un archivo.
Asegurarse de que este archivo esté disponible y accesible desde la aplicación creada.

### Container y Publicación en Cloud Run

- Crear una imagen Docker del servicio API desarrollado.
- Publicar la imagen en Google Cloud Artifact Registry.
- Crear un archivo Dockerfile para construir la imagen Docker.

### Implementación del Pipeline

**Objetivo**

- Crear un pipeline que automatice el proceso de construcción, almacenamiento y despliegue del servicio API.

- Configurar el pipeline para ejecutarse automáticamente cuando se realicen cambios en el repositorio del proyecto.

- Utilizar Github Actions para configurar el pipeline.
Definir dos pasos en el pipeline:

  - Paso 1: Ejecutar el script Bash que consulta la lista de usuarios de GCP y almacena el resultado en formato CSV. Construir la imagen Docker del servicio API.
  - Paso 2: Publicar la imagen en Artifact Registry y desplegarla en Cloud Run.


### Entregables

- Código fuente del servicio API.
- Documentación clara y detallada.
- Script Bash para consultar usuarios en GCP y generar el archivo CSV.
- Archivo Dockerfile para construir la imagen Docker.
- Configuración del pipeline en Cloud Build.

### Evaluación

- Revisión a través de Pull Request "Feedback"
- Funcionalidad del servicio.
- Correcta integración con GCP servicios (Artifact Registry, Cloud Run).
- Automatización exitosa del pipeline incluyendo ambientes distintos para s
- Documentación sobre ejecución, variables necesarias para correr en local, como probar la imagen docker en local, etc

### Parte 2

[Pendiente]
- Controles de calidad
- Logging GCP y Queries
- Gestión ambientes Staging y Producción

### Parte 3

[Pendiente]
- Métricas, análisis, Alarmas y Paneles
- Proyecto integración con Terraform para crear:
  - Cuentas para Pipeline
  - Reglas de acceso para Cloud Run
  - Informes

### Sobre Accesos de GCP

- En caso de contar con alguna cuenta de servicio que no tenga los suficientes permisos para interactuar con algún producto de Google solicitar al administrador de la cuenta que sume los accesos requeridos.

- Si no se cuenta con ideas para aplicación, se pueden reutilizar cualquiera que haya sido presentada en los laboratorio del curso.

- No olvidar crear archivos para ignorar credenciales o información sensible.

¡Éxito!
