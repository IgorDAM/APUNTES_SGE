# Unidad 4 - Implantación de sistemas ERP_CRM-24-25

## Índice

- 1 Introducción. Tipos de empresa y sus necesidades
- 2 Ciclo de vida del sistema ERP
	- 2.1 Adopción
	- 2.2 Selección
	- 2.3 Implantación
	- 2.4 Puesta en marcha
- 3 Adaptación del sistema ERP a una empresa
- 4 Operativa del sistema ERP
	- 4.1 Modelo de Objetos
	- 4.2 Control de acceso: Grupos, Usuarios y Permisos
	- 4.3 Modificación de los Menús
	- 4.4 Creación y Modificación de Objetos del Sistema. Vistas
		- 4.4.1 Gestión de vistas
		- 4.4.2 Creación de un nuevo campo en un objeto existente y modificación de sus vistas
		- 4.4.3 Creación de un nuevo objeto y sus vistas asociadas
		- 4.4.4 Creación de relaciones entre objetos
	- 4.5 Gestión de Tableros
	- 4.6 Informes Personalizados
	- 4.7 Herencia de Vistas
	- 4.8 Creación de Manuales

[⬅ Volver al índice](#índice)

<a id="1-introducción-tipos-de-empresa-y-sus-necesidades--3"></a>

## 1 Introducción. Tipos de empresa y sus necesidades ...................................................................... 3

[⬅ Volver al índice](#índice)



---

<a id="2-ciclo-de-vida-del-sistema-erp--4"></a>

## 2 Ciclo de vida del sistema ERP ..................................................................................................... 4

[⬅ Volver al índice](#índice)



---

<a id="21-adopción-4"></a>

## 2.1 Adopción.............................................................................................................................. 4

[⬅ Volver al índice](#índice)



---

<a id="22-selección-5"></a>

## 2.2 Selección.............................................................................................................................. 5

[⬅ Volver al índice](#índice)



---

<a id="23-implantación-6"></a>

## 2.3 Implantación......................................................................................................................... 6

[⬅ Volver al índice](#índice)



---

<a id="24-puesta-en-marcha--10"></a>

## 2.4 Puesta en marcha ................................................................................................................ 10

[⬅ Volver al índice](#índice)



---

<a id="3-adaptación-del-sistema-erp-a-una-empresa--11"></a>

## 3 Adaptación del sistema ERP a una empresa .............................................................................. 11

[⬅ Volver al índice](#índice)



---

<a id="4-operativa-del-sistema-erp--12"></a>

## 4 Operativa del sistema ERP ........................................................................................................ 12

[⬅ Volver al índice](#índice)



---

<a id="41-modelo-de-objetos--12"></a>

## 4.1 Modelo de Objetos ............................................................................................................. 12

[⬅ Volver al índice](#índice)



---

<a id="42-control-de-acceso-grupos-usuarios-y-permisos--12"></a>

## 4.2 Control de acceso: Grupos, Usuarios y Permisos .............................................................. 12

[⬅ Volver al índice](#índice)



---

<a id="43-modificación-de-los-menús--19"></a>

## 4.3 Modificación de los Menús ................................................................................................ 19

[⬅ Volver al índice](#índice)



---

<a id="44-creación-y-modificación-de-objetos-del-sistema-vistas--22"></a>

## 4.4 Creación y Modificación de Objetos del Sistema. Vistas .................................................. 22

[⬅ Volver al índice](#índice)



---

<a id="441-gestión-de-vistas--22"></a>

## 4.4.1 Gestión de vistas ......................................................................................................... 22

[⬅ Volver al índice](#índice)



---

<a id="442-creación-de-un-nuevo-campo-en-un-objeto-existente-y-modificación-de-sus-vistas"></a>

## 4.4.2 Creación de un nuevo campo en un objeto existente y modificación de sus vistas

[⬅ Volver al índice](#índice)

asociadas............................................................................................................................... 29

---

<a id="443-creación-de-un-nuevo-objeto-y-sus-vistas-asociadas--33"></a>

## 4.4.3 Creación de un nuevo objeto y sus vistas asociadas .................................................. 33

[⬅ Volver al índice](#índice)



---

<a id="444-creación-de-relaciones-entre-objetos--39"></a>

## 4.4.4 Creación de relaciones entre objetos .......................................................................... 39

[⬅ Volver al índice](#índice)



---

<a id="45-gestión-de-tableros--43"></a>

## 4.5 Gestión de Tableros ............................................................................................................ 43

[⬅ Volver al índice](#índice)



---

<a id="46-informes-personalizados--45"></a>

## 4.6 Informes Personalizados .................................................................................................... 45

[⬅ Volver al índice](#índice)



---

<a id="47-herencia-de-vistas--53"></a>

## 4.7 Herencia de Vistas .............................................................................................................. 53

[⬅ Volver al índice](#índice)



---

<a id="48-creación-de-manuales--55"></a>

## 4.8 Creación de Manuales ........................................................................................................ 55

[⬅ Volver al índice](#índice)

Bibliografía y Webgrafía .................................................................................................................. 56
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="1-introducción-tipos-de-empresa-y-sus-necesidades"></a>

## 1 Introducción. Tipos de empresa y sus necesidades

[⬅ Volver al índice](#índice)

En la actualidad, y como ya hemos visto en unidades anteriores, se puede encontrar una amplia oferta de
software de planificación de recursos empresariales. Podemos diferenciarlos unos de otros por el tipo de
licencia con el que se distribuyen, los módulos que incorporan, los sistemas bajo los que trabajan, etc...
Se nos plantea, por tanto, una cuestión: ¿Cuál elegir de entre todos ellos?
La respuesta a esta pregunta determinará el éxito o el fracaso de la implantación del ERP. Para que sea un
éxito, es conveniente realizar un ejercicio de autoevaluación de procesos. En otras palabras, un estudio de las
necesidades y motivos para adquirir un ERP. Esto, que parece muy sencillo, en la práctica es una labor
complicada. Se puede contratar a consultoras externas que se encarguen de analizar las necesidades de la
empresa y emitir un informe final con las características y recomendaciones de implantación de un ERP. El
objetivo es que con el resultado de dicho estudio se pueda tomar la decisión de adquirir una u otra aplicación.
Los procesos a identificar van a depender del tipo de empresa de que se trate. El diseño modular de las
aplicaciones de planificación empresarial permite que estén disponibles para un gran número de empresas.
Dependiendo del tipo de empresa, las necesidades a cubrir variarán, y determinarán qué módulos de entre
todos los que dispone la aplicación son seleccionados.
Entre los tipos de empresa susceptibles de implantar un ERP nos encontramos los siguientes:
•Pequeña  y  mediana  empresa:  cualquier  empresa  de  pequeña  o  mediana  dimensión  puede  ser
susceptible de utilizar un ERP en lo relativo a la gestión de clientes, proveedores, productos, y los
procesos de compras, ventas y almacén.
•Sector servicios: este tipo de empresas se basan en la gestión por proyectos por lo que la aplicación
deberá tener un módulo específico basado en el control y seguimiento de proyectos.
•Tiendas y restaurantes: la venta de productos se realiza a través de terminales de punto de venta, que
se instalan en lectores de código de barras o cualquier dispositivo táctil. Permiten seleccionar los
productos a través de una interfaz táctil y amigable. Existen distintas categorías de productos (por
ejemplo: bebidas, comidas, aperitivos, etc.) y el empleado puede grabar al mismo tiempo múltiples
pedidos y utilizar distintos métodos de pago.
•Ayuntamientos: también es posible la implantación de ERP en la Administración Pública, abarcando
los diferentes procesos automáticos. Por ejemplo:
◦Gestión de proyectos y contabilidad de determinados departamentos de los Ayuntamientos.
◦Control de compras y stocks disponibles.
◦Gestión de Recursos Humanos.
◦Atención al ciudadano, haciendo uso del CRM y enlazándolo con los portales de cada municipio.
◦Padrón municipal.
◦Gestión de tasas municipales.
•Venta telefónica: en este tipo de empresas, el módulo de CRM cobra especial importancia, pues el
empleado registra en él toda la información resultante del contacto telefónico con el cliente.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="2-ciclo-de-vida-del-sistema-erp"></a>

## 2 Ciclo de vida del sistema ERP

[⬅ Volver al índice](#índice)

Como cualquier sistema de información, el ciclo de vida de los sistemas ERP está dividido por una serie de
fases.
•Adopción
•Selección
•Implantación
•Puesta en marcha
El ciclo se inicia cuando una organización detecta que su sistema de información ha quedado obsoleto y
quiere optimizar el funcionamiento de sus procesos relevantes, o cuando la organización quiere cambiar su
estrategia de negocio. Los directivos toman conciencia del problema y deciden analizar, evaluar, seleccionar
e implementar la opción del sistema de información más alineado a sus necesidades para alcanzar los
objetivos planteados.

---

<a id="21-adopción"></a>

## 2.1 Adopción

[⬅ Volver al índice](#índice)

En la organización se ha detectado el problema y se evalúa rigurosamente la solución más adecuada para las
necesidades actuales existentes y las previstas a corto y largo plazo.
En esta fase, los directivos de la organización se cuestionan la decisión de implantar un sistema ERP o, si es
más adecuado por motivos técnicos, económicos o funcionales, la adquisición e implantación de otro tipo de
sistema.
Las tareas y la documentación que se tendrá que realizar en esta fase son: elaborar un análisis de los
procesos, establecer los objetivos y los beneficios que se quieren alcanzar, y analizar el impacto de la
implantación en el negocio.
En general, las motivaciones para ir a un sistema ERP se pueden agrupar en las siguientes categorías:
tecnológica, proceso de negocio, estratégica y competitiva.
Razones tecnológicas
•Diversidad de sistemas. La organización tiene una variedad de entornos informáticos que limitan la
capacidad de la empresa para integrar la información de las diferentes unidades de negocio.
•Sistemas actuales de baja calidad. Los sistemas de información existentes son ineficientes o fallan a
menudo.
•Integración de las empresas adquiridas. La adquisición de distintas empresas puede ser un motivo
sustancial para ir a un sistema ERP, a la hora de facilitar la integración de las empresas adquiridas.
La  coexistencia  de  los  diversos  sistemas  de  información  y  los  diferentes  procesos  dificulta  la
comunicación entre las áreas de negocio y la explotación de la información.
Razones de procesos de negocio
•Mejorar la eficiencia de la organización. Se basa en mejorar aspectos concretos de los procesos
críticos de la organización: la mejora del proceso de productividad, la reducción del tiempo del cierre
financiero o la reducción del tiempo de realizar el proceso de inventario.
•Disminuir costes. Reducción del número de almacenes y de las compras de materia prima para
reducir el inventario.
Razones de estrategia
Enfocadas a obtener una mejora de la calidad en la organización o a diseñar una estrategia de negocio
orientada al cliente.
Razones de competitividad
Las empresas de la competencia disponen de un sistema ERP, el cual les permite avanzar en el diseño de
reglas para fidelizar y captar a nuevos clientes y a obtener, con rapidez, informes para la dirección en la toma
de decisiones; es decir, las empresas de la competencia tienen ventaja competitiva.
Además  de  definir  una  razón  para  adoptar  un  ERP,  la  mayoría  de  las  empresas  usan  un  análisis  de
coste/beneficio para decidir si adoptan un sistema ERP u otro tipo de sistema.

---

<a id="22-selección"></a>

## 2.2 Selección

[⬅ Volver al índice](#índice)

Una vez tomada la decisión de adoptar un ERP, el siguiente paso es seleccionar dicho sistema y los módulos
que se implantarán.
La selección del sistema ERP es un proceso crítico con un alto impacto en la organización. Equivocarse en
los primeros pasos del proyecto, en una incorrecta selección del sistema ERP, implica arrastrar y hacer crecer
el problema durante las fases posteriores, con una alta probabilidad de fracaso del proyecto de implantación.
La fase de selección consiste en la evaluación, la selección y la adquisición del sistema ERP que mejor esté
alineado a los requerimientos funcionales de la organización, minimizando las necesidades de adaptación y
personalización.
En esta fase, el primer paso será:
•Hacer un análisis riguroso de la situación;
•Definir las funcionalidades que se quieren cubrir con el sistema ERP;
•Determinar cuáles son los procesos críticos y las áreas que están implicadas en ellos.
En la realización de estas tareas, que afectan los sistemas y procesos que tiene la empresa, tienen que
participar las personas que conozcan el funcionamiento global de la empresa. Probablemente, ninguno de los
sistemas ERP candidatos nos proporcionará la cobertura de todos los requerimientos de la empresa. La
organización tendrá que escoger entre personalizar el sistema ERP, para adaptarse a los procesos de la
organización o cambiar los procesos de negocio al estándar que propone el sistema ERP. Muchas empresas
utilizan la adopción de un sistema ERP como una oportunidad para cambiar sus procesos de negocio básicos,
haciendo una reingeniería de estos para coincidir con la "mejor práctica" (best practice) de los procesos del
sistema ERP. Todo tiene sus ventajas y sus inconvenientes.
Dependiendo del tamaño de la empresa, los recursos económicos y el tamaño del proyecto de implantación
del ERP, la empresa puede externalizar el proceso de evaluación y selección del sistema ERP en empresas
consultoras especializadas. En la selección de la empresa de consultoría externa se analizan factores como el
precio, la formación y el mantenimiento de los servicios, y se negocia el acuerdo contractual.
En la selección del ERP se analizará el mercado de los diferentes proveedores de sistemas ERP, en base a un
conjunto de criterios que previamente se habrán definido, para ser capaces de obtener aquel o aquellos
sistemas ERP que mejor se adapten tanto a las funcionalidades específicas como a los procesos de negocio.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="23-implantación"></a>

## 2.3 Implantación

[⬅ Volver al índice](#índice)

Una vez que se ha tomado la decisión del ERP a instalar, se debe esbozar la forma en que se va a gestionar el
proyecto de implantación. La gestión de la implantación del ERP como un proyecto es necesaria para que
todas las tareas se lleven a cabo de forma sistematizada y controlada.
Aunque cada tipo de empresa posee casuísticas diferentes, casi todas las empresas necesitan, al menos,
consultar la siguiente información:
•Datos de la empresa.
•Clientes.
•Proveedores.
•Productos.
•Almacén.
•Información de Compra y Venta: tarifas, formas de pago, etc.
•Información financiera: definición del plan contable, impuestos, etc.
Cuando hay que enfrentarse a un nuevo proyecto de implantación, se debe realizar un proceso estructurado y
metodológico  para  llevar  a  buen  término  el  desarrollo.  Este  proceso  se  denomina  metodología  de
implantación. Lo que hay que tener claro desde el primer momento es que una aproximación desorganizada
llevará al fracaso en el proyecto. La mayoría de las implantaciones que se desechan son por una mala
organización, por lo que es imprescindible establecer un procedimiento ordenado fiable. Poder definir una
metodología (o mecanismo de implantación) eficiente para todos los posibles proyectos es inviable, ya que
cada uno tendrá sus propias particularidades, pero lo que sí se puede avanzar es un mecanismo general
adaptable al mayor número posible de casos.
Esta metodología se basa en el ciclo de vida clásico de un proyecto, según el cual se pretende crear una serie
de pasos consecutivos generando documentación informativa, descriptiva y organizativa para llevar a cabo la
implantación. Por supuesto es una propuesta que se puede adaptar a las necesidades del proyecto, con la que
no se pretende ser exhaustivo ni representar una guía fiel, simplemente una aproximación desde la que partir.
El ciclo de vida clásico se inicia con una fase de análisis, en la que se determinan todas las características
básicas del proyecto, se imponen límites y se definen las metas. La salida de esta fase lleva al diseño del
sistema, tanto a nivel físico como a nivel lógico, creando la documentación técnica suficiente para poder
realizar el desarrollo. En esta fase se definen elementos funcionales, fuentes y salidas de datos, etc. Una vez
diseñado correctamente el sistema se pasa a desarrollar. Se crea el código de la aplicación y se prueba
independientemente. Al finalizar la programación se realizan una serie de pruebas de integración entre los
diferentes elementos y se asegura el correcto funcionamiento de todos los módulos. El objetivo de este tipo
de pruebas de integración es verificar el diseño y la construcción del programa. Son de tipo caja negra y
normalmente las realiza el desarrollador. Hay dos tipos fundamentales de integración:
•Integración no incremental: Se prueba cada módulo por separado y luego se integran todos de una
vez y se prueba el programa completo.
•Integración incremental: Se combina el siguiente módulo que se debe probar con el conjunto de
módulos que ya han sido probados, dando lugar a una jerarquía arborescente de módulos.
Una vez que el software está probado se implanta en la empresa, realizando todos los procesos necesarios
para dejar funcionando el sistema. En primer lugar, se instala, se migran los datos, se forma a los usuarios y
se realizan pruebas finales de conformidad con respecto a los requerimientos iniciales, y para terminar esta
fase se proporciona toda la documentación necesaria al cliente. Con el sistema implementado se lanza la fase
de  mantenimiento,  en  la  que  se  actualizará  el  sistema,  se  modificarán  aquellas  partes  necesarias,  se
subsanarán errores hasta que se decida sustituir el sistema por otro nuevo y comience el ciclo.
Esta metodología va a implementarse en cinco fases, en vez de las seis que presenta el modelo clásico.
La fase de iniciación busca principalmente detectar la viabilidad del proyecto en etapas tempranas. Si éste no
es viable se abortará sin seguir adelante, en caso afirmativo se organizará y planeará el resto del proyecto
creando  las  especificaciones  del  sistema  a  alto  nivel  y  un  conjunto  de  calendarios  de  actividades.  La
planificación se seguirá utilizando a lo largo de todo el proyecto. Las especificaciones sirven de entrada en la
siguiente fase y de referencia en la fase cuarta para la conformidad del cliente.
En el desarrollo se extiende el análisis de la fase anterior recogiendo todas las necesidades de los usuarios,
los datos obligatorios, los procesos y toda la información relevante del sistema actual. También se detectan
los módulos necesarios, informes, consultas y modificaciones a realizar en el sistema ERP. Con toda la
información se creará una especificación detallada del sistema en sus dos vertientes, hardware y software.
Durante  la  implementación  se  instala  y  configura  el  sistema  adquiriendo  el  hardware  y  el  software,
configurando  los  sistemas  físicos,  instalando,  configurando  y  modificando  el  sistema  ERP,  realizando
pruebas y documentando todo el proceso. Una vez terminada esta fase se tendrá un sistema informático
funcional pero no integrado en la empresa.
Es la fase cuatro, implantación, la que se encarga de integrar el sistema funcional con el sistema productivo
actual,  sustituyéndolo.  Este  cambio  es  el  más  traumático  para  la  empresa  y  se  deberá  de  plantear
correctamente, integrando no solo el cambio de equipos, sino también la formación del usuario, la migración
de datos y todo el soporte necesario para llevar el proyecto a buen término. El final de esta fase es la
aceptación por parte del cliente del sistema.
La última fase abarca el funcionamiento normal de la empresa usando el sistema recién instalado, dotando de
soporte  y  mantenimiento  al  cliente  si  así  se  ha  determinado  en  el  contrato  y  facilitándole  toda  la
documentación del proyecto. En resumen, la metodología desarrollada es la siguiente:
•Detectar la viabilidad (presupuestar) y en caso afirmativo crear las necesidades del proyecto.
•Recoger la información actual y diseñar el nuevo sistema.
•Implantar el nuevo sistema fuera de la empresa.
•Integrar el sistema en la empresa.
•Cerrar el proyecto.
Fase 1: Iniciación
Es la fase inicial de cualquier proyecto y su objetivo es analizar si la empresa debe o no embarcarse en
dicho proyecto, pues en ciertas ocasiones la compañía puede tener más problemas que beneficios a la hora
de realizar un proyecto. Tiene como finalidad determinar al más alto nivel los requerimientos que el cliente
necesita y cómo se van a desarrollar en el tiempo. Esta fase incluye las siguientes subfases:
a)Estudiar el ámbito del proyecto.
b)Realizar un estudio de viabilidad económica, técnica y organizativa.
c)Determinar el nivel de cambio del nuevo sistema con respecto al original.
d)Organizar y planear el proyecto.
De esta fase surge una memoria llamada SRD (documento de especificación de requisitos), que contiene la
especificación completa de lo que debe hacer el sistema sin entrar en detalles internos.
Fase 2: Desarrollo
La finalidad principal de la fase de desarrollo es  crear el sistema informático completo en papel . Se
empezará analizando la especificación funcional, ampliando el documento (utilizando un diseño top-down)
hasta el nivel de detalle más alto posible en el que se especifiquen las entradas y salidas de datos, las
modificaciones  de  los  mismos,  las  relaciones  entre  los  diferentes  elementos,  etc.  Con  el  sistema
completamente descrito mediante DFDs (o cualquier herramienta que creamos necesaria) se pasará a crear el
diseño del hardware del sistema, los ordenadores y sus conexiones, su distribución, etc. A continuación, se
definirán todos los elementos software necesarios, los módulos a utilizar en el sistema gestor, los permisos y
configuraciones especiales, etc. Esta documentación servirá de base a la siguiente fase.
Esta fase incluye las siguientes subfases:
a)Análisis detallado.
b)Diseño físico del sistema (hardware).
c)Diseño lógico del sistema (software).
d)Revisión de las previsiones.
Como resultado surge el  SDD (Documento de Diseño del Software), que contiene la descripción de la
estructura relacional global del sistema y la especificación de lo que debe hacer cada una de sus partes, así
como la manera en que se combinan unas con otras. Ésta es a menudo la fase más difícil para un director de
proyecto, ya que tiene que hacer un importante esfuerzo de abstracción para calcular las necesidades de
personal, recursos y equipo que habrán de preverse para lograr la consecución a tiempo y dentro de los
parámetros previstos.
Fase 3: Implementación
En este punto del proyecto ya está definido completamente el sistema y al más bajo nivel posible, y ahora es
el momento de empezar a instalarlo . Se comienza comprando todo el hardware correspondiente, pasando
después a instalar la red subyacente y configurar completamente todo lo que se haya adquirido. También se
instalará todo el software relativo al sistema de gestión y se configurará correctamente, se añadirán los
módulos necesarios y comenzaremos con las pruebas. Esta fase tendrá que documentarse completamente
desde el comienzo, dotando al equipo de mantenimiento que posteriormente se hará cargo de información
suficiente y detallada de todo el sistema.
Esta fase incluye las siguientes subfases:
a)Adquisición del hardware.
b)Desarrollo de software.
c)Plan de pruebas.
d)Documentación.
Fase 4: Implantación
En  esta  etapa  se incorpora  el  sistema  gestor en  la  empresa ,  se  asume  el  control  de  las  funciones
especificadas en el contrato y se comprueba que todo es correcto. Para que la implantación sea adecuada se
formará correctamente a todos los usuarios y se dará soporte inicial, se supervisará el funcionamiento del
sistema, se migrarán y adaptarán los datos anteriores a la nueva situación. Se termina comprobando que todo
funciona mediante unas pruebas determinadas por el cliente con las que se demuestra que el trabajo está
terminado.
Esta fase incluye las siguientes subfases:
a)Plan de implantación.
b)Implantación.
c)Formación.
d)Conversión y migración de datos.
e)Test de aceptación.
Fase 5: Producción y soporte
El proyecto ha llegado a su fin, se han cumplido las expectativas y los tiempos produciendo un sistema
funcional, el cliente está satisfecho y solo queda realizar el traspaso de documentación. En las entrevistas
finales se proporcionará todo el material disponible al cliente , recabando información de satisfacción si
fuera posible.
Con esta fase se abre un periodo largo de operación, mantenimiento y soporte. Se entiende operación normal
y soporte como los procesos dedicados a asegurar que los sistemas sigan funcionando  y que los usuarios los
utilicen de forma correcta. Se define mantenimiento como las modificaciones mínimas del sistema a través
del  tiempo  por  detección  de  algún  error  o  por  una  nueva  necesidad.  Estos  cambios  deben  realizarse
asegurándose que no se ven afectadas otras partes del sistema.
Si  se  incorpora  el  soporte  al  contrato  habrá  que  implementar  los  mecanismos  de  comunicación  y  de
resolución de problemas. Esta fase es la menos creativa, pero es tan importante como las demás, si se quiere
mantener el sistema vivo. Los errores que se presenten durante este periodo se tendrán que resolver en un
tiempo menor que el utilizado hasta ahora. Hay que saber que el número de errores que aparecen se
incrementa con el tiempo que el sistema lleve implantado, aumentando la dificultad de la solución, por lo que
puede ser necesario plantearnos un nuevo sistema en algún momento de esta fase.
Esta fase incluye las siguientes subfases:
a)Operación normal.
b)Soporte.
c)Mantenimiento.
d)Documentación al cliente.
Entre los riesgos de implantación e integración de un software ERP se encuentran los siguientes:
•Finalización fuera del plazo previsto.
•Sobrepasar el presupuesto asignado al proyecto.
•Funcionamiento no esperado de la aplicación.
•Acontecimientos imprevistos que impidan el desarrollo del proyecto con normalidad.

---

<a id="24-puesta-en-marcha"></a>

## 2.4 Puesta en marcha

[⬅ Volver al índice](#índice)

Este apartado prácticamente está íntimamente relacionado con el de producción y soporte en la implantación
del sistema teniendo muchos puntos en común.
Una vez finalizada la fase de implantación del sistema ERP, sigue un periodo de estabilización. Se empieza a
usar el nuevo sistema y los nuevos procesos. Se observan los primeros resultados del cambio y se detectan
defectos de mal funcionamiento que se tendrán que corregir. En este periodo de estabilización, los usuarios
todavía no están lo bastante familiarizados con los cambios, lo cual puede suponer que, durante los primeros
meses, no se obtenga el resultado esperado. En el uso del sistema es importante que los usuarios reciban
formación y apoyo de la organización. Pasado el periodo de estabilización, los problemas y las paradas
tienen que ser mínimas.
La organización quiere conocer si la implantación ha sido un éxito, comparar entre lo que se planificó y la
realidad. Así, se hará una auditoría por parte de diferentes personas o por una empresa externa. En la
auditoría se comparará si el funcionamiento del sistema es el que se acordó. Se evaluará la duración del
proyecto, el coste y los beneficios reales contrastándolos con los que se planificaron.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="3-adaptación-del-sistema-erp-a-una-empresa"></a>

## 3 Adaptación del sistema ERP a una empresa

[⬅ Volver al índice](#índice)

Una parte de las tareas del análisis y diseño es detectar e implementar cambios en el ERP utilizado, con el fin
de adaptarlo a la empresa actual. Esta adaptación se puede hacer estableciendo nuevas tablas y vistas en la
base de datos y programando módulos completos que incorporen todas las características que se necesiten.
La otra posibilidad es que la empresa se adapte al ERP, ya que la oferta de ERPs hoy en día hace que
presenten  todas  las  opciones  posibles,  luego  eligiendo  adecuadamente  el  ERP no  habría  necesidad  de
cambiar su funcionalidad. Además, al adaptarse la empresa al ERP, se consigue disminuir el tiempo de
implantación, y lo que es más importante, se facilitan las futuras migraciones a nuevas versiones mejoradas
del ERP que nos aportarán mayor eficiencia de gestión.
Debido a la particularidad de cada empresa, sería necesario realizar un análisis caso por caso, de lo que se
concluye que no existe una única respuesta ante este interrogante. Lo que sí es necesario identificar son las
principales características que conllevan a escoger una de estas opciones. A continuación, se detallan estas
características:
a)Sin eliminar las malas prácticas . Cada organización considera que sus procesos como vienen
funcionando son los más adecuados, ya que fueron concebidos de acuerdo con sus necesidades, y
sustentan su progreso gracias a ello. Lo que las empresas no contemplan es que siempre existirán
posibles mejoras a las actividades cotidianas. Si se determina adecuar el ERP a los procesos sin
haberlos analizado, es decir, tal y como vienen funcionando, se desaprovechan con esto las bondades
del ERP, debido a que se estarían automatizando los mismos procesos posiblemente defectuosos.
b)Los modelos establecidos por el ERP . El sistema ERP cuenta con procesos de negocio que han sido
definidos y mejorados después de un amplio estudio de casos de éxito. Pero, a pesar de ello, siempre
será necesario contrastarlos con los procesos propios de la empresa solicitante. Cabe resaltar que la
adaptación a estos procesos modelo es ineludible, pues se estaría suprimiendo un valor esencial que
aporta el ERP.
c)Comodidad. Una de las principales razones por la cual las organizaciones se resisten a utilizar un
ERP, se justifica con el sistema actual, creado a la medida, el cual realiza funciones que el ERP no
tiene en cuenta. Una de las quejas más sonadas por parte de los usuarios es que el ERP no es efectivo
ni práctico, como, por ejemplo: que deben dar muchos clics, que solicita información innecesaria
(los usuarios lo consideran así, pues el sistema actual no lo requiere y así marchan bien los procesos
desde su punto de vista), que el sistema en uso, desarrollado a la medida, genera informes en
formatos más prácticos y amigables que los que genera el ERP. Al examinar estas molestias por parte
de los usuarios, se concluye que estos cambios no generan un impacto relevante en sus labores
diarias.
d)El coste de cambiar de sistema.  De todas maneras, será necesario realizar transformaciones al ERP
implementado, siendo algunas modificaciones más sencillas de realizar que otras. Finalmente, se
evidenciará que el realizar algunas tareas manuales adicionales será manejable frente al rendimiento
del ERP.
La práctica desvela que después del rechazo inicial al cambio de procedimientos manuales que conlleva la
implementación,  se  testifican  los  grandes  beneficios  de  trabajar  con  el  ERP,  entre  los  que  se  pueden
mencionar: integración de todas las áreas de la empresa, buenas prácticas empresariales, estandarización de
procesos, seguridad de la información, consultas en tiempo real, etc.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="4-operativa-del-sistema-erp"></a>

## 4 Operativa del sistema ERP

[⬅ Volver al índice](#índice)



---

<a id="41-modelo-de-objetos"></a>

## 4.1 Modelo de Objetos

[⬅ Volver al índice](#índice)

La base de datos de un sistema ERP suele ser de gran envergadura. Almacena las tablas con los datos de la
aplicación, vistas de las diferentes tablas y otros elementos como funciones o desencadenadores que realizan
operaciones sobre los datos. Por ello, debido a esta gran cantidad de información almacenada, se hace
necesaria una organización entre sus componentes.
Lo  que  se  hace  generalmente  es  establecer  una  nomenclatura  para  organizar  la  información,  que  los
desarrolladores deben seguir a la hora de modificar el código fuente o el esquema de la base de datos. Por
ejemplo, incluir un prefijo en los componentes de la base de datos para saber a qué módulo pertenecen, o
establecer una serie de campos dentro de una tabla como obligatorios, para poder asegurar el funcionamiento
correcto de la aplicación.
En los sistemas de planificación empresarial desarrollados en un lenguaje orientado a objetos, cualquier dato
es accesible a través de objetos. Por ejemplo, en Odoo existe un objeto res.partner para acceder a los datos
concernientes a los colaboradores o socios, un objeto  account.invoice para los datos de las facturas, etc.
Como podemos ver, ambos van precedidos de un prefijo que indica el módulo al cual pertenecen.
En Odoo se puede ver el modelo de objetos yendo a Técnico / Estructura de la base de datos / Modelos
(siempre que se hayan activado las herramientas de desarrollador). Hay que tener en cuenta que cada uno de
los objetos que aparecen son en realidad tablas de la base de datos. Haciendo clic en cada uno de ellos, se
pueden ver los campos de la tabla correspondiente en la base de datos, así como las relaciones.
Aunque se verá en sucesivos apartados, es importante destacar como desde esta utilidad se puede incluso
modificar la base de datos, añadiendo nuevos campos, para adaptarla a las posibles necesidades de la
empresa.
Otro aspecto a destacar es que los módulos instalados en el sistema influyen en la base de datos que se va a
tener.  Esto  quiere  decir  que  la  instalación  de  nuevos  módulos  puede  conllevar  la  modificación  de  la
estructura de datos de Odoo. En los siguientes apartados se verá cómo editar estos objetos y sus vistas
correspondientes para adaptarse a las necesidades de una empresa en cuestión.

---

<a id="42-control-de-acceso-grupos-usuarios-y-permisos"></a>

## 4.2 Control de acceso: Grupos, Usuarios y Permisos

[⬅ Volver al índice](#índice)

El manejo del control de acceso en Odoo se controla mediante usuarios y grupos.
Cada usuario puede pertenecer a uno o más grupos lo cual determina:
•¿Qué menús se pueden utilizar?
•¿A qué tablas del modelo de datos se puede acceder?
Por ejemplo, un grupo Comercial puede tener sólo acceso a algunos menús de Empresas y puede no tener
acceso a ninguna información contable. A cada usuario del Departamento de Ventas se le hace miembro del
grupo Comercial, y con esta simple acción está adquiriendo todos los derechos de acceso que tenga el grupo,
lo cual facilita toda esta gestión de accesos.
Para configurar los derechos de acceso se debe empezar definiendo los grupos, y es importante que sean
representativos de las funciones que hay en la empresa. Siguiendo con el ejemplo del Departamento de
Ventas, se podría definir un grupo Responsable de Ventas que tendría los mismos permisos que Comercial
pero además tendría acceso a las comisiones de venta.
Para crear usuarios y grupos, primero hay que activar el modo desarrollador en Ajustes / Activar modo
desarrollador. Dentro de Ajustes, en el menú superior, se encuentran Usuarios y compañías (se utilizó
previamente para ajustar los datos de la empresa). En este grupo de opciones de menú, una vez desplegado,
se encuentran tres opciones: Usuarios, Grupos y Compañías. Las dos primeras son las que se necesitarán en
este caso.
La gestión de los grupos de usuario se realiza en la opción Grupo. Cuando se accede a ella, el sistema listará
los grupos ya existentes, entre los cuales se puede ver una amplia gama de opciones. Estos grupos se
muestran con el filtrado por defecto Grupos internos tal como se aprecia en la figura.
Esta opción de menú permite la creación de nuevos grupos. Cuando se procede a la creación de estos, se
muestra una ventana como la siguiente:
A simple vista se puede apreciar que, además del nombre del grupo como campo clave, es posible asociar
aquel a una aplicación concreta para de esta forma restringir el uso tal como se desee. En la creación /
modificación del grupo, existe la posibilidad de registrar los usuarios que forman parte de él.
Si ahora se accede a la pestaña Heredado, se puede ver que proporciona la posibilidad de incluir otros grupos
de forma que cada usuario que se añada al recién creado, lo hará de forma automática al grupo o grupos que
se incluyan en este apartado. El resto de pestañas tales como Menús, Vistas, etc. se tratarán en los siguientes
apartados, aunque se puede observar que habrá una alta granularidad en la configuración de lo que se puede
utilizar o no para los usuarios de este grupo, lo que da muchas posibilidades a la hora de restringir o permitir
operaciones a cada usuario.
En cuanto a los usuarios, la gestión se realiza accediendo a la entrada de menú con el mismo nombre. Para
hacerse una pequeña idea de qué aspectos se pueden configurar de cada usuario, un buen ejemplo es observar
qué sucede con el usuario Administrador que se utilizó para la creación y gestión de la empresa. Al acceder a
Usuarios  muestra  una  vista  general  con  todos  los  existentes  en  el  ERP.  Si  se  selecciona  el  usuario
Administrator y se hace clic sobre la opción Editar, es posible observar una figura similar a la siguiente:
A simple vista, se puede apreciar que aparecen una serie de categorías de la configuración del usuario con el
mismo nombre que las aplicaciones instaladas (Contabilidad, Ventas, CRM en este ejemplo). Por lo general,
el desplegable a continuación de cada literal, permite elegir el nivel de permisos sobre dicho módulo que
tiene el usuario.
Por ejemplo, en Ventas se contemplan estas tres posibilidades de permisos sobre dicho módulo:
•Usuario: Solo mostrar documentos propios
•Usuario: Mostrar todos los documentos
•Administrador
De primeras, se observa que hay una diferencia entre lo que sería un perfil de usuario y un administrador. El
usuario administrador, como configurador del sistema y responsable de los aspectos técnicos de él, tiene
dichos permisos de administración (Administrator) mientras que por otra parte está el Usuario que opera con
dicho módulo.
A continuación, se va a seguir un pequeño ejemplo práctico. Primeramente, hay que asegurarse de tener
instalados los módulos de Compra, Ventas e Inventario. Se creará un usuario al que se le va a dar permisos
sobre un módulo en concreto, en este caso de inventario. Si se trabaja sobre una base de datos en la que ya se
hayan realizado ventas, habrá que dar acceso al usuario ya que podría haber problemas a la hora de consultar
un producto. En este ejemplo, se añade también acceso a dicho módulo, pero solo mostrando documentos
propios:
Los usuarios creados van inicialmente sin contraseña, con lo que, una vez creado, hay que acceder al menú
Acción / Cambiar la contraseña.
Ahora se probará a acceder al sistema con el usuario recién creado. Cuando se trabaja en este modo de
administración y hay que ir probando cada usuario, en lugar de salir de una sesión y comenzar otra, es más
eficiente abrir otro navegador y realizar en él las pruebas correspondientes. Otra opción si solo se dispone de
un navegador, es abrir una sesión privada. Una vez accedido, se comprueba que efectivamente, el usuario
solo tiene permisos para operar en el módulo de inventario y en el de ventas, que son los que se han
proporcionado previamente.
¿Pero cómo se puede saber en detalle cuáles son los permisos que tiene el nuevo usuario sobre el módulo de
inventario? Como ya se ha visto, los usuarios están unidos a un grupo o varios. Si se acude a la página en la
que se muestran los datos del usuario, aparece un apartado referido a los grupos en los que está incluido:
Como se puede ver, por defecto le ha asignado una serie de grupos que variarán según la configuración del
ERP. Ahora mismo interesa más conocer en qué consiste el grupo Inventario / Usuario por ser el que se ha
utilizado como principal al crear el usuario. Si se consulta, se mostrará algo similar a lo que aparece en la
siguiente figura:
En la primera pestaña se encuentran los usuarios que forman parte del grupo, algo que no interesa tanto como
en la siguiente, ya que se puede ver que los usuarios de inventario heredan de Tipos de Usuario / Usuario
interno.
Si se sigue navegando por las pestañas se encuentran los siguientes apartados:
•Menús. Donde se enumeran los menús a los que puede acceder este usuario relacionados con su
pertenencia al grupo. Obviamente, estos menús complementan a aquellos que pudiera tener por el
grupo heredado (Usuario interno) y a los de otros grupos a los que pertenezca.
•Vistas. Aquí se indican las vistas a las que puede acceder el usuario. Una vista no es ni más ni menos
que un interfaz gráfico de consulta/edición de las entidades propias del sistema. Entre los datos que
se pueden ver de la vista en esta opción son tanto el propio nombre de la vista como su tipo, modelo
al que hace referencia, identificador externo y la vista heredada. Posteriormente habrá ocasión de
profundizar en estos conceptos.
•Permisos de acceso.  Estos permisos de acceso hacen referencia a los distintos objetos del modelo de
datos del sistema y a qué podemos hacer sobre ellos (lectura, escritura, creación y/o eliminación).
La modificación de productos se hace desde la Plantilla de producto. Tal como está configurado ahora
mismo, no se puede crear ni eliminar ni siquiera modificar un producto, únicamente leerlo. Se va a marcar el
Permiso de escritura dentro del grupo tanto para la Plantilla del producto como para el Producto en sí. A
continuación, se refresca la página en la que se está con el usuario creado (María en este ejemplo). A partir
de este momento, el sistema deja editar el producto seleccionado.
Si se quiere crear un nuevo producto, hay que habilitar los permisos de creación sobre los objetos plantilla y
el producto. Igualmente, se dispone de permisos de eliminación de un registro.
En cualquier caso, esta no sería la metodología a seguir, ya que se está modificando un grupo predeterminado
por Odoo y esto al final puede dar más de un quebradero de cabeza. Existe una solución más elegante, la cual
consiste en crear un nuevo grupo heredado del base Inventario / Usuarios. Como se vio previamente, un
grupo puede tener permisos heredados de otro; en este caso se va a crear uno llamado Usuario avanzado al
cual se le van a dar permisos de edición de productos. El nuevo grupo tendrá las siguientes características:
•Aplicación: Inventario
•Nombre: Usuario avanzado
•Heredado: Hereda de Inventario / Usuario
•Permisos de acceso: Se le da un nombre de regla y se determina que tenga permiso de modificación
sobre  Plantilla de producto  añadiéndole permisos de lectura y escritura. Se realiza la misma
operación sobre el objeto Producto añadiendo otra regla.
Quedará algo similar a lo siguiente:
Ahora se podrá modificar la pertenencia al grupo del usuario con el que se está trabajando, pero ¡ojo! ya no
se hará desde el desplegable del módulo, sino que aparecerá una nueva categoría etiquetada como Other u
Otros volviendo a aparecer el Inventario y el nuevo grupo en un desplegable.
Si ahora se actualiza la web de trabajo de la usuaria se puede ver cómo permite la edición del producto sin
mayor problema.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="43-modificación-de-los-menús"></a>

## 4.3 Modificación de los Menús

[⬅ Volver al índice](#índice)

Los menús en Odoo pueden modificarse en su totalidad. La configuración se realiza desde el apartado
Ajustes / Técnico / Interfaz de usuario / Elementos de menú. En él se pueden ver todos los elementos de
menú creados para todos los usuarios y grupos. Como se ha visto en el apartado anterior, los distintos menús
que a aparecen a un usuario concreto dependen del grupo o grupos a los que pertenezca.
La estructura de menús es jerárquica: cada opción de menú tiene un padre. Por ejemplo, la Gestión de
almacenes cuelga de Configuración y a su vez de Inventario.
El ERP permite la personalización de los menús, por lo que se va a establecer un caso práctico en el que se
configurará un entorno para disponer de una entrada que permita acceder a una opción de forma más directa.
Se va a suponer que se requiere una entrada de menú más directa hacia los productos que aparezca en la
parte superior como menú raíz.
Si dentro de Elementos de menú se hace una búsqueda que incluya el término Productos se obtendrán las
distintas ubicaciones mostrando algo similar a lo que aparece en la figura, dependiendo de la configuración
del ERP:
En este caso, hay que ir a la opción Inventario / Productos / Productos haciendo clic sobre ella.
El sistema permite una serie de operaciones en el desplegable Acción entre las cuales se encuentra Duplicar,
que es la que se va a utilizar para crear una nueva entrada de menú a partir de esta. Cuando se duplica, lo que
hace el sistema es crear esa nueva entrada permitiendo editarla. En este caso, la idea es que Productos sea
una entrada raíz, con lo que se elimina el contenido de Menú padre. Al actualizar, se ve que Productos
aparece en el menú lateral como un elemento principal más.
Esta modificación, tal como se ha realizado, tiene la particularidad de que afecta a cualquier usuario,
independientemente de sus permisos. Ello implica que la usuaria que se creó en el apartado anterior también
tendrá su opción Productos en el menú. Esto, que a priori parece una ventaja, podría no  servir al querer que
solo una parte de los usuarios pudieran ver esta opción. Como se vio anteriormente, los grupos tienen una
pestaña dedicada exclusivamente a los menús. Si se modifica dicha entrada en el caso del Usuario avanzado
que se creó en su momento y se le añade el nuevo menú Productos, únicamente los usuarios en ese grupo
podrán hacer uso de esta entrada.
A partir de ese momento, el usuario Administrator deja de ver esa opción mientras que el usuario avanzado
María la puede encontrar en su menú principal.
En resumen, una entrada de menú que no esté adscrita a ningún grupo puede ser visualizada por cualquier
usuario, pero en el crítico momento en que empieza a formar parte de al menos un grupo, ya deja de ser
visible para todo usuario que no pertenezca al mismo.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="44-creación-y-modificación-de-objetos-del-sistema-vistas"></a>

## 4.4 Creación y Modificación de Objetos del Sistema. Vistas

[⬅ Volver al índice](#índice)

Lo primero que hay que que hacer es estudiar la información a introducir en la aplicación. Puede ser que
haya  que  añadir  campos  a  objetos  existentes  o  bien  crear  objetos  nuevos  para  poder  representar  la
información que necesita la empresa. Todas las modificaciones se pueden hacer sin tener que tocar una línea
de código de Odoo.
Un caso de uso para realizar una operación de este tipo es tener que almacenar algún dato extra para algún
objeto de la aplicación (por necesidades de la propia empresa). En este apartado se verá cómo se pueden
añadir nuevos objetos al sistema con el objetivo de poder gestionar información de un tipo que el ERP no
gestiona por defecto. De igual manera, se pueden añadir nuevos campos a objetos del sistema existentes.
También es posible borrar campos de los objetos existentes, aunque esta opción no es recomendable ya que
un mismo campo de un objeto puede ser usado por muchos módulos al mismo tiempo y su eliminación
podría tener efectos no deseados.
Todos estos cambios implican también la creación o modificación de los mecanismos para la edición de los
nuevos objetos o de los objetos modificados. Es decir, una vez creado el nuevo objeto hay que crear los
interfaces de usuario para poder listarlo, dar altas, borrar, etc. En Odoo estas tareas se realizan por lo que se
conoce como vistas.

---

<a id="441-gestión-de-vistas"></a>

## 4.4.1 Gestión de vistas

[⬅ Volver al índice](#índice)

Cada objeto tiene su propia interfaz, por ejemplo, no se muestran de la misma manera los datos de las
Empresas que los datos de una Factura.
Las interfaces pueden ser:
•Estáticas: se crean dentro del código de la aplicación y no pueden ser modificadas.
•Dinámicas: pueden ser modificadas por parte del usuario, para lo cual se almacena la descripción de
la vista en un lenguaje de descripción de datos que permita su modificación, como por ejemplo
XML.
Por tanto, las interfaces dinámicas son construidas de forma dinámica por la descripción XML de la pantalla
del cliente. Para ello no es necesario ser unos expertos en ese lenguaje, se pueden hacer objetos sencillos
simplemente tomando como ejemplo otros objetos que haya creados en la aplicación. No obstante, muchas
aplicaciones proveen la forma de crear las descripciones de manera gráfica sin necesidad de introducir
código manual.
Un ejemplo de una vista simple en Odoo, que es capaz de acceder a los campos de un objeto es la siguiente:
<form string="Persona">
<field name="nombre"/>
<field name="apellidos"/>
<field name="edad"/>
</form>
Con el código anterior se está creando una vista de tipo formulario. Esta vista servirá para editar o introducir
datos a la entidad “Persona”. Concretamente recoge tres campos denominados: nombre, apellidos y edad.
Esta definición se almacenará en un archivo XML que, al abrirlo desde la aplicación, mostrará el objeto
resultante de la definición anterior.
Las vistas pueden ser además de diferentes tipos. Se dispone, entre otras, de las siguientes:
•Formulario (form)
•Árbol o Lista (list)
•Actividad
•Calendario•Kanban
•Búsqueda
•QWeb
Por ejemplo, la siguiente figura en la que se pueden ver los clientes y proveedores de la empresa, es de tipo
Kanban (precisamente basada en el método de producción homónimo, también aplicado al desarrollo de
software), siendo la que aparece por defecto:
Fijándose en la parte derecha del interfaz de usuario, se pueden ver un par de botones que permiten cambiar
entre tipos de vista:
Si se cambia al icono más a la derecha, se muestra una vista de tipo lista representando los clientes en forma
de listado:
Al entrar en cualquier producto, la vista mostrada es la de formulario, tanto para consultar la información de
un objeto como para editarla. Es importante destacar que no todas las vistas están asociadas a cada objeto.
Para otros tipos de objetos las vistas asociadas pueden ser otras. También hay que destacar que existen una
gran cantidad de vistas en el ERP ya creadas. Por ejemplo, cuando se ve el listado de productos, la vista que
aparece es de tipo Kanban. En el caso de hacer clic sobre un registro, se entra en la vista de tipo Formulario.
Todas estas vistas del ERP pueden ser modificadas además de poder crear vistas nuevas.
¿Cómo se pueden gestionar tanto las vistas existentes como la creación de nuevos interfaces? V olviendo al
menú Técnico dentro de Interfaz de usuario / Vistas se muestra la totalidad de las vistas existentes en el
sistema, las cuales dependen del número de módulos instalados.
Como se puede ver, en este listado aparece tanto el nombre técnico de la vista como su tipo, el modelo con el
que trabaja, un ID externo y si se trata de una vista heredada de otra y cuál sería su ancestro.
A continuación, se va a realizar un ejemplo de modificación de vista existente. Se accede a la vista Kanban
de Productos donde hay que posicionarse en la entrada de menú correspondiente a las herramientas de
desarrollador con el modo de depuración  activado. Esta entrada tiene un icono con forma de bicho para
dejar claro que se trata de debug.
La edición de la vista se realiza mediante la opción Técnico/Interfaz de usuario/Vistas. Lo que vamos a
modificar es la forma en la que se muestra la información de los productos. Localizamos la vista que
debemos modificar.
La vista actual de los productos es de esta forma, podemos utilizar una segunda pestaña para comprobar los
cambios que se van efectuando.
Si editamos la vista Product.template.product.kanban  veremos algo similar a esto:
Como se puede ver, muestra el nombre de la vista, su tipo, a qué objeto del modelo hace referencia, si es
heredada y de quién o si es una vista base, entre otros datos. En este caso, Odoo permite la edición de la vista
mediante el apartado Estructura, aunque hay que ser cuidadoso en lo que se hace ya que puede haber vistas
heredadas de ésta que dejen de estar operativas si se realiza algún cambio de calado. Se trata de un archivo
XML pero que contiene elementos propios de HTML lo que hace que sea sencilla la curva de aprendizaje
para cualquier técnico con conocimientos de diseño Web.
Si se quiere editar la vista para que no se muestre la imagen del producto , lo primero que se pensaría es en
eliminar su capa correspondiente:
<aside>
<field name="image_128" widget="image" alt="Product" options="{'img_class': 'w-100 object-fit-contain'}"
invisible="not image_128"/>
</aside>
Como ya se citó, esta operación es peligrosa con lo que no se recomienda su realización. Lo que se puede
hacer es simplemente utilizar los atributos del elemento, concretamente invisible el cual se ajustará a 1
quedando su código así:
<aside invisible="1">
<field name="image_128" widget="image" alt="Product" options="{'img_class': 'w-100 object-fit-contain'}"
invisible="not image_128"/>
</aside>
Si se consulta la vista Kanban de productos una vez realizada la modificación, se podrá ver que esta vez ya
no aparece la imagen:
Igual que se ha podido editar esta vista, es posible hacerlo con la de árbol y aquí se puede realizar otra
operación muy interesante: añadir nuevos campos. Con la vista de lista activada, se vuelve al bichito
eligiendo Vista de edición: List.
En la figura se ve la ventana de edición cuyo código esta vez es mucho más sencillo:
Echando un ojo al código XML se ven detalles. Es posible ocultar campos, reordenarlos, hacerlos de solo
lectura, etc. El tema se complica cuando ya se desea editar una vista formulario. Si se accede a cualquier
producto, tal como ya se anticipó, se entraría en su vista de formulario y también se podría modificar
accediendo al bichito, esta vez mediante la opción Vista de edición: Form. En la figura se puede ver un
ejemplo de este tipo de edición sobre el formulario de productos.
A la vista de la figura, llama la atención que apenas tiene codificación para toda la información que muestra
el  formulario.  Esto  se  debe  a  que  hereda  de  otra  vista  más  compleja  llamada
product.template.common.form . Si se accede al icono a la derecha del nombre de la vista, se puede
proceder a su edición también y ya aquí se ve que encaja más con el contenido visualizado.
Por último, si se vuelve a los Elementos de menú  seleccionando cualquiera de los que hacen referencia a
productos, se puede observar que hay un campo referido a la Acción que realiza dicha entrada.
Cuando se hace clic sobre el icono a la derecha de la acción, se abre una vista como la de la figura a
continuación:
Esta acción contiene los tres tipos de vista que están disponibles para el producto (kanban, list, form) junto
con otros campos.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="442-creación-de-un-nuevo-campo-en-un-objeto-existente-y-modificación-de-sus-vistas"></a>

## 4.4.2 Creación de un nuevo campo en un objeto existente y modificación de sus vistas

[⬅ Volver al índice](#índice)

asociadas
El acceso a los objetos de la base de datos se realiza también en la opción Ajustes / Técnico  dentro de la
categoría Estructura de la base de datos. Principalmente ahora interesa ver cómo cambiar las entidades que
forman parte del modelo de datos. Para ello se acude a la opción Modelos en la categoría citada.
En esta vista se observan todas las entidades del sistema enumeradas. Puesto que tiene la posibilidad de
filtrar, se volverá a realizar una búsqueda con el patrón “producto” para encontrar aquellos objetos de esta
entidad sobre la que se están realizando los ejemplos.  En la figura se muestra una posible salida a esta
búsqueda.
Si se accede, por ejemplo, a la plantilla de producto, que es con la que queremos trabajar, se podrá ver toda
su estructura al completo, incluyendo no solo los tipos de datos de los campos sino sus relaciones con otras
entidades (many2many, one2many y many2one).
Se va a añadir a los productos que tenemos, los años de garantía que proporciona el fabricante y hay que
crear una entidad para ello. Lo primero agregamos una nueva linea para que ya dependa de productos.
Debemos cubrir los siguientes campos, es conveniente iniciar el nombre del campo con la x para poder
localizar todas las modificaciones en el caso que produzcan errores posteriores.
Nombre de campo: x_garantia
Etiqueta de campo: Años de garantíaTipo de campo: Carácter
Campo ayuda: Opcional
Podemos ver que se ha creado un nuevo tipo de dato.
Ahora vamos a incorporar este nuevo campo al producto para eso localizamos en Ajustes/Técnico/Interfaz de
usuario/Vistas la vista de formulario product.template.product.form
Insertamos la línea para crear un nuevo campo que mostrará en el formulario.
<field name="x_garantia"/>
Lo inserto debajo de la opción para el código de barras. Se podría buscar otra posición a nuestro gusto.
Guardamos y comprobamos que aparece un nuevo campo Garantía en nuestros productos.
Los tipos de campos disponibles son los usuales en las bases de datos, he elegido el tipo carácter aunque
hubiese sido una mejor elección tipo entero.
Inserto valores en algunos de los productos. También voy a modificar la vista kanban para que muestre el
nuevo campo agregado.
Localizamos  en  Ajustes/Técnico/Interfaz  de  usuario/Vistas  la  vista  de  kanban
product.template.product.kanban
Insertamos el siguiente código.
<span>Garantía:
<field name="x_garantia"/>
</span>
Lo que nos mostrará al acceder a productos.
Tenemos que aparece la palabra Garantía en todos los productos, tengan o no valor en ese campo.
Si añadimos un t-if podremos mejorar la vista de forma que solo mostrará esa parte cuando exista ese campo.
<span t-if="record.x_garantia.value" >Garantía:
<field name="x_garantia"/>
</span>
Ahora la vista solo mostrará el campo garantía cuando tenga algún valor.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="443-creación-de-un-nuevo-objeto-y-sus-vistas-asociadas"></a>

## 4.4.3 Creación de un nuevo objeto y sus vistas asociadas

[⬅ Volver al índice](#índice)

Para realizar esta parte vamos a suponer que tenemos una agencia de alquiler de vehículos y que interesa
disponer de una base de datos para asignarlos. Los campos que voy a utilizar a modo de concepto de
funcionamiento son:
Modelo del vehículo
MatrículaFecha de Alta
N.º de pasajeros
El acceso a los objetos de la base de datos se realiza también en la opción Ajustes / Técnico dentro de la
categoría Estructura de la base de datos . Principalmente ahora interesa ver cómo cambiar las entidades que
forman parte del modelo de datos. Para ello se acude a la opción Modelos en la categoría citada.
Esta vez utilizaremos la opción de crea un nuevo modelo. Llamaremos Coches a este nuevo modelo.
Borramos el campo por defecto x_name que me sugieren y creamos nuestros campos.
Nombre del campo: x_fecha_alta; Etiqueta: Fecha de Alta y tipo de campo: fecha
Nombre del campo: x_matricula; Etiqueta: Matrícula y tipo de campo: Carácter
Nombre del campo: x_modelo; Etiqueta: Modelo y tipo de campo: Carácter
Estos tres los hacemos obligatorios marcando la opción de Requeridos.
Nombre del campo: x_pasajeros; Etiqueta: N.º de pasajeros y tipo de campo: entero (No requerido)
Al guardar nos muestra otros campos propios que utilizará el sistema
El siguiente paso es crear las vistas para poder interaccionar con este modelo, en este caso solo voy a crear
las de lista y formulario.
Accedemos a Ajustes / Técnico / Interfaz de usuario /Vistas  y creamos una nueva. Empiezo por la lista.
<list string="Coches">
<field name="x_modelo"/>
<field name="x_matricula"/>
<field name="x_fecha_alta"/>
</list>
En el listado no voy a mostrar el campo número de pasajeros.
Creo otra nueva vista esta vez de tipo formulario para poder registrar los datos.
El código será de la forma
<form string="Coches">
<group>
<field name="x_modelo"/>
<field name="x_matricula"/>
<field name="x_fecha_alta"/>
<field name="x_pasajeros"/>
</group>
</form>
Ahora debemos añadir la posibilidad de llegar al modelo Coches mediante la modificación del menú.
Nos situamos en Ajustes / Técnico / Interfaz de usuario /Elementos de menú
Creamos uno nuevo
Pero no tenemos habilitada la acción Coches, así que deberemos crearla.
Nos situamos en Ajustes / Técnico / Acciones /Acciones de ventana Creamos una nueva y nos aseguramos
que aparece list, form en el Modo de vista.
También debemos dar permisos de acceso al Modelo Coches
Ajustes / Técnico / Seguridad / Permisos de acceso
He puesto el grupo Tipo de Usuario/Usuario interno
Ya podemos crear nuestro elemento de menú Coches
He creado elemento de menú dentro de inventario
Podemos ir introduciendo los datos en la vista formulario
Y nos muestra
En esta vista no habíamos añadido el campo pasajeros.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="444-creación-de-relaciones-entre-objetos"></a>

## 4.4.4 Creación de relaciones entre objetos

[⬅ Volver al índice](#índice)

Entre los posibles tipos de datos que se vieron en el apartado anterior existían unos concretos para establecer
relaciones entre objetos del modelo. Para ello, Odoo proporciona tres tipos:
•one2many:  Relación  uno  a  muchos.  En  el  modelo  en  el  que  se  establece,  define  que  puede  estar
relacionado con varios elementos. Por ejemplo, si se supone que un cliente puede tener varios coches, se
establecería en aquella entidad un campo de tipo x_coches que referenciara a aquellos que posee.
•many2one: Relación muchos a uno. Se utiliza en el modelo en el que se va a relacionar con otro, aunque
solo puede haber una ocurrencia. Por ejemplo, en el caso del coche, suponiendo que solo puede tener un
propietario, sería el campo referido a este (por ejemplo, x_propietario).
•many2many: Relación muchos a muchos. Al igual que en las anteriores, pero teniendo en cuenta que
puede estar asociado a varias ocurrencias. Si se decide que un coche puede tener varios propietarios y que
un cliente puede tener varios coches, se establecerían campos de esta tipología en ambos modelos.
Evidentemente, este tipo de columnas entroncan directamente con el modelo relacional que precisamente es
coherente con la base de datos subyacente, en este caso, PostgreSQL.
En el ejemplo, se va a suponer que el coche puede tener un propietario/cliente y que se puede pagar con
alguna de las opciones de pago predeterminado. Esta vez no se va a crear una nueva entidad para ello, sino
que se utilizará una de las que proporciona Odoo, en este caso, los  clientes y los métodos de pago.
El problema que surge ahora es que a priori se desconoce qué modelo subyacente soportase la creación de
clientes en Odoo. Hay múltiples formas de obtener esta información. Una de ellas es ir a la vista de
formulario de cliente (con las herramientas de desarrollador activadas) y editarla.
Como se ve en la figura, el modelo asociado al cliente es res.partner. A partir de aquí, lo que hay que hacer
es modificar la estructura de la tabla de coches para añadir un campo propietario ( x_propietario) teniendo en
cuenta que será un elemento de este modelo. La operación es muy simple, basta con añadir al modelo un
campo de tipo many2one (ya que se ha determinado que un vehículo solo puede tener un propietario) que se
asocie a res.partner.
También añado el campo ( x_pago) que se asocia  a payment.provider.
Para visualizar clientes he añadido dos al sistema con los nombres Cliente 1 y Cliente 2.
Activo alguno de los métodos de pago que trae por defecto.
Añado los dos nuevos campos en Ajustes / Técnico / Estructura de la base de datos / Modelos
localizamos el modelo coches, en los campos presentes añadimos los nuevos como en la imagen.
Debemos relacionar este campo con res.partner (clientes).
Lo relacionamos con payment.provider
Modifico la vista de coches.form para poder introducir los propietarios y los pagos.
<field name="x_propietario"/>
<field name="x_pagos"/>
Si queremos ver el resultado podemos modificar cualquiera de los registros existentes y ver como se presenta
la selección de usuario mediante un combo. Me muestra los clientes, puedo buscarlos e incluso crear nuevos
desde este opción, de igual marea que aparecía en la creación de facturas.
De la misma manera para los pagos.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="45-gestión-de-tableros"></a>

## 4.5 Gestión de Tableros

[⬅ Volver al índice](#índice)

Lo primero que hay que saber de un tablero es que en realidad es una vista formada de una agrupación de
otras vistas más simples. Su finalidad es agrupar en un solo interfaz de usuario toda la información necesaria
para un usuario determinado.
En Odoo ya vienen creados varios tableros. Por ejemplo, al acceder al Inventario se puede ver cómo aparece
un tablero con varias vistas aglutinadas (Recepciones, Órdenes de entrega, etc.).
De un vistazo se puede ver cómo está el inventario sin entrar en ninguna otra parte del sistema.
Los tableros se pueden modificar y por supuesto el ERP debe permitir crear nuevos con el fin de agrupar las
vistas que puedan resultar interesantes. Aunque estas modificaciones pueden realizarse vía código, por suerte
existe una aplicación realizada para tal efecto en Odoo con el mismo nombre,
es decir, Tableros.
Cuando se accede por primera vez, se observa que el tablero está vacío.
Tal como muestra el mensaje, informa de que se puede acudir a cualquier menú, cambiar a vista lista o
gráfico y hacer clic en Añadir a mi tablero  (Add to Dashboard) en las opciones extendidas de búsqueda.
En este ejemplo, se quiere añadir al tablero los pedidos de ventas. Basta con acudir a Ventas / Pedidos y en
el menú Favoritos seleccionar la opción Añadir a mi tablero  con el nombre que se desee (por defecto nos
da el nombre que ya tiene la vista). Cuando se añade un ítem al tablero, el sistema pide que se refresque la
página en el navegador. Si se hace así y se accede a la sección Tableros aparecerá  Mi Tablero y en su
contenido el ítem recién añadido.
Ahora se van a añadir también los pedidos de compra al mismo tablero y con la misma operativa. Por último,
se incluirá uno de los informes gráficos de los que constan los pedidos de venta para tener 3 elementos en el
nuevo tablero.
Se puede observar que, al poner el ratón sobre cada elemento del tablero, visualiza el icono estándar para el
movimiento de componentes de un interfaz gráfico. Por tanto, se puede ajustar el tablero colocando los
elementos  en  el  orden  que  se  quiera.  Además,  consta  de  un  botón  llamado  Cambiar  diseño  el  cual
proporciona la posibilidad de elegir entre distintos diseños para el tablero. En esta figura se ve cómo quedan
los elementos una vez colocados:
Y si se hace clic sobre el botón Cambiar diseño, proporciona varias formas de maquetar el contenido del
tablero:
Por supuesto, un tablero puede ser ubicado donde se desee, ya que tiene su propio elemento de menú
perfectamente configurable como se vio anteriormente.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="46-informes-personalizados"></a>

## 4.6 Informes Personalizados

[⬅ Volver al índice](#índice)

Los informes personalizados son vistas nuevas creadas por usuario que recogen información de la base de
datos y permiten gestionarla de forma más acorde a cómo se realiza en una empresa. Estos informes usan las
estructuras de datos ya existentes aumentando su eficiencia. En una analogía con bases de datos, se estaría
hablando de vistas sobre datos.
Odoo dispone de varios informes ya creados y totalmente funcionales. Por ejemplo, cuando desde el módulo
de ventas se genera una factura para un cliente, el PDF que se crea es un informe que contiene la información
sobre dicha factura presente en la base de datos.
La personalización de informes se realiza, una vez más, activando el modo desarrollador. Una vez adquirido
ese rol, hay que ir a las opciones en Ajustes / Técnico / Acciones / Informes , donde se ven aquellos que
tenga instalados en ese momento el sistema.
Como se ve en la figura, los nombres son lo suficientemente descriptivos como para hacerse una idea de qué
hay disponible. Se probará consultando uno concreto relacionado con las ventas, por ejemplo, Presupuesto /
Pedido.
Por supuesto, el sistema permite editar cada uno de los atributos del informe. Uno de los más interesantes es
el Tipo de informe, el cual en este caso es un PDF. Odoo permite modificar la salida de este informe de
forma que se pueda elegir un PDF, una página en HTML o simplemente texto plano (aunque en este caso no
deja de ser un HTML).
La parte más importante en esta vista es la que remite al nombre de plantilla, ya que es la que define el
formato del informe. Como cabría esperar, y una vez que se vio el formato de las vistas, los informes
también están diseñados utilizando XML. Para visualizar su codificación hay que ir a la opción  Vistas
QWeb que ya va dando pistas con los símbolos utilizados para los lenguajes de marcado </>. Al acceder a
esas vistas, se va a ver que el informe consta de una serie de vistas QWeb. Hay que tener en cuenta que un
informe puede ser una entidad compleja que a su vez conste de otros informes, gráficos, etc.
Si se accede a la vista QWeb principal, en este caso, report_salesorder, se ve algo similar a lo que aparece
en la siguiente figura:
Sin entrar en detalles sobre la codificación del XML, en este caso, dice que para cada documento (pedido en
este caso) llame a otra vista llamada sale.report_saleorder_raw
La referencia completa de lo que es QWeb se puede consultar (cómo no) en la web de nuestro ERP, en este
caso Odoo dentro del siguiente enlace:
https://www.odoo.com/documentation/18.0/developer/reference/frontend/qweb.html
Tal como puede verse en ella, existen todo tipo de herramientas de maquetado para las plantillas de informe
(condicionales, bucles, atributos, subinformes, etc.). Al ser este un elemento imprescindible en cualquier
ERP, lo normal es que el fabricante proporcione una referencia completa, con lo que OpenBravo, SAP, etc.
también tienen bien documentada la forma de crear informes personalizados.
V olviendo al informe anterior, por su codificación se sabe que esta plantilla va a llamar a otra llamada
sale.report_saleorder_document . Se puede, por tanto, ver qué muestra.
Observando bien esta plantilla, ya parece más elaborada y detallada. A simple vista, se ven una serie de
etiquetas span con sus condicionales. En este ejemplo, se va a suponer que no interesa el comercial que ha
realizado la operación (es uno de los campos del informe). Se edita la estructura del informe parándose en un
elemento concreto:
<div t-if="doc.user_id.name" class="col-auto col-3 mw-100 mb-2">
<strong>Salesperson:</strong>
<p class="m-0" t-field="doc.user_id"/>
</div>
Esta capa representa al comercial, pero ¿cómo es posible que cuando se obtenga un pedido de venta no
aparezca así sino como comercial? Ello se debe a que Odoo realiza las traducciones automáticas según el
idioma seleccionado. De esta forma, una misma plantilla sirve para el idioma ajustado sin necesidad de tener
tantas como lenguas instaladas.
Si se elimina cuidadosamente esta etiqueta, al visualizar el pedido, se verá que ese campo ya no aparece.
Pero eliminar una etiqueta completa puede entrañar un riesgo si no se hace bien e incluso más adelante se
podría necesitar. En este caso, tal como se hizo con las vistas, es posible ocultarla.
Con unos ligeros conocimientos de CSS basta saber que con lo siguiente se podría conseguir:
<div t-if="doc.user_id.name" class="col-auto col-3 mw-100 mb-2" style="display:none">
<strong>Salesperson:</strong>
<p class="m-0" t-field="doc.user_id"/>
</div>
Et voilá, ya se tiene un nuevo informe, pero esta vez sin que aparezca el comercial.
A continuación, se va a crear un informe completamente nuevo partiendo de la entidad creada anteriormente
(x_coches) para diseñar una salida que no existía previamente, al igual que la entidad antes de ser
creada. Hay que ir a Ajustes / Técnico / Informes / Informe  y al botón Crear para dar de alta un nuevo
informe.
Se va a dar de alta con los datos que se ven en la figura, teniendo en cuenta que el nombre ( Informe de
coches) es descriptivo, que el modelo tiene que ser con el que se esté trabajando (en este caso, x_coches) y
que de momento solo hay una vista simple, por lo que se partirá de una plantilla sin demasiada complicación
llamada  coches.informe (en este caso, el nombre también ha de ser identificativo). El informe creado,
además va a ser de tipo HTML para facilitar el proceso.
Añado la opción del menú de impresión para que me salga en el modelo de coche.
A continuación, y en esta misma ventana de edición, se accede a la sección  Vistas QWeb y se crea una
nueva. Como nombre, se le dará el mismo de la plantilla (coches.informe ), tipo de vista, QWeb y el modelo,
el ya conocido x_coches.
Para probar el informe, se va a escribir simplemente un mensaje estático en él, ya que, aunque parezca que
con estas operaciones habríamos terminado, todavía hay que realizar otras tareas.
El código a insertar podría ser similar al siguiente:
<t t-name="coches.informe">
<div class="page">
<p>Informe de prueba</p>
</div>
</t>
Si se vuelve al informe, ahora se podría probar entrando en la opción Añadir al menú Imprimir , lo que hará
que se añada esa opción en la entidad vehículo cuando se consulte uno de ellos. El problema es que cuando
se prueba a imprimir el informe, muestra un error que finaliza con la siguiente cadena:
Vamos a Coches y en cualquiera de los que tenemos agregados pulsamos en imprimir
Nos muestra un error similar a este
No está diciendo que no encuentra el ID Externo en esta línea
ValueError: External ID not found in the system: coches.informe
Esto se debe a que no se ha ajustado ese identificador externo en la vista QWeb y es un dato requerido. Y no
se ha podido hacer porque en la ventana de edición no lo ha permitido. Para ello, hay que dar un pequeño
rodeo.
Localizamos el ID en la vista del informe utilizando el  menú de desarrollador Metadata. (pulsando en el
bichito)
Para cada instalación será un número diferente así que no sirve de nada copiar el número que me sale a mi.
En mi caso tengo asignado el 1368
Nos dirigimos a Ajustes / Técnico / Secuencias e identificadores / Identificadores externos  y crear uno
nuevo.
En Módulo: coches y Identificador externo: informe, Nombre del modelo : ir.ui.view y colocamos el id en
ID de registro: 1368. Al pulsar en guardar se debe completar el Registro con el valor coches.informe
Si volvemos a imprimir el Informe de Coches nos debería salir el informe sin error.
Ahora  se  puede  comprobar  cómo  esta  vez  el  informe  se  muestra  correctamente.  Pero  obviamente,  la
intención es que el informe contenga datos del vehículo que se está consultando. Ya se ha comentado que la
documentación es extensa y se puede consultar en la web de Odoo. En cualquier caso, se mostrará un
ejemplo muy simple dando una serie de claves.
<t t-call="web.html_container">
<t t-call="web.internal_layout">
<t t-name="coches.informe">
<div class="page">
<p>Informe del Coche</p>
<t t-set="coche" t-value="docs"/>
<div>
<strong>Modelo:</strong>
<span t-field="coche.x_modelo"/>
</div>
<div>
<strong>Matrícula:</strong>
<span t-field="coche.x_matricula"/>
</div>
<div>
<strong>Fecha de Alta:</strong>
<span t-field="coche.x_fecha_alta"/>
</div>
<div>
<strong>Pasajeros:</strong>
<span t-field="coche.x_pasajeros"/>
</div>
</div>
</t>
</t>
</t>
Si volvemos a imprimir uno de los coches el resultado será similar al siguiente.
Para interpretar este ejemplo, se van a enumerar una serie de puntos a tener en cuenta:
1.Las primeras llamadas son a contenedores y layouts que son comunes a todos los informes. Son
opcionales, pero en algunos casos el informe no carga si no se incluyen.
2.Cuando se trabaja con un registro del modelo (en este caso, un coche concreto), Odoo utiliza un
identificador llamado docs. Puesto que es tan genérico, es posible crear uno propio para hacer más
legible el código. En el ejemplo se ha utilizado el alias coche.
3.Se pueden utilizar todos los elementos de HTML que se consideren oportunos. En este ejemplo, se
juega con capas, párrafos con strong o etiquetas span.
4.Los campos se referencian con t-field y si nos fijamos, con el alias utilizado (el que sustituye a docs).
Por ejemplo, el modelo de coche es coche.x_modelo
5.Odoo trabaja con Bootstrap con lo que se pueden utilizar sus estilos CSS materializados en clases
para maquetar informes con más calidad. Es interesante consultar otros informes ya creados y para
poder diseñar nuevos a partir de ellos, especialmente si se busca vistosidad.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="47-herencia-de-vistas"></a>

## 4.7 Herencia de Vistas

[⬅ Volver al índice](#índice)

La herencia de vistas permite crear nuevas vistas a partir de otras sin tener que modificar las originales.
Supóngase que se desea modificar la vista de clientes para incluir un nuevo elemento. Por ejemplo, para la
empresa de alquiler, interesa conocer qué tipo de permiso de conducir tiene el cliente. Una posibilidad sería
incluir en la entidad res.partner (la relativa al cliente) un nuevo campo llamado x_permiso_conduccion . El
problema que tiene esta opción es que, al ser una tabla de sistema, en cuanto se lance una actualización, el
sistema borrará de nuevo el campo creado.
Si se acude a la vista de formulario de cliente en modo desarrollador, como se vio en anteriores apartados, es
posible editarla. En este caso, no se editará la vista original sino una heredada. La intención es añadir una
nueva pestaña donde incluir el dato del permiso. Las pestañas en el XML propio de las vistas de Odoo se
identifican por la etiqueta page. Lo que se quiere es introducir la nueva pestaña entre Venta y compra y
Facturación / Contabilidad y Notas internas .
Se crea una nueva vista basada en la anterior, por lo que hay que ir a la sección correspondiente para darla de
alta. El nombre elegido es libre, pero lo lógico es que se siga un orden. Si se va a crear una nueva vista
heredada de res.partner.form lo suyo es proporcionarle un nombre similar a res.partner.form.nuevosdato s
(es decir, manteniendo la ruta de vistas anterior). Será una vista de tipo  Formulario y trabajará sobre el
modelo res.partner. Obviamente, la vista heredada será res.partner.form, pero además entra en juego un
nuevo campo al que no habíamos prestado atención hasta ahora: la Secuencia. Si existen varias vistas del
mismo tipo que hagan referencia a una entidad, se mostrará la que tenga un número de secuencia menor. Si
se observa la vista original, se verá que su número de secuencia es 1, por lo que, si se quiere que se vea esta
vista heredada, hay que darle un valor menor. Solo queda el 0, así que éste será el número de secuencia
elegido para la vista heredada.
Ahora toca lo más arduo, pero a la vez, lo más interesante. En la estructura de la nueva vista se va a utilizar
XPath (https://es.wikipedia.org/wiki/XPath) ¿Para qué sirve XPath? Principalmente para recorrer un archivo
XML con el fin de buscar y seleccionar una parte de ese fichero. Mediante este lenguaje, va a resultar muy
sencillo  encontrar  la  pestaña  Facturación  /  Contabilidad  que  en  el  XML de  la  vista  original  viene
identificada como  sales_purchases. A continuación, se muestra el código para interpretarlo teniendo en
cuenta esta particularidad:
<xpath expr="//page[@name='sales_purchases']" position="after">
<page name="otros_datos" string="Otros datos">
<group>
<field name="x_permiso_conduccion"/>
</group>
</page>
</xpath>
Como puede verse, XPath tiene su etiqueta homónima para poder ser utilizado. En su atributo expr se le da
la expresión de búsqueda y la posición en la que se quiere insertar el código incluido en el elemento.
Respecto al código, nada que no se haya visto antes: una nueva página con un nombre y una etiqueta y un
grupo conteniendo un campo nuevo.
Debería quedar algo similar a lo siguiente:
Si ahora se consulta un cliente, se verá que aparece la nueva pestaña:
En cualquier caso, esto no tiene por qué ser así, ya que esta es la acción de ventana por defecto del modelo.
En algunos casos, la acción de ventana incluye de forma explícita las vistas que tiene que cargar en su
sección Vistas.
Unidad 4: Implantación de Sistemas ERP-CRM en una Empresa

---

<a id="48-creación-de-manuales"></a>

## 4.8 Creación de Manuales

[⬅ Volver al índice](#índice)

Dentro de la labor de mantenimiento y soporte entra la formación del personal. Un usuario del sistema puede
necesitar ayuda en cualquier momento y hay que dotarle de los mecanismos adecuados para solventar el
problema. Generalmente, la formación se enfoca a dos niveles: Una formación integral realizada durante la
implantación del sistema y un soporte o ayuda posterior durante el funcionamiento.
El soporte es más complicado de prever puesto que no se conocen cuáles van a ser las incidencias, aunque se
dispone de una serie de mecanismos de información:
1.Cursos  presenciales  u  online.  Formación  con  contenidos  establecidos  y  fijos.  Se  planeará
adecuadamente ya que implica el abandono temporal del puesto de trabajo por parte de la persona a
formar
2.Creación de documentación. Consiste en realizar todo tipo de documentación mediante diferentes
mecanismos y de dotar al usuario de acceso a ella. Entre este tipo de ayuda se encuentran manuales,
vídeo tutoriales, presentaciones, etc. La intención es que el usuario se forme por su cuenta y busque
la respuesta adecuada. Un recurso muy útil es crear una base de datos de conocimiento con las
preguntas más comunes y sus respuestas dirigiendo al usuario esta documentación antes de plantear
cualquier cuestión que le surja.
3.Soporte. Mediante mecanismos como la videoconferencia, correo electrónico, chat, teléfono, el
usuario contacta con nosotros y se le resuelven las dudas
En cualquier caso, la formación y soporte va a ser imprescindible en las primeras etapas de funcionamiento
del sistema, ya que es cuando el personal tendrá más dudas y problemas. Al ir evolucionando el sistema, el
soporte de ayuda será menor. Para la creación de manuales basta con cualquier editor de texto o suite
ofimática con la que además se puedan crear presentaciones. Existen también multitud de herramientas para
crear  video  tutoriales,  las  cuales  permiten  capturar  el  vídeo  y  audio  desde  el  ordenador  posibilitando
posteriormente una edición del archivo creado (añadiendo comentarios, efectos de sonido, visuales, etc.).
Bibliografía y Webgrafía
San Juan Pastor, C. (2013).
García Lazo, J.J. (2021).
https://www.odoo.com/documentation/18.0/es/  Documentación de Odoo en canales oficiales
https://www.youtube.com/playlist?list=PLF3O845vu6lAU_EtQZWbDnJhTh6vF-equ  Lista  de  vídeos  del
Canal de Youtube de

---
