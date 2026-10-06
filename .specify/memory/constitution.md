<!--
Sync Impact Report
- Version change: unversioned scaffold -> 1.0.0
- Modified principles: scaffold placeholders replaced with 12 TareasPro principles
- Added sections: Alcance del producto; Calidad y flujo de trabajo
- Removed sections: none; generic scaffold content replaced by project-specific governance
- Follow-up TODOs: RATIFICATION_DATE requires the date on which this constitution was formally adopted
-->

# TareasPro Constitution

## Core Principles

### I. Simplicidad ante todo
Ante dos soluciones válidas, TareasPro MUST elegir la más simple. La versión 1 MUST evitar complejidad anticipada y funcionalidades innecesarias.

### II. Idioma y mercado peruano
Todo el producto MUST estar en español de Perú. Las fechas, horas y formatos MUST ser comprensibles para usuarios peruanos.

### III. Cero alcance fantasma
El equipo MUST NOT implementar funcionalidades que no estén escritas en la spec. Toda idea nueva MUST proponerse y especificarse antes de construirse.

### IV. Éxito verificable
Cada criterio de éxito MUST poder comprobarse directamente usando la aplicación por una persona no técnica, sin leer código ni conocer detalles técnicos.

### V. Datos del usuario con respeto
TareasPro MUST pedir y almacenar únicamente la información imprescindible para gestionar tareas. El código MUST NOT incluir claves, contraseñas, tokens ni otros secretos.

### VI. Tareas claras y accionables
Cada tarea MUST contener información suficiente para entender qué se debe hacer y MUST evitar campos o datos innecesarios.

### VII. Estado visible
El usuario MUST poder identificar fácilmente qué tareas están pendientes, en progreso o completadas, siempre que esos estados estén definidos en la spec.

### VIII. Productividad primero
La interfaz MUST facilitar encontrar, crear, actualizar y completar tareas con la menor cantidad de pasos posible, según los flujos definidos en la spec.

### IX. Nada de funciones inventadas
TareasPro MUST NOT agregar calendarios, recordatorios, notificaciones, colaboración, inteligencia artificial, sincronización u otras funciones que no estén expresamente definidas en la spec.

### X. Interfaz consistente
Botones, formularios, mensajes, estados y acciones MUST comportarse de manera coherente en toda la aplicación.

### XI. Errores comprensibles
Cuando una acción no pueda realizarse, la aplicación MUST mostrar un mensaje claro en español que explique qué ocurrió y, cuando sea posible, cómo solucionarlo.

### XII. Primero lo esencial
Antes de mejorar el diseño o agregar características secundarias, el equipo MUST garantizar que crear, visualizar, editar, completar y eliminar tareas funcionen correctamente según la spec.

## Alcance del producto

TareasPro es una herramienta web para crear, organizar y gestionar tareas. La spec vigente es la fuente de verdad del alcance funcional. Si una capacidad no aparece en ella, queda fuera del producto hasta que se incorpore mediante una actualización formal de la spec.

## Calidad y flujo de trabajo

- Cada funcionalidad MUST vincularse con requisitos y criterios de éxito escritos en la spec.
- Las revisiones MUST comprobar el cumplimiento de los 12 principios y la ausencia de alcance no especificado.
- Las pruebas de aceptación MUST describir pasos que una persona no técnica pueda ejecutar en la aplicación y resultados observables.
- Los cambios MUST priorizar primero los flujos esenciales de gestión de tareas antes que mejoras secundarias.

## Governance

Esta constitución prevalece sobre prácticas o decisiones que entren en conflicto con ella.

Las enmiendas MUST:

1. describir el cambio y su motivación;
2. actualizar la versión y la fecha de última enmienda;
3. revisar su impacto en la spec, el plan y las tareas;
4. conservar los principios que sigan siendo aplicables; y
5. comprobar nuevamente que no queden placeholders sin justificar.

La versión usa SemVer: MAJOR para eliminar o redefinir principios de forma incompatible, MINOR para agregar o ampliar principios o secciones, y PATCH para aclaraciones no semánticas. Toda revisión o cambio de implementación MUST verificar el cumplimiento de esta constitución.

**Version**: 1.0.0 | **Ratified**: TODO(RATIFICATION_DATE): indicar fecha de adopción formal | **Last Amended**: 2026-10-06
