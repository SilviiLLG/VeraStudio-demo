# VÉRA Studio — E-commerce demo

Tienda frontend demostrativa de indumentaria, creada para el portfolio de Teknovya.

## Incluye
- Diseño responsive para desktop y celular.
- Catálogo de productos con filtros por categoría, búsqueda y ordenamiento.
- Vista rápida de producto y selección de talle.
- Carrito lateral con cantidades, eliminación y subtotal.
- Persistencia del carrito mediante `localStorage`.
- Barra de progreso para envío gratis.
- Checkout simulado: no procesa pagos ni genera pedidos reales.
- Formulario de newsletter demostrativo.
- No requiere base de datos ni variables de entorno.

## Publicar en GitHub y Vercel
1. Subí `index.html`, `styles.css`, `app.js`, `vercel.json` y `README.md` a la raíz de un repositorio.
2. En Vercel, elegí **Add New → Project** y conectá ese repositorio.
3. Framework Preset: **Other**.
4. Build Command: dejalo vacío.
5. Output Directory: `.` (raíz del proyecto).
6. Deploy.

También podés importar directamente el repositorio a Vercel si ya lo tenés conectado.

## Ejecutar localmente
Abrí `index.html` en el navegador o serví la carpeta con cualquier servidor estático.

## Nota importante
Este es un proyecto frontend de portfolio. Los productos, precios y compras son ficticios. El carrito se guarda localmente en el navegador de cada visitante; no se comparte entre usuarios. No hay pagos reales, inventario, gestión administrativa ni backend. Las fotografías se cargan desde Unsplash y las tipografías desde Google Fonts, por lo que esas partes requieren conexión a internet.
