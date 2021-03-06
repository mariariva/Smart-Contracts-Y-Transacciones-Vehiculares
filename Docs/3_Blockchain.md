### Blockchain
3.1. Definición y tipos estructurales de Blockchain.
La tecnología Blockchain fue descrita por primera vez en 2008 por el anónimo Shatoshi Nakamoto14, y se trata de “...una base de datos distribuida donde cada nodo o usuario en la red ejecuta y registra transacciones agrupandolas en forma de bloques…”15. Su propia estructura lógicamente relacionada y descentralizada hace posible que se aplique en diversos ámbitos que no sean necesariamente financieros, como es el caso del Gobierno. La utilización de herramientas como la tecnología Blockchain promueve la transparencia, trazabilidad y democratización en las operaciones que se realizan en la Administración Pública, generando confianza debido a su ejecución automática, fácil accesibilidad e imposibilidad de modificación. 
Podemos dividir las ventajas de esta tecnología en dos grupos16:
    • Con relación a las transacciones 
    a) Intercambio sin intermediación de terceros: No es necesaria la presencia de un tercero ya que la tecnología ofrece la posibilidad de que se realice la debida validación de las transacciones a través de los nodos. 
    b) Eficiencia: La mayor seguridad, eficacia y rapidez con la que se realizan las transacciones a través del Blockchain genera beneficios tales como la reducción de gastos y costes generados por los intermediarios innecesarios al valerse de una propia legitimación de las transacciones como la transparencia y eficiencia.
    • Con relación al sistema:
    a) Inviolabilidad: La descentralización de las operaciones robustece al sistema frente a posibles ataques maliciosos al carecer de un operador central.
    b) Disponibilidad: El sistema ofrece acceso y la posibilidad de concretar transacciones en cualquier momento.
    c) Inmutabilidad: las transacciones no pueden ser modificadas o eliminadas.
    d) Control: los usuarios tienen acceso y pueden verificar todas sus transacciones.
La red Blockchain cuenta con una estructura particular conformada por17:
    a) La base de datos donde se registran las transacciones o se guarda información.
    b) El bloque de transacciones con las correspondientes huellas (identidades digitales) de quienes envían o realizan la transacción y quien las reciben.
    c) Los nodos (computadoras).
    d) El algoritmo de encriptación con su correspondiente marca de tiempo (timestamp) que sirve para la validación del bloque mediante el conocimiento de la fecha y hora de su realización.
    e) Las Wallet, que permiten a los usuarios manejar sus propias identidades y realizar transacciones ya sea monetarias o no.
Asimismo, existen tres tipos de Blockchain18 que se diferencian entre sí por sus funcionalidades, métodos de consenso, flexibilidad en la administración de la red y las reglas para la validación de las transacciones. En primer lugar, se encuentran las Blockchain públicas (Ethereum, Bitcoin, entre otras) que son aquellas en las que cualquier persona puede participar pudiendo acceder libremente a los datos como también la posibilidad de realizar transacciones y que no poseen administradores. En segundo lugar, la Blockchain privada (Hyperledger, Ripple , etc)19 es aquella donde existe un administrador quien otorga los permisos para poder utilizar la red, manteniendo una base de datos centralizada que no se encuentra abierta al público. Por último, la Blockchain híbrida o federada (Evernym, BigchainDB, etc)20 es una combinación de la pública y la privada ya que su gestión está dada a varias entidades que se encargan de administrar la red y mantener las copias del registro sincronizadas, y cuyo acceso por parte del usuario se hace a través de una interfaz web con un acceso controlado.21
Las características de la red Blockchain22 se verán determinadas según la estructura que tenga la base de datos:


    a) Administración: La manera en que la base de datos es administrada dependerá de la estructura. Así, en las redes privadas encontraremos una administración centralizada en la que una única entidad mantiene la cadena, mientras que en las base de datos híbridas/federadas hay varias entidades que tienen esta función, lo que se denomina semi-centralizado. Por último, en los casos de estructuras públicas las transacciones pueden ser realizadas entre pares (peer to peer) sin ningún tipo de intervención que las valide, lo que la hace totalmente descentralizada.


    b) Persistencia: Las transacciones que se registran en la red Blockchain deben ser validadas por todos los nodos. Para lograrlo, son agrupadas en bloques que son confirmados y registrados de maner disbuida lo que genera que dicha información no sea manipulable debido a la forma de encriptación y linkeo entre los bloques.


    c) Identificación: En el caso de las redes Blockchain privadas o híbridas/federadas se requiere la identificación de los usuarios para poder otorgar los permisos necesarios para realizar transacciones, mientras que en las públicas los usuarios pueden interactuar a través de la utilización de claves sin que sea necesario que se asocien sus datos personales.


    d) Auditabilidad: Como se mencionó anteriormente, las transacciones que suceden en las redes Blockchain son validadas y registradas con su debida marca de tiempo (timestamp). Los usuarios, de acuerdo al nivel de permisos que obtengan, podrán rastrearlas y verificarlas, generando con este acceso una red transparente y trazable. 


    e) Participación: La intervención que cada usuario tenga será consecuencia del tipo de red que se trate. En el caso de las redes de Blockchain públicas los usuarios tienen acceso a todos los servicios de la misma y podrán colaborar como nodos, mientras que en las redes privadas, solo lo podrán hacer si el administrador  así lo permite. Por último, en las redes híbridas/federadas, los usuarios podrán participar siempre que cumplan con los requisitos necesarios, se identifiquen y sean aprobados por el administrador.


    f) Transparencia: La transparencia será consecuencia del nivel de participación que tengan los usuarios en la red y de la administración de la misma. En tal sentido, las redes públicas serán las que más transparencia pues la información allí almacenada podrá ser consultada por cualquier usuario, mientras que en las privadas serán las que menos transparencia tengan ya que usualmente no tienen acceso a la información, mientras que las híbridas/federadas se encuentran en un punto intermedio ya que el acceso que tengan los nodos estará determinada por los permisos que otorgue el administrador. 


