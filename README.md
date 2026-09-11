# Vault de Contactos - API REST

API desarrollada con ASP.NET Core y Entity Framework Core (SQLite) para la gestión de una agenda de contactos personal. El proyecto está completamente contenerizado mediante Docker para asegurar su portabilidad y ejecución aislada.

## Requisitos del Sistema

- Docker Desktop instalado y en ejecución en el equipo.

## Instrucciones de Instalación y Ejecución

Ubicado en la carpeta raíz del proyecto donde se encuentra el archivo `Dockerfile`, abre la terminal y ejecuta los siguientes comandos:

1. **Construir la imagen de Docker:**
   ```bash
   docker build -t vault-contactos-api .