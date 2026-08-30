# ClearTools

**ClearTools** es un ecosistema modular de herramientas y utilidades de línea de comandos en Python. Diseñado para alojar múltiples aplicaciones autónomas, combina procesamiento de archivos, automatización y gestión de medios en un solo lugar.

La herramienta principal de la suite es **CLAI** *(Command Line Interface)*, una consola interactiva avanzada diseñada para reemplazar la necesidad de comandos del sistema nativo al realizar tareas de medios y gestión de documentos.

---

## Suite de Herramientas

Actualmente, **ClearTools** integra las siguientes herramientas:

* **CLAI (Command Line Interface):** Consola interactiva autónoma con soporte para navegación de archivos, descargas de medios (YouTube/Audio/Video en MP3/MP4) y manipulación de documentos PDF.
* *(Próximamente...)* Nuevas utilidades y módulos en desarrollo.

---

## Filosofía del Proyecto

* **100% Gratuito y Local:** Funciona en tu equipo sin necesidad de claves API ni suscripciones de pago.
* **Consola Interactiva Propia (CLAI):** Motor REPL dedicado con historial de comandos y estilo gráfico enriquecido en terminal.
* **Agnóstico al Sistema Operativo:** Misma experiencia y sintaxis en Windows, Linux y macOS.
* **Arquitectura Escalable:** Preparado para incorporar nuevas aplicaciones dentro de la suite ClearTools.

---

## Estructura del Repositorio

```text
ClearTools/
├── cleartools/              # Paquete principal de la suite
│   ├── __init__.py
│   ├── __main__.py          # Punto de entrada de CLAI
│   ├── cli.py               # Motor REPL de la consola CLAI
│   ├── core/
│   │   ├── __init__.py
│   │   └── console.py       # Renderizado de consola interactiva
│   └── modules/
│       ├── __init__.py
│       ├── media.py         # Módulo de descargas (YouTube/MP3)
│       ├── pdf.py           # Módulo de lectura/escritura de PDF
│       └── sysops.py        # Módulo de operaciones de sistema
├── README.md
└── requirements.txt

Por Clearline :)