Una de las fallas más conocidas que puede afectar a este tipo de tecnología distribuida es la llamada “Falla Bizantina” 23por la cual el sistema no logra identificar si hay o no hay un error. Este tipo de problemas ocurre cuando el sistema presenta distintas fallas frente a distintos observadores, lo que genera dificultad para determinar el error y excluirlo de la red ya que para eso es necesario, en primer lugar, el consenso sobre qué componente está funcionando defectuosamente.
Aunque el riesgo es mínimo, si existiera un ataque a una red Blockchain no implica necesariamente que se pueda leer o acceder a la información que en ella reside. Esto se debe a la encriptación máxima de bloque a bloque que garantiza la confidencialidad de los mismos e incluso de la información que se encuentre en proceso de ser validada. Sin embargo, uno de los ataques posibles a esta red es el denominado “ataque del 51%”24 que se origina cuando uno o varios participantes logran tener control de al menos del 51% de la red, es decir, cuando logran tener una participación mayoritaria que permita controlarla.


3.2. El uso del Blockchain para el desarrollo de Smart Cities.
La aplicación de la tecnología Blockchain a la esfera de Gobierno responde al concepto de “Smart Cities” (ciudades inteligentes), que implica la utilización de tecnologías de la información y la comunicación (TICs) aplicadas a la gestión de los recursos y los servicios de los que hace uso la ciudadanía.25 El origen de las smart cities se basa en la digitalización de la información  y los sistemas que la rodean, tomando como eje de desarrollo a las personas que la habitan y sus necesidades, y aplicando la tecnología para lograr una planificación colaborativa y mejor gestión urbana.
Ahora bien, si nos preguntamos ¿Por qué es necesario desarrollar ciudades inteligentes?, la respuesta radica en la creciente cantidad de personas que viven en las ciudades por lo que resulta necesario que se desarrollen de manera que sean sustentables y sostenibles a lo largo del tiempo. Esto, se añade a la demanda actual de la sociedad de contar con procesos más transparentes, eficientes y abiertos, que conlleven una mayor participación ciudadana y un acceso más libre a la información pública. En este sentido, la Administración tiene a su cargo numerosos procesos que implican grandes cantidades de registros y documentación, que sumado a la creciente cantidad de ciudadanos, nos lleva a repensar en nuevos modelos de relacionamiento entre la Administración y los ciudadanos que estén basadas en la innovación y el uso de las nuevas tecnologías y que tengan como resultado procesos más óptimos e integrales donde haya una mayor participación ciudadana.


El concepto de smart cities implica un reto para el Gobierno de conjugar la tecnología con las políticas públicas con la finalidad de integrar todos los sistemas de la sociedad (comercial, salud, infraestructura, etc.) y lograr servicios confiables y de calidad a todos los usuarios y Blockchain aparece como una opción con múltiples beneficios.Esta tecnología, con su carácter  de base de datos descentralizada e inmutable, brinda un soporte seguro para el almacenamiento de información, la transferencia de documentación y la realización de transacciones de toda índole, lo que resulta de gran valor para evitar la corrupción y establecer la transparencia con la Administración Pública en espacios donde actualmente el ciudadano no tiene confianza.26 


