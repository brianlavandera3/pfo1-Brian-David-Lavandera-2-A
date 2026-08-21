# PFO1 — Landing de Portafolio Personal

## Descripción del Proyecto

Este proyecto consiste en le desarrollo de una landing page de portafolio personal, realizada como parte de la Práctica de Formación Obligatoria (PFO1) de la materia Desarrollo de Sistemas Web — Front End.

El objetivo principal es presentar de forma clara y visual mi perfil como estudiante de desarrollo de software, mis habilidades técnicas, una sección personal y diferentes canales de contacto. La propuesta busca combinar una estética tecnológica con una estructura clara, responsive y accesible, priorizando tanto la presentación visual como la experiencia de navegación.

---

## Tecnologías Utilizadas

* HTML5
* CSS3
* JavaScript
* Google Fonts
* CSS Grid
* Flexbox

---

## Enlaces

* URL de Vercel: falta
* Perfil de GitHub: [https://github.com/brianlavandera3]

---

## Decisiones de Diseño y Estética

Desde el inicio del proyecto busqué desarrollar una identidad visual inspirada en el universo estético de Matrix, relacionándola con el ámbito tecnológico. La intención fue utilizar elementos característicos para construir una interfaz propia, manteniendo una lectura clara y profesional.

### Paleta y Tipografías

* Colores: Fondo oscuro para generar contraste y verde brillante como color de acento.
* Tipografía: Inter para textos generales y JetBrains Mono para elementos relacionados con código y terminal.
* Variables CSS: Utilizadas para centralizar los principales valores visuales, garantizando coherencia y facilidad de mantenimiento.

### Equilibrio Visual

Debido a que la estética de Matrix puede resultar intensa, el fondo se mantuvo sutil mediante el uso de transparencias, scanlines, gradientes y un canvas interactivo con opacidad reducida, posicionado detrás del contenido para no interferir con la legibilidad.

---

## Decisiones Técnicas

### HTML Semántico

La estructura utiliza elementos semánticos (`header`, `nav`, `main`, `section`, `footer`) para organizar el contenido, facilitando la interpretación tanto para usuarios como para tecnologías de asistencia.

### Maquetación: CSS Grid y Flexbox

Se utilizaron ambas tecnologías de maquetación según las necesidades de cada componente:

* CSS Grid: Utilizado para organizar estructuras en filas y columnas, como las tarjetas de habilidades, el timeline, la grilla de intereses y la distribución de los campos del formulario.
* Flexbox: Empleado para la distribución y alineación de componentes como el encabezado, navegación, contenido principal, botones, formularios y footer.
La combinación de ambas tecnologías permite adaptar la distribución de los elementos según el tamaño de pantalla.

### Interactividad y Animaciones

El sitio incorpora recursos para mejorar la experiencia de usuario:

* Efecto de escritura: Presentación dinámica del nombre del autor.
* Fondo interactivo: Canvas con símbolos relacionados con la programación.
* Navegación: Menú mobile, scroll suave y barra de progreso.
* Efectos visuales: Spotlight en tarjetas, transiciones y animaciones de entrada progresiva.

### Diseño Responsive y Accesibilidad

El diseño es completamente adaptativo y utiliza media queries para reorganizar los elementos en diferentes tamaños de pantalla, incluyendo tablets y dispositivos móviles.

También se integraron criterios de accesibilidad como:

* Atributos `alt` en imágenes.
* Etiquetas `label` asociadas a los campos del formulario.
* Estados `:hover` y `:focus`.
* Soporte para `prefers-reduced-motion` para reducir las animaciones según las preferencias del sistema.

---

## Declaración de Uso de Inteligencia Artificial

Durante el desarrollo de este proyecto utilicé ChatGPT (versión gratuita) como herramienta de consulta y apoyo técnico.

* ¿Cómo la utilicé?: Fue utilizada para explorar ideas de diseño, consultar alternativas de maquetación, resolver dudas técnicas específicas y obtener apoyo en la lógica del canvas con estética Matrix y el efecto de escritura.
* Experiencia previa: Ya contaba con experiencia utilizando la IA como apoyo para resolver dudas de sintaxis y lógica durante mis estudios de desarrollo de software.
* Criterio propio: Todo el código fue revisado, probado y adaptado manualmente. Decidí personalmente la intensidad del efecto visual, la paleta de colores, la tipografía, la distribución de los componentes y diferentes aspectos de accesibilidad para priorizar la experiencia de lectura y cumplir con los requisitos de la consigna.

---

## Datos de la Entrega

* Materia: Desarrollo de Sistemas Web — Front End (2do Cuatrimestre, 2026)
* Instancia: PFO1
* Autor: Brian David Lavandera