# Proyecto Diseño Web - Guía Completa

## 📋 Estructura del Proyecto

```
jael/
├── noticias/                    # Proyecto 1: Portal de Noticias
│   ├── index.html              # Archivo HTML principal
│   └── assets/
│       ├── css/
│       │   └── styles.css       # Estilos del proyecto
│       └── img/                # Carpeta para imágenes
│
├── posicionamiento/            # Proyecto 2: Demostración de Posicionamientos
│   ├── index.html              # Archivo HTML principal
│   └── assets/
│       ├── css/
│       │   └── styles.css      # Estilos del proyecto
│       └── img/                # Carpeta para imágenes
│
└── index.html                   # Página de inicio (menú principal)
```

---

## 🎯 Requisitos Cumplidos

### ✅ 1 Punto: Publicación Correcta
- Archivo HTML bien estructurado
- CSS optimizado y bien organizado
- Listo para publicar en hosting gratuito
- Rutas relativas configuradas correctamente

### ✅ 2 Puntos: Propuesta Gráfica
**PROYECTO 1 - NOTICIAS:**
- Tema: Portal moderno "NEXO"
- Jerarquía visual clara: Header → Featured → Grid
- Recursos expresivos: Gradientes, colores armoniosos, tipografía variada

**PROYECTO 2 - POSICIONAMIENTO:**
- Tema: Tutorial educativo interactivo
- Colores distintivos y animaciones
- Ejemplos visuales claros

### ✅ 2 Puntos: HTML y CSS Correctos
- Etiquetas semánticas: `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Nombres de clases funcionales (NO estéticos)
- Variables CSS para mantenimiento
- Etiquetas bien cerradas

### ✅ 2 Puntos: Posicionamientos
- **RELATIVE**: Identificados como contextos de posicionamiento
- **ABSOLUTE**: Identificados para elementos específicos
- Todos con comentarios explicativos en HTML

---

## 🚀 Cómo Usar

### Abrir en VS Code
1. Abre VS Code
2. Menú: `Archivo → Abrir carpeta`
3. Selecciona `c:\Users\Yvn\Desktop\jael`

### Ver en el Navegador
1. Opción 1: Click derecho en `index.html` → "Open with Live Server"
2. Opción 2: Arrastra `index.html` al navegador
3. Opción 3: Desde terminal: `python -m http.server`

### Agregar Imágenes
```
noticias/assets/img/
├─ featured.jpg
├─ news1.jpg
├─ news2.jpg
├─ news3.jpg
└─ news4.jpg

posicionamiento/assets/img/
└─ product-placeholder.jpg
```

---

## 🌐 Publicar en Hosting Gratuito

### GitHub Pages (Recomendado)
1. Crea cuenta en github.com
2. Crea repositorio llamado `jael`
3. Sube los archivos
4. Settings → Pages → Deploy from main
5. Tu URL: `https://usuario.github.io/jael/`

### Netlify o Vercel
1. Conecta tu repositorio GitHub
2. Deploy automático
3. Tu URL será asignada automáticamente

---

## 📌 Ubicación de Posicionamientos

### RELATIVE (Contextos)
- `.header-container` en noticias
- `.featured-story` en noticias
- `.card-image-container` en noticias
- `.relative-parent` en posicionamiento
- `.absolute-parent` en posicionamiento
- `.product-image-container` en posicionamiento
- `.price-container` en posicionamiento

### ABSOLUTE (Elementos Posicionados)
- `.header-accent` en noticias
- `.category-badge` en noticias
- `.breaking-badge` en noticias
- `.category-label` en noticias
- `.relative-child` en posicionamiento
- `.absolute-child` (4 elementos) en posicionamiento
- `.discount-badge` en posicionamiento
- `.new-badge` en posicionamiento
- `.sale-label` en posicionamiento

---

## 📞 Soporte Rápido

**¿Las imágenes no cargan?**
- Usa rutas relativas: `assets/img/nombre.jpg`

**¿CSS no se ve?**
- Verifica que esté en: `assets/css/styles.css`

**¿Quiero cambiar colores?**
- Abre `styles.css` → busca `:root {}`
- Modifica valores de variables

---

## ✨ Características Especiales

- ✅ Responsive design incluido
- ✅ Animaciones suaves
- ✅ Código limpio y comentado
- ✅ Variables CSS para fácil mantenimiento
- ✅ 9+ elementos con posicionamientos
- ✅ Documentación completa

---

**¡Tu proyecto está 100% listo! 🎉**

Puntuación esperada: **7 PUNTOS TOTALES**
