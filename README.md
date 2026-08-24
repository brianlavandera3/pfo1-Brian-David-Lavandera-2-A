# PFO1 — Landing de Portafolio Personal

## Descripción del Proyecto

Este proyecto consiste en el desarrollo de una landing page de portafolio personal, realizada como parte de la Práctica de Formación Obligatoria (PFO1) de la materia **Desarrollo de Sistemas Web — Front End**.

El objetivo principal es presentar de forma clara y visual mi perfil como estudiante de desarrollo de software, mis habilidades técnicas, mi formación, una sección personal y diferentes canales de contacto.

La propuesta busca combinar una estética tecnológica inspirada en Matrix con una estructura clara, moderna, responsive y accesible, priorizando tanto la presentación visual como la experiencia de navegación.

---

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript
- Google Fonts
- CSS Grid
- Flexbox
- Canvas API

---

## Enlaces

- **URL de Vercel:** https://pfo1-brian-david-lavandera-2-a.vercel.app/
- **Perfil de GitHub:** https://github.com/brianlavandera3

---

## Decisiones de Diseño y Estética

Desde el inicio del proyecto busqué desarrollar una identidad visual inspirada en el universo estético de **Matrix**, relacionándola con el ámbito tecnológico y con el perfil de un estudiante de desarrollo de software.

La intención fue utilizar elementos visuales asociados al código, las terminales y los sistemas informáticos para construir una interfaz reconocible y personal, manteniendo al mismo tiempo una lectura clara y profesional.

### Paleta de colores

- Fondo oscuro para generar contraste y una estética tecnológica.
- Verde brillante como color principal de acento, inspirado en la estética de Matrix.
- Tonos verdes y grises secundarios para jerarquizar la información sin saturar visualmente la interfaz.

### Tipografías

- **Inter:** utilizada para títulos, textos generales y contenido principal.
- **JetBrains Mono:** utilizada en elementos relacionados con código, etiquetas, números, estados y detalles visuales de estilo terminal.

### Variables CSS

Se utilizaron variables CSS para centralizar los principales valores visuales, como colores, bordes, radios y ancho máximo del contenido.

Esto permite mantener una mayor coherencia visual y facilita el mantenimiento y modificación del código.

### Equilibrio visual

Debido a que la estética de Matrix puede resultar visualmente intensa, el fondo se mantuvo sutil mediante transparencias, scanlines, gradientes y un canvas con símbolos relacionados con la programación.

El efecto de fondo utiliza una opacidad reducida y se mantiene detrás del contenido para evitar interferir con la lectura.

---

## Estructura del Sitio

La landing está organizada en diferentes secciones:

1. **Inicio:** presentación principal, nombre, perfil profesional, botones de navegación y acceso a GitHub.
2. **Mi historia:** recorrido resumido de formación y experiencia.
3. **Habilidades:** presentación de conocimientos relacionados con Front End, Java y Bases de Datos.
4. **Personal:** información personal, intereses y elementos que complementan el perfil profesional.
5. **Contacto:** formulario de contacto y enlace directo al perfil de GitHub.
6. **Footer:** información final de identificación del proyecto.

---

## Decisiones Técnicas

### HTML Semántico

La estructura utiliza elementos semánticos como `header`, `nav`, `main`, `section`, `article` y `footer` para organizar correctamente el contenido.

Esto permite mejorar la estructura del documento, facilitar su mantenimiento y favorecer la interpretación del contenido por parte de tecnologías de asistencia.

### Maquetación con CSS Grid y Flexbox

Se utilizaron ambas tecnologías de maquetación según las necesidades de cada componente:

- **CSS Grid:** utilizado para organizar estructuras en filas y columnas, como las tarjetas de habilidades, el timeline, la grilla de intereses y la distribución de los campos del formulario.
- **Flexbox:** empleado para la distribución y alineación de componentes como el encabezado, navegación, contenido principal, botones, formularios y footer.

La combinación de ambas técnicas permite construir una interfaz flexible y adaptable a diferentes tamaños de pantalla.

### Responsive Design

El diseño utiliza media queries para adaptar la interfaz a tablets, celulares y resoluciones reducidas.

Entre los cambios responsive se incluyen:

- Transformación de la navegación en menú hamburguesa.
- Reorganización del contenido principal.
- Adaptación de la imagen de perfil.
- Cambio de columnas a una sola columna en tarjetas y formularios.
- Ajuste de tamaños de tipografía y espaciados.
- Adaptación del footer.
- Reorganización de la sección personal.

