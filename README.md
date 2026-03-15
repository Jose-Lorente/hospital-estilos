# Sistema de Gestión Hospitalaria

## Nombre

Jose Antonio Lorente Moya

## Título del proyecto

Sistema de Gestión Hospitalaria – Proyecto de Desarrollo de Interfaces Web

## URL del despliegue en GitHub Pages

https://github.com/Jose-Lorente/hospital-estilos/tree/main

## Descripción del proyecto

Este proyecto consiste en el desarrollo de una aplicación web estática que simula la interfaz de un sistema de gestión hospitalaria. La aplicación permite navegar entre diferentes áreas del hospital como prescripciones médicas, unidad de enfermería y urgencias, mostrando distintas vistas con tablas, formularios y paneles informativos.

El objetivo del proyecto es aplicar los conocimientos adquiridos en la asignatura de Desarrollo de Interfaces Web mediante el uso de HTML5, CSS3, Sass y Tailwind CSS, organizando el código de forma estructurada y aplicando una guía de estilos común para toda la interfaz.

## Tecnologías utilizadas

HTML5 para la estructura semántica de las páginas
CSS3 para los estilos generales de la aplicación
Sass (SCSS) para la modularización de estilos en la sección de enfermería
Tailwind CSS para la maquetación de la sección de urgencias

## Estructura del proyecto

hospital-project/

index.html
home.html
guia-estilos.html

css/
main.css
prescripciones.css
enfermeria.css

sass/
_variables.scss
_mixins.scss
_layout.scss
_tables.scss
enfermeria.scss

pages/

prescripciones/
busqueda-pacientes-html
citas.html
detalle-cita.html
historia.clinica.html

enfermeria/
mapa-camas.html
hoja-medicacion.html

urgencias/
registro.html
triaje.html

assets/
img/
icons/

README.md

## Organización del proyecto

La aplicación está dividida en diferentes módulos que representan áreas del sistema hospitalario:

Prescripciones
Incluye páginas relacionadas con la gestión de citas y prescripciones médicas. Utiliza HTML y CSS tradicional.

Unidad de Enfermería
Incluye el mapa de camas y la hoja de medicación diaria. Los estilos de esta sección se han desarrollado utilizando Sass para demostrar el uso de preprocesadores CSS.

Urgencias
Incluye las páginas de registro de pacientes y triaje. Esta sección utiliza Tailwind CSS para aplicar estilos mediante clases utilitarias.

Guía de estilos
Se ha definido una guía de estilos con una paleta de colores orientada a un entorno sanitario, con el objetivo de mantener coherencia visual en toda la aplicación.

## Notas para el profesor

El proyecto se ha desarrollado como una aplicación web estática con el objetivo de aplicar distintas técnicas de maquetación y organización de estilos vistas durante el curso.

Se han utilizado tres enfoques diferentes de estilos en distintas partes del proyecto:
CSS tradicional para la estructura general del sitio
Sass para la sección de enfermería
Tailwind CSS para la sección de urgencias

