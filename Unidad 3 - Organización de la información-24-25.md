# Unidad 3 - Organización de la información-24-25

## Índice

- 1 Gestión de compras y ventas
	- 1.1 Creación de socios
	- 1.2 Productos
	- 1.3 Compras
	- 1.4 Ventas
	- 1.5 Devoluciones
	- 1.6 Informes
- 2 Gestión de almacén
- 3 Gestión de contabilidad
	- 3.1 Diarios
	- 3.2 Impuestos
	- 3.3 Mecanismos de pago
- 4 Gestión de recursos humanos
	- 4.1 Gestión de empleados y contratos
	- 4.2 Gestión de la asistencia
- 5 Gestión de las relaciones con los clientes (CRM)
- 6 Utilización del TPV
- 7 Generación de sitio web de empresa
- 8 Tienda online
- 9 Auditoría y control
	- 9.1 PostgreSQL
	- 9.2 Servidor

[⬅ Volver al índice](#índice)

<a id="1-gestión-de-compras-y-ventas--3"></a>

## 1 Gestión de compras y ventas ....................................................................................................... 3

[⬅ Volver al índice](#índice)



---

<a id="11-creación-de-socios--4"></a>

## 1.1 Creación de socios ............................................................................................................... 4

[⬅ Volver al índice](#índice)



---

<a id="12-productos-6"></a>

## 1.2 Productos.............................................................................................................................. 6

[⬅ Volver al índice](#índice)



---

<a id="13-compras-8"></a>

## 1.3 Compras............................................................................................................................... 8

[⬅ Volver al índice](#índice)



---

<a id="14-ventas-11"></a>

## 1.4 Ventas................................................................................................................................. 11

[⬅ Volver al índice](#índice)



---

<a id="15-devoluciones-13"></a>

## 1.5 Devoluciones...................................................................................................................... 13

[⬅ Volver al índice](#índice)



---

<a id="16-informes-14"></a>

## 1.6 Informes............................................................................................................................. 14

[⬅ Volver al índice](#índice)



---

<a id="2-gestión-de-almacén--15"></a>

## 2 Gestión de almacén .................................................................................................................... 15

[⬅ Volver al índice](#índice)



---

<a id="3-gestión-de-contabilidad--21"></a>

## 3 Gestión de contabilidad ............................................................................................................. 21

[⬅ Volver al índice](#índice)



---

<a id="31-diarios-21"></a>

## 3.1 Diarios................................................................................................................................ 21

[⬅ Volver al índice](#índice)



---

<a id="32-impuestos-23"></a>

## 3.2 Impuestos........................................................................................................................... 23

[⬅ Volver al índice](#índice)



---

<a id="33-mecanismos-de-pago--24"></a>

## 3.3 Mecanismos de pago .......................................................................................................... 24

[⬅ Volver al índice](#índice)



---

<a id="4-gestión-de-recursos-humanos--25"></a>

## 4 Gestión de recursos humanos .................................................................................................... 25

[⬅ Volver al índice](#índice)



---

<a id="41-gestión-de-empleados-y-contratos--26"></a>

## 4.1 Gestión de empleados y contratos ...................................................................................... 26

[⬅ Volver al índice](#índice)



---

<a id="42-gestión-de-la-asistencia--28"></a>

## 4.2 Gestión de la asistencia ...................................................................................................... 28

[⬅ Volver al índice](#índice)



---

<a id="5-gestión-de-las-relaciones-con-los-clientes-crm--30"></a>

## 5 Gestión de las relaciones con los clientes CRM ........................................................................ 30

[⬅ Volver al índice](#índice)



---

<a id="6-utilización-del-tpv--36"></a>

## 6 Utilización del TPV ................................................................................................................... 36

[⬅ Volver al índice](#índice)



---

<a id="7-generación-de-sitio-web-de-empresa--39"></a>

## 7 Generación de sitio web de empresa .......................................................................................... 39

[⬅ Volver al índice](#índice)



---

<a id="8-tienda-online-40"></a>

## 8 Tienda online.............................................................................................................................. 40

[⬅ Volver al índice](#índice)



---

<a id="9-auditoría-y-control--41"></a>

## 9 Auditoría y control ..................................................................................................................... 41

[⬅ Volver al índice](#índice)



---

<a id="91-postgresql-41"></a>

## 9.1 PostgreSQL........................................................................................................................ 41

[⬅ Volver al índice](#índice)



---

<a id="92-servidor-44"></a>

## 9.2 Servidor.............................................................................................................................. 44

[⬅ Volver al índice](#índice)

Bibliografía y Webgrafía .................................................................................................................. 47
Introducción
Durante este apartado se aprenderá a manejar Odoo para ello utilizaremos los recursos y blogs de ayuda
desde los soportes oficiales.
https://www.odoo.com/documentation/18.0/es/
Lo primero que es importante recordar es que Odoo es un producto ideado para trabajar en empresas de
diversos tamaños y situadas en diversos países. Esto quiere decir, que se ha diseñado de manera muy general,
utilizando posteriormente módulos para poder localizar y adaptar el producto a las necesidades particulares
de la empresa. En este tema nos vamos a centrar principalmente en las funcionalidades diseñadas para una
pequeña o mediana empresa española (PYME). La idea es trabajar con el ERP para familiarizarnos con su
uso.

---

<a id="1-gestión-de-compras-y-ventas"></a>

## 1 Gestión de compras y ventas

[⬅ Volver al índice](#índice)

Para  afrontar  la  gestión  de  compras  y  ventas  dentro  de  una  empresa,  primeramente,  es  preciso  tener
configurados los actores principales en estos módulos: clientes y proveedores.
En la siguiente figura se puede observar lo que podría representar un proceso de gestión de compraventa:
Unidad 3: Organización de la información

---

<a id="11-creación-de-socios"></a>

## 1.1 Creación de socios

[⬅ Volver al índice](#índice)

Se puede definir a un socio como cualquier persona u organismo con la que tengamos algún tipo de relación.
Principalmente, se refiere a clientes y proveedores, pero también se podría considerar a los empleados.
La configuración de los socios es parte vital de un ERP, ya que estos intervendrán en prácticamente todos los
módulos del mismo. Para nuestro sistema, un socio es cualquier persona u organismo con el que tengamos
algún tipo de relación. Esta definición incluye tanto a clientes como proveedores e incluso la podríamos
extender a los empleados.
Para poder acceder a la configuración de clientes y proveedores, han de estar instalados previamente los
módulos de Compra y Ventas.
El acceso al maestro de proveedores se realiza desde el menú Facturación / Contabilidad, y una vez dentro,
ya aparece un menú en la parte superior que está relacionado con los proveedores:
Una vez dentro, hay que ir a la opción Proveedores en la que ya aparece un botón para crear un nuevo
proveedor.
Lo primero que se ve es el campo nombre del proveedor y sus datos generales tales como correo electrónico,
teléfono, dirección, etc. Debajo de estos datos están las vistas del proveedor que se enumeran a continuación:
•Contactos y direcciones:  Desde esta vista se dan de alta todos los contactos de este proveedor
•Venta y compra: Datos propios de este proveedor referente a las acciones de compra y venta tales
como los plazos de pago
•Contabilidad: Datos para su facturación como la cuenta bancaria.
•Notas internas: Texto descriptivo para anotar cualquier mensaje que se desee ver cada vez que
consultamos los datos de este proveedor. Sirven para anotar información tales como sus horarios, etc.
a la vez que permite planificar actividades.
De forma similar, se pueden crear los clientes, los cuales se necesitarán en la gestión de ventas. Para ello hay
que dirigirse a Contabilidad / Clientes / Clientes y se pulsa en el botón de Crear.
Igual que para los proveedores, se ve su nombre y datos generales como correo electrónico, teléfono,
dirección, etc. Debajo de estos datos están las vistas del cliente con la misma denominación que para los
proveedores.
Unidad 3: Organización de la información

---

<a id="12-productos"></a>

## 1.2 Productos

[⬅ Volver al índice](#índice)

El funcionamiento de una empresa se basa en comprar productos a los proveedores y vender los suyos a los
clientes. Puede ser que solo distribuya, con lo cual venderá los mismos productos proporcionados o en un
proceso de fabricación, aquellos creados a partir de los entregados por los proveedores. En ambos casos, es
preciso tener una organización concreta de los productos con los que se trabaja, dónde se ubican y cómo se
clasifican.  Por  tanto,  lo  primero  que  hay  que  hacer  es  crear  un  conjunto  de  categorías  de  productos
clasificándolos, en la medida de lo posible, atendiendo a los estándares del mercado o a criterios utilizados
por empresas similares. Odoo dispone de una estructura jerárquica con un único padre: Todos los productos
(All). Por defecto, Odoo cuenta además con dos categorías hijas: All/Expenses, que podría corresponder a
esos productos que compramos y All/Saleable que se identificaría con los productos de salida.
La gestión de las categorías de productos se hace a través del módulo de inventario:En este módulo existe
una entrada de menú llamada Configuración y en ella una opción Productos/Categorías de productos . Al
entrar ya se ven las categorías por defecto además de un botón para la creación de nuevas categorías.
Los únicos datos que se cubren son el nombre y categoría padre, en caso de que sea requerida.
En la siguiente imagen se pueden ver una serie de categorías de ejemplo:
Es importante mantener actualizados los datos del producto además de establecerlos cuidadosamente con el
fin de disponer de la mayor información posible. La gestión de productos ya se realiza en el módulo de
ventas, en su opción correspondiente Productos.
Podemos ver la creación de un producto de ejemplo:
Como se ve en la imagen, lo primero que se pide es el Nombre del producto. Establecemos si el producto
Puede ser vendido, comprado o ambos. A continuación, se establece el tipo de producto, donde Consumible
significa que no se gestiona el stock y la cantidad es ilimitada, Almacenable implica que vamos a gestionar
su stock y Servicio si no es un producto al uso, sino un servicio que proporcionamos.
Además de la Categoría y de una referencia interna, se dispone del precio de coste y el de venta incluyendo
los impuestos. En la pestaña de Inventario tenemos la parte de Logística, en la que introducimos el Peso y
V olumen del producto además del Responsable.
Dentro de cada producto existe también la posibilidad de registrar su stock. En la parte superior de la ventana
de edición, se ven cuántas unidades tenemos a mano y cuántas previstas. Si se entra en cualquiera de las
opciones, se puede crear un stock de unidades relacionado directamente con el módulo de inventario, lo que
actualizará el stock previsto.
Unidad 3: Organización de la información

---

<a id="13-compras"></a>

## 1.3 Compras

[⬅ Volver al índice](#índice)

A nivel general, las aplicaciones del módulo de compra permiten:
•Identificar a los principales proveedores (ya visto en el anterior apartado)
•Negociar precios
•Dar la orden de compra al proveedor
•Recepción de la facturación
•Descuentos sobre compras
•Control de compras
•Control de pagos pendientes y realizados
•Estadísticas de compras
•Control de fechas de recepción de pedidos
•Predefinir pedidos periódicos
•Propuestas de pedidos
•Control de las devoluciones de compras
En este módulo, el proceso básico consiste en comprar productos a los
proveedores para luego venderlos a clientes. Una vez dados de alta
todos los productos que se tendrán en nuestro catálogo, se va a aprender
cómo realizar pedidos a proveedores para que envíen los productos y
así  tenerlos  en  stock.  Esta  funcionalidad  es  implementada  por  el
módulo Compra. En función de las necesidades, existen dos opciones:
•Solicitar  un  presupuesto  de  compra  para  convertirlo
posteriormente en un pedido
•Crear un pedido de compra directamente
El  flujo  de  una  operación  de  compra  se  representa  en  la  figura
siguiente:
En  Compra/Pedidos/Pedidos de compra  podemos crear la orden de compra en la que establecemos el
proveedor y los productos a solicitar. En cada línea de producto se nos pedirá tanto su nombre como la
cantidad y precio de venta, repitiendo la misma operación para cada producto comprado.
Una vez finalizado el albarán, se puede Enviar por correo electrónico, Imprimir una SdP (Solicitud de
Presupuesto) o Confirmar pedido. El único paso que es imprescindible que sea realizado, es este último,
dando entonces la posibilidad de Recibir productos, Enviar PC (Pedido de Compra) por correo electrónico o
de Crear factura. Con la primera opción se gestiona la recepción del pedido, la cual una vez validada,
actualizará el stock actual con las nuevas existencias (por ejemplo, consultándolo en Productos).
Siguiendo el ciclo de compra, se utiliza la última opción para crear la factura con las cantidades compradas
finalmente.
En el ejemplo que se puede ver en la figura, se han entregado menos unidades de la referencia LG… de las
inicialmente pedidas; esto provocará una entrega parcial de la que nos avisará el sistema. Una vez guardada,
se publica la factura, lo que ahora nos permitirá registrar el pago. La gestión de facturas puede realizarse
desde Facturación / Contabilidad > Proveedores > Facturas .
Unidad 3: Organización de la información

---

<a id="14-ventas"></a>

## 1.4 Ventas

[⬅ Volver al índice](#índice)

Cuando un cliente quiere comprar algo, es preciso hacer un orden de venta con los productos deseados. A
continuación, se creará un albarán de salida para la entrega y la factura correspondiente. Como se puede ver,
una orden de venta (al igual que una de compra), pasa por diferentes estados. Es importante que llegar hasta
el final del proceso de una venta, es decir, la generación de la factura para el cliente.
Se crea un nuevo pedido de venta en el menú Ventas / Pedidos / Pedidos y da de alta un nuevo Pedido de
ventas. Similar al pedido de compras, se establecen los datos del cliente que realiza el pedido, añadiendo
tantos productos como se deseen.
Una  vez  creado,  es  cuando  se  puede  crear  la  factura  correspondiente,  además  de  enviar  por  correo
electrónico. El sistema da tres posibilidades de factura. En este caso, se crea una Factura regular.
Se hace clic sobre  Crear y ver factura  creándose un borrador que se puede validar. Antes de realizar el
pago, lo que habría es que registrar la entrega pendiente. En la parte superior derecha del pedido de compra,
aparece la entrega pendiente, además de la factura y de otro botón donde previsualizar al cliente objetivo.
En esta parte, lo que se configura es un albarán de entrega que se podrá editar y finalmente validar.
En la edición del albarán hay que reflejar los productos realmente entregados en la columna Hecho. Una vez
cumplimentado, se guarda y valida la entrega. El siguiente paso es pagar la factura. Estos dos pasos se deben
realizar ya que la entrega actualiza el inventario mientras que el pago de la factura gestiona la contabilidad
de la empresa.
Unidad 3: Organización de la información

---

<a id="15-devoluciones"></a>

## 1.5 Devoluciones

[⬅ Volver al índice](#índice)

En las empresas sucede a menudo que de una compra o venta surja una devolución. En el primer caso, puede
ser que un producto haya venido defectuoso del proveedor, o en el caso de la venta a un cliente, puede ser
que este no esté satisfecho y lo quiera devolver (siempre dentro del plazo marcado por ley).
Es importante destacar que, en el caso de una venta, se dan hasta tres casos diferentes:
•La factura está en borrador. Se puede eliminar simplemente acudiendo a la opción de suprimir.
•El cliente no ha pagado todavía la factura. El procedimiento es similar a la factura pagada, es decir,
es preciso crear una factura rectificativa.
•El cliente ya ha pagado la factura: En este caso debemos gestionar una devolución en la que se
creará una factura con importe negativo, indicando que ese dinero ha entrado de nuevo en la
empresa. Así mismo, se debería también de gestionar una entrada en el stock ya que el producto
devuelto volvería a entrar en nuestro almacén.
Se verá el último supuesto por ser el que más miga tiene. Principalmente, lo que hay que hacer es rectificar
una factura, la cual se debe buscar en Facturación / Contabilidad > Clientes > Facturas .
Una vez seleccionada, hay que Agregar una factura rectificativa que incluya la devolución del importe,
realizando a continuación un proceso de aprobación, pago y validación como si fuera una factura normal.
Una vez que se pulsa Invertir, el sistema da un borrador que se puede editar. Una vez terminado, se publica
dicha factura y ya se puede registrar el pago (en este caso, devolución). Lo último que hay que hacer es
acudir a la sección de entregas del pedido de venta y realizar una devolución para que se refleje en el stock.
Si la factura está pagada, se puede registrar también el pago de la devolución si se ha realizado.
Los ítems añadidos en el detalle de la factura rectificativa son los que se devolverían. Por lo tanto, si se
quiere rectificar la totalidad de la factura, se deben indicar en la rectificativa los mismos productos que en la
factura original. Si solo se quiere devolver uno de los productos o menos unidades, simplemente hay que
indicar aquellos en la factura rectificativa.
La gestión de devolución de pedidos de compras es algo más compleja. Si se ha optado por retrasar la
confirmación del albarán hasta la llegada de los productos, el proceso es más sencillo: cancelar el albarán de
entrada y eliminar la factura. De esta forma, simplemente quedaría cancelar el pedido de compra.
Pero si tanto albarán como factura estaban confirmados, el procedimiento es similar al siguiente:
1.Buscar el albarán de entrada en el botón de Recepción y devolverlo. De esta forma, se crea un
albarán de salida que se validará de forma normal.
2.Crear la factura rectificativa como se hizo en la parte de ventas.
Unidad 3: Organización de la información

---

<a id="16-informes"></a>

## 1.6 Informes

[⬅ Volver al índice](#índice)

Uno de los puntos fuertes de un ERP es la elaboración de informes, imprescindible en todos sus módulos.
Para obtener un informe concreto, hay que acudir a la sección correspondiente (Compras o Ventas) y buscar
el elemento de menú Informes.
En ambos casos existen las siguientes posibilidades:
1.Obtener el informe por una serie de Medidas (Total, Total libre de impuestos, Cantidad enviada, etc.)
2.Utilizar Filtros. En el caso del informe de ventas, por Presupuestos y/o Pedidos de venta.
3.Agrupar por una serie de campos: Cliente, Comercial, País, etc.
4.Definir un Período de tiempo y compararlo con un período previo
5.Guardar la búsqueda actual en Favoritos
6.Mostrar vista gráfica (la que aparece por defecto) o la información en texto. En el primer caso,
tenemos una serie de gráficos disponibles (barras, quesitos, etc.)
Se pueden realizar análisis más completos exportando los datos a un fichero de Excel (xls) siempre que se
esté en modo texto con el botón
Unidad 3: Organización de la información

---

<a id="2-gestión-de-almacén"></a>

## 2 Gestión de almacén

[⬅ Volver al índice](#índice)

La gestión del almacén (stock de productos) está basada en dos principios: el concepto de ubicación y el de
almacén,  estando  ambos  relacionados.  Un  almacén  es  una  localización  física  de  elementos  de  stock,
dividiéndose cada uno de ellos en ubicaciones (secciones) diferentes.
De esta forma, un almacén estará formado al menos por una ubicación. Los elementos se desplazan entre
ubicaciones diferentes dejando constancia de ello en el sistema a través de los albaranes. Existen tres tipos de
albaranes: entrada, salida e internos. Los dos primeros ya se vieron en el apartado anterior, mientras que los
últimos se usan para realizar movimientos entre almacenes o ubicaciones propias de la compañía.
Para realizar todas las configuraciones posibles de almacén, se definen tres tipos de ubicaciones diferentes.
Las físicas, las cuales representan la estructura física de un almacén, de socios, las cuales se usan para
conciliar los stocks que se venden y compran en contabilidad, y las virtuales, usadas durante la producción
en el desplazamiento de una entrada en otra (adición de elementos) de forma que la cuenta total del stock
entre almacenes y ubicaciones sea cero.
Este sistema facilita la gestión y control de errores. Además, el sistema implementa la gestión mediante dos
valores de stock de un producto, como vimos en apartados anteriores: el valor real y el previsto. El real es la
cantidad existente del producto en ese momento mientras que el previsto se calcula aumentando al real los
que esperamos recibir y restando los que vamos a distribuir.
Antes de continuar asentando conceptos sobre esta gestión, lo primero que hay que hacer es modificar la
configuración del sistema para que permita la utilización de más de un almacén. Para ello, se debe ir a la
configuración general en Ajustes / Inventario y dentro del apartado Almacén, activar la opción Ubicaciones
de almacenamiento.
Una ubicación es una parte de la estructura jerárquica que representa la sección de un almacén. En Odoo se
pueden encontrar los siguientes tipos de ubicación:
•Ver. Ubicación  organizativa  que  puede  contener  otras  ubicaciones.  Solo  se  usa  para  tareas
organizativas, no podrá contener stock.
•Clientes  y  proveedores .  Ubicaciones  virtuales  que  representan  respectivamente  la  salida  de
productos y entrada de material. Se necesitan ya que en ellas se anotan los movimientos finales e
iniciales del abastecimiento.
•Interna. Gestión del stock propio.
•Pérdida de inventario . Se usa para la gestión de las correcciones manuales del inventario. Si
hacemos cambios de inventario sin albaranes, por ejemplo, desde la ficha del producto, se utilizará
esta ubicación para la gestión.
•Producción. Usado en la gestión del material básico que forma un producto y la producción de este.
•Tránsito. Utilizada en multinacionales para movimientos entre distintas sedes.
Un almacén se utiliza para agrupar varias ubicaciones y gestionarlas de forma conjunta. De esta forma, un
almacén constará de una ubicación de entrada (desde donde vienen las mercancías), una de salida (donde se
desplazarán los elementos al moverlos) y la de stock desde donde se venderán los productos.
Para operaciones sencillas, es posible ayudarse de órdenes de abastecimiento automáticas que se lanzan
cuando se cumplen unas reglas establecidas sobre los productos (reglas de stock mínimas). En esencia, se
determina para cada producto y ubicación diferente el nivel mínimo y el máximo que debe existir, de forma
que el sistema crea los presupuestos correspondientes de compra cuando la regla se rompe. Para ello, hay que
acceder a Inventario / Datos principales / Reglas de abastecimiento .
Para comprobar la regla se evalúa el inventario previsto, no el real. Para que funcione correctamente, es
preciso rellenar los datos del proveedor de cada producto. Una vez la regla se cumple, se lanza una
excepción de abastecimiento que es posible gestionar junto con el presupuesto de compra. Cuando está
activada, el sistema pregunta si se quiere ejecutar el planificador manualmente para que se active la regla. Se
puede probar la regla realizando una venta que deje el stock por debajo del mínimo establecido y observar
que se crea la correspondiente solicitud de presupuesto.
Ejemplo de gestión de almacén
Se parte de que la empresa decide abrir una nueva tienda en otro lugar de la provincia. Para mejorar la
gestión, creará dos almacenes físicos, uno en cada tienda. Por otra parte, tendrá uno global que repartirá a
dichas tiendas. Los productos se recogerán siempre en el almacén global y cuando las tiendas los necesiten,
estas solicitarán desplazarlos a su almacén. Las ventas se realizarán siempre desde los almacenes de las
tiendas.
Se van a ver los pasos a seguir para resolver este supuesto. Cabe señalar que el sistema funciona de tal
manera que al crear un almacén se generan a su vez dos ubicaciones, padre e hija. Por tanto, se comienza
creando  uno  de  los  almacenes  correspondiente  a  la  primera  tienda  yendo  a
Inventario/Configuración/Almacenes. Al acceder aparece una lista de los almacenes creados por defecto en
el sistema Odoo.
Haciendo clic en Crear se muestra una ventana donde poder configurar el almacén con datos como:
•Nombre del almacén: por ejemplo, Almacén principal.
•Nombre corto: es una abreviatura del nombre. Podría llamarse ALM0.
•Dirección: la dirección de la tienda, en este caso coincide con la de la empresa. Se puede poner
cualquier dirección.
Cuando se acaba, se guarda el almacén y puede verse que se crean dos ubicaciones, una Interna y otra de Ver.
Para ello, se va a Inventario / Configuración / Ubicaciones eliminando el filtro de búsqueda.
Automáticamente, el sistema genera una ubicación hija interna de Stock que tendrá como ubicación padre
ALM0. Con la misma operativa, se crean las dos tiendas con nombres cortos ALM1 y ALM2.
Si se va ahora a Inventario / Configuración / Tipos de operaciones,  se puede ver un listado formado por
varios grupos con las actividades asociadas a cada almacén de la empresa. Nos permiten llevar un control de
los movimientos referentes a:
•Recepciones de productos en los almacenes de las tiendas de la empresa.
•Entregas de productos (Albaranes de salida) desde los mismos almacenes.
•Movimientos internos de productos (Transferencias internas) dentro de los propios almacenes o de
uno a otro.
•Fabricación
Agrupando por tipo de operación se puede ver de forma más clara cada tipo de movimiento.
Las operaciones al completo pueden verse en Inventario / Operaciones / Transferencias . La vista Kanban
para esto es mucho más visual, tal como puede verse en la figura.
Si ahora se realiza un pedido de compra, se podrá seleccionar a qué almacén se quiere que sea
entregado una vez registrada la entrada. En este caso se hará al almacén principal para luego
repartirlo por las tiendas correspondientes:
Si se necesita stock en una tienda, habrá que hacer un albarán interno de entrega ( Transferencia Interna )
desde el almacén general donde se indicarán ubicaciones origen y destino y la cantidad requerida. Este
albarán se trata como uno más procesándolo y validándolo igualmente. Para ello, se acude a Inventario /
Operaciones  /  Transferencias  y  se  crea  una  Transferencia  interna  que  quedará  identificada  como  tal
indicando el almacén del que parte.
Una vez creada, hay que elegir la opción Marcar “Por realizar”, posteriormente Comprobar disponibilidad y,
por último, Validar la transferencia interna. En este caso, mostrará un mensaje indicando que procesará todas
las cantidades reservadas.
Informes
El seguimiento del stock es muy importante para el buen funcionamiento de la empresa y sobre todo para
aumentar significativamente la satisfacción del usuario. Comprobar el estado de albaranes, excepciones de
abastecimiento,  peticiones  de  compra,  etc.  es  un  trabajo  diario  que  el  sistema  nos  facilita  mediante
herramientas de gestión y análisis. En la pestaña de  Informes dentro de Inventario, existen una serie de
opciones interesantes para estos propósitos. Por ejemplo, el reporte de inventario da un resumen de productos
y sus ubicaciones. Para verlo mejor, es preferible utilizar la vista Kanban tal como se muestra en la figura:
Al igual que en otros tipos de informe, se puede filtrar, agrupar y delimitar qué información se necesita. El
informe de Inventario previsto muestra con distintos tipos de gráfico el stock previsto vs. el real.
En la  Valoración de inventario  se ve una lista que recoge todos los productos junto con su valoración
mediante el precio. Dispone de filtros para buscar stocks de productos según intereses.
Por último, la vista de Movimientos por producto muestra los movimientos que se han producido para cada
uno de los productos:
Unidad 3: Organización de la información

---

<a id="3-gestión-de-contabilidad"></a>

## 3 Gestión de contabilidad

[⬅ Volver al índice](#índice)

La contabilidad en Odoo está totalmente integrada con los sistemas de compras y ventas, lo que permite a la
información fluir en tiempo real. En el momento en que se crea un pedido con su factura, se dan de alta los
asientos contables necesarios quedando reflejado de forma automática en el sistema contable.
El  módulo  de  Contabilidad  se  abastece  de  dos  fuentes  para  su  funcionamiento:  La  primera  es  la
configuración de ejercicios y períodos, diarios, el plan contable, impuestos y sus plazos y tipos de pago. La
segunda es la actividad diaria del sistema que genera automáticamente información y  la introducida a mano
por el contable. Con todo ello se produce el resultado necesario para gestionar correctamente la contabilidad
empresarial, pudiendo conciliar lecturas, ver balances, crear informes internos e informes oficiales, etc.
En este apartado no se planteará un supuesto concreto, sino que se realizarán las tareas cotidianas de
contabilidad asociadas a una pequeña empresa, aprendiendo los procedimientos básicos que un contable
suele utilizar, familiarizándose con ellos y con su flujo de trabajo para poder realizar una labor eficiente en la
configuración y administración del sistema. A continuación, se ve la configuración del sistema en lo referido
a los aspectos contables.

---

<a id="31-diarios"></a>

## 3.1 Diarios

[⬅ Volver al índice](#índice)

Un diario es un libro contable en el que se registran los asientos (sucesos contables) que se producen en el
funcionamiento diario de la empresa. La configuración de los diarios y el número de ellos depende mucho
del departamento contable, siendo lo normal tener un único libro por empresa.
Odoo. Se recomienda crear un diario diferente para cada tipo de operación y como mínimo tres: uno para
compras, otro para ventas y otro para efectivo.
Así, por defecto, existen los siguientes tipos de diarios:
•Ventas: Registro de las ventas y facturas de los clientes
•Compra: Registro de las compras y facturas de un proveedor
•Efectivo: También llamado de caja, diarios con los que se gestiona el pago de dinero en metálico o
con tarjeta
•Banco: Gestión de cuentas bancarias y cheques
•Varios: Cualquier otro no incluido en los anteriores tales como nóminas, liquidaciones de impuestos,
movimientos de capital, correcciones, etc.
Para acceder a los diarios, hay que ir a Facturación / Contabilidad > Configuración > Diarios:
En  ese  apartado  se  ven  aquellos  que  ha  creado  el  sistema  por  defecto.  Si  se  decide  crear  un  diario
personalizado, es obligatorio darle un nombre y por supuesto, un tipo. También configurar los asientos
contables con un código y su mecanismo de numeración ( Próximo número). En la  configuración avanzada,
se pueden controlar qué cuentas contables pueden acceder al diario en el apartado Control de acceso, de
forma que exista un nivel extra de seguridad.
Unidad 3: Organización de la información

---

<a id="32-impuestos"></a>

## 3.2 Impuestos

[⬅ Volver al índice](#índice)

Por norma general, al instalar el software se configurarán correctamente los impuestos necesarios para su
gestión. En algún caso podríamos tener que modificarlos por cambios en la legislación.
A la gestión de impuestos se accede desde Facturación / Contabilidad > Configuración > Impuestos.
En la creación de un impuesto son imprescindibles el nombre y cuándo va a aplicarse, junto con el ámbito,
tipo de cálculo y el importe a aplicar.
Unidad 3: Organización de la información

---

<a id="33-mecanismos-de-pago"></a>

## 3.3 Mecanismos de pago

[⬅ Volver al índice](#índice)

En  esta  categoría  se  incluyen  las  distintas  configuraciones  de  plazos  de  pago.  Se  accede  mediante
Facturación / Contabilidad > Configuración > Plazos de pago. Este apartado determina el tiempo (o plazos)
en los que una factura será abonada o cobrada. Se puede configurar cualquier medio  temporal deseado, pero
generalmente incluye suficientes por defecto.
Otro  apartado  interesante  son  los  Métodos  de  Pago,  a  los  que  se  accede  mediante  Facturación  /
Contabilidad > Configuración > Métodos de pago . En él se encuentran las distintas formas de hacer frente
a un pago, teniendo desde lo más básico (transferencia bancaria) hasta otros más sofisticados como Paypal o
Adeudo directo SEPA.
En este apartado se ven grupos creados para Clientes y Proveedores donde se pueden gestionar buena parte
de lo visto en sus apartados correspondientes dentro de Compra / Venta (Facturas, recepciones, albaranes,
pagos, productos, etc.).
Unidad 3: Organización de la información

---

<a id="4-gestión-de-recursos-humanos"></a>

## 4 Gestión de recursos humanos

[⬅ Volver al índice](#índice)

En la figura puede verse el flujo de trabajo en la gestión de Recursos Humanos:
La gestión de RRHH abarca la creación, modificación y mantenimiento de los empleados y sus contratos,
control de asistencia al trabajo, organización de ausencias (vacaciones y otras faltas), gestión de nóminas y
obtención de informes entre otras tareas.
La  configuración  del  sistema  la  realiza  el  equipo  contable  antes  de  empezar  a  implantar  la  solución,
integrando los datos de la plantilla actual con la estructura de categorías y puestos planteados. Primeramente,
se  configuran  los  datos  de  asistencia  y  a  continuación  la  estructura  de  la  empresa.  Los  módulos  que
inicialmente necesitaremos para la gestión de recursos humanos, los podemos encontrar haciendo un filtrado
en las aplicaciones con el criterio Empleados. Inicialmente se introducirá el módulo de Empleados.
Algunas de las operaciones interesantes que se pueden configurar para la gestión de Recursos Humanos son
los departamentos de la compañía. Hay que acudir entonces a la opción  Empleados / Configuración /
Departamentos. Interesa reflejar fielmente la estructura actual de la empresa previendo el desarrollo futuro.
El sistema, por defecto, muestra dos: Administración (Administration) y Ventas (Sales). Se parte de que se
quiere crear uno nuevo, en este caso, de compras.
Como datos, tal como se ve en la siguiente figura, pide el nombre, un departamento padre (para poder
realizar una jerarquía) y el responsable:

---

<a id="41-gestión-de-empleados-y-contratos"></a>

## 4.1 Gestión de empleados y contratos

[⬅ Volver al índice](#índice)

Para realizar una buena gestión de empleados, habría que crear un usuario de sistema para cada uno de ellos,
de forma que pueda acceder al sistema con unos permisos concretos. De esta forma, se puede gestionar la
entrada y salida del personal junto con otros aspectos como sus ausencias o vacaciones. La gestión de
usuarios se realiza en Ajustes / Usuarios y compañías.
Ahora ya es posible crear un empleado en la sección Empleado.
Es imprescindible el nombre completo y el nombre de usuario (en Configuración RRHH), aunque muy
recomendable registrar el resto de información: mínimo el NIF y datos de contacto.
La contratación de empleados se gestiona mediante un módulo llamado Contrato de los empleados:
Una vez instalado, para acceder a los contratos de cada empleado, se acude a Empleados /Empleados /
Contratos. En la creación de un contrato, aparece un interfaz similar al de la figura:
En este interfaz existe la posibilidad de registrar el Salario donde se introduce la retribución mensual bruta.
Por supuesto, también se guardan las fechas de inicio y final junto con la del final del período de prueba en
caso de que lo hubiera.
Unidad 3: Organización de la información

---

<a id="42-gestión-de-la-asistencia"></a>

## 4.2 Gestión de la asistencia

[⬅ Volver al índice](#índice)

El mecanismo para controlar la asistencia de los empleados en la mayor parte de las empresas es la
justificación mediante el fichaje, en el que el empleado es responsable de comunicar al sistema su presencia
o ausencia en el puesto de trabajo. Para gestionar esta funcionalidad, hay que instalar el  módulo de
Asistencia.
El empleado registra su entrada y salida, por lo que tendrá que poder acceder a un terminal y a su usuario
asignado. Una vez llegado al centro, se desplazará al terminal introduciendo usuario y clave y fichará con la
opción Asistencias / Entrada / Salida, mostrando la siguiente vista:
Pulsando en el punto rojo se registra la entrada.
El botón rojo se convierte en verde que se pude desconectar.
En este mismo apartado se registra la salida. Con cada evento, el sistema registra un servicio que se utilizará
para contabilizar la estancia. Si el usuario es responsable de una serie de empleados, va a poder consultar sus
entradas y salidas en Asistencias / Responsable / Asistencias.
En la sección Informes, el empleado puede realizar un seguimiento de sus asistencias al puesto de trabajo.
En la asistencia aparece implícita la ausencia del trabajador. La gestión de ausencias tiene su módulo propio
con el mismo nombre:
En caso de falta justificada: Médico, visita a un cliente, etc., se debe crear una petición de ausencia, lo que se
realiza en Ausencias / Solicitud  de nueva ausencia.
Una vez creada, el responsable es el que tiene que aprobar o rechazar la ausencia. Como en estos supuestos
el usuario es administrador, dicha validación no es requerida. Las vacaciones se realizan de forma similar,
pero se acceden desde el apartado Solicitud de Asignación.
Por último, el sistema permite en su Configuración añadir tipos de Ausencia e indicar el modo de operar en
cada caso.
Unidad 3: Organización de la información

---

<a id="5-gestión-de-las-relaciones-con-los-clientes-crm"></a>

## 5 Gestión de las relaciones con los clientes CRM

[⬅ Volver al índice](#índice)

Llegados a este punto, la empresa decide embarcarse en proporcionar nuevos servicios a sus clientes como
soporte telefónico o la gestión de reclamaciones. En la siguiente figura se ve el flujo de operaciones de la
gestión de relaciones con el cliente:
La configuración de los aspectos relacionados con el cliente se puede encontrar principalmente en Ventas /
Clientes además de en otros apartados. Ya se vio cómo dar de alta, editar y eliminar clientes en la gestión de
socios  en  la  sección  correspondiente.  Para  utilizar  el  CRM  de  Odoo,  hay  que  utilizar  su  aplicación
correspondiente:
En la gestión de clientes, en este ejemplo se utiliza principalmente en un flujo como el que aparece en la
figura  que  encabeza  este  apartado.  Lo  que  se  consideramos  una  iniciativa  se  define  por  el  nombre,
actividades y su estado en el ciclo de vida. Para habilitar el poder crear iniciativas, debemos marcar la opción
correspondiente en la Configuración general del CRM en Ajustes / CRM / Iniciativas (o Leads) :
Se ven a continuación aspectos relacionados con la configuración de un CRM
1.El ciclo de vida determina las etapas sucesivas por las que va a pasar la iniciativa. Al entrar en el
apartado  CRM  se  ven  las  cuatro  etapas:  Nuevo,  Calificado,  Propuesta  y  Ganado.  Se  pueden
introducir nuevas etapas con solo pulsar en la opción “Agregar una columna”.
2.Cuando se crea una iniciativa, hay que indicar el motivo principal de la misma. Esta información se
refleja mediante categorías en la opción de menú: CRM / Configuración / Flujo (o Pipeline) /
Categorías (o Etiquetas).
3.También es relevante fijar el mecanismo de comunicación usado entre la empresa y el potencial
cliente. Entre ellos, tenemos las llamadas telefónicas, correos electrónicos, sitio Web, etc. Estos
canales se configuran en CRM / Configuración / Tipos de actividad
Iniciativas
Una iniciativa es una preventa, una posibilidad de venta generada desde el departamento de marketing (o
ventas, en caso de que no exista) que podrá concretarse o no en una venta. La iniciativa pasa exclusivamente
por un conjunto de fases según va avanzando el proceso de la misma. Una vez terminada se podrá convertir
en una oportunidad de venta si se llega a un acuerdo o podrá finalizarse sin haberse concretado nada. En
primer lugar, hay que crear la iniciativa a través de CRM / Iniciativas (Leads).
Para cada iniciativa es imprescindible únicamente el campo con el mismo nombre, en el que se incluirá una
descripción breve del tema que sirva para ordenar y encontrar rápidamente el documento. Además, hay que
establecer un conjunto de datos obligatorios que están presentes por defecto: Prioridad, Equipo de ventas y
Categoría. También se deben cubrir los datos imprescindibles para contactar con el cliente. Si ya está en la
base de datos, se usará el desplegable Cliente, lo que rellenará automáticamente el resto de los campos. En
caso contrario, se establecerá de forma manual la información requerida junto con el contacto.
El documento que se crea a partir de la iniciativa no es estático, sino que va a variar con el tiempo de forma
que reflejará la situación actual con el cliente y las comunicaciones que se han llevado a cabo. A partir de
aquí, se puede en un momento dado dar por perdida la iniciativa (Marcar como perdido) o Convertir en
oportunidad. Este último proceso creará una nueva oportunidad o la unirá a una existente.
Oportunidades
Cuando se crea una oportunidad, se da por sentado que el porcentaje de éxito es elevado y la persona
involucrada está interesada en la compra, por lo que necesita una mayor atención y registro que la iniciativa.
La oportunidad presenta una estimación en ventas, con lo que el primer campo a rellenar (si no se quiere
cambiar el nombre descriptivo), es el Ingreso estimado. Este dato es muy importante, ya que servirá a final
de año para determinar las posibles ganancias no realizadas.
Durante la vida de la oportunidad, habrá que ponerse en contacto con la persona relacionada mediante
distintos mecanismos. En la edición de la oportunidad, se puede Planificar Actividad donde el sistema nos
permite enviar un correo, hacer una llamada, convocar una reunión, subir un documento, establecer una
excepción o marcar una tarea “por hacer”. Por ejemplo, si se quiere convocar una reunión, cambiará de
forma dinámica los datos a registrar y dará la posibilidad de ajustarla en el calendario:
El seguimiento de las oportunidades se ve en el flujo de ventas dentro del apartado propio del CRM:
Desde aquí se podría generar un nuevo presupuesto como inicio de una venta, o marcar simplemente como
ganada la oportunidad. Esto se verá reflejado en el flujo, en la columna correspondiente.
Como cualquier módulo, la creación de informes es imprescindible, y también en las relaciones con los
clientes. En el apartado CRM / Informes se tienen a disposición informes de Iniciativas, Flujo y Actividades.
El funcionamiento es similar al de anteriores módulos.
Unidad 3: Organización de la información

---

<a id="6-utilización-del-tpv"></a>

## 6 Utilización del TPV

[⬅ Volver al índice](#índice)

TPV son las siglas de Terminal de Punto de Venta, la herramienta necesaria para que un empleado pueda
vender cara al público productos a los clientes. El TPV de Odoo es uno de los mejores del mercado y su
apariencia es muy intuitiva y visual.
Es importante destacar que, una vez instalado el punto de venta, este se integra perfectamente con los
productos y categorías que están creadas en la empresa además de con toda la parte de Ventas y contabilidad.
Se puede decir que es otra manera de realizar ventas, pero los efectos en la empresa son los mismos.
Este módulo resulta imprescindible para la gestión del negocio debido a su forma de trabajar. Al fin y al
cabo, la empresa está constituida por varias tiendas y se necesita gestionar sus actividades de venta diaria al
público de forma rápida y sencilla. El Terminal punto de venta cumple las funciones que necesita la empresa
en este sentido:
•En cada tienda se puede acceder al terminal correspondiente para realizar las ventas de cada jornada
de trabajo.
•Utiliza  como  interfaz  cualquier  ordenador  de  sobremesa,  portátil,  tabletas,  móviles  e  incluso
máquina TPV si se dispone de ellas. La empresa cuenta con ordenadores en cada tienda.
•Se puede utilizar a través de un navegador web, conectado en línea con el servidor de Odoo. Aunque
se pierda la conexión a Internet el TPV sigue funcionando y restablece los datos cuando vuelve la
conexión.
•Permite actualizar el nivel de inventario de los productos a tiempo real debido a su integración con el
módulo de Almacenes.
•Las actividades que lleva a cabo generan facturas de ventas y llevan asociado un asiento contable.
•Funciona con distintos métodos de pago: efectivo, tarjeta, etc. Usando el efectivo, simplemente se
introduce la cantidad abonada por el cliente a través de la interfaz (teclado), calcula el cambio y
confirma la venta generando una factura.
•Su manejo resulta sencillo e intuitivo pues los productos disponibles que hay en el almacén aparecen
en la pantalla con su imagen y precio correspondiente, ordenados por categorías. La búsqueda de
cualquiera de ellos es fácil y rápida
En la siguiente figura se puede ver el esquema de funcionamiento del TPV de Odoo:
Esta tarea se va a dividir en varias partes:
•Creación y configuración de los terminales de venta necesarios para la empresa. De momento se crea
uno a mayores del que ya existe por defecto y se configuran los parámetros que contiene.
•Creación de categorías de los productos para clasificarlos según sus características facilitando su
búsqueda en el sistema.
•Explicar el funcionamiento básico del módulo en una de las tiendas, es decir, ver cómo se registran
las ventas a clientes que entran en el establecimiento durante una jornada a través del interfaz TPV .
Para crear un terminal nuevo se acude al apartado Punto de Venta / Configuración / Punto de Venta.  El
botón Crear permite añadir uno nuevo.
El primero que se crea es el correspondiente a la Tienda 1 de la empresa. En la ventana abierta hay que
seleccionar las opciones convenientes para ese terminal y configurar los parámetros según las necesidades
del establecimiento.
Algunos de los datos más interesantes se enumeran a continuación:
•Información general: nombre del terminal, si es un bar/restaurante, ubicación física de la tienda.
•Métodos de pago: son las formas de pago disponibles para los clientes de la Tienda 1. Inicialmente
contamos  con  pago  en  efectivo  y  pago  mediante  banco.  Aquí  podemos  crear  y  editar  nuevos
métodos.
•Características de la interfaz: permite la integración de teclado virtual entre otras opciones.
•Facturas  y  recibos:  Todo  lo  relacionado  con  los  tickets:  encabezado  y  pie,  reimprimir  recibo,
impresión automática, etc.
•Inventario: En este apartado elegimos el tipo de operación donde podemos ajustar la ubicación que
creamos en su momento para las recepciones de Tienda 1
Unidad 3: Organización de la información

---

<a id="7-generación-de-sitio-web-de-empresa"></a>

## 7 Generación de sitio web de empresa

[⬅ Volver al índice](#índice)

Odoo permite realizar muy fácilmente una web para nuestra empresa sin necesidad de programar nada,
solamente arrastrando elementos y editándolos en un entorno WYSIWYG (What you see is what you get).
Esto es muy útil ya que cualquier empresa hoy en día necesita una presencia online y esta herramienta nos
facilita mucho la creación de una página web de estas características. El módulo que necesitamos se llama
Sitio Web, tal como aparece en la figura:
Mediante un asistente va a permitir editar un sitio y añadirle elementos que se muestran en un panel lateral:
En estructura existen elementos tales como banners, portadas, combinaciones de imagen y texto, bloques de
texto, carruseles, características (features) y columnas.
En otro grupo se encuentran características tales como galerías de imágenes, comparativas, equipo de la
compañía, llamadas a acción, referencias, acordeones, cuadrículas de características, pestañas, un generador
de formularios, etc. Algunas de ellas deben ser instaladas ya que no vienen por defecto.
Además, se dispone de efectos y de contenido interno donde encontrar elementos comunes en un diseño
Web: separadores, botones, mensajes de alerta, tarjetas, grupo de botones para compartir, etc.
Como puede verse, la generación del sitio Web de empresa es bastante completa y va a permitir configurar
una ventana al exterior de nuestra empresa, la cual puede resultar clave en nuestra estrategia.
Unidad 3: Organización de la información

---

<a id="8-tienda-online"></a>

## 8 Tienda online

[⬅ Volver al índice](#índice)

Odoo  dispone  de  un  módulo  para  la  creación  de  una  tienda  online.  Esta  tienda  online  se  integra
perfectamente en el sitio web de la empresa y permite vender los productos que tenemos dados de alta en el
ERP en internet.
Este módulo integra las principales plataformas de pago y es una buena manera de aumentar la presencia
online de la empresa.
El módulo para la tienda online se denomina Comercio electrónico, tal como se puede ver en la figura:
El manejo de este módulo se realiza desde el sitio Web el cual muestra un apartado Shop (Tienda)
Otras alternativas para tener una tienda online sería utilizar herramientas externas al ERP como por ejemplo
Magento (https://magento.com/) o Prestashop (https://www.prestashop.com/es). El inconveniente en este
caso es que habría mucho más trabajo a la hora de integrar el ERP con estas soluciones.
Unidad 3: Organización de la información

---

<a id="9-auditoría-y-control"></a>

## 9 Auditoría y control

[⬅ Volver al índice](#índice)

En este apartado se verá cómo consultar y tratar la información a nivel de administración de sistemas.
Cuando la misión de un técnico es administrar un sistema, aquel debe tener herramientas que permitan hacer
un seguimiento de los datos que arroja el equipo servidor donde se encuentran las aplicaciones.

---

<a id="91-postgresql"></a>

## 9.1 PostgreSQL

[⬅ Volver al índice](#índice)

Para una empresa el activo más importante es su información. Desprenderse de ella o inutilizarla implicará
mayores pérdidas que cualquier otro evento. Ante esta situación es imprescindible realizar una buena gestión
de la base de datos, concretamente del servidor PostgreSQL en nuestro caso. Para ello se establece una
política adecuada de copias de seguridad (que ya se vio anteriormente), distribución de datos y control de
acceso entre otras. La implementación de este tipo de medidas implica altos conocimientos de bases de datos
y redes, así como de seguridad informática.
PostgreSQL utiliza varios ficheros de configuración. En el fichero postgresql.conf se establecen los datos de
funcionamiento. Se puede encontrar en /etc/postgresql/XX/main  (donde XX es la versión de PostgreSQL).
Desplazándose por el fichero, se encuentra la sección ERROR REPORTING AND LOGGING , la cual se
encarga de configurar los aspectos relacionados con la creación de ficheros de auditorías. El fichero está muy
estructurado y comentado, estableciendo primero el mecanismo (log_destination) a utilizar en la creación de
los registros de logs, el nombre y directorio a usar para los ficheros, el modo de creación y si los ficheros se
rotarán  por  el  propio  PostgreSQL o  configuraremos  el  Sistema  Operativo.  A continuación,  aparece  la
configuración de la auditoría a través del demonio syslog que veremos posteriormente.
La sección When indica qué tipo de mensajes se van a guardar con respecto al cliente (client_min_messages)
para el sistema en general (log_min_messages), si una sentencia falla (log_min_error_statement) y cuando la
duración en la ejecución de una sentencia sea muy alta (log_min_duration_statment), la cual está expresada
en milisegundos. Determinamos posteriormente los eventos de la base de datos que queremos guardar y
formalizamos el formato de sentencia a escribir (log_line_prefix). A continuación, se puede ver un ejemplo
de este apartado:
La  siguiente  sección  STATISTICS  configura  estadísticas  de  uso  sobre  el  sistema  para  determinar  el
rendimiento. Las estadísticas que se pueden generar implican al sistema de consultas e indexado por una
parte (Query/Index Statistics Collector) y al sistema de auditoría (Statistics Monitoring)  por otra. Un
ejemplo:
Unidad 3: Organización de la información

---

<a id="92-servidor"></a>

## 9.2 Servidor

[⬅ Volver al índice](#índice)

El rendimiento del servidor puede disminuir o ser inexistente debido a diversos motivos. Para investigar qué
ocurre en cada caso, es necesario buscar información en los ficheros de registro o mensajes del sistema
llamados logs, o ejecutar herramientas que permitan realizar un análisis y monitorización del rendimiento.
Se  pueden  obtener  datos  instantáneos  del  rendimiento  del  sistema  relativo  al  funcionamiento  de  los
procesadores, de la memoria, de los dispositivos de entrada y salida, etc., pero también recoger datos
periódicamente  y  almacenarlos  en  ficheros  históricos  para  consultarlos  posteriormente.  Estos  datos
proporcionan información muy importante sobre las posibles carencias y cuellos de botella del sistema.
Existen diversas utilidades para recopilar y hacer un histórico del rendimiento y la actividad de los datos.
Estas utilidades recopilan la información del sistema, la almacenan por un periodo de tiempo y calculan los
valores medios. En cualquier momento se pueden tomar lecturas de los parámetros del servidor que se
determinen, para la resolución de problemas o bien simplemente para consultar el estado del servidor.
Entre las herramientas de monitorización y evaluación del rendimiento disponibles para un servidor Linux se
encuentra la herramienta sar, incluida en el paquete sysstat.
sysstat suele venir instalado por defecto, pero en caso de no ser así, se utilizaría la siguiente orden en
Ubuntu:
sudo apt-get install sysstat
De todas maneras, es preciso hacer una serie de ajustes para poder utilizar todas las funcionalidades de esta
utilidad activando la recopilación de datos.
Primeramente, hay que editar /etc/default/sysstat (con nano, por ejemplo) y cambiar ENABLED=”false”
por ENABLED=”true”:
Para que dicha recopilación tenga un intervalo de tiempo más corto, ahora hay que que cambiar el archivo
/etc/cron.d/sysstat y modificar la línea:
5-55/10 * * * * root command -v debian-sa1 > /dev/null && debian-sa1 1 1
por
*/2 * * * * root command -v debian-sa1 > /dev/null && debian-sa1 1 1
Por último, reiniciar el servicio:
sudo /etc/init.d/sysstat restart
A partir de ahí el script /usr/lib/sysstat/sa1, que se ejecuta por defecto cada 2 minutos empezará a
recoger datos de rendimiento (procesador, memoria, disco, red, etc) que se guardarán en el fichero de sistema
/var/log/sysstat/saXX , donde XX indica el día del mes actual. Por defecto, se guardan los datos de la última
semana.
Con esto ya se pueden ver datos instantáneos, tan sólo hay que tener en cuenta que todos los comandos de la
herramienta aceptan como parámetros el número de valores que queremos obtener (intervalo) y cada cuánto
tiempo queremos que los capture (segundos).
Por ejemplo, para obtener información de 3 valores sobre el uso del procesador, cada segundo, se utiliza la
siguiente orden:
sar 1 3
Y el resultado:
Los parámetros "1 3" indican que sar se ejecutará cada segundo un total de 3 veces, los valores de ejecución
se muestran en filas separadas, y la última fila es la media aritmética de todos los valores.
Para conocer la lista completa de los parámetros que se pueden utilizar con sar, es posible consultar la ayuda
del comando (man sar). Algunos ejemplos son los siguientes:
Procesador: sar -P ALL 1 3
Memoria: sar -r 1 3
Interfaces de red: sar -n DEV 1 3
Discos: sar -d 1 3
La actividad de los programas, sobre todo si se trata de programas que se ejecutan en servidores, queda
registrada en ficheros del sistema llamados logs. En ocasiones, puede quererse examinar los ficheros de
trazas del sistema para realizar un control de acceso a los datos, ya que estos ficheros de trazas van
almacenando toda la actividad y eventos que ocurren en el equipo: quién entra, qué comandos ejecuta, qué
errores muestran las aplicaciones, etc.
En la mayoría de las distribuciones Linux, estos ficheros se guardan en el directorio /var/log. Para visualizar
su contenido se necesitan permisos de root o pertenecer a un grupo de usuarios con permisos para ver esos
ficheros. En este directorio por ejemplo se guarda el fichero syslog, que guarda mensajes de trazas de
demonios y otros programas como cron, init, dhclient, y algunos mensajes relacionados con el núcleo del
sistema operativo.
Además del control de acceso a los datos, lo interesante del registro de trazas del sistema es consultar la
información posteriormente para resolver posibles problemas, ya que generalmente si una aplicación no
funciona, o no puede inicializarse, lo que hace es imprimir una traza de error, que puede poner sobre aviso de
lo que está ocurriendo.
Dentro del directorio /var/log se pueden encontrar las trazas del sistema de una aplicación en Ubuntu.
Por ejemplo, querer visualizar la actividad del servidor de Odoo con el siguiente comando:
sudo cat /var/log/odoo/odoo-server.log
El resultado de la instrucción puede ser algo como:
Cualquier incidencia quedará reflejada en estos archivos, y será misión del técnico identificar la causa y una
posible solución.
En cualquier caso, en ocasiones se producen errores en las bases de datos con las que se trabaja volviendo a
la aplicación inoperativa mostrando el fatídico “Internal server error”. Si la base de datos con la que se
trabaja ya está respaldada con una versión estable, una solución puede pasar por eliminarla de PostgreSQL ya
que gran parte de esos errores vienen derivados del gestor de base de datos. Es posible apoyarse del propio
pgAdmin tal como se vio en apartados anteriores o ejecutar el comando DROP DATABASE  accediendo por
consola con psql. Es posible que no deje eliminar la base de datos si la está usando Odoo. Bien, en este caso,
es preciso parar el servicio Odoo (por ejemplo, con sudo systemctl stop odoo ), eliminar la base de datos y
volverlo a arrancar (con sudo systemctl start odoo ). Una vez eliminada la base de datos corrupta, se podría
volver a arrancar el interfaz gráfico de Odoo e intentar restaurar una versión estable.
Bibliografía y Webgrafía
San Juan Pastor, C. (2013).
García Lazo, J.J. (2021).
https://www.odoo.com/documentation/18.0/es/  Documentación de Odoo en canales oficiales

---
