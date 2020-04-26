# Clase 2
	- Vamos a tener que programar algo como TP final o algo así
	- Se van a dar repasos generales, pero no van a enseñar como programar.
	- La programación es indistinto qué lenguaje se tome.

# Análisis de vulnerabilidades
	[Basado en las filminas]

Se ven más en Seguridad de las aplicaciones. Es una introducción nomás.

En el mercado tiene muchos nombres esto, pentesting, ethical hacking, análisis de riesgo, etc. Todos apuntan a identificar qué
vulnerabilidades tienen los activos de interés para una empresa determinada.
Desde el 1999 ha ido creciendo mucho las vulnerabilidades en las aplicaciones. Esto se debe a dos motivos:
	- Cada vez hay mayor cantidad de aplicaciones
	- Más artículos o dispositivos tienen aplicaciones (no sólo las computadoras y celulares, sino también electrodomésticos,
	  autos, la casa en general) todo ello impulsado por IOT (Internet of Things).
	- Y cada vez hay un Mercado más grande que tiene intereés que se descucbran estas vulnerabilidades.

Tipos de vulnerabilidades:
-------------------------
	- Overflow: desbordamiento de pila, muchas veces cuando se programa funciona de una manera no esperada, se le pide a una
	  variable que devuelva un número de 16bits pero está programado para que devuelva de 8 bits.
	- XSS: problema de web, ejecutar scripts dentro de página web a través del frontend
	- SQL injection: base de datos que no se controla el input.

Para detectar las vulnerabilidades se utilizan dos tipos de análisis:
	- Teste de caja negra: se realiza un análisis sin información respecto a los activos de la empresa,no se tiene ningún tipo
	  de datos
	- Test de caja blanca: se tiene cierta información, como los las direcciones IP, el hostname, los usuarios, las web que
	  utilizan.

	* Estos permiten:
		- listar los servicios disponibles que tiene. Dispositivos que comparten, y por lo tanto vulnerabilidades.
		- Debilidades,cuáles de estos servicios tienen vulnerabilidades

* Vulnerabilidades de Implementación:
	- Base datos muy segura, pero es pública y de afuera se puede acceder.
	  El error se produce en cómo se lleva a cabo esa puesta en marcha del activo. En el caso de la base de datos, que está
	  bien establecida, que tiene consistencia en sus datos, pero se implementó de forma pública, el cual no estaba pensada
	  para ello.

* Vulnerabilidades de Configuración:
	- Error humano que permite una vulnerabilidad, el error está en la persona que lo configura. Como por ejemplo tener las
	  mismas contraseñas para todos.

* Vulnerabilidades de redes:
	- El equipo en sí viene con la falla, el equipo que tiene un objetivo que cumplir.

* Vulnerabilidad de protocolo:
	- Cuando la práctica que la define, tiene un error, el protocolo ya tiene un error interno. Esto se soluciona actualizando
	  los dispositivos que tienen un nuevo protocolo.
	- HTTPS es un ejemplo, por lo que se fueron solucionando mediante la actualización de los intercambios de comunicación.

Herramientas que se utilizan para realizar análisis de vulnerabilidades:
------------------------------------------------------------------------
	- Escaneo de puertos: Servicios corriendo en distintos puertos, dependiendo de qué puertos tiene abierto se sabe qué
	  programa está corriendo, y qué tipos de servicios tienen corriendo.  Qué versión tiene ese servicio y qué problemas
	  tiene.

	- Detección de vulnerabilidades:

	- Analizador de protocolos:

	- Password crackers: los que testean todo el tiempo encontrar por medio de fuerza bruta el password de alguna cuenta, etc.

	- Ingeniería social: confianza para con otras personas que termina dando información sin saberlo. Como por el ejemplo de
	  Phishing, sino como Blackhat (conferencia de hackers), competencia de 5 personas que tratan de que una empresa
	  desconocida baje por unos minutos su antivirus.

	- Trashing: obtener información de la basura que tiran las empresas.

	- Passwords crackers:

Nota de color: Uso de VPN: acceder a una red interna desde cualquier parte del mundo. Las páginas que van por http, telefónica no
sabe a qué contenido se adscribe, sólo sabe a qué dirección me dirijo, las comunicaciones están cifradas punto a punto.

