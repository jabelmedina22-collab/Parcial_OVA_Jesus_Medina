# OVA — Teoría de la Información

**Objeto Virtual de Aprendizaje — Tema 14**  
Asignatura: Teoría General de Sistemas (TGS)  
Programa: Ingeniería de Sistemas  
Institución: Universidad Simón Bolívar — Sede Cúcuta  
Autor: Medina Peña Jesús Abel  

---

## Descripción

Este repositorio contiene el código fuente completo de la OVA (Objeto Virtual de Aprendizaje) desarrollada para el tema **Teoría de la Información**, correspondiente a la asignatura Teoría General de Sistemas. La OVA aborda los fundamentos matemáticos y conceptuales de la información, desde la formulación de Claude Shannon (1948) hasta sus aplicaciones en sistemas complejos, inteligencia artificial y telecomunicaciones.

La OVA fue diseñada e implementada íntegramente en HTML5, CSS3 y JavaScript puro, sin dependencias externas de frameworks, lo que garantiza su portabilidad y funcionamiento en cualquier navegador moderno.

---

## Contenido de la OVA

La OVA está organizada en nueve secciones navegables:

| Sección | Descripción |
|---|---|
| Contextualización | Justificación de la importancia de la Teoría de la Información en la TGS y en el mundo contemporáneo |
| Marco teórico | Explicación formal de entropía de Shannon, cantidad de información, redundancia y capacidad de canal |
| Línea del tiempo | Hitos históricos desde Nyquist (1924) hasta la era del Big Data |
| Ejemplos prácticos | Aplicaciones reales en telecomunicaciones, biología informacional e inteligencia artificial |
| Ejercicios | Tres ejercicios de cálculo con retroalimentación inmediata (entropía, canal binario, redundancia) |
| Juego 1 — Decodificador Binario | Juego cronometrado de traducción de cadenas binarias a caracteres ASCII |
| Juego 2 — Ordenamiento Huffman | Actividad de arrastrar y soltar para ordenar símbolos por frecuencia según el algoritmo de Huffman |
| Videos | Tres recursos audiovisuales curados sobre Shannon, entropía y compresión de datos |
| Quiz | Evaluación interactiva de diez preguntas con retroalimentación por ítem y puntaje automático |
| Créditos | Autoría, afiliación institucional y referencias bibliográficas en formato APA |

---

## Estructura del repositorio

```
ova-teoria-informacion/
│
├── index.html          # Archivo principal — contiene toda la OVA (HTML + CSS + JS)
└── README.md           # Documentación del proyecto
```

La OVA es un archivo único autocontenido. Todo el estilo y la lógica interactiva están embebidos en `index.html`, lo que facilita el despliegue en cualquier plataforma de alojamiento estático.

---

## Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica del contenido |
| CSS3 (custom properties, grid, flexbox) | Diseño visual, layout responsivo y animaciones |
| JavaScript (ES6+) | Lógica de juegos, quiz, ejercicios y animaciones de scroll |
| Google Fonts (Syne, DM Mono) | Tipografía |
| Claude AI | Apoyo en la generación y revisión de código |

---

## Despliegue

La OVA puede publicarse en cualquier plataforma de alojamiento de sitios estáticos. A continuación se describen los pasos para las plataformas recomendadas por la asignatura.

### GitHub Pages

1. Crear un repositorio público en GitHub.
2. Subir el archivo `index.html` y el `README.md` a la rama `main`.
3. Ir a **Settings > Pages**.
4. En **Source**, seleccionar la rama `main` y la carpeta raíz `/`.
5. Guardar. El sitio quedará disponible en `https://<usuario>.github.io/<repositorio>/`.

### Netlify

1. Acceder a [netlify.com](https://netlify.com) e iniciar sesión.
2. Seleccionar **Add new site > Import an existing project** o arrastrar la carpeta del proyecto a la zona de despliegue.
3. Netlify asignará automáticamente una URL pública.

### Vercel

1. Acceder a [vercel.com](https://vercel.com) e iniciar sesión.
2. Seleccionar **Add New Project** y conectar el repositorio de GitHub.
3. Vercel detecta automáticamente que es un proyecto estático y lo despliega.

---

## Ejecución local

No se requiere servidor ni instalación de dependencias. Para visualizar la OVA localmente:

1. Clonar o descargar el repositorio.
2. Abrir el archivo `index.html` directamente en un navegador web moderno (Chrome, Firefox, Edge, Safari).

---

## Criterios de evaluación cubiertos

- Contextualización del tema y justificación de su importancia.
- Explicación conceptual y teórica con referencias académicas.
- Ejemplos prácticos aplicados a casos reales.
- Ejercicios planteados con retroalimentación inmediata.
- Dos juegos interactivos.
- Videos relacionados con el tema.
- Quiz con puntaje automático.
- Diseño visual organizado, coherente y responsivo.
- Navegación clara e intuitiva.
- Página de créditos con autoría y referencias bibliográficas.

---

## Referencias principales

- Shannon, C. E. (1948). A mathematical theory of communication. *Bell System Technical Journal, 27*(3), 379–423.
- Shannon, C. E., & Weaver, W. (1949). *The mathematical theory of communication*. University of Illinois Press.
- Cover, T. M., & Thomas, J. A. (2006). *Elements of information theory* (2.a ed.). Wiley-Interscience.
- Bertalanffy, L. von (1968). *General system theory: Foundations, development, applications*. George Braziller.
- Wiener, N. (1948). *Cybernetics: Or control and communication in the animal and the machine*. MIT Press.

---

## Información académica

| Campo | Detalle |
|---|---|
| Asignatura | Teoría General de Sistemas |
| Tema | Teoría de la Información (Tema 14) |
| Autor | Medina Peña Jesús Abel |
| Institución | Universidad Simón Bolívar |
| Sede | Cúcuta, Colombia |
| Periodo académico | 2026-1 |
