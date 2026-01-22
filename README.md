# 🤖 Declaración de Uso de IAGen - Universidad Panamericana

Sistema interactivo para documentar el uso de Inteligencia Artificial Generativa en investigación académica.

## 📋 Descripción

Esta aplicación web permite a los investigadores generar declaraciones formales sobre el uso de herramientas de IA Generativa (como ChatGPT, Claude, Gemini, etc.) en sus trabajos académicos, cumpliendo con los estándares de transparencia científica.

## ✨ Características

- ✅ **Interfaz guiada paso a paso** - 6 pasos intuitivos
- ✅ **Múltiples autores** - Agrega tantos autores como necesites
- ✅ **Generación automática de documentos**:
  - Declaración oficial de uso de IAGen
  - Carta formal para la revista
- ✅ **Compatible con OJS** (Open Journal Systems)
- ✅ **40+ áreas de intervención** categorizadas
- ✅ **Exportación a PDF** - Mediante impresión del navegador
- ✅ **Sin instalación** - 100% web, funciona en cualquier navegador

## 🚀 Uso

### Acceso directo:
**[https://xixaro.github.io/DeclaracionIAGenUP/](https://xixaro.github.io/DeclaracionIAGenUP/)**

### Pasos para completar la declaración:

1. **Autores**: Ingresa la información de todos los investigadores
2. **LLMs utilizados**: Especifica los modelos de IA que empleaste
3. **Áreas de intervención**: Selecciona dónde usaste IAGen
4. **Detalles**: Describe cómo utilizaste la IA
5. **Resumen**: Verifica toda la información
6. **Descargar**: Obtén tus documentos en formato HTML/PDF

## 📥 Descarga de Documentos

La aplicación genera dos documentos:

1. **Declaración de IAGen**: Formulario oficial con todas las especificaciones técnicas
2. **Carta para la Revista**: Carta formal dirigida al editor

Ambos documentos pueden ser convertidos a PDF usando la función de impresión del navegador (Ctrl+P / Cmd+P).

## 🔧 Instalación Local

Si deseas usar la aplicación sin conexión:

1. Descarga el archivo `index.html`
2. Ábrelo en tu navegador (Chrome, Firefox, Edge, Safari)
3. ¡Listo! Funciona completamente offline

```bash
# Clonar el repositorio
git clone https://github.com/xixaro/DeclaracionIAGenUP.git

# Abrir el archivo
cd DeclaracionIAGenUP
open index.html  # Mac
start index.html  # Windows
xdg-open index.html  # Linux
```

## 🎓 Integración con OJS

### Opción A: Página estática
1. Copia el contenido de `index.html`
2. En OJS, ve a **Configuración → Sitio web → Páginas estáticas**
3. Crea una nueva página y pega el código

### Opción B: iFrame
Inserta este código en cualquier página de OJS:

```html
<iframe src="https://xixaro.github.io/DeclaracionIAGenUP/" 
        width="100%" 
        height="900px" 
        frameborder="0"
        style="border: none;">
</iframe>
```

## 📊 Áreas de Intervención Cubiertas

La aplicación cubre 8 categorías principales:

- 🔬 **Etapa Preliminar**: Ideas, objetivos, hipótesis
- 📚 **Etapa de Revisión**: Literatura, tendencias, novedad
- 🧪 **Metodología**: Diseño, protocolos, métodos
- 💻 **Software y Automatización**: Código, algoritmos
- 📊 **Gestión de Datos**: Recopilación, análisis, visualización
- ✍️ **Escritura y Edición**: Generación de texto, corrección, traducción
- ⚖️ **Revisión Ética**: Sesgos, riesgos, confidencialidad
- 🔍 **Revisión y Supervisión**: Calidad, limitaciones, recomendaciones

## 🛡️ Privacidad y Seguridad

- ✅ **Sin registro de datos**: La aplicación no almacena información del usuario
- ✅ **Procesamiento local**: Todos los datos se procesan en tu navegador
- ✅ **Sin cookies ni tracking**: Respeto total a tu privacidad

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/NuevaFuncionalidad`)
3. Commit tus cambios (`git commit -m 'Agrega nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/NuevaFuncionalidad`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 📧 Contacto

**Universidad Panamericana**
- Repositorio: [github.com/xixaro/DeclaracionIAGenUP](https://github.com/xixaro/DeclaracionIAGenUP)
- Issues: [github.com/xixaro/DeclaracionIAGenUP/issues](https://github.com/xixaro/DeclaracionIAGenUP/issues)

## 🙏 Agradecimientos

Esta herramienta fue desarrollada para facilitar la transparencia en el uso de IA Generativa en la investigación académica, promoviendo las mejores prácticas científicas.

---

**Versión 1.0** - Enero 2025

¿Tienes preguntas o sugerencias? [Abre un issue](https://github.com/xixaro/DeclaracionIAGenUP/issues)
