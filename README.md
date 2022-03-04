# Fasores-App-Inventor-
Creación de una Aplicación móvil en App inventor para la conversión de fasores (rectangular-polar) y operaciones con fasores.

UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

![image](https://user-images.githubusercontent.com/94182617/156445018-44072653-2317-44c3-bc03-35354bf25c0d.png)

DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA

FUNDAMENTOS DE CIRCUITOS ELECTRICOS

CREACIÓN DE UNA APLICACIÓN MÓVIL EN APP INVENTOR PARA LA CONVERSIÓN DE FASORES (RECTANGULAR-POLAR) Y OPERACIONES CON FASORES.

MARTÍN AUGUSTO CORONEL MOREIRA

TEMA: Creación de una Aplicación móvil en App inventor para la conversión de fasores (rectangular-polar) y operaciones con fasores.

1.	OBJETIVOS

1.1 Objetivo General
Diseñar una aplicación acerca de la conversión y operación de fasores en App Inventor.

1.2 Objetivos Específicos
-	Determinar y analizar las fórmulas de conversión de fasores juntos con sus operaciones.
-	Comprender el uso App Inventor para la creación de aplicaciones móviles.
-	Crear la aplicación acerca de fasores aplicando sus respectivas fórmulas para una correcta conversión.

2.	MARCO TEÓRICO

2.1 Qué es App Inventor?

App inventor es un entorno de programación que permite crear aplicaciones móviles de forma muy sencilla, por lo que es accesible a todo el mundo, incluso a los niños. App inventor está diseñado para programar aplicaciones sencillas, pero totalmente funcionales para smartphones y tablets de dispositivos Android o iOS. El objetivo de App Inventor es democratizar el desarrollo de software, permitiendo a los jóvenes dejar de ser consumidores pasivos de tecnología para convertirse en creadores activos de tecnología. Para ello, App Inventor se ha creado como un software de programación profundamente visual e intuitivo. Funciona con un lenguaje de programación basado en bloques, al estilo de un juego de construcción Lego (pero en formato digital).

La herramienta proporciona una librería con miles de bloques gráficos, con formas y colores diversos. Cada uno de ellos, lleva asociado un código de programación, por ejemplo: listar, ejecutar, abrir otra pantalla o mostrar un mensaje. Estos bloques pueden agruparse y combinarse en cadena para ir creando la App deseada. ¿El resultado? Un recién iniciado en App Inventor puede tener lista su primera aplicación (sencilla) en media hora. App Inventor es una herramienta creada de forma conjunta por el Instituto Tecnológico de Machasuset (MIT) y Google Educatión. Su primera versión fue lanzada en 2010 por un pequeño equipo de personal y estudiantes del MIT, dirigido por el profesor Hal Abelson, que en aquel entonces se tomaba un año sabático de Google para ejercer de profesor universitario. En 2012 Google dio por finalizado el proyecto App Inventor y cedió su desarrollo al MIT, que ha seguido desarrollando mejoras, aumentando su compatibilidad y enfocándose en hacer accesible la programación a cualquier persona. Gracias a ello, App Inventor cuenta con más de un millón de usuarios mensuales únicos procedentes de 195 países que han creado 30 millones de aplicaciones.

(Serrano)

2.2 Creación de la aplicación 

Paso 1: Ingresar a la página oficial de App Inventor:
 
 ![image](https://user-images.githubusercontent.com/94182617/156445257-0457b645-0935-4adb-b900-e4d1c6a6390a.png)

Paso 2: Presionar en crear una aplicación e ingresar con una cuenta de mail.

![image](https://user-images.githubusercontent.com/94182617/156445298-070bdb04-8f51-4a4d-b2b8-22d81cca757f.png)

Paso 3: Se comienza creando un nuevo proyecto, luego se procede a realizar en programa de manera ordenada. Primero se va a diseñar el procedimiento para poder pasar a una forma polar.

![image](https://user-images.githubusercontent.com/94182617/156445326-1977859b-3f85-469a-b3f5-85e19f2df7b2.png)

En este caso son dos entradas, en el procedimiento hay una variable global por si hay una comprobación por si ingresa un numero imaginario, se reemplaza la j por un valor nulo para que solamente tome el número y no la letra, la función ‘trim’ es para cortar los espacios adicionales. En la siguiente variable el primer resultado va a ser para hallar la raíz cuadrada de ambos números que van a ser elevados al cuadrado en el cual ambos números se van a sumar y el formato decimal será de dos decimales para la respuesta. Para el resultado número dos de la variable local va a ser el mismo procedimiento, pero se va a hallar el otro valor el cual se determina con la tangente inversa. Finalmente se va a concatenar con un join para hallar el primer resultado con el segundo.

Paso 4: Luego se creará el procedimiento para pasar a su forma rectangular.

![image](https://user-images.githubusercontent.com/94182617/156445371-ceac8fb2-13a5-4204-9d4f-e669c3b189c3.png)

El procedimiento es parecido al anterior, comienzo con dos variables globales, pero en este caso es para hallar el Coseno y Seno, el cual va a tener su ángulo interno y todo esto multiplicado por la amplitud tal cual indica la formula y su resultado dará un numero con máximo dos decimales. Luego se hace una concatenación para obtener el resultado en el cual se hace una verificación con un if que se contiene un signo negativo, de tal manera que primero vaya el signo negativo, luego el numero imaginario y se va a reemplazar la variable global para quitarle el signo negativo y colocarlo delante de la j con remplazamiento nulo para que no ocupe cambio y si no corresponde a un signo negativo entonces se va a colocar un signo positivo delante.

Paso 5: Se procede a realizar las operaciones respectivas en el cual se colocar un procedimiento para poder poner el tipo de operación que se va a realizar, usando un solo bloque, incluyendo los cuatro valores que son dos reales y dos imaginarios (suma y resta entre rectangulares - multiplicación y división entre polares):

•	Suma:
 
 ![image](https://user-images.githubusercontent.com/94182617/156445416-70b86b64-e804-45af-a0ba-6e6883ff978d.png)

Para sumar el tipo de operación es suma y se realiza el procedimiento en el cual se va a poner una variable global n1 y n2, el cual va a tomar variable del número imaginario y si se coloca el símbolo de una j lo va a quitar y reemplazar por una A para que solamente tome el número, de igual manera en el imaginario dos. Para el resultado se va a concatenar, en este caso se va a sumar el valor real del número uno y dos, de igual manera entre números imaginarios, en este caso también se va a comprobar si es que contiene un signo negativo se hará una concatenación por signo negativo para colocarlo delante del valor, y se va a reemplazar el negativo por una j para que nos del resultado, luego si no contiene un numero negativo se va a colocar en el formato donde la j va a ser positiva seguida por el número.

•	Resta:
 
 ![image](https://user-images.githubusercontent.com/94182617/156445458-8e046f46-f971-45e4-a375-284f694fbaed.png)

Para la resta va a ser el mismo procedimiento que el de la suma, se declaran dos variables, se le va a reemplazar el símbolo j por un valor nulo para que solamente tome el número, se va a hacer una concatenación con el ‘join’ en el cual se hace la resta entre el número uno y dos de números reales, se pone un ‘if’ para comprobar el segundo número que son los imaginarios, si es que su resta contiene un signo negativo se va hacer una concatenación primero con el signo negativo y reemplazar el valor de esta resta del signo negativo a una j para que vaya en un correcto orden, en caso de que sea positivo se hará lo mismo que en la suma, el signo más con la j y al final el valor.

•	Multiplicación:

![image](https://user-images.githubusercontent.com/94182617/156445493-01d6b566-2810-4dfa-95f6-37e38c3a8d86.png)

Para realizar esta operación se va a realizar entre polares en el cual se multiplica entre números reales, en el medio el signo de ángulo y luego se suman los ángulos para así obtener el resultado final.

•	División:

![image](https://user-images.githubusercontent.com/94182617/156445665-f54f19ae-3b2f-4af7-945d-dd7207f8c8d6.png)

Esta operación es muy parecida a la anterior, la diferencia es que aquí se divide ambos números reales y se restan los ángulos entre sí, en caso el tipo operación que se esté realizando sea diferente a la que se coloque aparecerá un mensaje de tipo error.

Paso 6: Se realiza otro tipo de procedimiento para hacer el cambio en el cual se quiera verificar la operación que se quiera realizar.

![image](https://user-images.githubusercontent.com/94182617/156445700-80b507bb-c968-4350-900e-c8bf3f640491.png)

Se realiza un ‘check’ para seleccionar una de las 6 operaciones que permite realizar el programa para tomar el valor de la casilla seleccionada, se hace una comprobación si el ‘checkbox’ del componente toma el componente global en ‘when any checkbox’  para poder seleccionar una de las opciones que queremos operar, la condición sería de que si el ‘checkbox’ del componente que se está haciendo el cambio es revisado devuelve un true e inicializa la variable local lista, que va a contener todas la opciones y lo que va a hacer es remover de esta lista el ‘check’ que ha sido seleccionado en el evento para que los demás se vuelvan al estado de la casilla no marcada, para esto se toma en ‘for each’ de la lista global y el ‘check’ de todos los elementos restantes menos el que se ha removido va a estar en false, de este modo se hace una comprobación del ‘check’ que se quiere activo.

Paso 7: A continuación, se desarrolla el evento del ‘click’ para definir las funciones al momento de utilizar la app.
 
![image](https://user-images.githubusercontent.com/94182617/156445755-31d8e893-50ff-43eb-97ba-15601609766f.png)

![image](https://user-images.githubusercontent.com/94182617/156445773-26e77ef8-112c-46dc-be99-20d7961c3b17.png)

![image](https://user-images.githubusercontent.com/94182617/156445797-28bc9a13-a88e-4bde-b656-53d4269e9dc2.png)

![image](https://user-images.githubusercontent.com/94182617/156445818-e37dd5c6-0dfc-4775-847a-960b7be5ee2d.png)

En este evento tenemos dos condiciones porque vamos a utilizar un ‘switch’ que se le puso ‘Set_Op’ para las operaciones el cual se podrá activar mediante un interruptor para poder realizarlas, si se encuentra activo te manda a una condición en la que te dice que si el componente está vacío aparecerá el cuadro en pantalla, luego se pone otro ‘if’ en el caso de que se escoja una de las dos opciones sea polar o rectangular realice la operación requerida. En caso de que el Set_Op no esté activo va a tomar el procedimiento para poder realizar las operaciones de suma, resta, multiplicación y división, y se realiza lo mismo que vimos antes y finalmente si todos los campos están vacíos en el ‘LB_Results’ va a colocar campos vacíos.  

Paso 8: Como paso final se implementa el manejo de los cambios del interruptor.

![image](https://user-images.githubusercontent.com/94182617/156445854-3d0bc0ee-e611-4d80-863d-077b79c42fdc.png)

![image](https://user-images.githubusercontent.com/94182617/156445873-5e5106b7-5f30-495a-9e96-b7104cac85bd.png)

Aquí se aplican las funciones cuando se hace el cambio de activar o desactivar el interruptor, que es parecido al momento del botón ‘click’, si está activo, va a mandar a un ‘for each’ de la lista para que muestre los ‘check’ que corresponden a procedimiento que se va a realizar, en el primer caso va a mostrar el polar y rectangular para poder determinar si es true o false para que sean o no visible junto con sus funciones y operaciones. En caso opuesto de que el interruptor esté desactivado va a tomar el segundo valor, se vuelve a llamar a la lista ‘for each’ es lo contrario, en este caso se van a poder realizar las operaciones y la parte de polar y rectangular ahora van a estar en false para que se presenten las cuatro operaciones matemáticas. Finalmente, el último ‘for each’ es para colocar todos los campos de texto y vaciarlos cada vez que se haga ese cambio del ‘switch’ por el interruptor y el ‘LB_result’ se va a encargar de hacer un borrado cada vez que el interruptor se active. 

Paso 9: Finalmente se realiza el diseño de la aplicación y así es como queda:

![image](https://user-images.githubusercontent.com/94182617/156445907-cb169ef2-e3d3-4b50-9f60-d30c39cdca4d.png)

2.3	Resultados

![image](https://user-images.githubusercontent.com/94182617/156446186-9c28fdeb-560a-42ab-960d-6de0be2ce4a9.png)
![image](https://user-images.githubusercontent.com/94182617/156446201-f4e322e9-32e4-4c90-83f8-416b1e03e88f.png)
![image](https://user-images.githubusercontent.com/94182617/156446221-7159b2c9-0b57-43c3-935c-0de3d3680912.png)

![image](https://user-images.githubusercontent.com/94182617/156446242-735c36e0-ac9a-47a6-991d-ef1c0b49169b.png)
![image](https://user-images.githubusercontent.com/94182617/156446250-8b0e2b33-d384-4ebd-a8a7-ecbff8bbb094.png)
![image](https://user-images.githubusercontent.com/94182617/156446262-6c09d1ca-d92b-44ac-807d-5bc65fb9ac2f.png)

![image](https://user-images.githubusercontent.com/94182617/156446274-6b456dff-d0f9-4055-a19d-ac7a161efb97.png)
![image](https://user-images.githubusercontent.com/94182617/156446282-3e9a81c3-45b5-413c-9ddc-b183e0907791.png)
![image](https://user-images.githubusercontent.com/94182617/156446288-7f5caf1b-9ff0-4bef-bede-abd8c5feaaf1.png)

2.4 Aplicación
Apk: 


3. Video

https://www.youtube.com/watch?v=1zFUUoq-x9o

4.	Conclusiones:

•	Al crear una aplicación en App Inventor es evidente notar que éste mecanismo para la creación de aplicaciones brinda facilidad y comodidad al momento de diseñar la app y poder utilizarla como una aplicación para el teléfono. 

•	Esta aplicación se trata de una herramienta web de desarrollo para iniciarse en el mundo de la programación la cual brinda una construcción sencilla y eficiente del programa con un código de fuente abierto.

•	Se establece que esta aplicación sirve para indicarle al cerebro del dispositivo móvil qué queremos que haga, y cómo, en el caso de esta aplicación su función es obtener el resultado de conversiones y operaciones de fasores, la cual es una aplicación simple que la puede usar cualquiera.

5.	Recomendaciones:

•	La aplicación se puede descargar fácilmente, modificar e incluso crear su propia versión de la herramienta lo que beneficia enormemente a la comunidad. Las aplicaciones desarrolladas pertenecen al creador. No hay que pagar dinero por la licencia por crear con MIT App Inventor.

•	Se recomienda utilizar esta aplicación en un sistema operativo Android para su correcto funcionamiento e ir probando los programas.

•	Es importante realizar pruebas de la aplicación que se va generando para ello se necesita tener un dispositivo móvil con conexión a internet y descargar en el móvil una aplicación llamada “MIT AI Companion”. 

5.	Bibliografías y Referencias: 

Serrano, A. S. (n.d.). ¿Qué es App Inventor y para qué sirve? Space Techies. Retrieved March 1, 2022, from https://www.spacetechies.com/que-es-app-inventor-y-para-que-sirve/

Abelson, H. A., & Friedman, M. F. (2010, December 15). MIT App Inventor | Explore MIT App Inventor. MIT App Inventor. Retrieved March 2, 2022, from https://appinventor.mit.edu/







