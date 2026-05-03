# 🐣 Lista para Leandro José

Lista de compras interactiva para bebé de 0 a 6 meses.

## 📋 ¿Qué es?

Un dashboard que te ayuda a hacer seguimiento de todo lo que necesitás comprar antes y después del nacimiento de Leandro José. Incluye 13 categorías con 119 ítems sugeridos, organizados por etapa de urgencia.

## 🚀 Cómo usar

1. Abrí `index.html` en el navegador (doble click)
2. Ves el progreso general y por categoría
3. Tocá los botones **+** y **−** para marcar lo que vas comprando
4. Usá **➕ Agregar ítem** para sumar productos personalizados
5. Todo se guarda automáticamente en tu navegador

## 📦 Categorías

- 🚗 Seguridad y transporte
- 😴 Sueño
- 🧷 Pañales e higiene
- 🛁 Baño y cuidado personal
- 👕 Ropa talla RN, 0-3m y 3-6m
- 🍼 Lactancia y alimentación
- 🧣 Pañitos y mantas
- 👜 Paseos y salidas
- 🤱 Cargar y calmar
- 🧸 Juego 0-3m y 3-6m

## 🛠️ Estructura

| Archivo | Función |
|---------|---------|
| `index.html` | Dashboard interactivo (HTML + CSS + JS, sin dependencias) |
| `data.js` | Lista maestra de ítems sugeridos (editá este para cambiar la base) |
| `data.json` | Respaldo en JSON |

## 🔄 Actualizar

- **Tus compras**: usá los botones **+**/**−** en el dashboard. Se guardan solos.
- **La lista base**: editá `data.js` y refrescá el navegador.
- **Reset**: botón "🔄 Restablecer lista" para volver a la lista original.
