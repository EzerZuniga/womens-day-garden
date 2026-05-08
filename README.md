# 🌸 Jardín Digital de Flores - Día de la Mujer

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-Modular-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-11-0085FF?style=for-the-badge&logo=framer&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-2ea44f?style=for-the-badge)

Experiencia web interactiva y personalizada para celebrar el Día Internacional de la Mujer.  
Un jardín digital donde cada flor cobra vida para revelar un mensaje especial dedicado a **Diana Saenz Pahuara**.  
Construido con React y animado con Framer Motion, desplegado de forma continua en Vercel o Netlify.

---

## 🌺 Tabla de contenidos

1. [Características clave](#-características-clave)
2. [Stack tecnológico](#-stack-tecnológico)
3. [Flujo de la experiencia](#-flujo-de-la-experiencia)
4. [Comenzar](#-comenzar)
5. [Scripts disponibles](#-scripts-disponibles)
6. [Estructura del proyecto](#-estructura-del-proyecto)
7. [Despliegue](#-despliegue)
8. [Buenas prácticas](#-buenas-prácticas)
9. [Contribuidores](#-contribuidores)
10. [Licencia](#-licencia)

---

## ✨ Características clave

- **Pantalla de bienvenida personalizada**: introducción en español con el nombre de la homenajeada.
- **Jardín animado con flores interactivas**: cada flor responde al clic mostrando un mensaje único.
- **Mensajes dedicados**: frases especiales pensadas exclusivamente para Diana.
- **Animación ambiental de pétalos realistas**: efecto visual inmersivo generado con Framer Motion.
- **Mensaje final revelador**: sorpresa especial al desbloquear todas las flores del jardín.
- **Interfaz responsive**: experiencia fluida y optimizada tanto en móviles como en escritorio.

---

## 🛠️ Stack tecnológico

| Capa | Tecnologías | Descripción |
| --- | --- | --- |
| Frontend | React 18, JavaScript ES6+, JSX | Componentes funcionales y lógica interactiva de la UI. |
| Build & Dev | Vite 5 | Empaquetador ultrarrápido con HMR para desarrollo ágil. |
| Estilos | SCSS (Sass) modular | Estilos organizados, reutilizables y fáciles de mantener. |
| Animaciones | Framer Motion 11 | Animaciones fluidas, declarativas y de alto rendimiento. |
| Despliegue | Vercel / Netlify | CI/CD configurado con `vercel.json` y `netlify.toml`. |

---

## 🌸 Flujo de la experiencia

1. **Pantalla de inicio**: el usuario es recibido con una dedicatoria personalizada.
2. **Exploración del jardín**: se muestra el jardín digital con flores animadas.
3. **Interacción con las flores**: al hacer clic en cada flor, esta revela un mensaje especial.
4. **Ambientación continua**: los pétalos caen suavemente durante toda la experiencia.
5. **Revelación final**: al desbloquear todas las flores, aparece un mensaje de cierre.

---

## 🚀 Comenzar

### Requisitos previos

- Node.js 18 LTS o superior
- npm 9+ (o yarn/pnpm equivalente)
- Navegador web moderno

### Instalación rápida

```bash
# 1) Clonar repositorio
git clone https://github.com/EzerZuniga/womens-day-garden.git
cd womens-day-garden

# 2) Instalar dependencias
npm install

# 3) Iniciar servidor de desarrollo
npm run dev
```
---

La aplicación estará disponible por defecto en `http://localhost:5173`.

---

## 📟 Scripts disponibles

### npm

| Comando | Descripción |
| --- | --- |
| `npm run dev` | Inicia el servidor de desarrollo Vite con HMR. |
| `npm run build` | Genera la build de producción en la carpeta `dist/`. |
| `npm run preview` | Previsualiza localmente la build de producción. |

---

## 📁 Estructura del proyecto

```text
womens-day-garden/
├── public/                  # Archivos estáticos
├── src/
│   ├── components/          # Componentes React (flores, pétalos, mensajes, etc.)
│   ├── styles/              # Hojas de estilo SCSS modulares
│   ├── data/                # Mensajes y contenido personalizado
│   ├── App.jsx              # Componente raíz
│   └── main.jsx             # Punto de entrada
├── .gitignore
├── index.html               # Plantilla HTML principal
├── package.json
├── vite.config.js           # Configuración de Vite
├── vercel.json              # Configuración de despliegue en Vercel
├── netlify.toml             # Configuración de despliegue en Netlify
└── README.md
```
---

## 🌐 Despliegue

### ▲ Vercel
1. El repositorio incluye un archivo `vercel.json` listo.
2. Al importar el proyecto, Vercel detecta Vite automáticamente.
3. **Configuración por defecto:**
   * **Framework:** Vite
   * **Build Command:** `npm run build`
   * **Output Directory:** `dist`

### 🔷 Netlify
1. El repositorio incluye un archivo `netlify.toml` listo.
2. Al conectar el repositorio, Netlify usa esta configuración:
   * **Build command:** `npm run build`
   * **Publish directory:** `dist`

Ambos servicios despliegan automáticamente con cada push a la rama `main`.

---

## 💡 Buenas prácticas

- Ejecuta `npm run build` localmente antes de hacer push para verificar que no haya errores.
- Mantén los estilos organizados en la carpeta `src/styles/` usando la metodología modular de SCSS.
- Si personalizas los mensajes, edita únicamente el archivo de datos correspondiente en `src/data/`.
- Usa componentes funcionales y evita lógica compleja fuera de los hooks de React.

---

## 👩‍💻 Contribuidores

| Nombre | Rol |
| --- | --- |
| **Ezer Benito Zuñiga Chura** | Desarrollo y conceptualización |
| **Miguel Flores Sollasi** | Colaboración |

---

## 📄 Licencia

Este proyecto se distribuye bajo licencia **MIT**.  
Consulta [LICENSE](./LICENSE) para más detalles.

---

*🌸 Creado con dedicación para celebrar el 8M.*
