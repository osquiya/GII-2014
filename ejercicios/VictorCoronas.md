<h1> Victor Coronas Lara </h1>

#Clase del 29 de septiembre de 2014

#Ejercicios

* [+]Ejercicio 1: 
 - A) Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.

     Para realizar este ejercicio he usado el siguiente [servidor](http://www.lambda-tek.com/N12000PRO-Thecus-N12000PRO-12-Bay-NAS-Intel-Xeon-E3-1275-3-4GHz-Quad-Core-8GB-DDR3-SDRAM-3-x-1GbE-upgradeable-to-10GbE-SATA-III-and-SAS-6G-~csES/B1611704&origin=gbaseES14.4?gclid=CjwKEAjwk_OhBRD06abu3qSoxlwSJACt7sZ78IJ-fmymrW9xgsNDK9HuX8r032jrGU7uTbTSydYPahoC6SPw_wcB).

    Este servidor tiene un coste de:
    - 3647.38€ precio neto
    - 3039.48€ precio bruto

####Cálculo de la amortización en 4 años:
    Vamos a deducirnos el 25% por año que es lo máximo que podemos.
     - Primer año: 3039.48€ * 25% = 759,87€  
     - Segundo año: 3039.48€ * 25% = 759,87€ 
     - Tercer año: 3039.48€ * 25% = 759,87€  
     - Cuarto año: 3039.48€ * 25% = 759,87€  

####Cálculo de la amortización en 7 años: 
    Vamos a ir deduciendonos cada año un cierto porcentaje, pero los primeros años más ya que es inversión.  
     - Primer año: 3039.48€ * 25% = 759,87€ 
     - Segundo año: 3039.48€ * 25% = 759,87€  
     - Tercer año: 3039.48€ * 15% = 455,922€  
     - Cuarto año: 3039.48€ * 15% = 455,922€  
     - Quinto año: 3039.48€ * 10% = 303,948€  
     - Sexto año: 3039.48€ * 5% = 151,974€  
     - Séptimo año: 3039.48€ * 5% = 151,974€


* [+]Ejercicio 2: 
 - A) Usando las tablas de precios de servicios de alojamiento en Internet y de proveedores de servicios en la nube, Comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) si la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.
 
    Para la comparación voy a utilizar dos de los servicios más conocidos:  [Google Compute Engine](https://cloud.google.com/products/compute-engine/) y [Amazon EC2](http://aws.amazon.com/es/ec2/)

    Características de la máquina de Google n1-standard-1-d:
    * CPU: 1 core
    * Memoria: 3,75GB
    * Disco duro: 420GB
    * Precio por hora: 0,114834658 €/hora
    
    Características de la máquina de Amazon m3.medium:
    * CPU: 1 core
    * Memoria: 3,75GB 
    * Disco duro: 410GB
    * Precio: 0,126714105 €/hora

   ####Cálculo de los precios al 1% de uso:
    Google: 0,114834658 * 87,6 horas = 10,105449904 €.
    Amazon: 0,126714105 * 87,6 horas = 11,15084124 €.  
      
    
   ####Cálculo de los precios al 10% de uso:
    Google: 0,114834658 * 876 horas = 100,595160408 €
    Amazon: 0,126714105 * 876 = 111,00155598 €
      


* [+]Ejercicio 3: 
 - A) ¿Qué tipo de virtualización usarías en cada caso? Comentar en el foro
   [Comentario en el foro](https://github.com/JJ/GII-2014/issues/71)

 -Si queremos alojar varios clientes en un servidor, utilizaría la virtualización a nivel de sistema operativo, ya que esta nos permite aislar las cuentas de cada usuario por separado, nos permite a la vez que el anfitrión y el cliente usen el mismo sistema operativo pero aislandose entre si y por último el administrados de sistema puede gestionar todo.
  
 -Para la creación de un sistema eficiente de web + middleware + base de datos, elegiría una virtualización plena, ya que nos permite virtualizar todo el sistema por completo, para la ejecución tanto de sistemas operativos, así como cualquier tipo de aplicación.
  
 -Para un sistema de prueba de software e integracion continua, yo usaria la virtualizacion de entornos de desarrollo para probar en las diferentes versiones de forma más rápida, ya que consigue reproducir cada entorno de producción de la forma parecída posible.

 - B) Crear un programa simple en cualquier lenguaje interpretado para Linux, empaquetarlo con [CDE](http://www.pgbovine.net/cde.html) y probarlo en diferentes distribuciones.

  -He usado un programa de prueba muy sencillo, usa en la asignatura DAI en el lenguaje PYTHON.
  [Programa de prueba](https://www.dropbox.com/s/xkl4fdvnuw4lpuy/ejer1.py?dl=0)
  Se descargar el archivo CDE, se le dan permisos de ejecución y lo ejecutamos junto con le programa.
[imagen1](https://www.dropbox.com/s/zdpyscmwd5bfupu/Captura%20de%20pantalla%202014-10-16%20a%20la%28s%29%2009.50.17.png?dl=0)
[imagen2](https://www.dropbox.com/s/a1lb65uf082rtcb/Captura%20de%20pantalla%202014-10-16%20a%20la%28s%29%2009.47.01.png?dl=0)

* [+]Ejercicio 4:
 - A) Hacer el tutorial de línea de órdenes de docker para comprender cómo funciona.
 - [imagen1](https://www.dropbox.com/s/z9bk890uv05nqth/Captura%20de%20pantalla%202014-10-16%20a%20la%28s%29%2009.58.31.png?dl=0)

#Clase del 30 de septiembre de 2014

#Ejercicios

* [+]Ejercicio 5
 - Instala el sistema de gestión de fuentes git.
 - Una vez instalado git "sudo apt-get install git" comprobamos que esta instalado con la orden "git version".
  [imagen1](https://www.dropbox.com/s/o9k9vpk29dvc3d9/Captura%20de%20pantalla%202014-10-16%20a%20la%28s%29%2010.02.40.png?dl=0)

* [+]Ejercicio 6
 - A) Crear un proyecto y descargárselo con git. Al crearlo se marca la opción de incluir el fichero README.
  
-En mi repositorio de [GITHUB](https://github.com/VictorCoronas) he creado un nuevo [proyecto "Prueba"](https://github.com/VictorCoronas/Prueba).

    touch README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/VictorCoronas/prueba.git
    git push -u origin master
 
 - B) Modificar el readme y subir el fichero modificado.
  
-He realizado una modificación del archivo [README.md](https://github.com/VictorCoronas/Prueba/blob/master/README.md).


* Ejercicio 7
 - A) Crear diferentes grupos de control sobre un sistema operativo Linux. Ejecutar en uno de ellos el navegador, en otro un procesador de textos y en uno último cualquier otro proceso. Comparar el uso de recursos de unos y otros durante un tiempo determinado.

Voy a usar el paquete cgroup-bin puesto permite un control por línea de órdenes algo más sencillo sin necesidad de trabajar directamente con sistemas de ficheros virtuales.

En primer lugar lo que debemos hacer es instalar este paquete:

    sudo apt-get install cgroup-bin

Lo siguiente es crear un grupo que contendrá varios subgrupos. Para crearlo usamos la siguiente orden:

    sudo cgcreate -a francisco -g memory,cpu,cpuacct:ejercicio7

Este grupo se encarga de controlar la memoria, CPU y de contabilizar el uso de recursos de CPU y da permiso al usuario francisco para que trabaje con el.

Creado el grupo, vamos a crear varios subgrupos: uno encargado de ejecutar el navegador, otro de ejecutar el procesador de textos y otro de ejecutar el cliente de correo electrónico Mozilla Thunderbird.

    sudo cgcreate -g memory,cpu,cpuacct:ejercicio7/navegador
    sudo cgcreate -g memory,cpu,cpuacct:ejercicio7/editor
    sudo cgcreate -g memory,cpu,cpuacct:ejercicio7/correo

Con cgexec asignamos los procesos de cada subgrupo.

    sudo cgexec -g memory,cpu,cpuacct:ejercicio7/navegador firefox
    sudo cgexec -g memory,cpu,cpuacct:ejercicio7/editor gedit
    sudo cgexec -g memory,cpu,cpuacct:ejercicio7/correo thunderbird

Para comparar el uso de recursos visualizamos los resultados en:

    /sys/fs/cgroup/(memory|cpu|cpuacct)/ejercicio7/(navegador|editor|correo)

Resultados para el navegador:

    - cpuacct.usage --> 2943724935
    - cpuacct.stat:
           user 244
           system 38
    - cpuacct.usage_percpu --> 422363850 1046168504 1273224787 205078078 
    - memory.max_usage_in_bytes --> 327741440

Resultado para el editor:

    - cpuacct.usage --> 2345308237
    - cpuacct.stat:
           user 201
           system 21
    - cpuacct.usage_percpu --> 747258934 1008912121 407984020 181153162 
    - memory.max_usage_in_bytes --> 153321472
    
Resultados para el correo:

    - cpuacct.usage --> 0
    - cpuacct.stat:
          user 0
          system 0
    - cpuacct.usage_percpu --> 0 0 0 0
    - memory.max_usage_in_bytes --> 0

 - B) Calcular el coste real de uso de recursos de un ordenador teniendo en cuenta sus costes de amortización. Añadir los costes eléctricos correspondientes.
 
He localizado una página web que explica muy bien el consúmo eléctrico de un ordenador aproximado que tiene durante un sin desconectarlo de la corriente,

En primer lugar hay que [LeanTricity](http://www.leantricity.es/es/2012/07/11/cuanta-energia-gasta-un-ordenador-aproximaciones/)
Basandome en estos valores de la página paso a realizar el calculo de costes de amortización.

Coste eléctrico por año:

    365 días x (0,437 kWh + 0,1524 kWh) = 215 kWh (Aproximación)
    
    0,20 € * 215 kWh = 43€/año (Anual)

La vida media de un PC esta rondando los 5 años y suponiendo un precio de 1000€.

Amortización:

     Año 2014: 120€ + 43€ = 143€
     Año 2015: 200€ + 43€ = 243€
     Año 2016: 200€ + 43€ = 243€
     Año 2017: 200€ + 43€ = 243€
     Año 2018: 200€ + 43€ = 243€
     Año 2019: 57€ + 43€ =  100€
     
     Precio total: 1215€

  
* Ejercicio 8
 - A) Discutir diferentes escenarios de limitación de uso de recursos o de asignación de los mismos a una u otra CPU.
 
Las funciones de control de recursos de Oracle Solaris permiten que se comparta el ancho de banda entre las VNIC en la red virtual de un sistema. También puede utilizar funciones de control de recursos para asignar y gestionar el ancho de banda en una interfaz física sin VNIC ni máquinas virtuales. 
[Enlace a oracle](http://docs.oracle.com/cd/E26921_01/html/E25833/gewag.html)

 - B) Implementar usando el fichero de configuración de cgcreate una política que dé menos prioridad a los procesos de usuario que a los procesos del sistema (o viceversa).

Para cambiar la prioridad a los procesos de usuario y a los del sistema debemos modificar el archivo:

    /etc/cgconfig.conf

Antes de empezar a modificar nada, tenemos que crear dos grupos, uno que sería para lo usuarios y otro para los procesos.
Para ello hacemos:

    sudo cgcreate -g memory,cpu,cpuacct:usuario
    sudo cgcreate -g memory,cpu,cpuacct:sistema

Una vez que hemos realizado el paso anterior ya si podemos modificar el archivo "/etc/cgconfig.conf", donde podremos modificar las prioridades.

    group usuario {
        cpu {
            ## 10% de CPU disponible para los procesos
            cpu.shares = 100;
        }
    }
    group sistema {
        cpu {
            # 90% de CPU disponible para los procesos
            cpu.shares = 900; 
        }
    }

En este caso lo que estamos haciendo es dándole menos prioridad a los procesos de usuario (20%) con respecto a los procesos del sistema (80%).

 - C) Usar un programa que muestre en tiempo real la carga del sistema tal como htop y comprobar los efectos de la migración en tiempo real de una tarea pesada de un procesador a otro (si se tiene dos núcleos en el sistema).

Instalamos htop, ya que no viene instalado por defecto:

    apt-get install htop

Enlace de referencia para usar [HTOP](http://bitelia.com/2010/03/comando-linux-htop-administra-interactivamente-los-procesos-del-sistema)

Una vez instalado "htop", lo ejecutamos con "htop", y nos mostraria lo [siguiente](https://www.dropbox.com/s/r0otmlznc22536b/Captura%20de%20pantalla%202014-10-18%20a%20la%28s%29%2016.50.48.png?dl=0).
Como se puede apreciar en la imagen, solo tiene una cpu por lo que no puedo probar al migración de una cpu a otro, aunque sinceramente no se como se haría migrarar de una cpu a otra.

 - D) Configurar un servidor para que el servidor web que se ejecute reciba mayor prioridad de entrada/salida que el resto de los usuarios.

Para poder realizar esta modificación, tenemos que modificar los parámetros de blkio(block I/O) que esta dentro del grupo que anteriormente hemos metido el servidor web (nginx, apache,..)

    group web{
       blkio{
             blkio.weight = 150 
       } 
    }
   
// Asignación por defecto 500 [Informacion de blkio](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Resource_Management_Guide/ch-Subsystems_and_Tunable_Parameters.html)


#Clase del 6 de octubre de 2014

#Ejercicios

* [+]Ejercicio 9
 - A) Comprobar si el procesador o procesadores instalados tienen estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden?
-Con el comando "cat /proc/cpuinfo", vemos la CPU que tenemos: Intel(R) Core(TM) i5 CPU M 520 @ 2.40GHZ

-Después ejecutamos la ordem: "egrep '^flags.*(vmx|svm)' /proc/cpuinfo", pero no aparece nada ya que no esta activada esa opción.

* [+]Ejercicio 10
 - A) Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok.
-Al introducir el comando "kvm-ok", me dice que no se puede usar el comando y que instale "apt-get install cpu-checker", una vez instalado ejecutamos el comando "kvm-ok" y me dice que no esta soportado.
[Imagen](https://www.dropbox.com/s/gra5sown1f7y5sf/Captura%20de%20pantalla%202014-10-16%20a%20la%28s%29%2010.52.43.png?dl=0)

* [+]Ejercicio 11
 - A) Comentar diferentes soluciones de Software as a Service de uso habitual
 [Comentario](https://github.com/JJ/GII-2014/issues/72#issuecomment-58912586). 

El concepto de SaaS existe desde hace tiempo, solo que en estos últimos años se ha hablado mucho más de ello y se a definido que és. Es todo aquel software como servicio(SaaS), son un modelo de distribibución software en el cual, tanto los datos y soportos lógicos que se usan se alojan en servidores remotos, a los que se pueden acceder através de internet haciendo uso de un cliente. 
Algunos ejemplos sencillos son: Webmail de Gmail, los CRM onlines. En este tipo de servicios nosotros accedemos normalmente a través del navegador sin atender al software. Todo el desarrollo, mantenimiento, actualizaciones, copias de seguridad es responsabilidad del proveedor.
Por lo que tenemos poco control, nosotros nos situamos en la parte más arriba de la capa del servicio. Si el servicio se cae es responsabilidad de proveedor hacer que vuelva a funcionar.
Ejemplos más conocidos de Saas son Google Docs, Salesforce, Dropbox, Gmail…

##TEMA 2

#Clase del 20 de octubre de 2014

* [+]Ejercicio 1
 - A) Instalar un entorno virtual para tu lenguaje de programación favorito (uno de los mencionados arriba, obviamente).
 
- Voy a instalar el entorno virtual "virtualenv" para Python. Para ello vemos a instalar PIP, que nos sirve apra instalar paquetes de python.

    sudo apt-get install python-setuptools python-dev build-essential
    sudo easy_install pip

Una vez realizado estos pasos damos el definitivo para la instalación de "virtualenv".

    sudo pip install --upgrade virtualenv 

La forma de usarlo y activarlo es la siguiente:

    virtualenv ENV
    source bin/activate

El uso de "virtualenv" es muy sencillo, para ello simplemente creamos una entorno virtual:

    virtualenv mi_entorno

Una vez creado, entramos en el y lo activamos:

    cd mi_entorno
    source mi_entorno/bin/activate

Sabremos que estamos en el entorno virtual, porque nuestra terminal cambia de:

    $
 
 a
 
    (mi_entorno)$

* [+]Ejercicio 2
 - A) Darse de alta en algún servicio PaaS tal como Heroku, Nodejitsu u OpenShift.

 Por probar diferentes servicios, me voya dar de alta en Heroku. Para ello nos damos de alta en [Registro Heroku](https://signup.heroku.com/www-home-top). Simplemente con introducir el correo electrónico es más que suficiente.
 Una vez registrado, te mandarán un correo para verificar el registro. Cuando le demos al enlace nos llevará a una página donde podremos elegir [nuestra contraseña](https://www.dropbox.com/s/uz8ysumr44kgw4s/Captura%20de%20pantalla%202014-11-09%20a%20la%28s%29%2018.02.26.png?dl=0). Una vez aceptada nuestra contraseña nos aparecera la siguiente página en la cual ya podremos proceder a usar [Heroku](https://www.dropbox.com/s/hxpdhmn704ugkzm/Captura%20de%20pantalla%202014-11-09%20a%20la%28s%29%2018.04.15.png?dl=0). [Panel de Heroku](https://www.dropbox.com/s/j74vla3g9eg9kpk/Captura%20de%20pantalla%202014-11-09%20a%20la%28s%29%2018.05.37.png?dl=0).


#Clase del 21 de octubre de 2014

* [+]Ejercicio 3
 - A) Crear una aplicación en OpenShift y dentro de ella instalar WordPress.
 
Lo primero que tenemos que hacer es registrarnos como en el caso de Heroku, para ello vamos a la página de [registro de OpenShift](https://openshift.redhat.com/app/account/new?__utma=222392261.655486696.1381573316.1381573316.1381573316.1&__utmb=222392261.2.10.1381573316&__utmc=222392261&__utmx=-&__utmz=222392261.1381573316.1.1.utmcsr=google%7Cutmccn=(organic)%7Cutmcmd=organic%7Cutmctr=(not%20provided)&__utmv=-&__utmk=111961607). Una vez que hemos rellenado todos los campos y nos hemos registrado satisfactoriamente, nos mandarán un correo para verificar nuestro resgistro, le damos al enlacen de verificación y nos aparecera la siguiente [página](https://www.dropbox.com/s/7gq23aihktadbo3/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.10.33.png?dl=0) y le damos a "Aceptar los términos". Cuando hayamos aceptado nos aparecera la siguiente página, donde le daremos a [Create your first application now](https://www.dropbox.com/s/ajekyxx09xkt4ch/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.12.12.png?dl=0) que nos mostrará el [panel de trabajo](https://www.dropbox.com/s/frizikrl9wpzkja/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.17.49.png?dl=0). Ahora unavez estemos ya en este panel de trabajo, nos encontraremos con una sección de [Instant app](https://www.dropbox.com/s/1itxucid9kocvi4/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.18.53.png?dl=0), donde seleccionaremos "WordPress4".
Una vez seleccionado "WordPress4", tendremos que rellenar el campo con la [dirección](https://www.dropbox.com/s/azit2zq4n1yobs2/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.25.22.png?dl=0) que queremos tener, el resto de opciones se quedan como estan, y le damos a "Create Application".
Cuando se haya creado, aparece lo [siguiente](https://www.dropbox.com/s/f06b29n2qdirhbu/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.27.38.png?dl=0), y le damos a "Not now, continue".[Ya esta creada](https://www.dropbox.com/s/dg9654hrycclidl/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.29.27.jpg?dl=0).

Ahora tenemos que registrarnos en [WordPress](https://www.dropbox.com/s/ancwhqe88zuvqgb/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.42.05.png?dl=0). Entraremos en el [panel de control de WordPress](https://www.dropbox.com/s/4scyktk2kutwx5d/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.43.36.png?dl=0).
Creo una ueva entrada, ya estaria todo [terminado](https://php-walkerazos.rhcloud.com/).

* [+]Ejercicio 4
 - A) Crear un script para un documento Google y cambiarle el nombre con el que aparece en el menú, así como la función a la que llama.

Nos vamos a [Google Drive](https://www.dropbox.com/s/aptx9tbfm7ys7l4/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.54.46.png?dl=0) y creamos un nuevo documento de texto. Una vez creado el documento nos vamos a [Herrramientas -->Editor de secuencia de comandos..](https://www.dropbox.com/s/zttpeyothwvqndj/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.51.45.png?dl=0)
Ahora creamos el nuevo [Script](https://www.dropbox.com/s/ew3jmx20ah2kvaw/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2016.56.32.png?dl=0).

Una vez terminado nuestro [Script](https://www.dropbox.com/s/bbwj4y30pl7txxs/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2017.05.38.png?dl=0), lo ejecutamos, y en nuestro documento [aparecerá](https://www.dropbox.com/s/pvxyx4dmjnm6nde/Captura%20de%20pantalla%202014-11-11%20a%20la%28s%29%2017.08.45.png?dl=0).


#Clase del 27 de octubre de 2014

* [+]Ejercicio 5
 - A) Buscar un sistema de automatización de la construcción para el lenguaje de programación y entorno de desarrollo que usemos habitualmente.

Lo primero que tenemos que tener es tener [node.js](http://nodejs.org/), para ello aqui dejo un tutorial de como [instalar](http://geekytheory.com/instalacion-de-nodejs/).

Uno de los automatizadores de construcción de "node.js" es [Grunt](http://gruntjs.com/). Hay que [instalarlo](http://gruntjs.com/getting-started).
Para ello usamos el comando:

    npm install -g grunt-cli

* [+]Ejercicio 6
 - A) Identificar, dentro del PaaS elegido o cualquier otro en el que se dé uno de alta, cuál es el fichero de automatización de construcción e indicar qué herramienta usa para la construcción y el proceso que sigue en la misma.

Como yo he usado tanto Heroku como OpenShift, en este caso voy a usar Heroku, por lo que el fichero de automatización de 
construcción es:

[/apps/:app/builds](https://blog.heroku.com/archives/2014/5/21/introducing_programmatic_builds_on_heroku)

EL proceso que sigue es que el nombre de la aplicación se le pasa un guión con la URL, a un archivo que contiene el código fuente, todo ello comprimo en dicho archivo.

Dicho Script coge las entradas y para ello usa "/apps/:app/builds", para poder crear así una nueva estructura dentro de "Heroku". Dentro de la plataforma de Heroku se identifica la nueva estructura, seuidamente pasa a estar en el estado "pendiente" y el siguiente paso sería a "Contrucción". Cuando la estructura se haya creado, pasaría a estar en estado "Éxito" o "Fracaso". De la salida se obtienen los resultados y se muestra por nuestra ventana de trabajo, si ha sido "Éxitosa", la estructura se despliega sola.

* [+]Ejercicio 7
 - A) Buscar un entorno de pruebas para el lenguaje de programación y entorno de desarrollo que usemos habitualmente.

Hay varios entornos de pruebas para node.js, pero es uno de los que más se suelen usar, [Sails.js](http://sailsjs.org/#/).

Aquí dejo como [instalarlo en diferentes sistemas](http://sailsjs.org/#/getStarted) y un poco más de infomación sobre él.

#VIRTUALIZACIÓN

#Clase del 4 de Noviembre de 2014

* [+]Ejercicio 1
 - A) Crear un espacio de nombres y montar en él una imagen ISO de un CD de forma que no se pueda leer más que desde él. Pista: en ServerFault nos explican como hacerlo, usando el dispositivo loopback.

Lo primero que tenemos que hacer es crear un espacio de nombres con:

    unshare -u /bin/bash

y cambio el nombre con:

    hostname ejercicio1

con lo que ahora "ejercicio1" será nuestro nombre del sistema.

Loa segundo es crear la carpeta en "/mnt", para ello hacemos:

    mkdir disk
    chmod 7777 -R disk

Ahora lo que hacemos es montar la imagen ".iso" en esa carpeta, situandonos previamente en la carpeta donde esta la imagen:

    mount -o loop - ubuntu-12.04.4-server-i386.iso /mnt/disk

Aquí esta el [ejemplo](https://www.dropbox.com/s/a4rgma5oq2xd59x/Captura%20de%20pantalla%202014-11-17%20a%20la%28s%29%2018.00.58.png?dl=0) que yo he realizado. 


* [+]Ejercicio 2
 - A) Mostrar los puentes configurados en el sistema operativo.

Lo primero que debemos de hacer es [installar](https://www.dropbox.com/s/ldc9ye4vdfdfa7e/Captura%20de%20pantalla%202014-11-17%20a%20la%28s%29%2018.08.37.png?dl=0)
la utilidad para poder mostrar la información:

    apt-get install bridge-utils

Ahora para [consultarlo](https://www.dropbox.com/s/68veyuua9xtg4le/Captura%20de%20pantalla%202014-11-17%20a%20la%28s%29%2018.14.48.png?dl=0) usamos el siguiente comando:

    brctl show

 - B) Crear un interfaz virtual y asignarlo al interfaz de la tarjeta wifi, si se tiene, o del fijo, si no se tiene.

Lo primero que debemos de hacer es crear la interfaz virtual con:

    brctl addbr interfazejercicio2

Lo segundo es asignar la nueva interfaz creada "interfazejercicio2" a "eth0" con:

    brctl addif interfazejercicio2 eth0

Una vez realizado todo esto, vemos que se ha asignado todo correctamente con:

    brctl show

[Ver Proceso](https://www.dropbox.com/s/upz9ttfzfhrypns/Captura%20de%20pantalla%202014-11-17%20a%20la%28s%29%2018.20.53.png?dl=0)

#Clase del 10 de Noviembre de 2014

* [+]Ejercicio 3
 - A) Usar debootstrap (o herramienta similar en otra distro) para crear un sistema mínimo que se pueda ejecutar más adelante.

 El primer paso que tenemos que dar es instalar [Debootstrap](https://www.dropbox.com/s/i7mr26g6ea9qm4w/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2013.23.04.png?dl=0), para ello usamo la siguiente orden:

    apt-get install debootstrap

Una vez ejecutada la orden comenzará el proceso de [descarga e instalación](https://www.dropbox.com/s/647vckmf8beiybf/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2013.23.26.png?dl=0).

Sigo los pasos del ejemplo usado en las transparecias del tema pero no encuntra [quantal](https://www.dropbox.com/s/18sszawhl77uhvt/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2013.32.49.png?dl=0), por lo que proceso a usar "lucid".

Para ello sigo los pasos seguidos anteriormente con en el ejemplo de quantal, así que creamos los [directorios](https://www.dropbox.com/s/gzobsb4o5w0wc9e/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2013.42.57.png?dl=0) siguientes donde se realizara la instalación:

    home/jaulas/lucid

Por último ejecutamos las orden:

    debootstrap --arch=amd64 lucid /home/jaulas/lucid/ http://archive.ubuntu.com/ubuntu

Tras un rato de espera se termina el proceso y se nos quedaría como se [muestra](https://www.dropbox.com/s/mhtyxhtcffld6hs/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2013.55.43.png?dl=0), siempre que se muestre el mensaje de "Base system installed successfully". 

 - B) Experimentar con la creación de un sistema Fedora dentro de Debian usando Rinse.

El primer paso que debemos de dar es instalar rinse, para ello [usamos](https://www.dropbox.com/s/ez0quh68jpuxg6e/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.10.41.png?dl=0) la siguiente orden:

    apt-get install rinse

Después tenemos que ver la lista de sistemas que hay disponibles con la [orden](https://www.dropbox.com/s/lbumgl8ip3lij2z/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.15.24.png?dl=0):

    rinse --list-distributions

Una vez localizado el sistema que vamos a usar, creamos un [directorio](https://www.dropbox.com/s/ezyq33qf3cfut5m/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.13.59.png?dl=0) nuevo donde meteremos nuestro sistema Fedora:

    /home/jaulas/fedora

Ahora ejecutamos la siguiente orden y comenzara de [descargar](https://www.dropbox.com/s/qiqp4u3ws8noy7x/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.19.40.png?dl=0) la distribución elegida:

    rinse --arch=amd64 --distribution fedora-core-4 --directory /home/jaulas/fedora

Tras un rato esperando a que se descargue por completo la distribución selecionada, nos aparecerá lo siguiente:
[Ver](https://www.dropbox.com/s/osdoao6noymb8vd/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.26.53.png?dl=0)

* [+]Ejercicio 4
 - A) Instalar alguna sistema debianita y configurarlo para su uso. Trabajando desde terminal, probar a ejecutar alguna aplicación o instalar las herramientas necesarias para compilar una y ejecutarla.

El primer paso es usar "chroot" para poder entrar en la jaula, usando el siguiente comando:

    chroot /home/jaulas/fedora

Después ejecutamos el comando "top", pero nos da un [error](https://www.dropbox.com/s/1si50v7wagmur13/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.34.02.png?dl=0).

Para solucionar dicho problema y poder visualizar el listado de directorios, usamos el siguiente comando:

    mount -t proc proc /proc

Una vez realizado este paso, volvemos a ejecutar la orden [top](https://www.dropbox.com/s/vogfekhjj4jbw2s/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.39.40.png?dl=0).

Ahora instalamos un editor de texto, en mi caso uso "nano":

    yum install nano

Ejecutamos [nano](https://www.dropbox.com/s/wphygjj43cq0hyb/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.56.35.png?dl=0) y creamos un pequeño programa.

Después lo ejecutamos con:

    python hola.py

[Ver](https://www.dropbox.com/s/ovyp0l469daft7x/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2016.57.45.png?dl=0)

* [+]Ejercicio 5
 - A) Instalar una jaula chroot para ejecutar el servidor web de altas prestaciones nginx.

Lo primero es entrar en la jaula que vamos a usar para instalarlo:

    chroot /home/jaulas/lucid

Como segundo paso, ejecutamos [apt-get install curl](https://www.dropbox.com/s/ytsi73smv3p2yyt/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2017.08.50.png?dl=0).

El tercer paso para poder instalar "nginx" es el [siguiente](https://www.dropbox.com/s/nal29eerjdk54rv/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2017.13.54.png?dl=0).

Por último ejecutamos "nginx" con:

    service start nginx

* [+]Ejercicio 6
 - A) Crear una jaula y enjaular un usuario usando `jailkit`, que previamente se habrá tenido que instalar.

Lo primero que debemos de hacer es instalar "jailkit", para ello tenemos que hacer es [ejecutar](https://www.dropbox.com/s/ye3pqyjiznv3xm5/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2017.28.53.png?dl=0):

    wget http://olivier.sessink.nl/jailkit/jailkit-2.16.tar.gz

Después [descomprimimos](https://www.dropbox.com/s/b22tnaqg5fmwvco/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2017.30.11.png?dl=0) el archivo descargado:

    tar -xzvf jailkit-2.16.tar.gz

Cuando ya lo hayamos descomprimido vamos a la carpeta de "jailkit" y ejecutamos: 

    ./configure
    make
    sudo make install

Ahora vamos a seguir las transparencias de clase:

    sudo mkdir -p /seguro/jaulas/dorada
    sudo chown -R root:root /seguro

[Ver](https://www.dropbox.com/s/cv3vrkebit4emsn/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2017.37.13.png?dl=0)

Una vez realizado lo anterior procedemos ha ejecutar lo siguiente:

    sudo jk_init -v -j /seguro/jaulas/dorada jk_lsh basicshell netutils editors

Tras unos segundos de espera, nos aparecerá lo siguiente:
[Ver](https://www.dropbox.com/s/ml0xnp27r0acw5o/Captura%20de%20pantalla%202014-11-18%20a%20la%28s%29%2017.41.08.png?dl=0)

Ahora creamos un usuario y lo enjaulamos dentro de su jaula:

    useradd ejercicio6
    jk_jailuser -m -j /seguro/jaulas/dorada ejercicio6

Se le cambia la contraseña al usuario:

    passwd usuarioIV

Por último editamos el archivo de configuración del usuario en este caso "ejercicio6", cambiando "jk_lsh" por "/bin/bash":

    /seguro/jaulas/dorada/etc/passwd


#CONTENEDORES

#Clase del 11 de Noviembre de 2014
* [+]Ejercicio 1
 - A) Instala LXC en tu versión de Linux favorita. Normalmente la versión en desarrollo, disponible tanto en GitHub como en el sitio web está bastante más avanzada; para evitar problemas sobre todo con las herramientas que vamos a ver más adelante, conviene que te instales la última versión y si es posible una igual o mayor a la 1.0.

* [+]Ejercicio 2
 - A) Comprobar qué interfaces puente se han creado y explicarlos.

* [+]Ejercicio 3
 - A) Crear y ejecutar un contenedor basado en Debian.
 - B) Crear y ejecutar un contenedor basado en otra distribución, tal como Fedora. Nota En general, crear un contenedor basado en tu distribución y otro basado en otra que no sea la tuya. Fedora, al parecer, tiene problemas si estás en Ubuntu 13.04 o superior, así que en tal caso usa cualquier otra distro. Por ejemplo, Óscar Zafra ha logrado instalar Gentoo usando un script descargado desde su sitio, como indica en este comentario en el issue.

* [+]Ejercicio 4
 - A) Instalar lxc-webpanel y usarlo para arrancar, parar y visualizar las máquinas virtuales que se tengan instaladas.
 - B) Desde el panel restringir los recursos que pueden usar: CPU shares, CPUs que se pueden usar (en sistemas multinúcleo) o cantidad de memoria.

* [+]Ejercicio 5
 - A) Comparar las prestaciones de un servidor web en una jaula y el mismo servidor en un contenedor. Usar nginx.

* [+]Ejercicio 6
 - A) Instalar juju.
 - B) Usándolo, instalar MySQL en un táper.

* [+]Ejercicio 7
 - A) Destruir toda la configuración creada anteriormente.
 - B) Volver a crear la máquina anterior y añadirle mediawiki y una relación entre ellos.
 - C) Crear un script en shell para reproducir la configuración usada en las máquinas que hagan falta.
 
* [+]Ejercicio 8
 - A) Instalar libvirt. Te puede ayudar esta guía para Ubuntu.

* [+]Ejercicio 9
 - A) Instalar un contenedor usando virt-install.

#Clase del 17 de Noviembre de 2014
* [+]Ejercicio 10
 - A) Instalar docker.

* [+]Ejercicio 11
 - A) Instalar a partir de docker una imagen alternativa de Ubuntu y alguna adicional, por ejemplo de CentOS.
 - B) Buscar e instalar una imagen que incluya MongoDB.

* [+]Ejercicio 12
 - A) Crear un usuario propio e instalar nginx en el contenedor creado de esta forma.

* [+]Ejercicio 13
 - A) Crear a partir del contenedor anterior una imagen persistente con commit.

* [+]Ejercicio 14
 - A) Crear una imagen con las herramientas necesarias para DAI sobre un sistema operativo de tu elección.
