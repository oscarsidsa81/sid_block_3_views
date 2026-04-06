# sid_block_3_views

## Descripción
`sid_block_3_views` es un metamódulo de Odoo orientado a agrupar y activar un conjunto de personalizaciones de vistas relacionadas con ventas y compras.

Según su manifiesto, este módulo no declara datos propios para cargar (`data: []`), por lo que su función principal es servir como punto de consolidación de dependencias.

## Información del módulo
- **Nombre técnico:** `sid_block_3_views`
- **Versión:** `15.0.1.0.0`
- **Autor:** SIDSA
- **Licencia:** LGPL-3
- **Categoría:** Hidden
- **Instalable:** Sí
- **Aplicación:** No
- **Auto-instalable:** No

## Dependencias (módulos en el manifest)
Este módulo depende de los siguientes módulos:

1. `sid_block_2_sales_purchase`
2. `sid_sale_line_views_ov`
3. `sid_purchase_views_ov`

> Importante: para instalar `sid_block_3_views` correctamente, estos tres módulos deben estar disponibles en la ruta de addons de Odoo.

## Estructura actual
- `__manifest__.py`: metadatos y dependencias del módulo.
- `__init__.py`: inicialización Python del módulo (sin carga adicional en su estado actual).

## Instalación
1. Copia este módulo dentro de tu ruta de addons.
2. Asegúrate de tener instaladas sus dependencias.
3. Actualiza la lista de aplicaciones en Odoo.
4. Instala `sid_block_3_views` desde Apps o con línea de comandos.

## Notas
Al tratarse de un metamódulo sin `data` propio, cualquier cambio funcional visible dependerá de lo definido en los módulos listados como dependencia.
