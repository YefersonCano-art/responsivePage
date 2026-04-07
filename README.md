# Landing Responsive con Astro

Una landing page moderna y responsive construida con **Astro** y **Tailwind CSS**, con énfasis en semántica HTML5, mobile-first y rendimiento.

## 🎯 Características

- **Responsive Design**: Múltiples breakpoints (sm, md, lg, xl) adaptados a cualquier dispositivo.
- **Componentes Reutilizables**: Arquitectura modular con componentes Astro independientes.
- **Modal Interactivo**: Botón CTA con modal emergente y animación de flecha.
- **Optimizaciones**: SSG, lazy loading en imágenes, código CSS mínimo.
- **Accesibilidad**: Semántica HTML5, atributos alt, contraste de colores.

## 📁 Estructura del Proyecto

```
src/
├── layouts/
│   └── MainLayout.astro       # Layout base con metadatos
├── components/
│   ├── Hero.astro             # Sección héroe con imagen
│   ├── Card.astro             # Componente de tarjeta
│   ├── Grid.astro             # Grid responsive
│   ├── Button.astro           # Botón CTA reutilizable
│   └── Footer.astro           # Pie de página
├── pages/
│   └── index.astro            # Página principal
└── styles/
    └── global.css             # Estilos globales (Tailwind)
```

## 🚀 Comandos

| Comando       | Descripción                         |
| :------------ | :---------------------------------- |
| `bun dev`     | Inicia servidor de desarrollo       |
| `bun build`   | Construye la versión de producción  |
| `bun preview` | Previsualiza la build de producción |

## 🛠️ Stack Técnico

- **Framework**: Astro 6.1.4
- **Estilos**: Tailwind CSS 4.2.2
- **Package Manager**: Bun
