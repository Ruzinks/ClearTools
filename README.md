# 🛠️ ClearTools

**ClearTools** es un ecosistema modular de herramientas y utilidades de línea de comandos desarrolladas en Python. Está diseñado para alojar aplicaciones autónomas enfocadas en la productividad, procesamiento de medios, gestión de documentos y automatización de tareas.

La herramienta insignia de la suite es **Clai** *(Command Line Interface)*, una consola interactiva avanzada diseñada para simplificar el procesamiento de archivos sin depender de terminales complejas.

---

## 🚀 Descarga Rápida

No necesitas instalar Python ni configurar entornos para probar la herramienta principal de la suite:

[![Descargar Clai](https://img.shields.io/badge/Descargar-Clai.exe%20v1.0.0-brightgreen?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Ruzinks/ClearTools/releases/latest/download/Clai.exe)

> 💡 **¿Buscas el ejecutable portátil?** [Descarga Clai.exe directamente aquí](https://github.com/Ruzinks/ClearTools/releases/latest/download/Clai.exe) y haz doble clic para iniciar la consola.

---

## 📦 Suite de Herramientas

Actualmente, **ClearTools** incluye:

* **⚡ Clai (Command Line Interface):** Consola interactiva autónoma con descarga de medios (MP3/MP4 desde YouTube), lectura/conversión/manipulación de documentos PDF y gestión del sistema de archivos.
* *(Próximamente...)* Nuevos módulos y utilidades en desarrollo para la suite.

---

## 💡 Filosofía del Proyecto

* **100% Local y Gratuito:** Sin suscripciones, consumo de tokens ni necesidad de API Keys externas.
* **Interfaz Limpia en Consola:** Renderizado gráfico visualmente atractivo en terminal con tablas y alertas formateadas.
* **Multiplataforma:** Diseñado para mantener la misma experiencia en Windows, Linux y macOS.
* **Arquitectura Escalable:** Estructura modular preparada para añadir nuevas herramientas fácilmente.

---

## 📂 Estructura del Repositorio

```text
ClearTools/
├── clai/                    # Paquete fuente de la herramienta Clai
│   ├── __init__.py
│   ├── __main__.py          # Punto de entrada de Clai
│   ├── cli.py               # Motor REPL de la consola
│   ├── core/
│   │   ├── __init__.py
│   │   └── console.py       # Renderizado visual y consola
│   └── modules/
│       ├── __init__.py
│       ├── media.py         # Descargas de medios (YouTube/MP3)
│       ├── pdf.py           # Operaciones con documentos PDF
│       └── sysops.py        # Comandos del sistema de archivos
├── README.md                # Presentación principal de ClearTools
└── requirements.txt         # Dependencias del proyecto
