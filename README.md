# Depiro - Portfolio Personal

Portfolio personal desarrollado con tecnologías modernas para mostrar proyectos y experiencia profesional.

## 🛠️ Stack Tecnológico

- **HTML5** - Estructura semántica
- **Tailwind CSS v4** - Framework de utilidades CSS
- **Sass/SCSS** - Preprocesador CSS para estilos personalizados
- **PostCSS** - Procesamiento y optimización de CSS
- **Node.js** - Entorno de desarrollo y build tools

## 📁 Organización del Proyecto

```
depiro/
├── src/
│   └── styles/
│       ├── main.css          # Archivo principal de Tailwind CSS
│       └── custom.scss       # Estilos personalizados en Sass
├── dist/
│   └── styles/
│       └── main.css          # CSS compilado y optimizado
├── index.html               # Página principal
├── package.json             # Dependencias y scripts
└── postcss.config.js        # Configuración de PostCSS
```

## 🎨 Organización del CSS

### Tailwind CSS (main.css)
- Utiliza las directivas estándar de Tailwind: `@tailwind base`, `@tailwind components`, `@tailwind utilities`
- Importa automáticamente los estilos personalizados compilados desde Sass

### Sass/SCSS (custom.scss)
- **Variables CSS personalizadas** - Fuentes, colores, dimensiones
- **Estilos base** - Reset, tipografía, layout
- **Componentes personalizados** - Clases utilitarias específicas del proyecto
- **Responsive design** - Media queries y breakpoints

## 🚀 Comandos de Desarrollo

```bash
# Instalar dependencias
npm install

# Compilar para producción
npm run build

# Modo desarrollo con watch
npm run dev

# Comandos individuales
npm run build:sass    # Compilar solo Sass
npm run build:css     # Procesar solo Tailwind/PostCSS
npm run dev:sass      # Watch solo Sass
npm run dev:css       # Watch solo CSS
```

## 📝 Flujo de Trabajo

1. **Desarrollo**: Escribe estilos personalizados en `src/styles/custom.scss`
2. **Compilación**: Sass se compila a CSS y se importa en el archivo principal de Tailwind
3. **Procesamiento**: PostCSS aplica Tailwind y optimizaciones (autoprefixer, etc.)
4. **Resultado**: CSS final optimizado en `dist/styles/main.css`

## 🎯 Características

- ✅ Compilación automática de Sass a CSS
- ✅ Integración moderna con Tailwind CSS v4
- ✅ Optimización automática con PostCSS
- ✅ Autoprefixer para compatibilidad entre navegadores
- ✅ Modo watch para desarrollo en tiempo real
- ✅ Estructura modular y mantenible

## 📞 Contacto

Para más información sobre el proyecto o colaboraciones, no dudes en contactarme.
