# Manuales de PrestaShop 9.1

**74 manuales en PDF** para el dueño de una tienda PrestaShop 9.1, en castellano y con
las pantallas reales del back-office.

Están escritos para quien lleva la tienda, no para quien la programa: nada de rutas de
fichero ni de código, y en cada manual una sección con **lo que se suele hacer mal** y
cómo salir de ello. Las capturas están tomadas de una tienda 9.1.1 en funcionamiento, con
sus productos, sus clientes y sus pedidos.

> **[⬇ Descargar los 74 manuales en un solo PDF con índice](../../releases/latest)**
> Los manuales sueltos están en la carpeta [`PDF 9.1/`](PDF%209.1).

| | |
|---|---|
| Manuales | 74 PDF + 1 PDF unificado con índice |
| Versión | PrestaShop 9.1.1 |
| Idioma | castellano de España |
| Formato | A4, con portada, índice de bloque y numeración |

> ¿Tu tienda todavía va con la 8? La misma colección para esa versión está en
> **[ManualesPS8.2](https://github.com/ecomyseo/ManualesPS8.2)**.

---

## Qué cambia respecto a PrestaShop 8.2

Esta colección **no es la de 8.2 con el número cambiado**. Cada manual se ha contrastado
pantalla por pantalla contra una instalación real de 9.1, y esto es lo que había que
reescribir:

| Manual | Qué cambia en 9.1 |
|---|---|
| **25, 26** | Los vales de carrito ahora se llaman **Descuentos**, con pantalla nueva y dos pestañas. El formulario antiguo del cupón sigue existiendo y conviven los dos caminos |
| **50, 51, 53** | **Se acabó el asistente de cuatro pasos** del transportista: ahora es un formulario con tres pestañas y un solo *Guardar*. Los rangos se esconden detrás de un botón |
| **21, 22** | Los valores de atributo y de característica tienen pantallas propias |
| **30-33** | Cambian los rótulos de la ficha del pedido, y hay botones que **desaparecen** cuando el pedido ya ha salido del almacén |
| **36, 38** | Todas las casillas de los estados de pedido se llaman distinto, y hay dos campos nuevos: *Icono* y *Color* |
| **37** | Los carritos tienen columna **Estado** con filtro propio de *Carrito abandonado* |
| **70, 71** | El tema de serie es **Hummingbird**, no *Classic* |
| **74** | De 7 tamaños de imagen a **16**, y varios formatos a generar a la vez (JPEG, WebP, AVIF) |
| **101** | Los **perfiles** pasan a llamarse **roles** |
| **103, 113** | PrestaShop 9 intercala un aviso de seguridad al abrir pantallas antiguas desde un enlace guardado. No es un error, y conviene saberlo |

> **Ojo: en 9.1 hay catorce funciones que vienen APAGADAS.** Están en
> *Parámetros avanzados > Características nuevas y experimentales*, y se
> encienden una a una. Entre ellas, el motor nuevo de cálculo de los
> descuentos en el carrito. El manual **02** las explica todas, con el aviso
> de cómo y cuándo tocarlas.

Y varias cosas que el manual de 8.2 daba por buenas y **no eran ciertas ya**: *Meta
keywords* ha desaparecido de categorías, marcas, proveedores y páginas; el albarán no lo
crea marcar el pedido como enviado sino como **entregado**; y los botones de reembolso no
dependen de que haya factura, sino del cobro.

---

## Por dónde empezar

| Si eres… | Empieza por |
|---|---|
| Nuevo en PrestaShop | **00** índice y mapa del back-office → **01** primeros pasos → **110** de tienda vacía a primera venta |
| Vas a montar el catálogo | **10** cómo se organiza → **11** crear un producto → **20** categorías → **18** precios |
| Vas a empezar a vender | **50** transportistas → **62** impuestos → **55** métodos de pago → **91** configuración de pedidos |
| Ya vendes y toca el día a día | **30** pedidos → **31** la ficha de un pedido → **33** reembolsos → **40** clientes |
| Vienes de PrestaShop 8 o de la 1.7 | **02** todo lo nuevo en 9.1 → **25** descuentos → **50** transportistas → **74** ajustes de imagen |
| Algo no funciona | **113** problemas frecuentes → **100** caché, correo y copias de seguridad |

---

## Los 74 manuales

### Entrada
| | Manual |
|---|---|
| 00 | Índice general y mapa del back-office |
| 01 | Primeros pasos: entrar, panel de control, buscador y modo mantenimiento |
| 02 | **Todo lo nuevo en PrestaShop 9.1** (respecto a la 1.7 y a la 8.2) |

### Catálogo
| | Manual |
|---|---|
| 10 | Catálogo: cómo se organiza una tienda |
| 11 | Crear un producto sin combinaciones, de cero a publicado |
| 12 | Editar un producto: pestaña por pestaña |
| 13 | Crear un producto con combinaciones (talla y color) |
| 14 | Editar combinaciones: imágenes, referencias, GTIN y combinación por defecto |
| 15 | Producto tipo pack (lote de varios artículos) |
| 16 | Producto virtual o descargable |
| 17 | Imágenes del producto: subir, ordenar, portada y miniaturas |
| 18 | Precios: base, IVA, coste, precios específicos y descuentos por cantidad |
| 19 | El listado de productos: filtros, duplicar, borrar y acciones masivas |
| 20 | Categorías: crear, subcategorías, imagen, SEO y orden |
| 21 | Atributos y valores (talla, color con su muestra) |
| 22 | Características (ficha técnica) |
| 23 | Marcas y proveedores |
| 24 | Archivos adjuntos (manuales en PDF, fichas técnicas) |
| 25 | Descuentos: vales y códigos promocionales |
| 26 | Descuentos de catálogo: rebajas automáticas |
| 27 | Stocks: stock disponible, movimientos y stock por combinación |
| 28 | Monitoreo: productos sin imagen, sin precio y categorías vacías |

### Pedidos y ventas
| | Manual |
|---|---|
| 30 | Pedidos: listado, filtros, exportar y qué significa cada estado |
| 31 | La ficha de un pedido: estados, mensajes, documentos y direcciones |
| 32 | Modificar un pedido ya hecho: añadir, quitar y cambiar cantidades |
| 33 | Reembolsos: estándar, parcial y devolución al monedero |
| 34 | Facturas: generar, reimprimir y opciones de la factura |
| 35 | Abonos (notas de crédito) |
| 36 | Albaranes de entrega |
| 37 | Carritos de compra y carritos abandonados |
| 38 | Estados de pedido y de devolución: crear uno propio con su correo |
| 39 | Devoluciones de mercancía |

### Clientes
| | Manual |
|---|---|
| 40 | Clientes: ficha, alta manual, historial, monedero y RGPD |
| 41 | Direcciones |
| 42 | Grupos de clientes: precios y descuentos por grupo |
| 43 | Servicio de atención al cliente: hilos, respuestas y contactos |
| 44 | Mensajes de pedido predefinidos |

### Transporte
| | Manual |
|---|---|
| 50 | Crear un transportista paso a paso |
| 51 | Tarifas de envío: por peso y por precio, rangos y zonas |
| 52 | Preferencias de transporte: gastos de gestión y envío gratis |
| 53 | Caso real: Península, Baleares y Canarias con precios distintos |

### Pago
| | Manual |
|---|---|
| 55 | Métodos de pago: qué hay instalado y cómo activar uno |
| 56 | Preferencias de pago: restringir por moneda, grupo, país y transportista |

### Internacional
| | Manual |
|---|---|
| 60 | Localización: paquetes, idiomas, monedas y unidades |
| 61 | Ubicaciones geográficas: zonas, países y provincias |
| 62 | Impuestos y reglas de impuestos: IVA español e IGIC canario |
| 63 | Traducciones: traducir la tienda, un módulo o un correo |

### Diseño
| | Manual |
|---|---|
| 70 | Tema y logotipo: logos, favicon y tema del móvil |
| 71 | Instalar, cambiar y exportar un tema |
| 72 | Páginas (CMS): crear páginas legales y enlazarlas |
| 73 | Posiciones: mover módulos y trasplantarlos a otro sitio |
| 74 | Ajustes de imagen: tamaños, miniaturas y formatos |
| 75 | Enlaces del pie de página y menú superior |

### Módulos y estadísticas
| | Manual |
|---|---|
| 80 | Gestor de módulos: buscar, configurar, activar y desinstalar |
| 81 | Instalar un módulo desde un ZIP y qué hacer si falla |
| 82 | Alertas de módulos y actualizaciones |
| 83 | Los módulos que toda tienda debe revisar |
| 85 | Estadísticas: las vistas explicadas y cuáles miran de verdad |

### Parámetros de la tienda
| | Manual |
|---|---|
| 90 | Configuración general: mantenimiento, SSL y cookies |
| 91 | Configuración de pedidos: invitado, mínimo de compra, condiciones y regalos |
| 92 | Ajustes de productos: paginación, stock, últimas unidades y novedades |
| 93 | Ajustes de clientes: registro, B2B, contraseñas y RGPD |
| 94 | Contacto y tiendas físicas |
| 95 | Tráfico y SEO: URL amigables, meta, robots.txt y redirecciones |
| 96 | Buscar: alias, palabras vacías, indexación y etiquetas |

### Parámetros avanzados
| | Manual |
|---|---|
| 100 | El día a día: rendimiento y caché, correo (SMTP) y copias de seguridad |
| 101 | Personas y control: equipo, roles, permisos y registros |
| 102 | Importar CSV: productos, combinaciones, clientes y precios |
| 103 | La parte técnica, con aviso: gestor SQL, webservice y depuración |

### Guías prácticas
| | Manual |
|---|---|
| 110 | De tienda vacía a primera venta: lista de comprobación de 20 puntos |
| 111 | Montar una campaña de rebajas completa |
| 112 | Dar de alta una temporada entera: CSV y generador de combinaciones |
| 113 | Problemas frecuentes y cómo salir de ellos |
| 114 | Glosario de términos de PrestaShop |

---

## Por qué son 73 manuales y el último es el 114

El número **no es un contador: es una dirección**. La decena dice a qué bloque pertenece
el manual, y entre bloque y bloque se dejan huecos a propósito.

| Bloque | Rango usado | Huecos libres |
|---|---|---|
| Entrada | 00-02 | 03-09 |
| Catálogo | 10-28 | 29 |
| Pedidos y ventas | 30-39 | — |
| Clientes | 40-44 | 45-49 |
| Transporte | 50-53 | 54 |
| Pago | 55-56 | 57-59 |
| Internacional | 60-63 | 64-69 |
| Diseño | 70-75 | 76-79 |
| Módulos | 80-83 | 84 |
| Estadísticas | 85 | 86-89 |
| Parámetros de la tienda | 90-96 | 97-99 |
| Parámetros avanzados | 100-103 | 104-109 |
| Guías prácticas | 110-114 | — |

74 números ocupados y 41 libres entre el 00 y el 114.

La razón es práctica: **los manuales se citan entre ellos por su número** todo el rato
(«el IGIC canario está en el 62», «el detalle de las miniaturas, en el 74»). Hay más de
cien referencias cruzadas de ese tipo. Con una numeración correlativa, añadir mañana un
manual nuevo obligaría a renumerar todo lo que viene detrás y a repasar esas cien
referencias una a una. Con huecos, el manual nuevo entra en su bloque y no se mueve nada.

Efecto secundario que conviene saber: **el orden alfabético de la carpeta no es el orden
de lectura** (el `100` aparece antes que el `11`). El orden bueno es el de esta página y
el del índice del PDF unificado.

---

## Cómo está hecho cada manual

La misma estructura en los 74, para que se lean rápido y se puedan usar como referencia:

- **Para qué sirve esto** — el porqué, en tres frases.
- **Dónde está** — la ruta del menú, con la pantalla delante.
- **La pantalla, campo por campo** — con los nombres literales que trae PrestaShop en
  castellano, no traducidos a ojo.
- **Cómo se hace, paso a paso** — una acción por punto.
- **Lo que se suele hacer mal** — los fallos reales, con su aviso.

---

## Aviso

Guías no oficiales. PrestaShop es una marca de PrestaShop S.A.; esta colección no está
asociada a ella. Verificadas sobre **PrestaShop 9.1.1**: en otras versiones algunas
pantallas cambian de sitio.

## Autoría

**Ecom Experts** · [ecomyseo@gmail.com](mailto:ecomyseo@gmail.com) · gmartos.es
Servicios, mantenimiento y módulos a medida para PrestaShop.
