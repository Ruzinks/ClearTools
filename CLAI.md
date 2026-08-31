# Clai

**Clai** es una herramienta multipropósito de escritorio con interfaz gráfica basada en terminal oscura, diseñada para ejecutar operaciones de sistema, procesamiento de archivos PDF y descarga de contenido multimedia.

---

## 🎨 Características

* **Interfaz Oscura Elegante:** Construida sobre `customtkinter` con paleta en tonos carbón y gris oscuro (`#121212`).
* **Terminal Integrada:** Consola interactiva de salida en modo lectura para evitar modificaciones accidentales del texto.
* **Descarga de Medios:** Descarga de videos e interacciones de audio (`get <URL>`).
* **Herramientas PDF:** Lectura, conversión de `.txt` a `.pdf` y extracción de páginas.
* **Utilidades de Sistema:** Navegación de directorios, información del sistema y comandos rápidos.
* **Branding Integrado:** Comando `logo` para desplegar el emblema en arte ASCII a petición.

---

## 📜 Historial de Versiones y Novedades

### [v1.2.0] - 30/08/26
#### Añadido
- **Módulo de Temas Persistentes (`theme`):** Selección y guardado de temas visuales (`dark`, `matrix`, `dracula`).
- **Gestor de Tareas integradas (`todo`):** Comandos `add`, `list` y `clear` con almacenamiento local.
- **Herramientas Web:** Comandos `wiki` (resumen rápido de Wikipedia) e `ip` (consulta de IP pública).
- **Persistencia de Configuración:** Creación automática de `clai_config.json` para mantener el estado entre sesiones.

#### Mejoras
- Normalización automática de rutas arrastradas (soporte para eliminación de comillas en `Entry`).
- Manejo de excepciones mejorado en la captura de pantalla (`execute_with_capture`).

---

### [v1.1.0] - 30/08/26
#### Añadido
- **Módulo PDF (`pdf`):** Lectura, inspección de metadatos, conversión de TXT a PDF y extracción de páginas (`pdf copy`).
- **Descargas Multimedia (`get`):** Integración con `yt-dlp` para extracción de video y audio MP3.
- **Manejo del Historial:** Navegación por comandos anteriores con las teclas `Flecha Arriba` y `Flecha Abajo`.

---

### [v1.0.1] - 29/08/26
#### Añadido
- Lanzamiento inicial de **Clai**.
- Interfaz gráfica basada en `CustomTkinter`.
- Comandos básicos de sistema: `list`, `goto`, `cat`, `open`, `sys`, `info`, `clear` y `logo`.

---

## 🚀 Uso Rápido (Entorno Python)

Para ejecutar la aplicación desde el código fuente:

```bash
python -m clai
