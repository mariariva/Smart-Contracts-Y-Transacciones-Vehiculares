### Smart Contract

##### 2.1. Descripción de los smart contract y su potencial en las relaciones contractuales

Para comprender el concepto de smart contract y su funcionamiento es importante recordar la definición del contrato tal como se describe en la legislación local. El Código Civil y Comercial argentino define al contrato en su artículo 597 como “el acto jurídico mediante el cual dos o más partes manifiestan su consentimiento para crear, regular, modificar, transferir o extinguir relaciones jurídicas patrimoniales”2.


Los contratos se basan en la libertad de las partes de determinar su contenido siempre que se encuentre dentro de los límites impuestos por la ley, el orden público, la moral, y las buenas costumbres  y en el “principio de la buena fe”3 por el cual  estos deben celebrarse, interpretarse y ejecutarse de buena fe. Respecto a esto último, es importante destacar que, una vez establecidas las cláusulas del contrato, estas tienen fuerza vinculante para las partes quienes deben someterse a ellas como si fuera ley pero que, al ser escritas, pueden ser susceptibles de diversas interpretaciones.


La naturaleza jurídica de los contratos tradicionales implica la intervención por parte de terceros para la validación de sus condiciones y ejecución de las cláusulas, circunstancia que muchas veces genera costos elevados y procesos complejos y lentos. 


El smart contract surge como una herramienta que reduce las falencias del método tradicional contractual conservando la posibilidad de dar respuesta a las necesidades de las partes que se someten al contrato. El origen del smart contract se remonta a 1994, cuando por primera vez fue utilizado y definido por el científico y criptógrafo Nick Szabo4. En aquel entonces, Szabo describió a estos como “...un proceso de transacciones computarizadas que ejecutan los términos de un contrato…”5 cuyo objetivo es asimilar las consecuencias jurídicas más comunes que pueden darse a través de un contrato tradicional (pagos, gravámenes, confidencialidad, etc). 


Se trata de un contrato que por sus características es posible de ejecutar por sí mismo, de manera autónoma y automática, sus cláusulas, sin intervención de un tercero. En estos casos, la información que se graba en el contrato es consolidada en la red Blockchain y su ejecución queda suspendida al cumplimiento de los términos allí impuestos.


Es importante señalar que las cláusulas del smart contract se encuentra escrito como códigos informáticos con un lenguaje de programación  (por ejemplo, solidity en el caso de Etherum)6, como así también que tienen la capacidad no sólo de implementar determinadas consecuencias por las reglas en las que se base (“si sucede X, se pagará Y”) sino que también pueden tomar información (input), procesarlas y asignarles un resultado específico. 


El smart contract también puede nutrirse de información del exterior que no se encuentra dada en el mismo contrato y que resulta de gran importancia para su ejecución a través de los denominados oráculos. Los oráculos son servicios ofrecidos por terceros que proporcionan a los smart contract información externa en forma de datos electrónicos que puedan ser asimilados por los nodos. Los oráculos no son la fuente de información en sí misma sino que funcionan como una herramienta que consulta, verifica y autentifica fuentes de datos externas para luego transmitir dicha información al smart contract y que este pueda ejecutar una tarea determinada. La importancia de los oráculos radica en que permite que el smart contract tenga  comunicación con el mundo exterior y no dependa exclusivamente de la información que esté dentro de su red, ampliando su operatividad y alcance.


Sin embargo, el problema principal que presentan los oráculos es que al no pertenecer a la cadena de consenso de la Blockchain, no es parte de los mecanismos de seguridad que se encuentran en ella. De tal manera, los oráculos se podrían volver un punto de ataque para alguien que busque dañar el smart contract, ya que al tratarse de una fuente tercera en la que hay que confiar, se está centralizando esta parte del proceso, con los riesgos que esto conlleva (fallas, crackeo, etcétera). Actualmente existen proyectos de oráculos que combinan los resultados obtenidos de diversas fuentes que se le indiquen, y construye su decisión en función de lo que la mayoría de ellas determine, descentralizando de esta manera el resultado obtenido (Orisi, Oraclize).7


La vulnerabilidad más importante del smart contract radica en el hecho de que una vez introducido a la cadena de bloques de la Blockchain no puede ser eliminado ni modificado, por lo que las opciones para solucionar problemas por algún ataque o mismo alguna cuestión mal definida se limitan mucho.


El smart contract ha surgido como una alternativa a la forma tradicional de celebración de contratos  para la realización de transacciones económicas y jurídicas. En tiempos como los actuales, donde la población del mundo está viviendo restricciones de movilización, los mercados se encuentran restringidos y el contacto físico ha disminuido notablemente, estos contratos cobran gran valor para continuar con la vida comercial y jurídica. 


