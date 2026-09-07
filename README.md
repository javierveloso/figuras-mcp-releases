# Figuras MCP · descargas oficiales

Este repositorio público contiene exclusivamente el canal estable de instalación y actualización de **Figuras MCP**. El desarrollo se mantiene en un repositorio privado.

## Descargar

Abre siempre la [versión estable más reciente](https://github.com/javierveloso/figuras-mcp-releases/releases/latest) y descarga el archivo de tu sistema:

- **Windows 10/11 x86-64:** `FigurasMCP-<versión>-windows-x86_64.zip`. Extrae el ZIP y ejecuta `INSTALAR EN WINDOWS.cmd`.
- **Zorin OS/Ubuntu x86-64:** `figuras-mcp-<versión>-linux-x86_64.tar.gz`. Extrae el paquete y ejecuta `INSTALAR EN LINUX.sh`.
- **Verificación:** `SHA256SUMS.txt` contiene la huella de ambos paquetes.

Cada paquete incluye la guía detallada, el complemento de Blender, el servidor MCP y la Skill de Codex. No contiene modelos, tokens, preferencias personales, el entorno `.venv`, Bambu Studio ni el contenido de `workspace`.

## Avisos de actualización

El archivo [`latest.json`](latest.json) es el canal estable que consulta Figuras MCP. La aplicación guarda el resultado durante 24 horas y muestra un aviso en Blender cuando existe una versión superior.

La comprobación sólo descarga ese manifiesto público. No envía escenas, modelos, nombres de archivos, rutas ni estadísticas de uso. Tampoco descarga o instala actualizaciones automáticamente.

## Seguridad y licencia

Comprueba el SHA-256 antes de instalar. Figuras MCP sólo enlaza versiones publicadas en este repositorio y rechaza manifiestos con otro producto, formato u origen.

El código incluido dentro de los paquetes se distribuye bajo GPL-3.0-or-later. Bambu Studio se instala por separado y conserva su propia licencia.
