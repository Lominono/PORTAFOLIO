# Portafolio Profesional — Juan Fernando Ospina Tigreros

Portafolio digital minimalista desarrollado con **Next.js** y **React**. Diseñado con criterio editorial suizo, tipografía protagonista, animaciones fluidas al hacer scroll y una estructura técnica optimizada para despliegue inmediato en Vercel.

## 🚀 Despliegue en Vercel

Este proyecto está 100% preparado para desplegarse en **Vercel** sin necesidad de bases de datos, variables de entorno ni configuraciones complejas:

1. Ve a [vercel.com](https://vercel.com) e inicia sesión con tu cuenta de GitHub.
2. Haz clic en **"Add New..."** > **"Project"**.
3. Selecciona el repositorio **`PORTAFOLIO`**.
4. Haz clic en **"Deploy"**. En menos de 1 minuto estará en línea con dominio SSL gratuito.

---

## 🛠️ Desarrollo Local

```bash
# 1. Instalar dependencias
npm install

# 2. Iniciar servidor de desarrollo
npm run dev

# 3. Compilar para producción
npm run build
```

Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

---

## 📂 Estructura del Proyecto

```
PORTAFOLIO/
├── app/
│   ├── layout.tsx        # Layout raíz con metadatos SEO y tipografía Inter
│   ├── page.tsx          # Las 6 secciones del portafolio profesional
│   ├── NavMenu.tsx       # Navegación sticky responsive y menú hamburguesa
│   ├── ScrollReveal.tsx  # Animaciones suaves al hacer scroll (Intersection Observer)
│   └── portfolio.css     # Estilos y variables de diseño editorial
├── public/
│   └── docs/             # Carpeta para tus PDFs (cv-habilidades.pdf, cv-europass.pdf)
├── package.json
├── tsconfig.json
└── next.config.ts
```

---

## 📝 Secciones

1. **01 — Presentación / Identidad Profesional:** Cabecera editorial con espacio para foto, biografía y disponibilidad.
2. **02 — Matriz de Competencias:** Hard skills de SMR y soft skills organizadas y honestas.
3. **03 — Proyectos / Escaparate Técnico:** Fichas de proyectos con enlaces directos a GitHub y demos.
4. **04 — Formación y Aprendizaje:** Ciclo SMR en curso e itinerario de certificaciones y cursos previstos.
5. **05 — Documentación Profesional:** Botones preparados para ver y descargar CV de Habilidades y Europass.
6. **06 — Contacto:** Canales directos a GitHub, correo y redes.
