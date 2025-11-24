# Proyecto UD2 – Uso de Estilos  
Simulación de una aplicación web para la gestión de un hospital

---

## 👤 Datos del alumno
**Nombre del alumno:** José Antonio Lorente Moya  
**Curso:** 2º DAW 
**Módulo:** Diseño de Interfaces Web 
**Profesor:** Javier Úbeda Vázquez
**Colaborador invitado al repositorio:**  
**📧 jubevaz228@g.educaand.es**

---

## 🏥 Descripción del proyecto
Este proyecto consiste en crear una estructura de páginas web simulando una aplicación para la gestión de un hospital.  
Se incluyen dos áreas principales:

### ✔ Área de Prescripciones  
Realizada **únicamente con CSS**.

### ✔ Área de Enfermería  
Realizada utilizando **SASS/SCSS**, compilado a CSS.

También se incluye una **guía de estilos**, una página principal y una página de login.  
Todo el proyecto está desarrollado con HTML5 + CSS3 + SASS.

---

## 📁 Estructura del proyecto

PROYECTO UD2/
│
├── index.html
├── login.html
├── guia-estilos.html
│
├── prescripciones/
│ ├── lista-citas.html
│ ├── detalle-cita.html
│ ├── historia-clinica.html
│ ├── busqueda-pacientes.html
│ └── css/
│ └── styles.css (CSS puro)
│
└── enfermeria/
├── mapa-camas.html
├── hoja-medicacion.html
├── scss/
│ ├── _variables.scss
│ └── styles.scss (fuente SASS)
└── css/
└── styles.css (CSS compilado desde SASS)


---

## 🎨 Guía de estilos aplicada

### 🔹 Paleta de colores
- **Primary:** #0b6efd  
- **Secondary:** #0d9488  
- **Neutral:** #f3f4f6  
- **Danger:** #ef4444  
- **Texto:** #111827  

### 🔹 Tipografía
- Fuente principal: **Inter**, con fallback sans-serif  
- Jerarquía:
  - h1: 32px
  - h2: 24px
  - párrafo: 16px

### 🔹 Iconografía
- Iconos recomendados: **SVG simples y optimizados**
- Se permiten imágenes .jpg/.png para ilustraciones menores.

---

## 🛠 Tecnologías utilizadas
- **HTML5**
- **CSS3**
- **SASS / SCSS**
- **Node.js + npm** (para compilar SASS)
- **Visual Studio Code**

---

## ⚙️ Instalación y compilación de SASS

### 1️⃣ Instalar Node.js (si no está aún instalado)  
https://nodejs.org

### 2️⃣ Instalar Sass (global)
```bash
npm install -g sass
