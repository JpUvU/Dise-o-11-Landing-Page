# 🌐 Proyecto: Landing Pages

Este proyecto muestra una **colección de páginas tipo landing page** diseñadas en Figma y presentadas dentro de un sitio web simple con **HTML y CSS**.  
El objetivo es tener una galería visual donde se puedan ver miniaturas de las páginas (capturas) y acceder fácilmente a cada diseño mediante un botón de “Ver detalles”.

---

## 📁 Estructura del Proyecto


```
📦 DISEÑO LANDING PAGES
├── 📂 assets
│ ├── captura 1.png
│ ├── captura 2.png
│ ├── captura 3.png
│ ├── captura 4.png
│ ├── captura 5.png
│ ├── captura 6.png
│ ├── captura 7.png
│ ├── Captura 8.png
│ ├── captura 9.png
│ └── captura 10.png
│
├── 📂 css
│ └── styles.css
│
├── 📄 index.html
│
└── 🧾 README.md
```


---

## 🧱 Descripción de los Archivos

### **index.html**
Archivo principal que contiene la estructura del sitio:
- Un encabezado (`header`) con el título del proyecto.  
- Una sección principal (`section.section-paginas`) donde se muestran las tarjetas (`.card`) de cada diseño.  
- Cada tarjeta incluye una imagen, el nombre de la página y un botón que redirige al diseño en Figma.

### **css/styles.css**
Define los estilos visuales del sitio:
- Colores base, tipografía y márgenes globales.  
- Diseño en cuadrícula flexible (`.grid`) que se adapta a diferentes tamaños de pantalla.  
- Tarjetas (`.card`) con sombra, bordes redondeados y alturas simétricas.  
- Imágenes con altura fija y `object-fit: cover` para mantener proporción visual.  
- Botones estilizados con hover animado.

---

## 🎨 Estilo Visual

Las tarjetas de cada landing se presentan con un diseño limpio y uniforme.  
Cada imagen tiene un tamaño controlado (180px de alto), lo que mantiene todas las tarjetas alineadas visualmente, sin importar el tamaño original de las capturas.

---

## 🧰 Tecnologías Utilizadas

- **HTML5:** para la estructura del sitio.  
- **CSS3 (Flexbox):** para el diseño responsivo y la disposición simétrica de las tarjetas.  
- **Figma:** para los diseños originales de las landing pages.

---

## 🚀 Cómo Usarlo

1. Clona o descarga este repositorio.  
2. Asegúrate de mantener la estructura de carpetas (`assets`, `css`, etc).  
3. Abre el archivo `index.html` en tu navegador.  
4. Verás todas las miniaturas de las páginas y podrás acceder a cada diseño con el botón **“Ver detalles”**.

---

## 💡 Mejoras Futuras

- Agregar diseño responsive con media queries.  
- Implementar un filtro o buscador para las landing pages.  
- Añadir efectos de transición al pasar el cursor por las tarjetas.

---

## 👨‍💻 Autor

**Juan Pablo**  
📅 *Octubre 2025*  
✨ Proyecto creado con HTML, CSS y mucho diseño.

