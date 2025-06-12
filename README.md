Descripción
Este proyecto es un bot de automatización desarrollado en Python que realiza dos funciones principales:

Llenado de formularios web: Toma datos de un archivo Excel y los ingresa registro por registro en un formulario web.

Validación de datos: Permite validar los datos de un archivo Excel según reglas de negocio personalizables por el usuario.

El proyecto incluye un instalador para facilitar su despliegue.

Características principales
Automatización de interacción web

Procesamiento de archivos Excel

Sistema de reglas de negocio configurables

Interfaz de usuario intuitiva

Instalador incluido

Estructura del proyecto
text
/crear_hc          - Carpeta con recursos para creación de ejecutables
/dist              - Carpeta con distribuciones generadas
/img               - Imágenes utilizadas en la aplicación
/pyinstaller       - Configuraciones para PyInstaller
/venv              - Entorno virtual Python (ignorar en despliegue)

.gitignore         - Archivo para ignorar en control de versiones
__version__.py     - Control de versiones
areas.json         - Configuración de áreas
bases.json         - Configuración de bases de datos
environment.yml     - Configuración de entorno Conda
error_log.txt      - Registro de errores
fondo.jpg          - Imagen de fondo
get-pip.py         - Script para obtener pip
index.py           - Archivo principal de la aplicación
index.spec         - Configuración para PyInstaller
info para ejecutable.txt - Instrucciones para crear ejecutable
info_leeme.txt     - Documentación adicional
install_dependencies.bat - Script para instalar dependencias
logo.ico           - Icono de la aplicación
0din.py            - Módulo principal del bot
0din.spec          - Configuración alternativa para PyInstaller
requirements.txt   - Dependencias de Python
setup.iss          - Script para crear instalador con Inno Setup
setup.py           - Script de configuración del proyecto
version.txt        - Control de versiones
Requisitos del sistema
Windows 10/11

Python 3.8 o superior

Navegador web (Chrome recomendado)

Instalación
Ejecutar el instalador setup.exe (generado a partir de setup.iss)

Seguir las instrucciones del asistente de instalación

Instalación manual
Clonar el repositorio

Ejecutar install_dependencies.bat para instalar dependencias

Crear un entorno virtual (recomendado)

Uso
Ejecutar 0din.py o el archivo ejecutable generado

Seleccionar modo de operación (llenado o validación)

Seleccionar archivo Excel de entrada

Para validación, cargar o crear reglas de negocio

Iniciar el proceso

Configuración
Las reglas de negocio se pueden crear/modificar desde la interfaz

Configuraciones avanzadas en areas.json y bases.json

Soporte
Para reportar problemas, consultar el archivo error_log.txt y proporcionar su contenido al solicitar soporte.

Licencia
[Inserte información de licencia aquí]

Notas
El proyecto incluye configuraciones para generar ejecutables con PyInstaller

Se recomienda usar el entorno virtual incluido (/venv) para desarrollo
