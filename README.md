# Astro + Tailwind CSS - Guía de Inicio

Este repositorio proporciona una configuración básica para comenzar un proyecto con [Astro](https://astro.build/) y [Tailwind CSS](https://tailwindcss.com/).

## Características
- 🚀 **Astro**: Un framework moderno para construir sitios estáticos rápidos.
- 🎨 **Tailwind CSS**: Un framework de utilidades para diseñar interfaces responsivas y modernas.

## Requisitos Previos
Asegúrate de tener instalados los siguientes programas y extenciones en tu sistema:
- [Visual Studio Code](https://code.visualstudio.com/)
- [Extension Astro](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode)
- [Extension Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Node.js](https://nodejs.org/) (versión 16 o superior)
- [npm](https://www.npmjs.com/) o [pnpm](https://pnpm.io/)

## Instalación
1. Clona este repositorio:
   ```sh
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio
   ```
2. Instala Astro:
   ```sh
   npm create astro@latest 
   cd nombre de tu proyecto
   ```
   o tambien
   ```sh
   pnpm create astro@latest
   cd nombre de tu proyecto
   ```
3. Instalar Tailwind CSS
   ```sh
   npx astro add tailwind
   ```
   
## Uso
Para iniciar el entorno de desarrollo, ejecuta:
```sh
npm run dev 
```
o tambien
```sh
pnpm dev
```
Luego, abre en tu navegador `http://localhost:4321/` (o el puerto que se indique en la terminal).

## Estructura del Proyecto
```
/
├── src/
│   ├── components/   # Componentes reutilizables
│   ├── layouts/      # Diseños de página
│   ├── pages/        # Páginas del sitio
│   └── styles/       # Archivos de estilos adicionales
├── public/           # Archivos estáticos
├── astro.config.mjs  # Configuración de Astro
├── tailwind.config.cjs # Configuración de Tailwind CSS
├── package.json      # Dependencias y scripts
└── README.md         # Documentación
```

## Personalización
Para modificar la configuración de Tailwind CSS, edita el archivo `tailwind.config.cjs`.

Si deseas agregar nuevos estilos globales, puedes hacerlo en `src/styles/global.css` y asegurarte de importarlo en el proyecto.

## Despliegue
Puedes desplegar el proyecto en plataformas como:
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [Cloudflare Pages](https://pages.cloudflare.com/)

Para un build de producción, ejecuta:
```sh
npm run build
```
o tambien
```sh
 pnpm build
```
Esto generará archivos estáticos listos para ser servidos desde un hosting.

## Contribución
Si deseas contribuir, por favor abre un issue o envía un pull request. ¡Todas las mejoras son bienvenidas!

## Licencia
Este proyecto está bajo la licencia [MIT](LICENSE).

