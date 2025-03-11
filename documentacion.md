# Documentación del Proyecto

## Índice
- [Documentación del Proyecto](#documentación-del-proyecto)
  - [Índice](#índice)
  - [Introducción](#introducción)
  - [Estructura del Proyecto](#estructura-del-proyecto)
  - [Descripción de Archivos](#descripción-de-archivos)
    - [HTML](#html)
    - [CSS](#css)
    - [Imágenes](#imágenes)
    - [Sonidos](#sonidos)
  - [Modo Oscuro](#modo-oscuro)
  - [Accesibilidad](#accesibilidad)
  - [Scripts](#scripts)
  - [Estilos](#estilos)
  - [Referencias](#referencias)

## Introducción
Este documento proporciona una visión general del proyecto, incluyendo la estructura de archivos, la funcionalidad del modo oscuro, las características de accesibilidad y más.

## Estructura del Proyecto
El proyecto está organizado de la siguiente manera:
```
Proyecto_diseno-PabloGarcia_DavidLopez_RaquelAldilla_SebastianBorquez/
├── css/
│   ├── styleDark.css
│   ├── styleRegistro.css
│   └── styles.css
├── images/
│   └── ... (imágenes utilizadas en el proyecto)
├── sounds/
│   └── ... (archivos de sonido utilizados en el proyecto)
├── index.html
├── indexBosque.html
├── indexGrazalema.html
├── indexRestaurantes.html
├── indexUbrique.html
├── login.html
├── registro.html
└── contacto.html
```

## Descripción de Archivos

### HTML
- **index.html**: Página principal del proyecto.
- **indexBosque.html**: Página dedicada a El Bosque.
- **indexGrazalema.html**: Página dedicada a Grazalema.
- **indexRestaurantes.html**: Página para la reserva de restaurantes.
- **indexUbrique.html**: Página dedicada a Ubrique.
- **login.html**: Página de inicio de sesión.
- **registro.html**: Página de registro de usuarios.
- **contacto.html**: Página de contacto.

### CSS
- **styleDark.css**: Estilos para el modo oscuro.
- **styleRegistro.css**: Estilos específicos para la página de registro.
- **styles.css**: Estilos generales del proyecto.

### Imágenes
- **images/**: Contiene todas las imágenes utilizadas en el proyecto.

### Sonidos
- **sounds/**: Contiene todos los archivos de sonido utilizados en el proyecto.

## Modo Oscuro
El proyecto incluye una funcionalidad de modo oscuro que se puede activar mediante un interruptor en la interfaz. Los estilos para el modo oscuro se encuentran en el archivo `styleDark.css`.

## Accesibilidad
Se han implementado varias características de accesibilidad, como etiquetas `aria` y descripciones para mejorar la experiencia del usuario.

## Scripts
Los scripts utilizados en el proyecto se encuentran directamente en los archivos HTML y manejan funcionalidades como el modo oscuro, la reproducción de sonidos y la gestión de formularios.

## Estilos
Los estilos están organizados en varios archivos CSS para mantener el código limpio y modular. Los estilos específicos para el modo oscuro y la página de registro se encuentran en archivos separados.

## Referencias
- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)
