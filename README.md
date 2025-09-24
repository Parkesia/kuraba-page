# 🔍 Kuruba - Sitio Web Oficial

Sitio web oficial de Kuruba, la aplicación móvil para escanear ingredientes de productos en tiempo real.

## 📋 Descripción

Este repositorio contiene el sitio web estático de Kuruba, implementado como GitHub Pages. Kuruba es una aplicación móvil que permite a los usuarios escanear etiquetas de productos para obtener información instantánea sobre sus ingredientes, todo procesado localmente para garantizar la máxima privacidad.

## 🌟 Características del Sitio Web

- **Diseño responsivo**: Optimizado para dispositivos móviles, tablets y desktop
- **Política de privacidad completa**: Documentación detallada de nuestras prácticas de privacidad
- **Rendimiento optimizado**: Carga rápida y experiencia de usuario fluida
- **Accesibilidad**: Implementado siguiendo las mejores prácticas de accesibilidad web
- **SEO optimizado**: Metadatos y estructura optimizada para motores de búsqueda

## 📁 Estructura del Proyecto

```
kuraba-page/
├── index.html          # Página principal
├── privacy.html        # Política de privacidad
├── styles.css          # Estilos CSS
└── README.md          # Este archivo
```

## 🚀 Despliegue con GitHub Pages

### Configuración Automática

1. Ve a la configuración del repositorio en GitHub
2. Navega a la sección "Pages" en el menú lateral
3. En "Source", selecciona "Deploy from a branch"
4. Selecciona la rama `main` y la carpeta `/ (root)`
5. Haz click en "Save"

El sitio estará disponible en: `https://[tu-usuario].github.io/kuraba-page/`

### URL Personalizada (Opcional)

Para usar un dominio personalizado:

1. Crea un archivo `CNAME` en la raíz del proyecto:
   ```
   tudominio.com
   ```
2. Configura los DNS de tu dominio para apuntar a GitHub Pages

## 🛠️ Desarrollo Local

Para trabajar en el sitio localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/[tu-usuario]/kuraba-page.git
   cd kuraba-page
   ```

2. Abre `index.html` en tu navegador o usa un servidor local:
   ```bash
   # Con Python 3
   python -m http.server 8000
   
   # Con Python 2
   python -m SimpleHTTPServer 8000
   
   # Con Node.js (live-server)
   npx live-server
   ```

3. Visita `http://localhost:8000` en tu navegador

## 📱 Sobre Kuruba

### ¿Qué es Kuruba?

Kuruba es una aplicación móvil innovadora que escanea ingredientes de productos alimenticios y proporciona información relevante sobre su consumo para ayudarte a tomar decisiones alimentarias informadas. La aplicación analiza los ingredientes en tiempo real y ofrece recomendaciones personalizadas, todo procesado localmente en tu dispositivo.

### Características Principales

- **🔍 Escaneo inteligente**: Análisis instantáneo de ingredientes con evaluación de impacto
- **🧠 Análisis de consumo**: Información relevante sobre cómo los ingredientes afectan tu bienestar
- **🎯 Recomendaciones personalizadas**: Sugerencias basadas en el análisis de ingredientes
- **📊 Información nutricional**: Análisis detallado de cada ingrediente
- **☁️ Procesamiento en la nube**: API propia para análisis preciso y actualizado
- **🌐 Conexión requerida**: Acceso a nuestra base de datos actualizada de ingredientes
- **📱 Multiplataforma**: Disponible para iOS y Android

### Privacidad y Datos

- 📊 **Métricas de ingredientes**: Recopilamos datos sobre consultas para mejorar el servicio
- 🔒 **Sin datos personales**: No recopilamos información personal identificable
- ☁️ **API propia**: Procesamiento seguro en nuestros servidores
- 🎯 **Mejora continua**: Los datos nos ayudan a tomar decisiones sobre nuevas funcionalidades
- ✅ **Transparencia completa**: Te informamos claramente qué datos utilizamos y cómo

## 📞 Contacto

> **Nota**: Información de contacto pendiente de finalización

- **Email**: info@parkesia.com
- **Sitio web**: *En desarrollo*

## 📄 Licencia

Este sitio web está diseñado específicamente para Kuruba. Los contenidos están protegidos por derechos de autor.

## 🔄 Actualizaciones

Para mantener el sitio actualizado:

1. Realiza cambios en los archivos HTML/CSS
2. Haz commit de los cambios:
   ```bash
   git add .
   git commit -m "Actualizar contenido del sitio"
   git push origin main
   ```
3. GitHub Pages se actualizará automáticamente

## 📊 Métricas y Analytics

El sitio está preparado para integrar herramientas de analytics que respeten la privacidad de los usuarios, siguiendo la misma filosofía de la aplicación Kuruba.

## 🤝 Contribuir

Si encuentras algún error o tienes sugerencias para mejorar el sitio web, puedes:

1. Abrir un issue en GitHub
2. Enviar un email a info@parkesia.com
3. Crear un pull request con tus mejoras

---

**Kuruba** - Decisiones alimentarias inteligentes al alcance de tu mano. 🥗✨
