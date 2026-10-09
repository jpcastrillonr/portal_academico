# Portal académico - Gestión de notas y asistencia

Interfaz web para una institución educativa que permite consultar y registrar notas y asistencias. Proyecto de la materia **Introducción a la programación** (CESDE), segundo momento: capa visual con **HTML semántico y CSS puro**.

## Equipo

|Integrante|Documento|
|-|-|
|*Juan Pablo Castrillon Rendon*|*1001226410*|
|*Juan Daniel Gil Barros*|*1007109162*|
|*Ediee Santiago Salazar Vanegas*|*1113362042*|

**Equipo:** Desarrollo FrontEnd - Capa visual (estructura y estilos)
**Docente:** Diego Giraldo Zapata

## Objetivo

Transformar la estructura HTML en una interfaz visual organizada, aplicando estilos con un archivo CSS externo y manteniendo un enfoque MVP.

## Vistas del proyecto

|Archivo|Rol|Descripción|
|-|-|-|
|`index.html`|Todos|Login de ejemplo con acceso por rol|
|`estudiante-notas.html`|Estudiante|Consulta de notas y promedio por materia|
|`estudiante-asistencia.html`|Estudiante|Consulta del estado de asistencia por clase|
|`profesor-asistencia.html`|Profesor|Registro y modificación de asistencia de todos los estudiantes|
|`profesor-notas.html`|Profesor|Registro y modificación de notas de todos los estudiantes|
|`style.css`|-|Hoja de estilos externa compartida por todas las páginas|

## Estructura del repositorio

```
portal-academico/
├── index.html
├── estudiante-notas.html
├── estudiante-asistencia.html
├── profesor-asistencia.html
├── profesor-notas.html
├── style.css
└── README.md
```

## Cómo ver el proyecto

1. Clona o descarga el repositorio.
2. Abre `index.html` en el navegador (doble clic o clic derecho > Abrir con).
3. Elige **Entrar como estudiante** o **Entrar como profesor**.

No requiere instalación, servidor ni dependencias.

## Funcionalidades representadas

**Estudiante (solo consulta)**

* Ver notas por materia y su promedio (verde si aprueba, rojo si no).
* Ver su asistencia por fecha: presente, ausente o excusa.

**Profesor (consulta y modificación)**

* Elegir materia y fecha, y marcar la asistencia de cada estudiante.
* Elegir materia y periodo, y editar las tres notas de cada estudiante.

## Contenidos aplicados 

* HTML y estructura semántica: `header`, `nav`, `main`, `section`, `footer`, `table`, `caption`, `form`, `fieldset`, `label`.
* CSS externo vinculado con `<link rel="stylesheet" href="style.css">`.
* Selectores de elemento, de clase (`.aprobado`, `.chip`), de id (`#login`) y de estado (`nav a:hover`).
* Propiedades básicas: colores, tipografía, márgenes, bordes, `display: flex` y `@media` para pantallas pequeñas.

## Alcance y limitaciones

* Solo HTML y CSS puro, sin frameworks ni JavaScript, según la guía de entrega.
* El login es una **simulación**: no valida usuario ni contraseña, solo redirige según el rol elegido.
* Los botones de guardar muestran la interfaz, pero no almacenan datos. Los datos mostrados son de ejemplo.

## 

