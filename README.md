# Multi-language Website Template with Material Design

This is a responsive and multi-language HTML template with Material Design. It is designed to be easy to use and customize, allowing developers to create modern and attractive websites with ease.

## Main Features

- **Material Design**: Uses Material Design principles to offer a clean and modern user interface.
- **Responsive**: Adapts to different screen sizes, ensuring an optimal experience on mobile and desktop devices.
- **Multi-language Support**: Includes functionality to switch between languages (English and Spanish) with ease.
- **Dark/Light Mode**: Allows users to toggle between dark and light themes.
- **Editable Sections**: Easily editable content to suit your project's needs.
- **AOS Animations**: Utilizes the AOS (Animate On Scroll) library for smooth scroll animations.

## Template Structure

- **Header (Navbar)**: Includes the logo, main navigation, language toggle button, and theme toggle button.
- **Hero Section**: Contains a slider with three main slides highlighting key features.
- **Steps Section**: Presents four steps to guide the user through a process.
- **Services Section**: Details the services or features you offer.
- **Testimonials Section**: Displays customer comments and reviews.
- **Pricing Section**: Describes the pricing plan or available packages.
- **Contact Section**: Includes a form for users to get in touch.
- **Footer**: Legal information and copyrights.
- **Login and Register Subpages**: Forms for user login and registration.

## How to Use the Template

### 1. Download and Initial Setup

Download the template code and save it in your project.

### 2. Content Customization

The content is editable and marked with the `data-key` attribute to facilitate the identification of elements you can customize.

- **Editable Content**: You can edit the content directly in the browser thanks to the `contenteditable` attribute. Double-click on the text you want to change, edit it, and the change will be saved locally.
- **Translations**: The JavaScript file includes a `translations` object where you can add or modify translations for different languages.

### 3. Language Configuration

The template supports two languages by default: English and Spanish. You can switch between them by clicking the language button in the navigation bar.

To add more languages:

- Add a new object in `translations` with the language code and corresponding translations.
- Update the language toggle button to include the new language.

### 4. Dark/Light Theme

Users can toggle between dark and light themes by clicking the sun/moon icon in the navigation bar.

### 5. Animations

Scroll animations are handled by the AOS library.

- To modify animations, you can adjust the `data-aos` attributes in the HTML elements.
- You can change the duration, delay, and type of animation.

### 6. Slider in the Hero Section

The slider changes automatically every 5 seconds and also allows manual navigation.

- To adjust the automatic change time, modify the value in `setInterval(nextSlide, 5000);` in the script.
- You can add more slides by following the existing structure in the HTML and updating the CSS if necessary.

### 7. Contact, Login, and Register Forms

The forms are designed to be functional but require backend integration to process data.

- **Validation**: Ensure you implement validation both on the frontend and backend.
- **Security**: Implement security measures like injection protection and password encryption.

## External Dependencies

- **Google Fonts**: The Roboto font and Material Icons are loaded from Google Fonts.
- **AOS (Animate On Scroll)**: Library for scroll animations. Loaded from a CDN.

## Advanced Customization

- **Styles**: The CSS styles use custom properties (variables) to facilitate color and theme customization.
- **JS Functionality**: The JavaScript file handles language switching, theme toggling, slider, and navigation to subpages. You can modify or extend these functions as needed.

## Support and Contributions

If you have any questions or need help with the template, feel free to get in touch. Contributions are welcome.

## License

This project is under the MIT License. You can freely use it in your personal or commercial projects.


---

# Plantilla de Sitio Web Multilenguaje con Diseño Material

Esta es una plantilla HTML receptiva y multilenguaje con diseño Material Design. Está diseñada para ser fácil de usar y personalizar, permitiendo a los desarrolladores crear sitios web modernos y atractivos con facilidad.

## Características Principales

- **Diseño Material Design**: Usa principios de diseño Material para ofrecer una interfaz de usuario limpia y moderna.
- **Responsiva**: Se adapta a diferentes tamaños de pantalla, asegurando una experiencia óptima en dispositivos móviles y de escritorio.
- **Soporte Multilenguaje**: Incluye funcionalidad para cambiar entre idiomas (Español e Inglés) con facilidad.
- **Modo Oscuro/Claro**: Permite a los usuarios alternar entre temas oscuro y claro.
- **Secciones Editables**: Contenido fácilmente editable para adaptarse a las necesidades de tu proyecto.
- **Animaciones AOS**: Utiliza la librería AOS (Animate On Scroll) para animaciones suaves al desplazarse.

