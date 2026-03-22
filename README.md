# 🛍️ Mi Negocio en Números

> **Herramienta de gestión financiera para negocios dropshipping** — diseñada para emprendedores sin base contable que quieren entender sus números mes a mes.

![Estado de Resultados Dropshipping](https://img.shields.io/badge/versión-1.0.0-c07a3a?style=flat-square) ![License](https://img.shields.io/badge/licencia-MIT-2d6a4f?style=flat-square) ![Sin instalación](https://img.shields.io/badge/sin%20instalación-funciona%20en%20el%20browser-1a73e8?style=flat-square)

---

## ¿Qué es esto?

Una app web que funciona directo en tu navegador (sin instalar nada) para llevar el **estado de resultados mensual** de tu tienda dropshipping en Shopify. Pensada para personas sin conocimientos contables — todo está explicado en lenguaje simple.

**Funciona con:**
- Shopify + Dropi (Chile)
- Meta Ads (Facebook / Instagram)
- Cualquier modelo de negocio ecommerce similar

---

## ✨ Funcionalidades

### 📂 Gestión de proyectos
- Crea múltiples proyectos (ej: "Tienda Ropa", "Empresa 2")
- Cada proyecto guarda su propio historial mes a mes
- Los datos persisten en el navegador (localStorage) — no se pierden al cerrar

### 📊 Estado de Resultados completo
- **Ingresos:** ventas brutas, devoluciones → ventas netas
- **Costos de venta:** producto, despacho, comisión Shopify, rechazos
- **Gastos operacionales:** Meta Ads, plan Shopify, apps, diseño
- **Resultado:** utilidad bruta y neta automática

### 🎯 KPIs automáticos con semáforo de color
- Margen bruto y neto
- ROAS (retorno en publicidad)
- Tasa de rechazo de pedidos

### 💡 Ayuda contextual
- Botón ⓘ en cada campo con explicación detallada en popup
- Ejemplos con números reales (ej: "40 pedidos × $5.000 = $200.000")
- Mensajes de diagnóstico automáticos al completar el mes

### 📅 Historial mensual
- Guarda cada mes con un clic
- Navega entre meses guardados desde la barra de historial
- Semáforo verde/rojo por mes según resultado

### 📊 Exportar a Google Sheets
- Genera un `.xlsx` descargable con formato profesional
- Incluye hoja "Mes actual" + hoja "Historial" con todos los meses comparados
- Compatible con Google Sheets sin necesidad de Excel instalado

### 🤖 Consultor del negocio (experimental)
- Genera un resumen estructurado de tus números del mes
- Listo para analizar con IA en el chat

---

## 🚀 Cómo usar

### Opción 1 — GitHub Pages (recomendado)
Accede directamente en el navegador: **[Ver demo →](https://matiasvelosocontreras-max.github.io/mi-negocio-en-numeros)**

### Opción 2 — Archivo local
1. Descarga `app/index.html`
2. Ábrelo con doble clic en cualquier navegador moderno (Chrome, Safari, Firefox)
3. ¡Listo! No necesitas internet para usarlo después de la primera carga

---

## 📁 Estructura del proyecto

```
mi-negocio-en-numeros/
├── app/
│   └── index.html          # App completa (single file)
├── docs/
│   └── screenshots/        # Capturas para documentación
├── README.md
└── LICENSE
```

---

## 🗺️ Roadmap

- [x] v1.0 — App single-file con proyectos y historial
- [ ] v1.1 — Modo comparación entre proyectos
- [ ] v1.2 — Gráfico de evolución mensual
- [ ] v2.0 — Versión web con backend (datos en la nube)
- [ ] v2.1 — Multi-usuario / equipos

---

## 🛠️ Stack técnico

- **HTML + CSS + JavaScript** puro — sin frameworks, sin dependencias de build
- **SheetJS (xlsx.js)** — exportación a Excel/Google Sheets
- **localStorage** — persistencia de datos en el browser
- **Google Fonts** (Fraunces + DM Sans) — tipografía

---

## 📄 Licencia

MIT © 2025 Matías Veloso — libre para uso personal y comercial con atribución.

---

*Construido con ❤️ para emprendedores dropshipping en Chile 🇨🇱*