Organismos de consulta (claves):
-------------------------------
	Para realizar un trabajo profesional, hay que basarse en estándares, y buenas prácticas de calidad, para ello son las
	siguientes páginas:
	- CERT: organimos que se encarga definir lo que es una buena práctica, cómo responder al hackeo, etc.
	- SANS: Informes de alertas y seguridad. Conferencias on-line. Es una organización de cursos de seguridad, así empezó, se
	  hizo un referente y sacó papers.
	- NSA: organismo de seguridad de USA. Liberan TICS que son templates para cosas que hay que chequear para realizar buenas
	  prácticas. Muchas cosas públicas buenas, pero también viola la privacidad.
	- NIST: organismo referente de estándares, documentos extensos, no son para nada prácticos.
	- Security Focus, empresa que publica vulnerabilidades.
	- CVE: Common Vulnerabilities and exposures: Clasificación de vulnerabilidades y bugs de sistema [fuente más grande que
	  existe desde las vulnerabilidades]
	- HackerOne: empresa que hace de intermediario entre el hacker que encuentra la vulnerabilidad y la empresa que es
	  hackeada.

Seis pasos a establecer antes de comenzar:
-----------------------------------------
	- Acuerdo de confidencialidad: Marco legal para garantizar que toda la información obtenida sea para uso informativo, que
	  no se puede divultar (aspectos legales), ya que se accede a información delicada.

	- Establecer reglas del juego (alcance): no se puede hackear toda la empresa, sino establecer a qué servicio se quiere
	  volcar el hacking. Establecer, limites, permisos y obligaciones.

	- Se debe establecer si se realizará un Test de Caja Blanca: Análisis a partir de información que se nos brinde [lista
	  larga] O más bien,

	- Un Test de caja negra: Dirección IP o nombre del dominio, sólo se cuenta con esa información.

	- No afectar la disponibilidad de los servicios de la empresa. Que se caiga un dominio porque le están haciendo un test de
	  impacto de vulnerabilidades, eso se tiene que establecer en el contrato.


# Test Interior:

Las pruebas que se deben realizar en el análisis son:
	- Revisión de privacidad: cómo se gestiona la información tranmisión y control de datos.
	- Testeo de aplicaciones: tratar de hackear algún servicio o aplicación.
	- IDS: programa que analisa el tráfico de redes. Si encuentra un comportamiento anómalo, lo reporta.
	- Contingencia: VSP ver si ese plan en caso de que ocurriese algo, siga laburando (como el caso cuando se cortó la luz en
	  argentina ¿Qué empresa pudo prevenirlo? Continuar con el negocio ante algún imprevisto.
	- Denegación de servicios: Analizar de robustes para soportar parámetros que abusen de ellos. ¿tienen algún programa para
	  poder bloquear quizás 40000 pin por segundo?
	- Evaluación de políticas y normas de seguridad: ¿tienen políticas definidas? Tanto para el empleado como para la empresa,
	  estos documentso dan un lineamiento de lo que se puede y no hacer.
	- Inteligencia competitiva: Información recolectada a partir de la información pública de internet. Investigación de lo
	  que dice internet de un empleado (mayormente utilizado con personas de altos rangos corporativos o persona pública).
	- Testeo de solicitud: Técnicas de ingeneiría social dirigida a
	- Sugerencia dirigida:
	- Sondeo de redes: analizar e identificar todos los recursos informáticos que hay en la red, en la capa TCP/IP, qué
	  equipos están prendidos, qué servicios dan.
	- Busqueda y verificación de... : encontrar esos dispositivos del punto anterior y encontrar las vulnerabilidades en las
	  páginas anteriores pasadas, como en la CVE.
	- Verificación de Redes inalámbricas: análisis de estas redes, estudiando el alcance, y eso.

# Análisis de Riesgo:
Se hace una lista de activos, se le da un puntaje y se le hace a cada una, otra lista de amenazas.
Indisponibilidad: no es lo mismo quemar una placa de red que nos quedemos sin memoria. Es muy a criterio de cada uno, subjetivo el
Análisis de riesgos.
Se hace un análisis de riesgo de cada una de las amenazas indicadas. Se le asigna un valor.
La frecuencia: ¿Qué tan seguido puede suceder algo?.

Con estos 3 Parámetros se arma una tabla para deteminar el riesgo asociado a cada amenaza (que es muy parecida la que dan los
profesores a una tabla booleana).
Se tiene un cuado que también es subjetivo (que está en la filmina). Luego se trata de obtener un porcentaje con unas sumatorias
con valores dividido por todas las amenazas, y nos da un número ponderado que es el buscado para poder generar un informe o para
una presentación.
	Aclaración sobre la filmina: "Punto de venta" son los activos, es como poner celulares de la empresa, etc.
	Por fila van los activos y por columna se ven los análisis.

# Práctica que se debe realizar:
	Impacto: cómo afecta al activo. Si Se inunda, ¿qué tanto afecta al router? (primer activo en el excel que está en el campus)
	Vulnerabilidad: qué tan fácil lo afecta al activo. El router si se lo tapa con agua ¿qué tanto lo afecta al router?

