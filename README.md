# Prueba Práctica — Unidad IV

Repositorio correspondiente al desarrollo individual de la **Prueba Práctica de la Unidad IV** de la asignatura **Ingeniería de Requisitos (ISR-401)**.

El trabajo desarrolla el caso **Sistema de Gestión de Pedidos** e incluye los modelos UML, requisitos, validación, priorización, pruebas de aceptación, trazabilidad y gestión del cambio solicitados en la evaluación.

## Estructura del repositorio

```text
Prueba_Unidad_IV/
│
├── Evaluacion_Unidad_IV_Herrera_Thais.tex
├── Evaluacion_Unidad_IV_Herrera_Thais.pdf
├── README.md
│
├── figuras/
│   ├── diagrama_clases.png
│   ├── diagrama_actividades.png
│   └── diagrama_estado.png
│
├── evidencias/
│   ├── evaluación_manualmente.pdf
│   ├── evidencias.md
│   ├── resumen_sga.png
│   └── revisión_intento_sga.pdf
│
└── prueba/
    └── prueba_unidad_IV.pdf
```

## Archivo principal

El archivo principal utilizado para generar el documento es:

```text
Evaluacion_Unidad_IV_Herrera_Thais.tex
```

Este archivo contiene el desarrollo completo de las actividades prácticas de la evaluación e incorpora los diagramas y evidencias correspondientes.

## Figuras

La carpeta `figuras/` contiene los tres modelos UML utilizados durante el desarrollo:

* `diagrama_clases.png`: diagrama de clases del Sistema de Gestión de Pedidos.
* `diagrama_actividades.png`: diagrama del proceso de registro de un pedido.
* `diagrama_estado.png`: máquina de estados correspondiente al ciclo de vida de un pedido.

## Evidencias

La carpeta `evidencias/` conserva los archivos utilizados como respaldo de la evaluación:

* `resumen_sga.png`: captura del resumen del cuestionario realizado en el SGA.
* `revisión_intento_sga.pdf`: evidencia de la revisión del intento.
* `evaluación_manualmente.pdf`: evidencia de la evaluación desarrollada manualmente.
* `evidencias.md`: información complementaria de las evidencias.

## Documento de la prueba

La carpeta `prueba/` contiene:

```text
prueba_unidad_IV.pdf
```

Este documento corresponde al material de la prueba práctica de la Unidad IV.

## Compilación reproducible

El documento está desarrollado en LaTeX y puede generarse nuevamente a partir del archivo fuente incluido en el repositorio.

### Compilador

Utilizar:

```text
pdfLaTeX
```

### Comandos de compilación

Desde la raíz del repositorio ejecutar:

```bash
pdflatex -interaction=nonstopmode -halt-on-error Evaluacion_Unidad_IV_Herrera_Thais.tex
```

Se recomienda ejecutar el comando una segunda vez:

```bash
pdflatex -interaction=nonstopmode -halt-on-error Evaluacion_Unidad_IV_Herrera_Thais.tex
```

El archivo resultante será:

```text
Evaluacion_Unidad_IV_Herrera_Thais.pdf
```

## Compilación en Overleaf

El documento también puede compilarse utilizando Overleaf:

1. Descargar o clonar el repositorio completo.
2. Subir todos los archivos a un nuevo proyecto de Overleaf conservando la estructura de carpetas.
3. Establecer `Evaluacion_Unidad_IV_Herrera_Thais.tex` como documento principal.
4. Seleccionar **pdfLaTeX** como compilador.
5. Recompilar el proyecto.

Los nombres y ubicaciones de las imágenes deben conservarse para que puedan ser localizadas correctamente durante la compilación.

## Reproducibilidad

El repositorio conserva el código fuente en LaTeX, los diagramas UML, las evidencias de la evaluación y los documentos PDF correspondientes. De esta manera, el documento final puede reproducirse directamente a partir de `Evaluacion_Unidad_IV_Herrera_Thais.tex`.

