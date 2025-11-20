# Steeleye Landing Page

Landing page para Steeleye - Plataforma de automatización de takeoffs de acero estructural.

## Características

✅ **Diseño exacto del Figma** - Replicación pixel-perfect del diseño original
✅ **HTML Semántico** - Estructura limpia y accesible
✅ **Tailwind CSS Compilado** - CSS generado localmente sin CDN
✅ **Tipografía Poppins** - Poppins Light (300) y Poppins Semibold (600)
✅ **Paleta de Colores Oficial**:
   - Negro Principal: #000000
   - Naranja/Rojo Corporativo: #F23312
✅ **Responsivo** - Funciona perfectamente en desktop, tablet y móvil
✅ **Interactividad** - Smooth scroll, animaciones de entrada, efectos hover

## Estructura del Proyecto

```
steeleye-soft-landing/
├── index.html              # Archivo HTML principal
├── styles.css              # CSS compilado de Tailwind
├── package.json            # Configuración de npm
├── tailwind.config.js      # Configuración de Tailwind
├── src/
│   ├── input.css          # Archivo CSS de entrada
│   └── script.js          # JavaScript para interactividad
├── assets/
│   └── img/
│       └── Frame 10.png   # Diseño Figma
└── README.md              # Este archivo
```

## Secciones del Sitio

1. **Navbar** - Navegación sticky con botón "Book a demo"
2. **Hero Section** - Propuesta de valor principal con CTA
3. **Contreras Steel Partner** - Sección de colaboración
4. **Problems Section** - Problemas que resuelve Steeleye
5. **Why Steeleye Section** - Razones para elegir Steeleye
6. **Features Section** - 3 características principales (AI, Manual, Estimation)
7. **How It Works** - Proceso de 4 pasos
8. **Operational Advantages** - Beneficios operacionales
9. **CTA Section** - Call-to-action final
10. **Footer** - Enlaces y información

## Cómo Usar

### Opción 1: Abrir directamente en navegador
```bash
# Simplemente abre index.html en tu navegador
```

### Opción 2: Usar Live Server (VS Code)
1. Instala la extensión "Live Server" en VS Code
2. Click derecho en `index.html`
3. Selecciona "Open with Live Server"

### Opción 3: Compilar Tailwind CSS (si realizas cambios)
```bash
# Instalar dependencias
npm install

# Compilar CSS
npm run build-css

# Modo watch (compilación automática)
npm run watch
```

## Personalización

### Cambiar Colores
Los colores están definidos directamente en las clases de Tailwind:
- Naranja/Rojo: `#F23312` (usa clase `text-[#F23312]`, `bg-[#F23312]`, etc.)
- Negro: `#000000` (usa clase `bg-black`, `text-black`)

### Agregar Imágenes
Reemplaza los placeholders con imágenes reales:
- Hero image: `<div class="bg-gradient-to-br from-[#F23312] to-orange-600">` 
- Contreras Steel logo: En la sección "Built in Collaboration"
- Otros gráficos: En secciones de características y ventajas

### Modificar Contenido
Todos los textos están en HTML y son fáciles de editar:
- Títulos, párrafos y CTAs
- Mantén la estructura HTML intacta para que Tailwind funcione correctamente

## Compatibilidad

- ✅ Chrome/Edge (versiones recientes)
- ✅ Firefox (versiones recientes)
- ✅ Safari (versiones recientes)
- ✅ Responsive en dispositivos móviles

## Próximos Pasos

1. **Agregar Imágenes**: Reemplaza todos los placeholders con imágenes reales
2. **Conectar con Backend**: Implementa formularios y validación
3. **SEO**: Agrega meta etiquetas y Open Graph
4. **Analytics**: Integra Google Analytics o similar
5. **Optimización**: Minificar CSS y comprimir imágenes

## Notas Importantes

- El CSS está compilado y optimizado en `styles.css`
- No uses el CDN de Tailwind en producción
- Todas las fuentes se cargan desde Google Fonts
- Los estilos están optimizados para velocidad de carga

---

**Realizado**: 19 de Noviembre de 2025
**Versión**: 1.0.0