También se realizaron ajustes específicos para evitar superposiciones y problemas de visualización en resoluciones pequeñas.

### Interactividad y JavaScript

El sitio incorpora diferentes recursos desarrollados con JavaScript:

- **Efecto de escritura:** presentación dinámica del saludo y nombre.
- **Cursor animado:** efecto de parpadeo al finalizar la escritura.
- **Menú mobile:** apertura y cierre mediante el botón hamburguesa.
- **Cierre con tecla Escape:** permite cerrar el menú utilizando el teclado.
- **Scroll suave:** navegación animada entre las diferentes secciones.
- **Barra de progreso:** indica visualmente el avance del usuario durante el desplazamiento.
- **Animaciones de entrada:** elementos que aparecen progresivamente al ingresar en el viewport.
- **Spotlight:** efecto visual que sigue la posición del cursor sobre las tarjetas de habilidades.
- **Canvas:** fondo animado con símbolos relacionados con programación.

### Fondo Matrix

El fondo animado se realizó mediante la **Canvas API de JavaScript**.

Se utilizan símbolos relacionados con Java y programación, como:

`0`, `1`, `{}`, `()`, `[]`, `if`, `else`, `for`, `class`, `public`, `static`, `String`, entre otros.

El efecto fue diseñado para ser sutil y no afectar la legibilidad del contenido.

---

## Accesibilidad

Se incorporaron diferentes criterios básicos de accesibilidad:

- Atributos `alt` descriptivos en las imágenes.
- Etiquetas `label` correctamente asociadas a los campos del formulario.
- Estados `:hover` y `:focus` para mejorar la interacción.
- Uso de atributos ARIA en elementos interactivos cuando resulta pertinente.
- Navegación mediante teclado.
- Cierre del menú mediante la tecla `Escape`.
- Soporte para `prefers-reduced-motion`, permitiendo reducir las animaciones cuando el usuario tiene configurada esta preferencia en su sistema.
- Contraste visual entre el fondo y el contenido para favorecer la legibilidad.

---

## Formulario de Contacto

El formulario incluye los siguientes campos:

- Nombre
- Email
- Mensaje

Cada campo cuenta con su correspondiente etiqueta `label` y controles de formulario correctamente identificados.

El objetivo del formulario es presentar una estructura funcional de contacto dentro de la landing.

---

## Compatibilidad y Adaptabilidad

El proyecto fue pensado para funcionar en diferentes tamaños de pantalla y navegadores modernos.

Se prestó especial atención a resoluciones reducidas para evitar desbordamientos, superposición de elementos y problemas de navegación.

La interfaz adapta sus componentes según el ancho disponible, manteniendo la jerarquía visual y la accesibilidad del contenido.

---

## Declaración de Uso de Inteligencia Artificial

Durante el desarrollo de este proyecto utilicé **ChatGPT, en su versión gratuita**, como herramienta de consulta y apoyo técnico.

### ¿Cómo utilicé la IA?

La herramienta fue utilizada para:

- Explorar ideas de diseño y organización visual.
- Consultar alternativas de maquetación con HTML y CSS.
- Resolver dudas técnicas específicas.
- Revisar y detectar posibles problemas de código.
- Obtener apoyo en la lógica del canvas con estética Matrix.
- Obtener apoyo para implementar y revisar el efecto de escritura.
- Analizar y mejorar el comportamiento responsive del menú y otros componentes.

### Experiencia previa

Ya contaba con experiencia utilizando herramientas de inteligencia artificial para resolver dudas de sintaxis, lógica y programación durante mis estudios de desarrollo de software.

### Criterio y trabajo propio

La IA fue utilizada como herramienta de apoyo y consulta, pero el proyecto fue revisado, probado y adaptado manualmente.

Las decisiones relacionadas con la identidad visual, la estética Matrix, la paleta de colores, las tipografías, la distribución de los componentes, las animaciones, la organización de las secciones y diferentes aspectos de accesibilidad fueron definidas y ajustadas durante el desarrollo del proyecto.

También se realizaron pruebas en diferentes resoluciones para detectar y corregir problemas de responsive y de navegación.

---

## Datos de la Entrega

- **Materia:**  Front End
- **Instancia:** PFO1
- **Período:** 2do Cuatrimestre, 2026
- **Autor:** Brian David Lavandera

