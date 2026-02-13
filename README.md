# 📱 Social Network Timeline - Jhon

Una **red social tipo Facebook** construida con HTML5, CSS3 (Grid, Flexbox, Float) completamente responsiva y accesible.

## 🎯 Características

### 📐 Componentes

- **Header Sticky:** Búsqueda rápida, notificaciones, perfil y mensajes
- **Sidebar Izquierdo:** Menú de navegación principal + comunidades
- **Feed Central:** Posts con interacciones, comentarios y estadísticas
- **Sidebar Derecho:** Sugerencias de amigos, eventos y publicidad
- **Footer:** Información del sitio

### 🎨 Elementos Visuales

- ✅ **Posts completos** con autor, timestamp, contenido e imagen
- ✅ **Sistema de reacciones**: Me gusta, comentarios, compartir
- ✅ **Comentarios anidados** con foto de perfil y tiempo
- ✅ **Sugerencias de amigos** con contador de contactos comunes
- ✅ **Calendario de eventos** con fechas y horarios
- ✅ **Anuncios publicitarios** con CTA
- ✅ **Animaciones suaves** y transiciones

### 📱 Responsivo

- **Desktop (1200px+):** 3 columnas (sidebar izq | feed | sidebar der)
- **Tablet (768-1024px):** 2 columnas (feed | sidebar der comprimido)
- **Móvil (480-768px):** 1 columna con widgets apilados
- **Móvil pequeño (<480px):** Optimizado para pantallas muy pequeñas

### ♿ Accesibilidad

- Atributos ARIA para navegación
- Focus states visibles en todos los elementos interactivos
- Colores con contraste suficiente
- Navegación por teclado completa

## 📁 Estructura

```
trabajo_flex-grid-float/
├── index.html         # 📄 Estructura HTML con posts y widgets
├── styles.css         # 🎨 Estilos CSS con variables y media queries
├── README.md          # 📖 Este archivo
└── imagenes/          # 🖼️ Carpeta de imágenes
    └── WhatsApp Image 2026-02-09 at 19.18.27.jpeg
```

## 🚀 Cómo Usar

### Opción 1: Abrir en el navegador
```bash
# Simplemente abre index.html
firefox index.html
# o
google-chrome index.html
```

### Opción 2: Servidor local con Python
```bash
python3 -m http.server 8000
# Accede a http://localhost:8000
```

### Opción 3: Servidor local con Node.js
```bash
npx http-server
# Accede a http://localhost:8080
```

### Opción 4: Servidor local con Live Server
```bash
# En VS Code, usa la extensión Live Server
# Click derecho en index.html > Open with Live Server
```

## 🎨 Paleta de Colores

| Color | Código | Uso |
|-------|--------|-----|
| Primario | `#667eea` | Botones, acentos, links |
| Secundario | `#764ba2` | Degradados, widgets |
| Texto | `#333` | Contenido principal |
| Texto Claro | `#65676b` | Subtítulos, timestamps |
| Fondo | `#e5e7eb` | Fondo del body |
| Blanco | `#fff` | Cards y contenedores |
| Hover | `#f0f2f5` | Estados hover |

## 📊 Breakpoints

| Dispositivo | Ancho | Columnas |
|-------------|-------|----------|
| Desktop | 1200px+ | 3 columnas |
| Laptop | 1024px-1200px | 3 columnas |
| Tablet | 768px-1024px | 2 columnas |
| Móvil | 480px-768px | 1 columna |
| Móvil pequeño | <480px | 1 columna optimizada |

## ✨ Tecnologías

- **HTML5** - Semántica moderna
- **CSS3** - Grid, Flexbox, Float, Media Queries
- **Variables CSS** - Mantenibilidad centralizada
- **Responsive Design** - Mobile-first approach
- **WCAG Accessibility** - Accesibilidad web

## 🔧 Mejoras Implementadas

✅ **Grid Layout** - Layout 3 columnas principal  
✅ **Flexbox** - Componentes flexible (header, posts, comentarios)  
✅ **Float** - Imágenes de perfil flotantes  
✅ **Sticky Positioning** - Header y sidebars pegajosos  
✅ **Variables CSS** - Colores, espaciados, sombras centralizados  
✅ **Animaciones** - Entrada de posts con fadeIn  
✅ **Focus States** - Navegación por teclado mejorada  
✅ **Sombras** - 3 niveles de profundidad visual  
✅ **Media Queries** - 5 breakpoints diferentes  
✅ **Scroll Styling** - Scrollbar personalizada  

## 📸 Contenido de Ejemplo

El sitio incluye:

- **4 Posts completos** con contenido, imágenes y comentarios
- **2 Sugerencias de amigos** con opción de agregar
- **2 Eventos próximos** en el sidebar
- **1 Anuncio** promocional
- **Sección de comentarios** con avatares y timestamps

## ⌨️ Navegación por Teclado

- `Tab` - Avanzar por elementos interactivos
- `Shift + Tab` - Retroceder por elementos
- `Enter` / `Space` - Activar botones

## 🎓 Aprendizaje

Este proyecto demuestra:

1. **Combinación de técnicas CSS** - Grid, Flexbox y Float juntos
2. **Diseño responsivo** - Múltiples breakpoints
3. **Accesibilidad** - ARIA labels, focus states
4. **Mantenibilidad** - Variables CSS, estructura clara
5. **UX/UI** - Interacciones suaves, feedback visual
6. **HTML semántico** - Roles y atributos correctos

## 📝 Notas

- Las imágenes usan `object-fit: cover` para mantener proporciones
- Los posts tienen animación `slideIn` al cargar
- El scrollbar personalizado es compatible con navegadores basados en Webkit
- Las tarjetas tienen efectos hover suaves
- El layout es completamente responsivo sin usar `@media print`

## 🤝 Contribuciones

- Siéntete libre de modificar los colores, espaciados o contenido
- Experimenta agregando más posts
- Intenta agregar funcionalidad JavaScript para likes y comentarios
- Personaliza con tus redes sociales o portfolio

## 📄 Licencia

Proyecto de aprendizaje - Uso libre para propósitos educativos

---

**Hecho por:** Jhon Espinosa  
**Fecha:** Febrero 2026  
**Tecnologías:** HTML5 | CSS3 | Responsive Design | Accesibilidad
