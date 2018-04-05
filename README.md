# MonitorIoTdeIncendios

#NXPchallenge

Equipo : Sistemas Inteligentes Multimedia 

Andres Alberto Lavariega Castellanos
Fabian Salinas López 
Renato Armando De S. Palomares Navarro

Abril 2018


#Generalidades

La Asociación Mexicana de Rociadores Automáticos Contra Incendio (AMRACI) informó que el 53% de los incendios que se registran en el país sucede en los hogares y es durante las fiestas navideñas cuando se incrementan.

Señaló que de acuerdo con estudios, más de 20,000 incendios en el país se dieron en casa habitación, y de esos 41% se generó por un cortocircuito, debido al uso de árboles de navidad, series luminosas, extensiones, velas, fuegos artificiales, entre otros.

Los incendios registrados en 2014 en casas habitación y empresas han costado al país alrededor de 4.8 billones de pesos, según cifras dadas a conocer por la industria aseguradora y la de fabricadores de rociadores automáticos contra incendios. 

Esta cifra equivale a 6 por ciento del Producto Interno Bruto, pero pudo ser menor de existir una mejor cultura de prevención fortalecida con la tecnología necesaria, dijo Carlos Morett, presidente de la Asociación Mexicana de Rociadores Automáticos contra Incendios (AMRACI).  Datos proporcionados por ambas agrupaciones destacan que la cantidad de incendios que ocurren en el país aumenta 10 por ciento año con año. Morett enfatizó en tan solo en las tres principales ciudades del país, el Distrito Federal, Monterrey y Guadalajara, se reportan alrededor de 15 mil incendios al año, mismos que dejan pérdidas económicas importantes. En atención a este fenómeno, la AMIS y la AMRACI establecieron un convenio de colaboración que tiene como objetivo fomentar la cultura ante incendios entre las empresas y familias, de manera que se logre disminuir la cantidad de estos siniestros. 

#Proyecto propuesto

Se propone utilizar la tarjeta LPC54018 de NXP con un sensor de humo en casa habitación, oficinas, escuelas, hospitales y otros establecimientos con la finalidad de monitorear en tiempo real la existencia de humo provocado por un incendio.

Esta tarjeta estará conectada al servicio de Amazon Web Service donde al momento de recibir una alarma por humo envíe una alerta a la estación de bomberos más cercana. 

Además de integrar una alarma auditiva (bocina) y visual (sirena) con la finalidad de alertar del peligro a las personas que concurren en la instalación.

El propósito de este proyecto es de optimizar el proceso de contingencia para atender un incendio, reduciendo el tiempo de reporte y reacción, permitiendo al cuerpo de bomberos atender el contingente de una manera más eficiente.

Este sistema también le ofrece al cuerpo de bomberos acceso a los datos de las ocurrencias de incendio y la posibilidad de gestionar la información para mantener un registro de la información y tener un mejor control de la cantidad de incendios y un mapa de los mismos.

#Metas
Utilizar la tecnología NXP y Amazon web service para conectar los servicios del proyecto.
Apoyar al cuerpo de bomberos y a la sociedad en reducir sus tiempos de respuesta en que un incendio es atendido evitando en medida de lo posible pérdidas humanas. 
Especificaciones

Se pretende implementar las tarjetas en las instalaciones y en cada estación de bombero. Para la detección del humo se podrá hacer uso de sensores como el MQ135, que además de detectar humo, también es sensible a amoniaco, benceno, humo, Co2 y otros gases tóxicos.

En una segunda fase se propone la integración de una aplicación móvil para notificar del incendio a las personas que concurren el lugar o vecinos.

La plataforma debe tener la posibilidad de utilizar protocolos estándar con la finalidad de poder servir de plataforma para otros servicios como seguridad municipal, robos, denuncias u otros.

#Referencias

Economiahoy.mx , 24/12/2016 http://www.economiahoy.mx/nacional-eAm-mx/noticias/8048190/12/16/El-53-de-los-incendios-en-Mexico-ocurre-en-los-hogares.html

19:42 Braulio Carbajal , http://m.milenio.com/negocios/danos_incendios_Mexico-incendios_Mexico-perdidas_incendios_Mexico_0_520148275.html,http://m.milenio.com/negocios/danos_incendios_Mexico-incendios_Mexico-perdidas_incendios_Mexico_0_520148275.html

TECHNICAL DATA MQ-135 GAS SENSOR , https://www.olimex.com/Products/Components/Sensors/SNS-MQ135/resources/SNS-MQ135.pdf

