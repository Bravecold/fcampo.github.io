# fcampo.github.io

Sitio profesional estático de Fabián Alberto Campo Henríquez.

## Publicación

Este repositorio es la fuente única del sitio y publica el mismo `index.html` en dos destinos:

- GitHub Pages
- Azure Storage Static Website: https://cs2100320009ddcadbe.z13.web.core.windows.net/

Los despliegues se ejecutan al integrar cambios en `main`.

## Configuración requerida

### GitHub Pages

En **Settings → Pages → Build and deployment**, selecciona **GitHub Actions** como origen.

### Azure Storage

Crea el secreto de Actions `AZURE_STORAGE_CONNECTION_STRING` en **Settings → Secrets and variables → Actions**. Debe contener la cadena de conexión de la cuenta de almacenamiento `cs2100320009ddcadbe`.

No almacenes la cadena de conexión en archivos, commits ni logs.
