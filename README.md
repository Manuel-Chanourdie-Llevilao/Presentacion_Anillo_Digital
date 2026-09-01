# División Anillo Digital - Presentación 2026 📊

Presentación HTML profesional de la División Anillo Digital de la Policía de la Ciudad con información operativa 2026.

## 📋 Descripción

Presentación de 5 diapositivas (slides) con:
- **Diapositiva 1:** Portada con 3 escudos institucionales (DAD, Policía, SIPGE)
- **Diapositiva 2:** Capacidades Operativas (Infraestructura y Funciones)
- **Diapositiva 3:** Resultados Operativos con Gráficos (Procedimientos y Alarmas)
- **Diapositiva 4:** Análisis Detallado con Tablas de Comparación 2025 vs 2026
- **Diapositiva 5:** Conclusiones y Logros

## 🎨 Características Técnicas

- **Diseño Responsivo:** Aspect ratio 16:9 adaptable a diferentes pantallas
- **Colores Corporativos:**
  - Azul Principal: `#2373aa`
  - Gris: `#b8b8b8`
  - Negro: `#06090a`
- **Gráficos Interactivos:** Chart.js para visualización de datos
- **Animaciones Fluidas:** Transiciones CSS3 y efectos hover
- **Tipografía:** Google Fonts - Poppins (300, 400, 600, 700)
- **Sin dependencias externas:** HTML5, CSS3, JavaScript vanilla + Chart.js

## 🚀 Requisitos

- Navegador moderno (Chrome, Firefox, Edge, Safari)
- Conexión a internet (para CDN de Chart.js y Google Fonts)
- Acceso a las imágenes locales (rutas configuradas en Windows)

## 📁 Estructura de Archivos

```
presentacion_anillo_digital.html  (Archivo principal - Todo en uno)
README.md                          (Este archivo)
```

### Rutas de Imágenes Utilizadas

Las imágenes están alojadas en:
```
C:\Users\chanu\OneDrive\02-Sistema de Gestion de Calidad\Datos\2024\Imagenes\
```

**Archivos necesarios:**
- `Escudo Dorado.jpeg` - Escudo DAD
- `01. Escudo nuevo policia de la ciudad recortado.png` - Escudo Policía
- `SIPGE.png` - Escudo Superintendencia

## 💻 Instalación y Uso

### Opción 1: Uso Local (Recomendado)

1. Descarga el archivo `presentacion_anillo_digital.html`
2. Colócalo en cualquier carpeta de tu computadora
3. Haz doble clic para abrir en tu navegador
4. ¡Listo! La presentación se abrirá automáticamente

### Opción 2: Usar con Servidor Local (Para mejor rendimiento)

```bash
# Con Python 3
python -m http.server 8000

# Con Python 2
python -m SimpleHTTPServer 8000

# Con Node.js (instala http-server primero)
npx http-server
```

Luego abre: `http://localhost:8000/presentacion_anillo_digital.html`

### Opción 3: Publicar en Línea

Puedes subir el archivo a:
- GitHub Pages
- Netlify
- Vercel
- Cualquier hosting web

## ⌨️ Navegación

### Controles de Teclado
- **Flecha Derecha (→)** o **Spacebar**: Siguiente diapositiva
- **Flecha Izquierda (←)**: Diapositiva anterior

### Controles del Ratón
- **Botón "Siguiente →"**: Avanza a la siguiente diapositiva
- **Botón "← Anterior"**: Retrocede a la diapositiva anterior
  - *Nota: Se oculta automáticamente en la Diapositiva 1*
  - *Nota: "Siguiente" se oculta automáticamente en la Diapositiva 5*

### Indicador
- Muestra: "Diapositiva X de 5"

## 📊 Contenido de Diapositivas

### Diapositiva 1: Portada
- 3 Escudos institucionales (180x180px cada uno)
- Título: "DIVISIÓN ANILLO DIGITAL"
- Subtítulo y detalles de departamento
- Año: 2026

