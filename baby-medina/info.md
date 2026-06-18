# Baby Medina

Aplicación Android que encapsula la tienda online Baby Medina, mostrando su catálogo, carrito y sistema de pedidos por WhatsApp dentro de un WebView con soporte offline.

## Características

- ✅ Catálogo de productos con filtros por categoría
- ✅ Búsqueda en tiempo real
- ✅ Carrito de compras local
- ✅ Envío de pedidos por WhatsApp
- ✅ **Modo offline**: navega sin conexión gracias a la caché del WebView
- ✅ **Progreso de carga en tiempo real** con barra indicadora
- ✅ **Página de error personalizada** cuando falla la carga o no hay conexión
- ✅ Pantalla de bienvenida (splash screen) con estilo de la marca
- ✅ Actualización por deslizamiento (pull-to-refresh)

## Tecnologías

- Kotlin
- WebView con caché avanzada (`LOAD_CACHE_ELSE_NETWORK`)
- `WebChromeClient` para seguimiento del progreso de carga
- SwipeRefreshLayout para recarga manual
- AndroidX Core y AppCompat

## Mejoras recientes (v1.1.0)

- **Progreso visual en tiempo real** durante la carga de la página.
- **Manejo elegante de errores** con una página HTML local que mantiene la identidad visual de la tienda.
- **Caché inteligente**: si no hay red, intenta mostrar la versión guardada; si no existe, muestra el fallback.
- **Limpieza de dependencias innecesarias** (eliminadas Compose, Room, Navigation, etc.).

## Contacto

Para soporte o consultas:  
📞 [WhatsApp](https://wa.me/5352461405)  
✉️ Email: eniomedina2003@gmail.com

---

*Para mi querido primo, un regalo de cumpleaños. Espero que triunfes en todo aquello que te propongas.*  
**Baby Medina** – Tu tienda de confianza.