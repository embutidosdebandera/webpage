# DeBandera Landing Page

Landing page para DeBandera - Productos Cárnicos Artesanales

## 🌐 Descripción

Esta es una página de aterrizaje (landing page) moderna y profesional creada con HTML y CSS puros para DeBandera. La página incluye:

- **Header** con logo y botón de navegación a la tienda principal
- **Hero Section** con título principal e imagen destacada
- **Sección de Características** mostrando las tres categorías principales de productos
- **Sección de Blog** con tres espacios para artículos/noticias
- **Vista Previa del Sitio** con imagen de la tienda online
- **Call-to-Action (CTA)** prominente para impulsar conversiones
- **Footer** completo con información de contacto y enlaces importantes
- **Diseño Responsive** que funciona perfectamente en todos los dispositivos

## 🎨 Características de Diseño

- Colores basados en la marca DeBandera (rojo #c41e3a)
- Diseño limpio y moderno
- Animaciones suaves y transiciones
- Optimizado para móviles, tablets y desktop
- Imágenes de alta calidad de Unsplash (placeholder)

## 🚀 Deployment en GitHub Pages

### Opción 1: Usando la interfaz web de GitHub

1. Crea un nuevo repositorio en GitHub (por ejemplo: `debandera-landing`)
2. Sube los archivos `index.html` y `style.css` al repositorio
3. Ve a **Settings** → **Pages**
4. En "Source", selecciona la rama `main` y carpeta `/ (root)`
5. Click en **Save**
6. Tu sitio estará disponible en: `https://[tu-usuario].github.io/debandera-landing/`

### Opción 2: Usando Git en terminal

```bash
# Inicializa el repositorio
cd /home/pbanosdev/Code
git init

# Añade los archivos
git add index.html style.css README.md
git commit -m "Initial commit: DeBandera landing page"

# Conecta con GitHub (reemplaza con tu URL)
git remote add origin https://github.com/[tu-usuario]/debandera-landing.git

# Sube los cambios
git branch -M main
git push -u origin main
```

Luego activa GitHub Pages desde la configuración del repositorio como se indica arriba.

## 📝 Personalización

### Cambiar el botón de redirección

En `index.html`, busca los enlaces con `href="https://debandera.com/es/"` y reemplázalos con la URL de tu tienda principal si es diferente.

### Cambiar imágenes

Las imágenes actuales son de Unsplash. Para usar tus propias imágenes:

1. Añade tus imágenes a una carpeta `images/` en el proyecto
2. Reemplaza las URLs en `index.html`:
   - Hero image: línea ~31
   - Blog images: líneas ~69, ~80, ~91
   - Site preview: línea ~106

### Personalizar colores

En `style.css`, modifica las variables CSS en `:root`:

```css
:root {
    --primary-color: #c41e3a;  /* Color principal */
    --secondary-color: #8b0000; /* Color secundario */
    --dark-color: #2c2c2c;     /* Color oscuro */
    --light-color: #f8f8f8;    /* Color claro */
}
```

### Actualizar contenido

Edita el texto directamente en `index.html`:
- Título y descripción: Hero Section (líneas ~25-28)
- Características: Features Section (líneas ~40-60)
- Artículos de blog: Blog Section (líneas ~67-100)
- Información de contacto: Footer (líneas ~129-136)

## 📱 Compatibilidad

- ✅ Chrome, Firefox, Safari, Edge (últimas versiones)
- ✅ Dispositivos móviles (iOS y Android)
- ✅ Tablets
- ✅ Escritorio

## 📄 Estructura de Archivos

```
/home/pbanosdev/Code/
├── index.html      # Página principal
├── style.css       # Estilos CSS
└── README.md       # Este archivo
```

## 🔗 Enlaces Importantes

- Sitio principal: https://debandera.com/es/
- Teléfono: (+34) 968 002 331
- Dirección: POL. IND. EL ARREAQUE, MULA (MURCIA)

## 📞 Soporte

Para cualquier duda o consulta sobre la landing page, contacta con el equipo de desarrollo.

---

**© 2026 DeBandera - HERBAHER CÁRNICAS S.L. - Todos los derechos reservados**
