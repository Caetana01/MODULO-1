# Entrega MODULO-1
**Los Inductores**

<p align="center">
  <img src="https://raw.githubusercontent.com/Caetana01/MODULO-1/refs/heads/main/Logo.png"/>
</p>


| APELLIDO Y NOMBRE | CORREO ELECTRÓNICO | TELEFONO | REPOSITORIO INDIVIDUAL | REPOSITORIO DE ENTREGA |
| :------: | :------: | :------: | :------: | :------: |
| Bressan Joaquín | joaquinbressan04@gmail.com | 2613637754 | <https://github.com/aidenisquino> | <https://github.com/aidenisquino/modulo_1>|
| Don Ignacio | nachodon3@gmail.com | 2615899400 | <https://github.com/IgnacioDon> | <https://github.com/IgnacioDon/Modulo_1>|
| Leo Caetana | caeleocrimi11@gmail.com | 2617173770 | <https://github.com/Caetana01> | <https://github.com/Caetana01/modulo1>|
| Ludueña Alondra | pilaralondra789@gmail.com | 2615709845 | <https://github.com/alondraluduena> |<https://github.com/alondraluduena/Modulo_1>|
| Manassero Franco | nalentiva99@gmail.com | 2615703870 | <https://github.com/Franco-Manassero> | <https://github.com/Franco-Manassero/modulo_1.git>|

---
**EJERCICIO 1 Cómo crear, modificar y hacer el archivo README.md**

**EJERCICIO 2 Creación de un archivo html de forma manual**

**EJERCICIO 3 Crea un archivo LaTex en <https://overleaf.com>**

**EJERCICIO 4 Creación de notebooks**

**EJERCICIO 5 Creación de un CV en un archivo LATex**

**EJERCICIO 6 Creación de archivo con metadatos en el entorno R**

---
**Atajos en GoogleDocs en lenguaje MarkDown**

Tener en cuenta que para el uso de esos atajos hay que crear un documento en GoogleDocs dirigirse a la pestañas de Herramientas luego seleccionar la opción de preferencia y habilitar MarkDown.

## Formato de texto
| Acción | Atajo Windows / Linux | Atajo Mac |
|------|----------------|-----------|
| Negrita | Ctrl + B | Cmd + B |
| Cursiva | Ctrl + I | Cmd + I |
| Subrayado | Ctrl + U | Cmd + U |
| Tachado | Alt + Shift + 5 | Cmd + Shift + X |
| Borrar formato | Ctrl + \ | Cmd + \ |

## Tamaño y estilo de texto
| Acción | Atajo Windows / Linux | Atajo Mac |
|------|----------------|-----------|
| Aumentar tamaño de fuente | Ctrl + Shift + > | Cmd + Shift + > |
| Disminuir tamaño de fuente | Ctrl + Shift + < | Cmd + Shift + < |
| Aplicar título | Ctrl + Alt + 1–6 | Cmd + Option + 1–6 |
| Texto normal | Ctrl + Alt + 0 | Cmd + Option + 0 |

## Alineación
| Acción | Atajo Windows / Linux | Atajo Mac |
|------|----------------|-----------|
| Alinear izquierda | Ctrl + Shift + L | Cmd + Shift + L |
| Alinear centro | Ctrl + Shift + E | Cmd + Shift + E |
| Alinear derecha | Ctrl + Shift + R | Cmd + Shift + R |
| Justificar | Ctrl + Shift + J | Cmd + Shift + J |

## Listas
| Acción | Atajo Windows / Linux | Atajo Mac |
|------|----------------|-----------|
| Lista numerada | Ctrl + Shift + 7 | Cmd + Shift + 7 |
| Lista con viñetas | Ctrl + Shift + 8 | Cmd + Shift + 8 |
| Lista de verificación | Ctrl + Shift + 9 | Cmd + Shift + 9 |
| Aumentar sangría | Tab | Tab |
| Disminuir sangría | Shift + Tab | Shift + Tab |

## Edición
| Acción | Atajo Windows / Linux | Atajo Mac |
|------|----------------|-----------|
| Copiar | Ctrl + C | Cmd + C |
| Cortar | Ctrl + X | Cmd + X |
| Pegar | Ctrl + V | Cmd + V |
| Deshacer | Ctrl + Z | Cmd + Z |
| Rehacer | Ctrl + Y | Cmd + Shift + Z |
| Seleccionar todo | Ctrl + A | Cmd + A |

## Navegación
| Acción | Atajo Windows / Linux | Atajo Mac |
|------|----------------|-----------|
| Buscar | Ctrl + F | Cmd + F |
| Buscar y reemplazar | Ctrl + H | Cmd + Shift + H |
| Ir al inicio del documento | Ctrl + Home | Cmd + Fn + ← |
| Ir al final del documento | Ctrl + End | Cmd + Fn + → |

## Comentarios y colaboración
| Acción | Atajo Windows / Linux | Atajo Mac |
|------|----------------|-----------|
| Insertar comentario | Ctrl + Alt + M | Cmd + Option + M |
| Abrir historial de versiones | Ctrl + Alt + Shift + H | Cmd + Option + Shift + H |

## Otros útiles
| Acción | Atajo Windows / Linux | Atajo Mac |
|------|----------------|-----------|
| Insertar enlace | Ctrl + K | Cmd + K |
| Insertar salto de página | Ctrl + Enter | Cmd + Enter |
| Mostrar ayuda de atajos | Ctrl + / | Cmd + / |

---
**Resumen de colab**

# Guía Técnica: Google Colaboratory

Google Colab es un entorno de desarrollo basado en **Jupyter Notebook**. Permite la ejecución de código Python sin configuración local, proporcionando acceso a recursos de cómputo de alto rendimiento.

---

## 1. Interfaz y Componentes

* **Notebooks:** Archivos `.ipynb` almacenados en Google Drive.
* **Celdas de Código:** Bloques ejecutables de Python.
* **Celdas de Texto:** Documentación en formato Markdown y soporte para $\LaTeX$.
* **Panel Lateral:** Índice de secciones, búsqueda y explorador de archivos.

## 2. Configuración del Entorno (Runtime)

Para tareas de cómputo intensivo, se debe configurar el acelerador:

1. **Entorno de ejecución** > **Cambiar tipo de entorno de ejecución**.
2. Seleccionar **T4 GPU** o **TPU**.

## 3. Gestión de Librerías y Sistema

Colab incluye librerías científicas preinstaladas (NumPy, Pandas, Scikit-learn).

* **Instalación de paquetes:** `!pip install <nombre_paquete>`
* **Comandos de terminal:** Anteponer `!` (ej. `!ls`, `!pwd`, `!git clone`).

## 4. Persistencia de Datos

Los archivos locales se eliminan al finalizar la sesión. Para almacenamiento persistente, se monta Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')

```

## 5. Atajos de Teclado Principales

| Acción | Comando |
| --- | --- |
| **Ejecutar celda** | `Shift + Enter` |
| **Insertar celda (arriba/abajo)** | `Ctrl + M + A` / `Ctrl + M + B` |
| **Convertir a texto** | `Ctrl + M + M` |
| **Eliminar celda** | `Ctrl + M + D` |

---

$$e^{i\pi} + 1 = 0$$
