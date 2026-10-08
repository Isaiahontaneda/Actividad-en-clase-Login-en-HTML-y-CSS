# Login AdminExpress

Actividad en clase: réplica de una página de login con HTML y CSS, con diseño responsive.

**Repositorio:** https://github.com/Isaiahontaneda/Actividad-en-clase-Login-en-HTML-y-CSS.git

## Descripción

El objetivo fue replicar el diseño de login "AdminExpress" mostrado en la imagen de la actividad, y que se adapte a escritorio, tableta y móvil. La página es una réplica visual: los campos y el botón son solo diseño y no tienen funcionalidad.

## Cómo se replicó el diseño

1. **Estructura en HTML:** un `main` que contiene dos `section`. La primera es el panel azul con el título "AdminExpress" y la segunda es el panel gris con el formulario (título, subtítulo, campos de Email y Password, "Forgot password?" y el botón "Sign In").
2. **División de la pantalla con CSS Grid:** el contenedor principal usa `display: grid` con `grid-template-columns: 1fr 1fr`, lo que reparte la pantalla en dos mitades iguales, como en la imagen de escritorio.
3. **Estilos visuales:** se usaron los colores, tamaños de letra, bordes redondeados y espaciados (`padding` y `margin`) necesarios para que los campos y el botón se parezcan al diseño original. Los elementos del formulario se centraron con Flexbox.
4. **Diseño responsive con Media Queries:** se agregaron dos puntos de quiebre.
   - `max-width: 1024px` (tableta): se reducen los tamaños de texto y el ancho del formulario.
   - `max-width: 768px` (móvil): el grid pasa a una sola columna, se oculta el panel azul, el botón ocupa todo el ancho y aparece el texto "Don't have an account? Sign Up", igual que en la imagen del celular.

## Técnicas utilizadas

- HTML semántico (`main`, `section`)
- CSS Grid para la estructura de dos columnas
- Media Queries para adaptar el diseño a distintos tamaños de pantalla
- Flexbox para centrar y alinear los elementos

## Estructura del proyecto

```
login/
├── index.html
├── README.md
└── css/
    └── estilos.css
```

## Cómo verlo

1. Descarga o clona el repositorio.
2. Abre el archivo `index.html` en el navegador (doble clic o clic derecho > Abrir con > Chrome).
3. Para comprobar que es responsive, presiona `F12`, activa el modo dispositivo (`Ctrl + Shift + M`) y prueba con anchos de **1280px** (escritorio), **900px** (tableta) y **390px** (móvil).

## Autor

Isaiah - Universidad de las Américas