# Módulo 1 - Country Explorer

## Fundamentos de Desarrollo Web con TypeScript

> Buscador de información turística de países usando TypeScript vanilla, HTML5 y Tailwind CSS 4.

---

## Stack Tecnologico

| Dependencia | Version |
|-------------|---------|
| TypeScript | 5.9.3 |
| Vite | 7.3.0 |
| Tailwind CSS | 4.1.8 |
| @tailwindcss/vite | 4.1.8 |
| ESLint | 9.17.0 |
| Prettier | 3.4.2 |

---

## Descripción del Proyecto

**Country Explorer** es una aplicación web educativa que permite buscar y explorar información detallada de cualquier país del mundo. El proyecto está diseñado para enseñar los fundamentos del desarrollo web moderno **sin utilizar frameworks** como React o Vue.

---

## Challenge Lab Implementado

### Part 1: Region Filter

Filtro por región geográfica que:

- Muestra un dropdown con todas las regiones disponibles (África, Américas, Asia, Europa, Oceanía)
- Filtra países por la región seleccionada
- Funciona en combinación con el buscador por nombre
- Incluye opción "Todas las regiones" para resetear el filtro

### Part 2: Favorites System

Sistema de favoritos que:

- Agrega un ícono de corazón (♡/♥) en cada tarjeta de país
- Permite agregar y quitar países de favoritos con un click
- Guarda los favoritos en `localStorage` para que persistan al recargar
- Incluye un toggle para mostrar solo países favoritos
- Incluye un botón para limpiar todos los favoritos

---

## Estructura del Proyecto
```
module1-country-explorer/
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── eslint.config.js
├── .prettierrc
├── .gitignore
└── src/
    ├── main.ts
    ├── styles/
    │   └── main.css
    ├── types/
    │   └── country.ts
    ├── services/
    │   └── countryApi.ts
    ├── components/
    │   ├── CountryCard.ts
    │   └── CountryModal.ts
    └── utils/
        ├── dom.ts
        ├── format.ts
        └── storage.ts
```

---

## Instalación y Uso
```bash
# Instalar dependencias
npm install

# Servidor de desarrollo
npm run dev

# Build de producción
npm run build

# Verificar tipos
npm run type-check

# Linter
npm run lint
```

---

## API Utilizada

**REST Countries API v3.1**
- Documentación: https://restcountries.com
- Sin autenticación requerida
- Endpoint principal: `https://restcountries.com/v3.1/all`
- Endpoint detalle: `https://restcountries.com/v3.1/alpha/{code}`

---

## Video de Demostración

[![Country Explorer Demo](https://img.shields.io/badge/▶_Ver_Demo-Google_Drive-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1Ta6miCqOnwCW3s6qD7qA04qtpa7PClAb?usp=sharing)

