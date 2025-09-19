# Posadas Web Suite

Este repositorio reúne un conjunto de aplicaciones web desarrolladas en el marco de la Oficina de Empleo de la Municipalidad de Posadas, Misiones (Argentina).
El objetivo del proyecto es avanzar en la digitalización y sistematización de datos, reemplazando procesos manuales por soluciones web modernas que integran HTML, CSS, JavaScript (frontend) y Google Apps Script (backend y conexión con Google Sheets).

Cada aplicación fue diseñada para resolver necesidades específicas de registro, organización y gestión de datos de los distintos programas de la Oficina de Empleo.

⸻

📂 Estructura de aplicaciones

1. apps/simulacro-entrevistas-inclusivas

Aplicación web para la inscripción a simulacros de entrevistas para personas con discapacidad.
Incluye validación de datos, control de duplicados y registro automático en Google Sheets, con el fin de facilitar la organización de inscripciones realizadas por la Oficina de Empleo.

2. apps/simulacro-entrevistas-generales
Aplicación similar a la anterior, centrada en entrevistas laborales a nivel general.

3. apps/formulario-at-publico-capacitaciones

Se compone de dos formularios: 
El primero es un formulario de chequeo de registro en Atención al Público. El cual sirve para corroborar si la persona que ingresa a la Oficina de Empleo lo hace por primera vez, o no. De manera tal de definir si es necesario relevar todos los datos socioeconómicos de la persona (acción que se realiza la primera vez). Este formulario incluye la importación y carga de datos de la encuesta de Atención al Público en Kobotoolbox, que se realiza automáticamente en triggers de 1 minuto. Con el motivo de actualizaciones constantes para revisión de inscriptos, como el mencionado antes, y para el formulario de capacitaciones. 
El Formulario digital de inscripción a capacitaciones es el segundo formulario en apps/formulario-at-publico-capacitaciones. Este inscribe a las personas que pasan por atención al público con el interés de inscribirse a alguno de los cursos disponibles a realizarse en la Oficina de Empleo.

La programación web de las tres aplicaciones incluyen la validación de datos, control de duplicados y registro automático en Google Sheets, con el fin de facilitar la organización de cursos, talleres y capacitaciones ofrecidas por la Oficina de Empleo.

⸻

⚙️ Tecnologías utilizadas
	•	Frontend: HTML5, CSS3, JavaScript
	•	Framework de estilos: TailwindCSS (para algunos formularios)
	•	Backend: Google Apps Script (lógica del servidor, conexión con Google Sheets y procesamiento de datos)
	•	Base de datos: Google Sheets (almacenamiento estructurado y accesible)

⸻

🚀 Objetivo

Con este conjunto de aplicaciones, la Oficina de Empleo de Posadas:
	•	Mejora la eficiencia en la gestión de inscripciones y entrevistas.
	•	Evita errores y duplicaciones propias del registro manual.
	•	Centraliza la información en hojas de cálculo online.
	•	Ofrece herramientas digitales accesibles tanto para trabajadores como para empleadores.
