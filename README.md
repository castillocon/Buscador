
# 🗂️ Buscador Avanzado de Archivos

**Buscador** es una aplicación de escritorio desarrollada en Python con `customtkinter` que permite realizar búsquedas potentes y detalladas de archivos en todo el sistema.

Este programa puede ejecutarse como script `.py` o como aplicación ejecutable `.exe` para Windows, sin necesidad de tener Python instalado. Se adjunta la versión `.exe` en la sección de *Releases* de este repositorio.

---

## 🧰 Funcionalidades Principales

- 🔍 **Búsqueda por nombre de archivo** usando patrones como `*.pdf`, `informe_*.docx`, etc.
- 📁 **Exploración por unidad** (ej: `C:`, `D:`) con posibilidad de establecer profundidad máxima.
- 🧠 **Búsqueda por contenido** dentro de archivos (`.txt`, `.pdf`, `.docx`, `.xlsx`, etc.)
- 📅 **Filtro por fecha** de última modificación (últimos días o rango personalizado).
- 📏 **Filtro por tamaño** (mínimo y máximo en KB).
- 🚫 **Exclusión de carpetas** como `node_modules`, `.git`, `__pycache__`, etc.
- 🧠 **Historial de búsquedas** reciente disponible desde un menú desplegable.
- 💾 **Guardar resultados** en formatos `.txt`, `.csv` o `.json`.
- 🎨 **Interfaz moderna** con modo claro y oscuro automático.
- ⚡ **Ejecución multi-hilo** para mejorar el rendimiento de las búsquedas.

---

## 🔍 ¿Cómo funciona la búsqueda?

1. Ingresá la unidad (por ejemplo `C:`) y el patrón que querés buscar (ej: `*.docx`).
2. Opcionalmente, podés:
   - Activar la búsqueda por contenido e ingresar una palabra clave.
   - Establecer un rango de fechas de modificación.
   - Filtrar por tamaño mínimo/máximo.
   - Limitar la profundidad de subcarpetas.
   - Excluir carpetas específicas.
3. Presioná **Buscar** y el programa recorrerá el disco, listando los archivos que coincidan.
4. Se muestra una barra de progreso y podés cancelar la búsqueda en cualquier momento.
5. Los resultados se pueden abrir directamente o guardar en distintos formatos.

---

## 📦 Archivos disponibles

- `buscador.py` → Código fuente (recomendado para programadores).
- `buscador.exe` → Ejecutable de Windows (en la sección de *Releases*).
  - ✅ No requiere Python instalado.
  - 📁 Puede copiarse a un pendrive y ejecutarse desde cualquier PC con Windows.

---

## 🛠️ Requisitos (solo para la versión `.py`)

Si querés ejecutar el script directamente desde Python:

```bash
pip install customtkinter PyPDF2 python-docx pandas openpyxl
```

---

## 🚀 Ejecución

### ✔️ Como `.exe`:

1. Descargá el archivo `buscador.exe` desde [Releases](../../releases).
2. Hacé doble clic para ejecutar.

### 🐍 Como script Python:

```bash
python buscador.py
```

---

--

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Podés usarlo, modificarlo y distribuirlo libremente.

---