La versatilidad dada por estos contratos que permiten codificar cualquier tipo de lógica empresarial basada en los datos, hace posible que numerosas industrias puedan aplicarlos a sus relaciones contractactuales a través de la incorporación de acuerdos digitales comerciales, ya sea que se trate de algo simple como una compra por internet hasta algo más complejo como garantizar un préstamo. El  objetivo principal de estos contratos es permitir que las personas hagan negocios con desconocidos, usualmente desde internet, sin necesidad de contar con un tercero de confianza que intervenga y valide el proceso, haciéndolo más simple, rápido y ahorrando costes para las partes. 


El potencial del smart contract y la tecnología Blockchain es mucho más grande cuando es conjugado con la “tokenización” de activos8 que permite convertir los derechos sobre un activo real en un token digital, lo cual amplía enormemente su utilización en intercambios comerciales y/o legales. Todos los activos (financieros, inmuebles, etcétera) pueden ser tokenizados no solo para almacenar datos relativos a su ciclo de vida sino también para facilitar transacciones digitales. La tokenización en conjunto con el smart contract no solo beneficia a la desintermediación sino también a la automatización de procesos.

#### 2.3 El caso Ethereum

 Estructura básica de un smart contract redactado en Solidity.
Como se mencionó anteriormente, el smart contract está compuesto de instrucciones escritas en un programa informático con un formato que es entendido por una computadora que evalúa sus términos y aplica las consecuencias que se hayan establecido. 
Ethereum es una plataforma global open source (de código abierto) para aplicaciones descentralizadas creada en 2015 por el programador Vitalik Buterin.9 Se trata, entonces, de una plataforma de tipo “abierta” que es pública para todos las personas que quieran interactuar allí, que posee su propia criptomoneda (Ether) y que resulta programable lo que hace posible que los usuarios puedan utilizarla para crear nueva aplicaciones e interactuar entre sí sin que una entidad centralice el servicio (Dapps - aplicaciones descentralizadas). 
La plataforma de Ethereum está basada en una blockchain pública con un formato específico llamado bytecode Ethereum Virtual Machine (EVM)10 que permite ejecutar smart contract peer to peer (P2P), es decir que los nodos interactúan entre sí sin servidores centrales o intermediarios. 
Las instrucciones que forman al smart contract están escritas en un lenguaje informático que es entendido por los nodos que las procesan. En el caso específico de la plataforma Ethereum, este lenguaje se llama Solidity, y es de tipo “turing completo” lo que le permite solucionar cualquier problema informático dentro de sus capacidades, añadiendo una lógica más completa la Blockchain11. 
Soliditiy fue desarrollado con el objetivo de generar smart contracts, facilitando el desarrollo de sus aplicaciones mediante la utilización de este lenguaje sencillo de leer y mantener, que luego es transformado a un segundo nivel de profundidad dada por los códigos de operación (OP_CODES) y por último a un bytecode, que es el código específico que la EVM entenderá. La existencia de Solidity y de la EVM junto con la naturaleza flexible, descentralizada y  programable de la plataforma, convierte a Ethereum en un gran ecosistema descentralizado que es capaz de realizar las instrucciones que lleven a la ejecución de cualquier tarea específica.
Respecto a los gastos que se generan por el uso de la plataforma, en el ámbito de Ethereum se utiliza el concepto de “GAS” que hace referencia al valor que tiene la realización de las operaciones ejecutadas  por un contrato que es medido en unidades de “GAS”12. Aquí, cada nodo tiene que realizar las instrucciones que se encuentran en la EVM, repitiendo los mismos cálculos una y otra vez, siendo esta acción parte del protocolo de verificación del bloque. Dicha acción de repetición tiene como función la autenticación de la información y prescindiendo, de esa manera, de un tercero confiable que los valide, lo que conlleva un costo alto, que a su vez es definido por los propios mineros según las leyes de mercado. 
Otra de las características importantes de Ethereum es que cuenta con su propia criptomoneda llamada Ether (ETH) que puede ser utilizada entre pares para solventar las transacciones que se realicen en esta plataforma, cuya emisión es de dieciocho millones anuales. En el caso de Ethereum se  utiliza como protocolo de consenso el Proof of Work (POw) con un algoritmo específico llamado Etash, y los validadores de bloques compiten para solucionar un problema matemático, y el ganador recibe una recompensa en Ethers, aunque en la actualidad esta en camino de ser modificada a un protocolo de consenso de tipo Proof of Stake (POs).
Por otro lado, respecto a los elementos que integran un smart contract que es escrito en lenguaje Solidity, encontramos:13
    • Determinación de la versión del compilador (Ejemplo: pragma Solidity ^0.4.0.)
    • Variables de estado que son valores almacenados de manera permanente en el smart contract.
    • Funciones que hacen referencia a unidades de código ejecutables en el contrato. 
    • Modificadores del contrato que sirven para añadir o cambiar el comportamiento del contrato.
    • Estructuras que son datos que sirven para agrupar varias variables.

[Introducción <<<](1_Introducción.md) *** [>>> Blockchain](3_Blockchain.md)