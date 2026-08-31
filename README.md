# Clai

**Clai** es una aplicación portátil e independiente para Windows con interfaz gráfica basada en terminal oscura. Permite ejecutar herramientas de sistema, manipulación de archivos PDF y descarga de contenido multimedia sin dependencias externas.

---

## Novedades de la Versión 1.0.1

* **Ejecutable Único (.exe):** Funciona como un solo archivo portátil. No requiere instalación de Python ni descompresión de carpetas.
* **Interfaz Nativa Oscura:** Diseño minimalista con paleta en tonos carbón (`#121212`) sin ventanas secundarias de consola de comandos (CMD/PowerShell).
* **Consola Protegida:** La pantalla de salida funciona en modo de solo lectura para evitar la edición o modificación accidental del historial de respuestas.
* **Comando Logo:** Incluye el nuevo comando `logo` para desplegar el arte ASCII oficial en pantalla.

---

## Comandos Disponibles

Escribe los siguientes comandos dentro de la barra de entrada de **Clai**:

### Medios
* `get <URL>` — Descarga video en formato MP4.
* `get <URL> --audio` — Extrae y convierte la pista de audio a formato MP3.

### Documentos PDF
* `pdf read <archivo.pdf>` — Muestra el texto extraído en pantalla.
* `pdf write <entrada.txt> <salida.pdf>` — Convierte un archivo de texto plano a PDF.
* `pdf copy <origen.pdf> <destino.pdf> <inicio> <fin>` — Copia un rango de páginas a un nuevo archivo PDF.

### Sistema y Utilidades
* `list [ruta]` (o `ls`) — Lista los archivos y carpetas del directorio.
* `goto <directorio>` (o `cd`) — Cambia el directorio de trabajo.
* `info` — Muestra detalles del entorno actual.
* `clear` — Limpia la pantalla de salida.
* `logo` — Despliega el arte ASCII de Clai.
* `help` — Muestra el menú con la lista de comandos.
* `exit` (o `quit`) — Cierra la aplicación.

---

## Uso Rápido

### Modo Ejecutable (Windows)
1. Descarga **`Clai.exe`**.
2. Haz doble clic para ejecutar directamente.

### Desde el Código Fuente
```bash
python -m clai
