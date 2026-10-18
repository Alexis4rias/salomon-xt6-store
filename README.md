# 👟 Salomon XT-6 Store

Tienda en línea interactiva y página de producto dedicada al icónico calzado **Salomon XT-6**. Desarrollada como una Single Page Application (SPA) moderna, rápida y completamente responsiva utilizando **React**, **Vite** y **Tailwind CSS**.

---

## 📋 Características Principales

* **Galería de Imágenes Interactiva (`ImageGallery`):** Visualización dinámica del calzado desde distintos ángulos según la variante seleccionada.
* **Personalización en Tiempo Real (`ColorSelector` & `SizeSelector`):** Selección interactiva de combinaciones de colores (colorways) y tallas disponibles alimentada por el catálogo local (`shoesData.js`).
* **Carrito de Compras Desplegable (`CartDrawer`):** Panel lateral deslizable para gestionar los productos agregados, modificar cantidades y revisar el resumen de compra sin salir de la vista principal.
* **Ficha de Especificaciones Técnicas (`TechnicalSpecs`):** Desglose detallado de las tecnologías, materiales y características de rendimiento del modelo Salomon XT-6.
* **Navegación Intuitiva (`Navbar`):** Barra superior con acceso rápido y contador de artículos en el carrito.
* **Diseño Estilizado con Tailwind CSS:** Interfaz moderna tipo e-commerce deportivo, adaptable a dispositivos móviles y de escritorio.

---

## 🛠️ Tecnologías Utilizadas

* **Framework / Librería UI:** [React](https://react.dev/) (JSX, Hooks, Gestión de Estado)
* **Entorno de Desarrollo y Bundler:** [Vite](https://vitejs.dev/)
* **Framework de Estilos:** [Tailwind CSS](https://tailwindcss.com/) (`tailwind.config.js`) + CSS3 (`index.css`, `App.css`)
* **Calidad de Código:** ESLint (`eslint.config.js`)
* **Gestor de Paquetes:** npm

---

## 📂 Estructura del Proyecto

El repositorio está organizado bajo una arquitectura modular de componentes y separación de datos:

```text
salomon-xt6-store/
├── public/
│   ├── favicon.svg                         # Ícono de la pestaña del navegador
│   └── icons.svg                           # Recursos vectoriales públicos
├── src/
│   ├── assets/
│   │   ├── hero.png                        # Imagen promocional / Hero
│   │   ├── react.svg                       # Logo de React
│   │   └── vite.svg                        # Logo de Vite
│   ├── components/
│   │   ├── CartDrawer.jsx                  # Panel lateral del carrito de compras
│   │   ├── ColorSelector.jsx               # Selector de variantes de color
│   │   ├── ImageGallery.jsx                # Galería visual del producto
│   │   ├── Navbar.jsx                      # Barra de navegación principal
│   │   ├── SizeSelector.jsx                # Selector de tallas disponibles
│   │   └── TechnicalSpecs.jsx              # Sección de especificaciones técnicas
│   ├── data/
│   │   └── shoesData.js                    # Datos del producto, precios, colores y tallas
│   ├── App.css                             # Estilos específicos de la aplicación
│   ├── App.jsx                             # Componente raíz e integración de estado
│   ├── index.css                           # Directivas de Tailwind CSS y estilos globales
│   └── main.jsx                            # Punto de montaje de React en el DOM
├── .gitignore                              # Archivos excluidos del control de versiones
├── eslint.config.js                        # Configuración de ESLint
├── index.html                              # Documento HTML base
├── Laboratorio_React_Vite_Salomon_XT6.docx # Documentación / Guía de laboratorio del proyecto
├── package.json                            # Dependencias y scripts de ejecución
├── tailwind.config.js                      # Configuración de diseño de Tailwind CSS
└── vite.config.js                          # Configuración del servidor y bundler Vite
```

---

## 🚀 Instalación y Ejecución Local

Sigue estos pasos para clonar y ejecutar la tienda en tu entorno de desarrollo local:

### Prerrequisitos

Tener instalado [Node.js](https://nodejs.org/) (versión 18 o superior recomendada) y `npm`.

### Pasos

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Alexis4rias/salomon-xt6-store.git
   ```

2. **Navegar al directorio del proyecto:**
   ```bash
   cd salomon-xt6-store
   ```

3. **Instalar las dependencias:**
   ```bash
   npm install
   ```

4. **Iniciar el servidor de desarrollo:**
   ```bash
   npm run dev
   ```

5. **Abrir en el navegador:**
   Accede a la URL indicada en la terminal (habitualmente `http://localhost:5173/`).

---

## 📜 Scripts Disponibles

Comandos configurados dentro de `package.json`:

* `npm run dev` — Inicia el servidor de desarrollo local con recarga instantánea (HMR).
* `npm run build` — Compila y empaqueta la aplicación optimizada para producción en la carpeta `dist/`.
* `npm run lint` — Ejecuta el análisis estático de código con ESLint.
* `npm run preview` — Sirve localmente la versión compilada de producción para pruebas finales.

---

## 👤 Autor

* **Jesús Alexis Arias Ricárdez** — [@Alexis4rias](https://github.com/Alexis4rias)

---

## 📄 Licencia

Este proyecto fue desarrollado con fines académicos y de portafolio (Laboratorio React + Vite).