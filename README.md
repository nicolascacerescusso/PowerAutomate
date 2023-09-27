# Power Automate

## Entornos mas utilizados

- Marketing Automation
- Finanzas
- Backend
- Administration 
- Ticketing
- IT

Debemos ver a Power Automate como esa pieza que permite interconectar distitnas herraminetas para poder crear soluciones digitales complejas.

Existen multiples conectores internos y externos que permiten integrarnos con cualquier otra aplicacion sea o no del entorno Microsoft.

![Conectores](../PowerAutomate/Imagenes/Conectores.jpg)

## Tecnologia RPA (Robotic Process Automation)

Tecnologia que trata de automatizar tareas repetitivas del día a día, tareas que hacemos de forma manual, extraer informacion de ciertos documentos, instroducir datos en una base de datos, gestionar archivos, etc.

Podemos utilizar Power Automate y Power Automate Desktop

## Flujo (Flow)

Es el proceso automatico que podemos llegar a crear con la herramienta

![Imagen Flow](../PowerAutomate/Imagenes/Flow%201.jpg)

La aplicacion PA Cloud nos permitira conectar a cualquier aplicacion que sea publica y que accedamos a través de internet y por lo tanto los flujos que se ejecutaran seran "Flujos de Nube".
La version PA Desktop nos permitita automatizar procesos en nuesrta propia maquina. 
Ambas son compatibles y se pueden combinar.

## Tipos de FLujos

### Flujos de Nube

- Automatizada
- Instantanea
- Programado

#### Automatizados:

Se ejecuta cuando pasa cualquier evento en otra aplicacion que esta en el cloud, sea de Microsoft o externa.
Ej: Correo en el buzon de outlook, subida de fichero a one drive o dropbok, etc.

Todo esto son pequeños disparadores que van a ejecutar flujos de nuevo automatizados, por lo tanto,
a través de eventos que suceden en otras aplicaciones se ejecuta nuestro proceso.

#### Instantaneos:

Que son flujos que se ejecutan manualmente, es decir, que nosotros podemos estar trabajando en nuestro
día a día nuestras tareas y llega a un punto que decimos bueno, ahora podemos ejecutar esta tarea que
la puedo hacer yo a mano, o la puede ser un proceso por mí de forma automatizada.
Tan fácil como darle a un botón, en este caso darle al play y se ejecutará ese proceso sin que nosotros
tengamos que hacer nada.
Por lo tanto, nosotros escogemos el momento y el lugar.

#### Programado:

Y por último, tenemos los flujos de nuevo programados, que son flujos que se ejecutarán cuando nosotros
queramos día, hora, segundo minuto y la periodicidad y la periodicidad que nosotros definamos.


### Flujos de Escritorio

tenemos los flujos de escritorio que, a diferencia de los flujos de nube, son los flujos que se ejecutan en la máquina de cada uno, es decir, en mi ordenador usual de trabajo diario puede ejecutar una serie de flujos con aplicaciones a las que quizá no puedo acceder a través de navegador, por ejemplo. Pues eso serían los flujos de escritorio.
Los flujos de escritorio se pueden conectar perfectamente con los flujos de nube, como ya hemos comentado
anteriormente, y será muy fácil integrarlos entre ellos.

### Flujos de proceso empresarial

Y por último, tenemos los flujos de proceso empresarial, que son una unión de los flujos de nube y los flujos de escritorio.Un flujo de proceso empresarial es una fusión de varios flujos.

## Instalacion de Power Automate

[*Pagina de descarga*] (https://powerautomate.microsoft.com/es-es/)

## Plantillas

ya directamente cuando accedemos a Power Automatic, vemos que en la pestaña de inicio nos sugiere varias plantillas como éstas que tenemos aquí, por ejemplo.
Nos nos da un buscador donde podemos buscar una plantilla por aplicación, tarea o sector.

![Plantillas](../PowerAutomate/Imagenes/Plantillas.png)

## Conectores

todas las aplicaciones que se integran con herramientas de Microsoft 365 y con power automate.
Como podemos ver, aquí tenemos conectores populares y al inicio que son los que más se usan en los
procesos automáticos que hacen los usuarios.

![Conectores](../PowerAutomate/Imagenes/Conectores1.png)


## Entornos
Veremos que cuando iniciemos sesión en nuestro power automate y creemos un flujo por primera vez, todos los flujos y los procesos se van a guardar en el entorno predeterminado.
Tenemos el nombre de nuestra cuenta y tenemos un entorno predeterminado entre paréntesis.
Cualquier cuenta que se creen por primera vez va a tener el entorno predeterminado. Eso significa que todos los flujos que se creen aquí en el apartado mis flujos los va a ver solo la persona que es miembro de esa cuenta, o por lo tanto, la persona que ha creado la cuenta al usuario que lo ha creado, tiene ese entorno predeterminado para él solo, entonces ahí todos los flujos que haya creado los va a ver sólo él, a no ser que los comparta con personas externas o personas dentro de la organización.
Podemos crear más entornos para que sean entornos grupales, es decir, podemos crear por ejemplo un entorno que sea departamento de finanzas y a ese entorno agregarle todos los usuarios del directorio activo que puedan tener acceso a ese departamento de finanzas y por tanto, que tengan ahí todos sus flujos agrupados y puedan ver exactamente como van los procesos automáticos del departamento.

Para crear nuevos entornos debemos dirigirnos a: 

*[Creacion de Entornos]* (https://admin.powerplatform.microsoft.com/environments/)

![Creacion de Entornos](../PowerAutomate/Imagenes/CreaciondeEntorno.png)


## Creacion de flujos desde cero

### Flujo de nuve AUTOMATIZADO

![](../PowerAutomate/Imagenes/Creacion%20flujo%20de%20nube%20automatizado.png)

![](../PowerAutomate/Imagenes/Nombre%20flujo%20de%20nube%20automatizado.png)

Eligiremos un nombre para el flujo y el *desencadenador de flujo automatizado* es decir el evento en alguna aplicacion que desencadena los pasos programados del flujo.

![](../PowerAutomate/Imagenes/resultado%20flujo%20de%20nube%20automatizado.png)


### Flujo de nube INSTANTANEO

Flujo que se desencadena de forma manual segun es necesario, es decir, en el momento del dia que a nosotros nos va mejor. Tareas repetitivas del día que se pueden hacer de manera automatica en el momento del dia que yo prefiera.

![](../PowerAutomate/Imagenes/Creacion%20flujo%20de%20nube%20instantaneo.png)

![](../PowerAutomate/Imagenes/Nombre%20flujo%20de%20nube%20instantaneo.png)

![](../PowerAutomate/Imagenes/resultado%20flujo%20de%20nube%20instantaneo.png)


### Flujo de nube PROGRAMADO

![](../PowerAutomate/Imagenes/Creacion%20flujo%20de%20nube%20programado.png)

![](../PowerAutomate/Imagenes/Nombre%20flujo%20de%20nube%20programado.png)

![](../PowerAutomate/Imagenes/resultado%20flujo%20de%20nube%20programado.png)