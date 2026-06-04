# ⚡ Simulador de Resistencia Eléctrica

> Herramienta educativa interactiva para el aprendizaje de circuitos eléctricos, electrónica digital y conceptos fundamentales de resistencia.

## 📋 Descripción

El **Simulador de Resistencia Eléctrica** es una aplicación web moderna e interactiva diseñada para estudiantes de electrónica y circuitos eléctricos. Permite explorar y comprender de manera visual y práctica los conceptos fundamentales de la ley de Ohm, códigos de color de resistencias, y comportamiento de circuitos en serie y paralelo.

### Características Principales

✨ **Interfaz moderna y responsiva** - Diseño oscuro profesional con animaciones suaves  
🎓 **Tres módulos educativos** - Ley de Ohm, Código de colores, Circuitos serie/paralelo  
⚙️ **Cálculos en tiempo real** - Actualizaciones instantáneas al ajustar parámetros  
📊 **Visualizaciones interactivas** - Circuitos animados con electrones en movimiento  
🎨 **Código de colores visual** - Representación gráfica de resistores con bandas coloreadas  
📱 **Diseño responsive** - Compatible con dispositivos móviles y de escritorio

---

## 🎯 Módulos del Simulador

### 1. ⚡ Ley de Ohm

Explora la relación fundamental: **V = I × R**

**Funcionalidades:**

- Ajusta voltaje (1-24V) y resistencia (1-100Ω) con sliders interactivos
- Calcula automáticamente:
  - Corriente eléctrica (A)
  - Potencia disipada (W)
- Visualización en tiempo real con barras de progreso
- Circuito animado con electrones moviéndose según la corriente
- Interpretación inteligente del comportamiento del circuito
- Medidor analógico integrado

### 2. 🎨 Código de Colores

Aprende a interpretar el código de colores de resistencias

**Funcionalidades:**

- Ajusta 4 bandas coloreadas de una resistencia
  - Banda 1: Decenas (0-9)
  - Banda 2: Unidades (0-9)
  - Banda 3: Multiplicador (×1 a ×1M)
  - Banda 4: Tolerancia (±1%, ±5%, ±10%)
- Cálculo automático del valor de resistencia
- Rango de tolerancia mostrado en Ohmios
- Tabla de referencia de colores estándar
- Representación visual del resistor con bandas

### 3. 🔗 Serie y Paralelo

Simula circuitos con múltiples resistencias en diferentes configuraciones

**Funcionamiento Serie:**

- Corriente igual en todas las resistencias
- Voltaje se divide entre ellas
- Fórmula: R_total = R1 + R2 + R3

**Funcionamiento Paralelo:**

- Voltaje igual en todas las resistencias
- Corriente se divide entre ellas
- Fórmula: 1/R_total = 1/R1 + 1/R2 + 1/R3

**Características:**

- Ajusta 3 resistencias independientes (10-200Ω)
- Control de voltaje de la fuente (1-24V)
- Cálculos automáticos de:
  - Resistencia total
  - Corriente total
  - Potencia total
  - Voltaje/Corriente en cada resistencia
- Diagramas esquemáticos animados
- Información conceptual sobre cada configuración

---

## 🚀 Cómo Usar

### Acceso Directo

Simplemente abre el archivo `simulador_resistencia.html` en tu navegador web favorito.

### Flujo de Uso

1. **Selecciona un módulo** - Haz clic en las pestañas superiores
2. **Ajusta los parámetros** - Usa los sliders para cambiar valores
3. **Observa los resultados** - Los cálculos se actualizan en tiempo real
4. **Estudia las visualizaciones** - Revisa gráficos y diagramas
5. **Lee las interpretaciones** - Entiende qué significan los números

### Ejemplos Prácticos

#### Ley de Ohm

- Aumenta el voltaje y observa cómo aumenta la corriente
- Aumenta la resistencia y observa cómo disminuye la corriente
- Experimenta con diferentes combinaciones

#### Código de Colores

- Busca una resistencia física y conviértela usando este módulo
- Practica con diferentes valores y tolerancias
- Verifica el rango mínimo y máximo permitido

#### Circuitos

- Cambia entre modo serie y paralelo
- Observa cómo se comporta la corriente y voltaje
- Experimenta con qué sucede al variar la resistencia total

---

## 💻 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Diseño responsive con custom properties (variables)
  - Grid y Flexbox para layouts
  - Animaciones y transiciones suaves
  - Tema oscuro profesional
- **JavaScript Vanilla** - Lógica interactiva
  - Cálculos matemáticos en tiempo real
  - Animaciones de electrones con requestAnimationFrame
  - Manipulación dinámica del DOM
  - SVG para gráficos vectoriales