## Estructura de la Plantilla

- **Encabezado (Navbar)**: Incluye el logo, navegación principal, botón de cambio de idioma y botón de cambio de tema.
- **Sección Hero**: Contiene un slider con tres diapositivas principales que destacan características clave.
- **Sección de Pasos**: Presenta cuatro pasos para guiar al usuario a través de un proceso.
- **Sección de Servicios**: Detalla los servicios o características que ofreces.
- **Sección de Testimonios**: Muestra comentarios y opiniones de clientes.
- **Sección de Precios**: Describe el plan de precios o paquetes disponibles.
- **Sección de Contacto**: Incluye un formulario para que los usuarios se pongan en contacto.
- **Pie de Página (Footer)**: Información legal y derechos de autor.
- **Subpáginas de Login y Registro**: Formularios para inicio de sesión y registro de usuarios.

## Cómo Usar la Plantilla

### 1. Descarga y Configuración Inicial

Descarga el código de la plantilla y guárdalo en tu proyecto.

### 2. Personalización del Contenido

El contenido es editable y está marcado con el atributo `data-key` para facilitar la identificación de los elementos que puedes personalizar.

- **Contenido Editable**: Puedes editar el contenido directamente en el navegador gracias al atributo `contenteditable`. Doble clic en el texto que deseas cambiar, edita y el cambio se guardará localmente.
- **Traducciones**: El archivo JavaScript incluye un objeto `translations` donde puedes agregar o modificar las traducciones para diferentes idiomas.

### 3. Configuración del Idioma

La plantilla soporta dos idiomas por defecto: Español e Inglés. Puedes cambiar entre ellos haciendo clic en el botón de idioma en la barra de navegación.

Para agregar más idiomas:

- Agrega un nuevo objeto en `translations` con el código del idioma y las traducciones correspondientes.
- Actualiza el botón de cambio de idioma para incluir el nuevo idioma.

### 4. Tema Oscuro/Claro

Los usuarios pueden alternar entre el tema oscuro y claro haciendo clic en el icono de sol/luna en la barra de navegación.

### 5. Animaciones

Las animaciones al hacer scroll están manejadas por la librería AOS.

- Para modificar las animaciones, puedes ajustar los atributos `data-aos` en los elementos HTML.
- Puedes cambiar la duración, el retraso y el tipo de animación.

### 6. Slider en la Sección Hero

El slider cambia automáticamente cada 5 segundos y también permite navegación manual.

- Para ajustar el tiempo de cambio automático, modifica el valor en `setInterval(nextSlide, 5000);` en el script.
- Puedes agregar más diapositivas siguiendo la estructura existente en el HTML y actualizando el CSS si es necesario.

### 7. Formularios de Contacto, Login y Registro

Los formularios están diseñados para ser funcionales, pero requieren integración con un backend para procesar los datos.

- **Validación**: Asegúrate de implementar validación tanto en el frontend como en el backend.
- **Seguridad**: Implementa medidas de seguridad como protección contra inyecciones y cifrado de contraseñas.

## Dependencias Externas

- **Google Fonts**: La fuente Roboto y los Material Icons se cargan desde Google Fonts.
- **AOS (Animate On Scroll)**: Librería para animaciones al hacer scroll. Se carga desde un CDN.

## Personalización Avanzada

- **Estilos**: Los estilos CSS utilizan variables (custom properties) para facilitar la personalización de colores y temas.
- **Funcionalidad JS**: El archivo JavaScript maneja el cambio de idioma, tema, slider y navegación a subpáginas. Puedes modificar o ampliar estas funciones según tus necesidades.

## Soporte y Contribuciones

Si tienes alguna pregunta o necesitas ayuda con la plantilla, no dudes en ponerte en contacto. Las contribuciones son bienvenidas.

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes usarlo libremente en tus proyectos personales o comerciales.
