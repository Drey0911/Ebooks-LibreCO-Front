<p align="center">
  <img src="./src/assets/img/readLogo.png" alt="LibreCO logo" width="420"/>
</p>

<h1 align="center">LibreCO · Frontend</h1>

<p align="center">
  SPA para la venta de libros digitales con catálogo, carrito, checkout y biblioteca personal.<br/>
  <sub>SPA to sell digital books with catalog, cart, checkout and a personal library.</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/stack-MERN-61DAFB?style=flat" alt="MERN"/>
  <img src="https://img.shields.io/badge/license-All%20rights%20reserved-6B7280?style=flat" alt="All rights reserved"/>
  <img src="https://img.shields.io/badge/year-2025-495057?style=flat" alt="2025"/>
</p>

<p align="center">
  <a href="#español">Español</a> · <a href="#english">English</a> ·
  <a href="https://github.com/Drey0911/Ebooks-LibreCO-BACKEND">Backend</a>
</p>

<p align="center">
  <img src="https://drey.is-a.dev/img/projects/project6/project6-7.png" alt="LibreCO home" width="90%"/>
</p>

## Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat&logo=react&logoColor=black" alt="React 19"/>
  <img src="https://img.shields.io/badge/Vite-7-646CFF?style=flat&logo=vite&logoColor=white" alt="Vite 7"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Tailwind%20CSS-CDN-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <br/>
  <img src="https://img.shields.io/badge/Axios-HTTP-5A29E4?style=flat&logo=axios&logoColor=white" alt="Axios"/>
  <img src="https://img.shields.io/badge/Lucide-Icons-F56565?style=flat" alt="Lucide"/>
  <img src="https://img.shields.io/badge/OGL-WebGL-000000?style=flat&logo=webgl&logoColor=white" alt="OGL"/>
  <img src="https://img.shields.io/badge/ESLint-9-4B32C3?style=flat&logo=eslint&logoColor=white" alt="ESLint 9"/>
</p>

## Screenshots

<table>
  <tr>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project6/project6-6.png" alt="Featured books"/>
      <br/><b>Destacados · Featured</b><br/><sub>Libros en promoción con descuento</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project6/project6-3.png" alt="Book details"/>
      <br/><b>Detalle del libro · Book details</b><br/><sub>Sinopsis, ficha técnica y compra</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project6/project6-4.png" alt="Checkout"/>
      <br/><b>Checkout</b><br/><sub>Tarjeta, PayPal o transferencia</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project6/project6-5.png" alt="My library"/>
      <br/><b>Mi biblioteca · My library</b><br/><sub>Leer y descargar los ebooks comprados</sub>
    </td>
  </tr>
</table>

---

## Español

> Frontend del e-commerce LibreCO, construido con React y Vite. Se conecta a la [API en Express](https://github.com/Drey0911/Ebooks-LibreCO-BACKEND) para el catálogo, la autenticación y las compras.

### Funcionalidades

| Área | Descripción |
|---|---|
| **Inicio** | Hero animado con una galaxia en WebGL (OGL). |
| **Catálogo** | Búsqueda, filtros por categoría y paginación. |
| **Destacados** | Libros en promoción con descuento, estados de carga y vacíos. |
| **Carrito** | Desplegable en el header con total y botón de pago. |
| **Checkout** | Pago con tarjeta, PayPal o transferencia. |
| **Biblioteca** | Abrir y descargar los ebooks comprados (PDF y EPUB). |
| **Cuenta** | Registro, inicio de sesión y alertas configurables. |

### Cómo ejecutarlo

1. Requisitos: **Node.js 18+**.
2. Ajusta `API_URL` en `src/services/api.js` (por defecto `http://localhost:5000/api`).
3. Ejecuta:
   ```bash
   npm install
   npm run dev        # http://localhost:5173
   ```

| Script | Acción |
|---|---|
| `npm run build` | Build de producción |
| `npm run preview` | Sirve el build |
| `npm run lint` | ESLint |

### Estructura

```
src/
  components/layout     Header (carrito), footer y modal de autenticación
  components/sections   Hero, catálogo, destacados, checkout, biblioteca
  hooks/useAuth.js      Login, registro y estado del usuario
  services/             Cliente REST, auth, libros y compras
```

---

## English

> Frontend for the LibreCO e-commerce, built with React and Vite. It connects to the [Express API](https://github.com/Drey0911/Ebooks-LibreCO-BACKEND) for the catalog, authentication and purchases.

### Features

| Area | Description |
|---|---|
| **Home** | Animated hero with a WebGL galaxy (OGL). |
| **Catalog** | Search, category filters and pagination. |
| **Featured** | Discounted books, with loading and empty states. |
| **Cart** | Header dropdown with total and checkout button. |
| **Checkout** | Pay by card, PayPal or bank transfer. |
| **Library** | Open and download purchased ebooks (PDF and EPUB). |
| **Account** | Sign up, sign in and configurable alerts. |

### Getting started

1. Requirements: **Node.js 18+**.
2. Set `API_URL` in `src/services/api.js` (default `http://localhost:5000/api`).
3. Run:
   ```bash
   npm install
   npm run dev        # http://localhost:5173
   ```

Other scripts: `npm run build`, `npm run preview` and `npm run lint`.

---

## Licencia · License

Todos los derechos reservados · All rights reserved. © 2025 Andrey Stteven Mantilla Leon. Si se usa como base, inspiración o referencia, se debe dar crédito al autor · If used as a base, inspiration or reference, credit the author.
