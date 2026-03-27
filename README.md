# Portfolio - Tomás Liendo

Portfolio personal minimalista y profesional.

## Tecnologías

- HTML5 semántico
- CSS3 (variables, flexbox, grid, animaciones)
- JavaScript vanilla
- Google Fonts (Inter)

## Estructura del proyecto

```
portfolio/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos
├── js/
│   └── main.js         # Funcionalidad
└── README.md          # Este archivo
```

## Desarrollo local

1. Clona el repositorio
2. Abre `index.html` en tu navegador

O usa un servidor local:

```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx serve

# Con PHP
php -S localhost:8000
```

## Deploy en GitHub Pages

1. Crea un repositorio en GitHub
2. Sube los archivos del proyecto
3. Ve a **Settings > Pages**
4. En "Source", selecciona **main** y **/ (root)**
5. Guarda los cambios
6. Tu portfolio estará disponible en: `https://tu-usuario.github.io/repo-name`

## Personalización

Para personalizar el portfolio, edita:

- **个人信息**: `index.html` (nombre, tagline, redes)
- **Proyectos**: Reemplaza las cards en la sección `#proyectos`
- **Tecnologías**: Modifica los badges en `#sobre-mi`
- **Formulario**: Cambia el `action` del formulario por tu propio endpoint
- **Colores**: Edita las variables CSS en `styles.css`

## Licencia

© 2026 Tomás Liendo. Todos los derechos reservados.