### Diapositiva 2: Capacidades Operativas
**Columna Izquierda - Infraestructura:**
- 75 Cámaras de Videovigilancia
- 886 Lectores ANPR/LPR
- 43 Rodados Operativos
- 254 Personal Capacitado

**Columna Derecha - Funciones:**
- 5 Funciones principales con emojis
- Certificación ISO 9001:2015

### Diapositiva 3: Resultados Operativos
**Gráfico 1 (Izquierda):** Procedimientos Realizados
- Procedimiento de Interceptación
- Procedimiento de Aprehensión
- Actuaciones GAP

**Gráfico 2 (Derecha):** Alarmas Atendidas
- Datos 2025 vs 2026
- Visualización comparativa

### Diapositiva 4: Análisis Detallado
**Tabla 1:** Procedimientos Realizados
- Interceptaciones: ↑23.5%
- Aprehendidos: ↑8.3%
- Actuaciones GAP: ↑82.4%

**Tabla 2:** Alarmas
- Alarmas Atendidas: ↑163.8% ⭐

### Diapositiva 5: Conclusiones y Logros
**Hitos Operativos Destacados (4 items)**
**Impacto Operacional (4 items)**
**Caja de Resumen** con conclusión general

## 🔧 Personalización

### Cambiar Colores Corporativos

En el archivo HTML, busca la sección `<style>` y modifica:

```css
/* Colores actuales */
--color-primary: #2373aa;    /* Azul principal */
--color-secondary: #267ca2;  /* Azul secundario */
--color-gray: #b8b8b8;       /* Gris */
--color-dark: #06090a;       /* Negro */
--color-dark-medium: #5d5d5d; /* Gris oscuro */
```

### Cambiar Imágenes

Localiza las líneas con etiquetas `<img>` y reemplaza las rutas:

```html
<img src="NUEVA_RUTA_AQUI" alt="Descripción" class="escudo">
```

### Modificar Contenido

Busca los títulos y textos en el HTML y edita directamente. Los estilos se aplicarán automáticamente.

## 📈 Mejoras Implementadas (Versión 2026)

✅ 3 escudos institucionales en portada
✅ Sin barras de desplazamiento (contenido ajustado a pantalla)
✅ Botones de navegación contextuales (se ocultan en extremos)
✅ Gráficos interactivos con Chart.js
✅ Diseño responsivo para múltiples resoluciones
✅ Animaciones suaves y profesionales
✅ Tablas de datos 2025 vs 2026
✅ Énfasis en resultados positivos
✅ Tipografía profesional con Google Fonts

## 🐛 Solución de Problemas

### Las imágenes no cargan
**Solución:** Verifica que las rutas a los archivos sean correctas. En Windows, debes usar `/` en lugar de `\` en las URLs de archivo.

### La presentación se ve pequeña
**Solución:** Presiona `Ctrl + +` en tu navegador para ampliar (o `Cmd + +` en Mac)

### Los gráficos no aparecen
**Solución:** Asegúrate de tener conexión a internet (se carga Chart.js desde CDN)

### Animaciones muy lentas
**Solución:** Tu navegador puede estar usando recursos limitados. Cierra otras pestañas.

## 📱 Compatibilidad

| Navegador | Soporte |
|-----------|---------|
| Chrome    | ✅ Completo |
| Firefox   | ✅ Completo |
| Edge      | ✅ Completo |
| Safari    | ✅ Completo |
| Internet Explorer | ❌ No soportado |

## 📄 Licencia

Este proyecto es de uso interno para la División Anillo Digital - Policía de la Ciudad.

## 👤 Autor

División Anillo Digital
Departamento Coordinación Operativa
Superintendencia Prevención y Gestión de Emergencias

## 📞 Contacto y Soporte

Para reportar problemas o solicitar cambios, contacta al equipo de la División Anillo Digital.

---

**Última actualización:** Septiembre 2026
**Versión:** 2.0
**Estado:** ✅ Producción

