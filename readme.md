
\# MyProyectoDevOps


Repositorio central del proyecto MyProyectoDevOps, diseñado bajo buenas prácticas de ingeniería de software y cultura DevOps. Integra el desarrollo de servicios (backend y frontend), gestión de base de datos, documentación técnica y flujos automatizados de Integración y Despliegue Continuo (CI/CD).

-------------Tabla de Contenidos---------------

Arquitectura y Estructura del Repositorio

Tecnologías y Herramientas

Prerrequisitos

Instalación y Configuración

Automatización CI/CD

Licencia y Autor

------------Arquitectura y Estructura del Repositorio----------------

El proyecto sigue una separación modular para facilitar el mantenimiento, escalabilidad y despliegue independiente de sus componentes:

MyProyectoDevOps
│
├── backend/             # API, lógica de negocio y servicios del servidor
├── frontend/            # Interfaz de usuario y aplicación cliente
├── database/            # Scripts SQL, migraciones, esquemas y semillas
├── docs/                # Manuales técnicos, diagramas y guías de arquitectura
├── images/              # Recursos gráficos y capturas de evidencia
├── .github/
│   └── workflows/       # Pipelines automatizados de GitHub Actions (CI/CD)
│
├── .gitignore           # Exclusión de archivos temporales, credenciales y dependencias
├── LICENCE              # Términos legales de uso (Licencia MIT)
└── readme.md            # Documentación principal del proyecto


----------Tecnologías y Herramientas--------------

Control de Versiones: Git & GitHub

Automatización (CI/CD): GitHub Actions

Arquitectura: Separación por capas (Frontend / Backend / Base de Datos)

Documentación: Markdown

 ------------------Prerrequisitos---------------

Antes de clonar y ejecutar este proyecto en tu entorno local, asegúrate de contar con:

Git instalado (git --version)

Editor de código recomendado: Visual Studio Code

Acceso a una cuenta de GitHub con permisos sobre el repositorio

------------ Instalación y Configuración----------------

Clonar el repositorio:

git clone https://github.com/pelucas255/MyProyectoDevOps.git


Ingresar al directorio del proyecto:

cd MyProyectoDevOps


Configurar variables de entorno:
Crea un archivo .env en las carpetas backend/ y frontend/ según corresponda (este archivo está protegido por .gitignore para no exponer credenciales).

Revisar documentación específica:
Consulta la carpeta docs/ para detalles sobre el levantamiento de servicios y scripts de database/.

---------- Automatización CI/CD ---------------------

La carpeta .github/workflows/ contiene las definiciones en formato YAML para ejecutar validaciones automáticas, pruebas y despliegues cada vez que se realiza un push o pull request hacia la rama principal (main).

--------------Licencia y Autor -----------------------

Este proyecto está distribuido bajo la Licencia MIT. Consulta el archivo LICENCE para más detalles.

Autor: Alexis Dominguez Esponda (@pelucas255)