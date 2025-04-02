# AQUAZONE

Este repositorio contiene el código fuente para la página web de AQUAZONE, un negocio de alquiler de parques acuáticos hinchables móviles.

## Estructura del Proyecto

```
aquazone/
├── admin/
│   ├── index.html
│   ├── styles.css
│   └── scripts.js
├── assets/
│   ├── images/
│   ├── videos/
│   └── logo.png
├── components/
│   ├── Header.js
│   ├── Footer.js
│   ├── ContactForm.js
│   ├── Gallery.js
│   └── SocialFeed.js
├── pages/
│   ├── Home.js
│   ├── Terrestres.js
│   ├── Flotantes.js
│   └── Admin.js
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── index.js
│   ├── App.js
│   ├── styles.css
│   └── scripts.js
├── .gitignore
├── package.json
└── README.md
```

## Descripción

La página web incluye las siguientes secciones:
- **Parques Acuáticos Terrestres**: Información sobre parques acuáticos urbanos móviles y Kamikaze Jam.
- **Parques Acuáticos Flotantes**: Información sobre piscinas y playas.
- **Galería**: Imágenes y vídeos de los parques acuáticos.
- **Contacto**: Formulario para contactar con la empresa.

El panel de administración incluye:
- Gestión de reservas.
- Gestión de clientes.
- Calendario para la gestión de fechas.

## Tecnologías Utilizadas

- React
- HTML
- CSS
- JavaScript
- GSAP para animaciones

## Instalación

Para clonar el repositorio y empezar a trabajar en él, usa el siguiente comando:

```bash
git clone https://github.com/tu-usuario/aquazone.git
```

Luego, instala las dependencias:

```bash
cd aquazone
npm install
```

Puedes iniciar el servidor de desarrollo con:

```bash
npm start
```

## Despliegue

Este proyecto está configurado para desplegarse automáticamente en Vercel. Solo necesitas conectar tu repositorio a Vercel y el despliegue se realizará automáticamente.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un *pull request* para discutir cualquier cambio que quieras hacer.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
