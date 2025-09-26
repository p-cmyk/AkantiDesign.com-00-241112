# Akanti Design - Coming Soon Page

Una página "Coming Soon" interactiva y elegante para Akanti Design.

## 🔄 **WORKFLOW DE DESARROLLO - IMPORTANTE**

### **Estructura de ramas:**
- **`main`** → Solo código estable y probado (SE PUBLICA AUTOMÁTICAMENTE)
- **`develop`** → Tu rama de trabajo diario (NO se publica)

### **Para trabajar SIN publicar:**
```bash
# 1. Asegúrate de estar en develop
git checkout develop

# 2. Haz tus cambios y commits libremente
git add .
git commit -m "✨ Cambios en desarrollo"
git push origin develop
```

### **Para PUBLICAR cambios (solo cuando estés seguro):**
```bash
# 1. Ve a main
git checkout main

# 2. Trae los cambios de develop
git merge develop

# 3. Publica (esto actualiza la web)
git push origin main
```

### **⚠️ RECUERDA:**
- Trabaja siempre en `develop` para cambios experimentales
- Solo haz merge a `main` cuando todo esté perfecto
- La web se actualiza automáticamente desde `main`

## 🎨 Características

- **Logo interactivo**: Arrastra, rota y duplica el logo
- **Animaciones suaves** con GSAP
- **Diseño responsive** para móvil y tablet
- **Branding Barcelona**: "design objects made with love in Barcelona"

## 🚀 Funcionalidades Interactivas

- **Arrastrar**: Mueve el logo por la pantalla
- **Rotar**: Haz clic en el logo para activar/desactivar rotación
- **Duplicar**: Usa Ctrl+C y Ctrl+V para copiar y pegar logos

## 🛠️ Tecnologías

- HTML5
- CSS3 con diseño responsive
- JavaScript vanilla
- GSAP para animaciones
- Google Fonts (Nunito & Poppins)

## 📱 Responsive Design

- **Desktop**: Experiencia completa con todas las funcionalidades
- **Tablet**: Adaptado para pantallas medianas
- **Mobile**: Optimizado para dispositivos móviles

## 🌐 Deploy

Este sitio está optimizado para GitHub Pages y funciona directamente abriendo `index.html` en cualquier navegador.

---

© 2024 akantidesign.com - Made with ❤️ in Barcelona