En el caso puntual de los Registros Públicos, estos sirven de nexos entre la Administración Pública y los ciudadanos que incorporan, bajo cierta normativa, documentos que contienen información sobre sí mismos, su entorno y  sus bienes a través de solicitudes, escritos y/o comunicaciones. La continua actualización de estos documentos, reflejando los cambios que se producen a lo largo del tiempo en la vida de las personas genera los denominados “documentos vivos”, que sirven para asociar datos con los individuos. 


Respecto a esto, la cadena de bloques que integran la Blockchain y su peculiar transmisión y validación de la información a través del algoritmo matemático denominado “hash” hace que los datos ingresados en ella sean inmutables, reduciendo al máximo los riesgos de fraude o modificación.


3.3  El Hash criptográfico como factor de seguridad. 
A lo largo de este trabajo hemos referenciado en varias oportunidades que una de las ventajas más importantes que ofrece la red Blockchain es la seguridad de los datos e información que transitan en ella. La seguridad de esta tecnología está dada por la utilización de criptografía que sirve para encriptar la información dentro de la Blockchain, que sirve para salvaguardar los datos e impedir que terceros no autorizados puedan acceder a información valiosa o alterarla27. 
Existen tres métodos de criptografía28 que se diferencian entre sí según las claves utilizadas:
    • Criptografía simétrica: Aquí tanto quien envía el mensaje o la información, como quien la recibe, comparten una misma clave lo cual implica que hay que resguardarse con mucha seguridad ya que de ser conocida por terceros estos pasarían a tener control sobre la misma.
    • Criptografía asimétrica: Este tipo de criptografía, más avanzada, permite que se intercambie información, datos y/o mensajes sin necesidad que las partes cambien entre sí una misma clave. La peculiaridad de la criptografía asimétrica es que las partes utilizarán dos claves: una pública que sirve para generar el mensaje encriptado y poder enviarlo a otra persona y una clave privada que es necesaria para recuperarla.


Una de las principales herramientas para utilizar la criptografía en la Blockchain es el hash o digesto criptográfico. En este sentido, el hash es un algoritmo que transforma o digiere un grupo de datos y lo transforma en un valor único de longitud fija29.  En la práctica, los hash funcionan como algoritmos matemáticos que sirven para transformar cualquier dato en una nueva serie de caracteres alfanuméricos únicos de longitud fija (número de serie). De esta manera, cualquier modificación que se realice en la información, por más mínima que sea, cambiaría por completo el hash, lo que permite conocer si se realizó alguna modificación sobre los datos. Asimismo, el  proceso de hashing es unidireccional, lo que permite que una vez obtenido el hash no se podrán obtener los datos que le dieron origen, es decir, no podrá descifrarse su contenido original.
Una de las principales funciones del hash dentro de Blockchain es la verificación del contenido de los nuevos bloques que ingresan a la red distribuida30. Dada la descentralización que caracteriza a la red Blockchain para que nuevos bloques puedan integrar es necesario que haya un consenso entre los nodos que participan de ella, el cual es llevado a cabo por los mineros a través de los hashes criptográficos. 


Existen varios procesos de consenso, pero los más comunes son31:
    • Prueba de Trabajo (Proof of Work - POW): En este modelo, todos los nodos son pares iguales en la red y compiten entre sí para sellar un bloque a través de la resolución de un complejo algoritmo matemático. El primero que pueda resolverlo satisfactoriamente podrá incorporar el algoritmo a la red y recibirá una recompensa en criptomonedas. Este método de consenso implica un alto procesamiento de los nodos lo que conlleva un costo energético alto.
    • Prueba de Participación (Proof of Stake- POS): En este caso la validación de los bloques se realiza de acuerdo a la participación de los participantes (cantidad de monedas acumuladas). Aquí, la Blockchain es verificada mediante un proceso que toma en consideración el capital del nodo y el tiempo en que dichas monedas han permanecido depositadas.

    
En conclusión, para que un hash sea exitoso, debe ser relativamente corto y ser capaz de representar de manera compacta un texto o cadena de entrada más larga. Asimismo, debe ser32:
    • Fácil de calcular: con bajo costo computacional.
    • Determinista: una misma cadena de entrada debe devolver siempre el mismo  valor hash.
    • Efecto avalancha (no continuidad): el más mínimo cambio de los valores de entrada modifica totalmente el hash. 
    • Resistente a colisiones: que resulte muy difícil de encontrar dos valores de entrada que obtengan el mismo valor hash o que resulte imposible porque las variaciones de los valores de entrada son inferiores a la cantidad de valores hasha disponibles.
    • OWF (One Way Hash Function): que la función hash sea unidireccional o de sentido único de manera de no encontrar a través de él los valores que tienen los datos de entrada que lo originaron.

[Smart contract <<<](2_Smart_Contract.md) *** [>>> Las transacciones vehiculares](4_Las_transacciones_vehiculares.md)