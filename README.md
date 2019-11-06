***Sistema de recoleccion y visualizacion de datos de procesos***

Este sistema fue construido para simplificar el trabajo de los analistas de procesos sin la necesidad de tener que aderirse alguna marca espesifica de sensores o algun proveedor de servicios en la nube.
Este sistema permite la subidad de los datos procesos (protocolos de comunicacion ) para que queden alamacenados en una base de datos heterogenia para asi poder ser luego visualizados mediante la misma herramienta 

***Bienvenido***

Estas Instrucciones le permitiran tener un copia del proyecto y tenerlo corriendo en su propia PC.Para mas informacion de como utilizar y instalar el sistema porfavor siga leyendo este documento 

***Prerequisitos de Instalacion***

Para poder Instalar el Sistema UD necesita lo siguiente 

Java version 8 update 231

Link https://www.java.com/es/download/

Zulu 11 (Buscar la version 11.0.5+10)

https://www.azul.com/downloads/zulu-community/?&architecture=x86-64-bit&package=jdk


***Instalacion*** 

Se presenta una guia paso a paso de como instalar el Sistema 

**Paso 1 Descargas para la version 5.2 del sistema** 

Descargar EasyModbusSimulator

Descargar PacketSender 

Descargar SRVDP

**Paso 2 Forma de uso** 

Una vez descargados los 3 programas anteriores porfavor inicie el EasyModbusSimulator y el PacketSender que se encuntran dentro de la seccion code de Github

Despues de iniciar los 2 progrmas anteriores porfavor copie el archivo SRVDP y peguelo en su ESCRITORIO 

Una vez iniciado el PacketSender porfavor donde dice Adress escriba local host y donde dice port escriba 8050

Una vez completado el paso anterior porfavor complete donde dice Package Name con la informaicon que desee

Una vez iniciado el EasyModbusSimulator porfavor clickee donde dice holding registers y cambie las 10 primeras filas con solo numeros

Despues vaya al simbolo del Sistema e inicie una consola 

Dentro de la consola porfavor escriba java -jar SRVDP y espere a que se ejucute el sistema 

Para finalizar la prueba porfavor cierre la ventana de la consola 


**Paso 3 Revisar los resultados (Solo por esta iteracion)**

Porfavor vaya a la direccion https://portal.azure.com/#home

Inicie secion dentro del portal de azure en el apartado que dice iniciar secion

En el apartado de busqueda porfavor seleccione todo los recursos

Una vez seleccionado todo los recursos en la venta que se abre oprima sobre la opccion que dice: hito-3

En el buscador que se abrira porfavor oprima en Explorador de Datos

Una vez echo los pasos anteriores donde dice SQL API oprima donce dice PLC y luego en DATA

Para ver los datos de UDP oprima donde dice PLC2 y luego en DATA UDP

En la ventana que le aparecera oprima sobre alguna de las casillas enumeradas para poder ver el dato alamacenado


***Este Sistema Fue construido con las siguiente Herramientas*** 

Eclipse IDE 219 - Para el desarrolo de la aplicacion 

Maven - Para el manejo de dependencias

Microsoft Azure CosmoDB - Para el almacenamiento de datos y visualizacion momentanea 

***Versiones*** 

Para las versiones se utilzo GitHub. Para poder versiones anteriores del proyecto y su forma de uso porfavor dirajase al apartado de code de este repisotorio 

***Autores***

Gianluca Garofalo - Desarrollador y Tester del Sistema de recolecion y visualizacion de datos de proceso