### Librerías Externas

- **Google Fonts** - Tipografías personalizadas:
  - JetBrains Mono (código)
  - Syne (títulos)

---

## 📦 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado
- Conexión a internet (para cargar las fuentes de Google)

**Navegadores Recomendados:**

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

---

## 📥 Instalación

### Opción 1: Uso Local

```bash
# Clona el repositorio
git clone https://github.com/usuario/academia-basica.git
cd academia-basica

# Abre el archivo en tu navegador
open simulador_resistencia.html
# o en Linux
xdg-open simulador_resistencia.html
```

### Opción 2: Servidor Local (Recomendado)

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (npm)
npx http-server

# Con Live Server en VS Code
# Extensión: Live Server
```

Luego accede a: `http://localhost:8000/simulador_resistencia.html`

### Opción 3: Hosting Online

Sube el archivo a cualquier servicio de hosting estático:

- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

---

## 📚 Conceptos Educativos Cubiertos

### Teoría de Circuitos

- ✅ Ley de Ohm (V = I × R)
- ✅ Potencia eléctrica (P = V × I)
- ✅ Resistencias en serie
- ✅ Resistencias en paralelo
- ✅ División de voltaje
- ✅ División de corriente

### Electrónica Básica

- ✅ Código de colores de resistencias (4 bandas)
- ✅ Tolerancia de resistencias
- ✅ Rango de valores estándar
- ✅ Comportamiento de componentes

---

## 🎨 Paleta de Colores

El simulador utiliza una paleta moderna y consistente:

| Color   | Uso                   | Hex     |
| ------- | --------------------- | ------- |
| Navy    | Fondo principal       | #0A1628 |
| Azul    | Voltaje               | #1E88E5 |
| Naranja | Resistencia/Highlight | #FF6D00 |
| Verde   | Potencia/Corriente    | #00897B |
| Blanco  | Texto principal       | #F5F7FA |
| Gris    | Texto secundario      | #8B9BAE |

---

## 🔧 Estructura del Código

```
simulador_resistencia.html
├── HEAD
│   ├── Meta tags (charset, viewport)
│   ├── Google Fonts
│   └── CSS estilos (1000+ líneas)
├── BODY
│   ├── Header (título y badge)
│   ├── Navegación (tabs)
│   ├── Panel 1: Ley de Ohm
│   │   ├── Fórmula
│   │   ├── Controles (sliders)
│   │   ├── Resultados (métricas)
│   │   └── Circuito animado (SVG)
│   ├── Panel 2: Código de Colores
│   │   ├── Controles de bandas
│   │   ├── Resistor visual
│   │   └── Tabla de colores
│   ├── Panel 3: Serie/Paralelo
│   │   ├── Toggle de modo
│   │   ├── Controles de resistencias
│   │   ├── Cálculos totales
│   │   └── Diagrama del circuito
│   ├── Footer
│   └── JavaScript (500+ líneas)
```

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Para contribuir:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

### Ideas de Mejoras Futuras

- Modo oscuro/claro toggleable
- Exportar circuitos como imagen
- Generador de problemas aleatorios
- Modo quiz/cuestionario
- Soporte para más tipos de circuitos
- Internacionalización (i18n)
- Compatibilidad con dispositivos táctiles mejorada
- Base de datos de componentes reales

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver archivo `LICENSE` para más detalles.

---

## 👨‍💻 Autor

Desarrollado como herramienta educativa para **Academia Básica** - 2026

**Contacto:** contacto@academia-basica.com

---

## 📞 Soporte

¿Preguntas o problemas? Abre un issue en el repositorio o contacta al equipo de desarrollo.

---

## ✅ Checklist de Funcionalidades

- [x] Interfaz responsiva
- [x] Ley de Ohm interactiva
- [x] Código de colores
- [x] Circuitos serie/paralelo
- [x] Animaciones de electrones
- [x] Cálculos en tiempo real
- [x] Visualizaciones SVG
- [x] Interpretaciones inteligentes
- [x] Diseño moderno
- [x] Compatible con navegadores modernos

---

## 🎓 Recursos Educativos Recomendados

- [Khan Academy - Circuitos Eléctricos](https://www.khanacademy.org/)
- [Electrónica Básica - Universidad de Stanford](https://online.stanford.edu/)
- [Código de Colores de Resistencias - IEC 60062](https://es.wikipedia.org/wiki/C%C3%B3digo_de_colores_de_resistencias)
- [Ley de Ohm - Wikipedia](https://es.wikipedia.org/wiki/Ley_de_Ohm)

---

**Última actualización:** 3 de Junio de 2026  
**Versión:** 1.0.0
