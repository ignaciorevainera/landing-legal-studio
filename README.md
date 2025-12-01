# 🏛️ Landing Legal Studio

Landing page moderna y profesional para un estudio jurídico especializado en servicios legales integrales. Desarrollada con Astro, TailwindCSS y DaisyUI.

## ✨ Características

- 🎨 **Diseño Profesional**: Interfaz elegante con tema oscuro corporativo
- 📱 **Totalmente Responsivo**: Optimizado para dispositivos móviles, tablets y escritorio
- ⚡ **Alto Rendimiento**: Construido con Astro para máxima velocidad
- ♿ **Accesible**: Cumple con estándares de accesibilidad (ARIA labels, navegación por teclado)
- 🎭 **Componentes Reutilizables**: Arquitectura modular y mantenible
- 🌙 **Modo Oscuro**: Tema oscuro corporativo por defecto
- 💬 **Interactividad**: Toasts animados y feedback visual inmediato
- 🔤 **Tipografía Premium**: Inter Variable para texto y Merriweather para títulos

## 🚀 Estructura del Proyecto

```text
landing-legal-studio/
├── public/
│   ├── site.webmanifest
│   └── ...
├── src/
│   ├── assets/
│   │   └── team/              # Imágenes del equipo
│   ├── components/
│   │   ├── shared/            # Componentes reutilizables
│   │   │   ├── Footer.astro
│   │   │   ├── Header.astro
│   │   │   ├── Section.astro
│   │   │   ├── SectionHeader.astro
│   │   │   ├── ServiceCard.astro
│   │   │   └── TeamMemberCard.astro
│   │   ├── About.astro        # Sección "Acerca del Estudio"
│   │   ├── Contact.astro      # Formulario de contacto
│   │   ├── Hero.astro         # Banner principal
│   │   ├── Services.astro     # Servicios legales
│   │   └── Team.astro         # Equipo de abogados
│   ├── layouts/
│   │   └── Layout.astro       # Layout base
│   ├── pages/
│   │   └── index.astro        # Página principal
│   └── styles/
│       ├── corporate-dark-theme.css  # Tema personalizado
│       └── global.css                # Estilos globales
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🛠️ Stack Tecnológico

- **Framework**: [Astro](https://astro.build) v5.1.3
- **Estilos**: [TailwindCSS](https://tailwindcss.com) v4.0.0
- **Componentes UI**: [DaisyUI](https://daisyui.com) v5.0.0
- **Iconos**: [Astro Icon](https://github.com/natemoo-re/astro-icon) con Remix Icons
- **Tipografía**: Inter Variable & Merriweather (Google Fonts)
- **Imágenes**: Astro Image Optimization integrado
- **Lenguaje**: TypeScript

## 📋 Requisitos Previos

- Node.js 18+
- npm o pnpm

## 🚀 Instalación y Uso

### 1. Clonar el repositorio

```bash
git clone https://github.com/ignaciorevainera/landing-legal-studio.git
cd landing-legal-studio
```

### 2. Instalar dependencias

```bash
npm install
```

### 3. Iniciar servidor de desarrollo

```bash
npm run dev
```

La aplicación estará disponible en `http://localhost:4321`

### 4. Construir para producción

```bash
npm run build
```

Los archivos optimizados se generarán en `./dist/`

### 5. Previsualizar build de producción

```bash
npm run preview
```

## 🎯 Comandos Disponibles

| Comando                   | Acción                                              |
| :------------------------ | :-------------------------------------------------- |
| `npm install`             | Instala las dependencias                            |
| `npm run dev`             | Inicia servidor de desarrollo en `localhost:4321`   |
| `npm run build`           | Construye el sitio para producción en `./dist/`     |
| `npm run preview`         | Previsualiza el build localmente antes de desplegar |
| `npm run astro ...`       | Ejecuta comandos CLI de Astro                       |
| `npm run astro -- --help` | Obtiene ayuda sobre la CLI de Astro                 |

## 🎨 Paleta de Colores

El proyecto utiliza un tema oscuro corporativo con la siguiente paleta:

```css
--color-primary: #4a90e2 /* Azul corporativo */ --color-secondary: #6b7280
  /* Gris neutro */ --color-accent: #e2a14a /* Dorado */
  --color-base-100: #0f1419 /* Fondo principal */ --color-base-200: #0a0e13
  /* Fondo secundario */ --color-base-300: #060810 /* Fondo terciario */;
```

## 📦 Componentes Principales

### Componentes Compartidos

- **`Section.astro`**: Wrapper para secciones con estructura semántica
- **`SectionHeader.astro`**: Encabezado de sección con título y línea decorativa
- **`ServiceCard.astro`**: Tarjeta de servicio legal con botón interactivo
- **`TeamMemberCard.astro`**: Tarjeta de miembro del equipo con acciones

### Secciones

- **`Hero.astro`**: Banner principal con imagen de fondo y CTAs
- **`About.astro`**: Información del estudio, filosofía y estadísticas
- **`Services.astro`**: Listado de servicios legales especializados
- **`Team.astro`**: Equipo de abogados con especialidades
- **`Contact.astro`**: Formulario de contacto e información de ubicación

## 🎭 Funcionalidades Interactivas

- **Toasts de Notificación**: Feedback visual con animaciones suaves al interactuar con botones
- **Navegación Responsiva**: Menú hamburguesa en móviles
- **Formulario de Contacto**: Validación y estructura semántica
- **Enlaces de Email**: Integración con cliente de correo predeterminado

## 🌐 Despliegue

El proyecto está optimizado para desplegarse en plataformas como:

- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)
- [GitHub Pages](https://pages.github.com)
- [Cloudflare Pages](https://pages.cloudflare.com)

### Ejemplo con Vercel

```bash
npm run build
vercel --prod
```

## 📝 Personalización

### Cambiar Contenido

Edita los archivos `.astro` en `src/components/` para modificar textos, imágenes y estructura.

### Modificar Colores

Ajusta las variables CSS en `src/styles/corporate-dark-theme.css`

### Agregar Servicios

Modifica el array `services` en `src/components/Services.astro`

### Actualizar Equipo

Edita el array `team` en `src/components/Team.astro` y agrega imágenes en `src/assets/team/`

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o pull request para sugerencias o mejoras.

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👨‍💻 Autor

**Ignacio Revainera**

- GitHub: [@ignaciorevainera](https://github.com/ignaciorevainera)

## 🙏 Agradecimientos

- [Astro](https://astro.build) por el increíble framework
- [DaisyUI](https://daisyui.com) por los componentes UI
- [Remix Icon](https://remixicon.com) por los iconos
- La comunidad de código abierto

---

⚖️ **Legal Studio** - Defendiendo sus derechos con integridad y profesionalismo desde 1998.
