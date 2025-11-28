# Viñatera Montpellier - Sitio Web

Sitio web elegante y moderno para Viñatera Montpellier, inspirado en el diseño de Viña Santa Rita, desarrollado con Tailwind CSS desde CDN.

## 🍷 Características

- **Diseño Responsive**: Adaptado para todos los dispositivos (móvil, tablet, desktop)
- **Tailwind CSS desde CDN**: Sin necesidad de instalación o build process
- **Animaciones Suaves**: Efectos de fade-in y hover elegantes
- **Navegación Smooth Scroll**: Transiciones suaves entre secciones
- **Galería Interactiva**: Imágenes con efectos hover
- **Formulario de Contacto**: Sección de contacto funcional
- **Optimizado para SEO**: Meta tags y estructura semántica

## 📁 Estructura del Proyecto

```
Vitiviinicola Montpellier/
│
├── index.html          # Página principal del sitio
└── README.md          # Este archivo
```

## 🚀 Cómo Usar

1. **Abrir el sitio**: Simplemente abre `index.html` en tu navegador
2. **Servidor Local (Recomendado)**: Para mejor experiencia, usa un servidor local:
   ```bash
   # Con Python 3
   python -m http.server 8000
   
   # Con Node.js (http-server)
   npx http-server
   
   # Con PHP
   php -S localhost:8000
   ```
3. **Acceder**: Abre `http://localhost:8000` en tu navegador

## 🎨 Secciones del Sitio

### 1. **Hero Section**
- Imagen de fondo impactante de viñedos
- Call-to-action principal
- Animación de scroll indicador

### 2. **Sobre Nosotros**
- Historia de la viñatera
- Imagen destacada
- Badge con años de experiencia

### 3. **Vinos / Productos**
- Grid de productos con cards elegantes
- Información de cada vino
- Precios y botones de acción

### 4. **Galería**
- Grid de imágenes responsive
- Efectos hover interactivos
- Inspirado en el contenido de Instagram

### 5. **Contacto**
- Información de contacto
- Formulario funcional
- Enlaces a redes sociales

### 6. **Footer**
- Información adicional
- Enlaces rápidos
- Redes sociales

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **Tailwind CSS**: Framework CSS desde CDN
- **JavaScript Vanilla**: Interactividad y animaciones
- **Google Fonts**: Tipografía elegante (Playfair Display + Inter)
- **Font Awesome**: Iconos desde CDN
- **Unsplash**: Imágenes de alta calidad (placeholder)

## 📝 Personalización

### Cambiar Colores
Los colores principales están basados en tonos de vino (rojos, marrones). Para cambiar:
- Busca `red-900`, `red-800` en el HTML
- Reemplaza con tus colores preferidos de Tailwind

### Agregar Imágenes Reales
1. Reemplaza las URLs de Unsplash con tus propias imágenes
2. Optimiza las imágenes para web (recomendado: WebP, compresión)
3. Considera usar un CDN de imágenes como Cloudinary o Imgix

### Actualizar Contenido
- Edita los textos directamente en `index.html`
- Reemplaza información de contacto con datos reales
- Agrega más vinos en la sección de productos

### Integrar con Instagram
Para mostrar contenido real de Instagram:
1. Usa la API de Instagram Graph API
2. O integra un widget de Instagram embebido
3. O usa servicios como Juicer.io o SnapWidget

## 🌐 CDN y Optimización

El sitio utiliza CDN para:
- **Tailwind CSS**: `https://cdn.tailwindcss.com`
- **Google Fonts**: Carga optimizada de fuentes
- **Font Awesome**: Iconos desde CDN

### Para producción, considera:
1. **CDN de Imágenes**: Cloudinary, Imgix, o Cloudflare Images
2. **CDN de Assets**: Cloudflare, AWS CloudFront, o Bunny CDN
3. **Optimización de Imágenes**: Comprimir y convertir a WebP
4. **Minificación**: Minificar HTML, CSS y JS

## 📱 Responsive Design

El sitio está optimizado para:
- **Móviles**: 320px - 768px
- **Tablets**: 768px - 1024px
- **Desktop**: 1024px+

## 🔗 Enlaces Importantes

- **Instagram**: [@montpellier.cl](https://www.instagram.com/montpellier.cl)
- **Inspiración**: [Santa Rita](https://www.santarita.com/)

## 📄 Licencia

Este proyecto es propiedad de Viñatera Montpellier.

## 👨‍💻 Desarrollo

Para contribuir o modificar:
1. Edita `index.html` directamente
2. Usa un editor con Live Server para ver cambios en tiempo real
3. Prueba en diferentes dispositivos y navegadores
4. Optimiza imágenes antes de subir a producción

---

**Desarrollado con ❤️ para Viñatera Montpellier**

"# VitivinicolaMontpellier" 
