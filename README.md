# 🤖 Bot de Automatización Web con Python

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/Licencia-MIT-green)
![Status](https://img.shields.io/badge/Estado-Activo-brightgreen)

## 📝 Descripción
Bot de automatización desarrollado en Python que permite:
1. **Autollenado de formularios web** desde archivos Excel
2. **Validación de datos** con reglas de negocio personalizables

## ✨ Características principales
- 🖥️ Automatización web con Selenium
- 📊 Procesamiento de archivos Excel (xlsx, csv)
- ⚙️ Sistema de reglas de negocio configurables
- � Interfaz intuitiva
- 📦 Instalador incluido (Inno Setup)
- 🛠️ Configuración para PyInstaller

## 📂 Estructura completa del proyecto

```bash
.
├── /crear_hc/          # Recursos para creación de ejecutables
├── /dist/              # Distribuciones generadas (ejecutables)
├── /img/               # Assets visuales (imágenes/iconos)
├── /pyinstaller/       # Configuraciones para PyInstaller
├── /venv/              # Entorno virtual Python (ignorar en producción)
│
├── .gitignore          # Archivos ignorados por Git
├── __version__.py      # Control de versiones del software
├── areas.json          # Configuración de áreas/segmentos
├── bases.json          # Configuración de bases de datos
├── environment.yml     # Configuración de entorno Conda
├── error_log.txt       # Registro de errores de la aplicación
├── fondo.jpg           # Imagen de fondo para la interfaz
├── get-pip.py          # Instalador de pip alternativo
├── index.py            # Punto de entrada alternativo
├── index.spec          # Configuración para PyInstaller (alternativa)
├── info_leeme.txt      # Documentación adicional
├── install_dependencies.bat  # Script de instalación de dependencias
├── logo.ico            # Icono de la aplicación
├── 0din.py             # Módulo principal del bot (entry point)
├── 0din.spec           # Configuración principal para PyInstaller
├── requirements.txt    # Dependencias de Python
├── setup.iss           # Script para crear instalador con Inno Setup
├── setup.py            # Script de configuración del proyecto
└── version.txt         # Control de versiones legible


