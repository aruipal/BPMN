# BPMN
### BUSINESS PROCESS MODEL AND NOTATION
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/1_Modelo%20de%20proceso.JPG" alt="modelo" width="900" />

***- Modelo y Notación de Procesos de Negocios***

### BPMN destaca por:
* Estar ampliamente extendido.
* Ser facilmente comprensible y altamente expresivo.
* Ser un estandar ISO.
* Facilitar la automatización.
* Existencia de multiples herramientas que manejan este estándar, lo que facilita el intercambio de información.

### NOTACIÓN BASICA
* Se realiza mediante diagramas que emplean un conjunto reducido de objetos.
* Se pretende que los procesos descritos sean fáciles de entender por todos los usuarios implicados.

### EVENTOS BÁSICOS
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/2_Eventos%20basicos.JPG" alt="basico" width="600" />

### ACTIVIDADES
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/3_Actividades.JPG" alt="basico" width="600" />

### DECISORES
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/4_Decisores.JPG" alt="basico" width="600" />

### OBJETOS DE CONEXIÓN
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/5_Conexion.JPG" alt="basico" width="600" />

### TOKEN
- Concepto que se utiliza para simular y probar el comportamiento de los procesos.
- Se “mueven” a través del flujo de secuencia y pasan por los diferentes objetos del proceso.
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/6_Token.JPG" alt="basico" width="900" />

### INSTANCIA
- Proceso concreto en la realidad. Por ejemplo, el pedido realizado por uncliente determinado en un instante concreto.
- Algunos procesos se instancian sólo un par de veces al año mientras que otros se pueden instanciar varias veces al día.

### PARTICIPANTES
- Los Pools y Carriles indican quién es el responsable de la ejecución de las actividadesdel proceso.
- El flujo de secuencia no puede cruzar los límites del pool pero sí los límites de los carriles.
- La comunicación entre pools se lleva a cabo mediante flujos de mensajes.
- Debido a que los proceso de trabajo se representan desde el punto de vista de nuestra organización,
- los actores externos se representan mediante pools colapsados, ya que no interesa ver su detalle.
- Un pool colapsado es una “caja negra” de la que entran y salen mensajes.
- Es importante tener en cuenta que el flujo del proceso de trabajo estará siempre
contenido en el pool de nuestra organización.
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/7_Participantes.JPG" alt="basico" width="900" />
- Ejemplo:
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/8_Participantes.JPG" alt="basico" width="900" />

### Eventos de mensaje
- representan la “entrada a nuestra organización” o “salida desde nuestra organización” de un mensaje.
- Se utilizan entre nuestra organización y otros actores externos.
- Representan tanto envíos postales o e-mails como llamadas telefónicas, bienes, dinero, etc.
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/9_Eventos%20de%20mensaje.JPG" alt="basico" width="600" />
- Ejemplo:
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/10_Eventos%20de%20mensaje.JPG" alt="basico" width="900" />

### Eventos de tiempo
- se utiliza cuando queremos representar que se ha producido una condición relacionado con el tiempo.
- Representan fechas, horas, momentos o periodos.
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/11_Eventos%20de%20tiempo.JPG" alt="basico" width="600" />
- Ejemplo:
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/12_Eventos%20de%20tiempo.JPG" alt="basico" width="900" />

### EVENTOS MULTIPLE
* El evento múltiple permite manejar varios eventos alternativos con un único símbolo.
* Como evento de entrada (de inicio o intermedio) se requiere únicamente la presencia de uno de los eventos para disparar el proceso.
* Como evento de salida (intermedio o fin) dispara todos los eventos asociados.
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/13_multiple.JPG" alt="multiple" width="600" />
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/14_multiple.JPG" alt="multiple" width="600" />

### RESUMEN
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/resumen1.JPG" width="600" />
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/resumen2.JPG" width="600" />
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/resumen3.JPG" width="600" />
<img src="https://github.com/aruipal/BPMN/blob/main/recursos/resumen4.JPG" width="600" />

### DECISOR COMPLEJO

### ACTIVIDADES CON EVENTOS SOBREPUESTOS




