# Clase 1:

# Forma de evaluación:
	- Si está todo bien, entonces se pasa a final
	- TP cada 14 días Se tiene que cargar las respuestas de lo pedido (es hasta determinada fecha), si se pasa con esa fecha,
	  se inhabilita el TP final. Después de las 00hs NO se puede subir el TP.
	- TP final.
	- Y queda a disposición de si se toma un parcial final o no (depende de la facultad).

# Prácticas (campus) Actividad práctica 1:
	La cursada tiene que durar 15 semanas: Serían 6 TP y quizás meter un TP integrador para evaluarnos al fin de la
	cursada (pero no está delimitado).

	La cursada es autoaprendizaje: la clases se quieren hacer con más dias, para consultas y explicar las dudas.
	Los días a consultar, queda a evaluación.

# Temas a tratar:
	- Se toman Malware: muy a nivel generarl
	- Protocolos, limitar el acceso a recursos a través de red se puede hacer más seguro, limitar el acceso a la red.
	- Dominio de colisiones: (VLAN) una sola red puede estar distribuido en 20 edificios distintos, análisis
	- Análisis de vulnerabilidad: Ethical hacking, metodología qe existe para lo que es análisis de vulnerabilidad. Servicio
	  que se brinda que evalúa la seguridad de una entidad (empresa, web, etc).
	- Firewall: hay que ver si es por linux o Windows. Distintos tipos, cómo configurarlos.
	- Proxys, arquitectura para monitorear el pase de info de una red. IDS equipo para monitorear el tráfico y salta de una
	  alarma en caso de detectar un corportamiento anómalo. Hony pot: equipos de acceso público para 3eros para que acceden,
	  es como una trampa, para que lo intenten vulnerar.
	- Criptografía: matemática y protocolos que hacen segura la conexión. Formas de configurar las conexiones. Critpgrafía es
	  lo que hace seguro el teletrabajo, token de bancos, etc. Películas: el código enigma, Snowmart.
	- VPNS: Túneles y Redes privadas, cómo desde la casa de uno se puede trabajar como si estuviésemos en el trabajo.

# Seguridad de la información (presentación):
	(Me quedé sin audio durante 4 minutos).
	- Tiró el link por telegram donde salen noticias de seguridad.
	- MOOC son cursos cortos y gratis.
	- Explicó los objetivos que están en la filmina.
		* Activos de la empresa: información (intangible), o routers(físico), en general los activos (hay que definir
		  cuáles son estos). Personas también son activos, como bullrich que le hackearon la cuenta. Lo que se hace es un
		  background-check (se busca la información pública que sea sensible,por lo que se enmascara, se cuida la
		  información de la persona). Porque afecta indirectamente a la empresa.
		* Control de acceso a la red y también el físico (quién monitorea la tarjeta de entrada). El datacenter también
		  tiene que tener un protocolo de seguridad (datacenter es física), no sólo la información.

	- Amenaza de seguridad:
	  	* Físicas: intrusos, personas que ingresan a máquinas de acceso público y conectan un pendrive a la máquina
		  pública del ANSES por ejemplo.
		* Catastrofes naturales: AFIP el único datacenter del mundo que no se apagó durante ese lapseo en el año pasado.
		* Daño informático: que tiene el acceso a la información pero que hace uso malintencionado, aprobar un préstamo
		  por ejemplo.
		* Error humano: es lo que dice el nombre.
		* Intrusiones: acceso de personas que NO están autorizadas.
		* Código malicioso: código malitencionado, para hacer uso indebido de la información.
	- Definción abstracta: sensación que perciben las personas sobre el nivel de protección de ¿su? información. ¿Cómo mejorar
	  la percepción? Política, y
	  	* diferencia entre Política y procedimiento. Política es el qué hacer, son los lineamientos generales para obtener un
		  objetivo. Procedimiento: es cómo hacerlo, los procedimientos, los pasos que llevan al objetivo. Ejemplo: Como en el
		  gobierno, el procedimiento oficial es el boletín oficial.
	- Se deben tomar medidas para aumentar la seguridad y el resguardo de la información.
	- Confidencialidad, disponilbiliada, integridad : La CIA (en inglés)
		* Confidencialidad: que la info sea accesible sólo por la persona que se quiere tener acceder.
		* Disponiblidad: Accesible cuando se quiere acceder a la información. Como cuando se baja el SIU cuando nos
		  anotamos en las materias.
		* Integridad: que la info que estoy viendo sea correcta y no errónea. Cuando
		* Protección a la réplica: el mensaje que se envié que nadie lo reenvíe como haciéndose pasar por uno. X realiza
		  una transaccióna Y, y que Y no pueda replicar eso con W;
		* NO Repudio: si se envia un mensaje que yo pueda validar que la persona que lo envió sea. No repudio es que si
		  vos mandas algo que no puedas negar que fuiste vos, despues.
		* Autencidad: comprobar que lo envió X
		* Control de acceso: limite de acceso
	- Laboratorio no se hace.
	- Escenario: Cada vez es más grande la cantidad de inseguridadaes que van surgiendo en todos los aparatos electrónicos.
	- Examen de lo que se quiere resguardar: no se puede proteger todo,  por lo que se hace un examen, debe haber una
	  prioridad:
	  	* Identificar activos
	  	* Identificar Uvlverabilidadles: qué amenazas existen.
	  	* Identificar de amenazas:
		* Estimación de riestos: qué porcentaje o cómo se verían implicados los activos de la empresa.
	- Vulnerabilidades: Es el error de los límites impuestos por la seguridad.
	- Amenazas: En la filmina
	- Impacto:En la filmina

	- Análisis de riesgos: identificamos los que vamos a protejer, hay que priorizar lo que tengan más valor para el negocio.
	  ¿Contra qué amenazas (corte de luz, terremonos, huracanes, etc)? ¿de quiénes?
	  Cada análisis depende de quién lo analices, de las características del profesional que lo analiza.
	- Política general de seguridad: Control que pide el negocio para todo lo que involucra manejar activos. Es lo que se
	  quiere hacer, no el cómo, sino el qué. Todo el tiempo se tienen que ir monitoreando, es  un proceso continuo, por eso de
	  ISO (normativas que dan una cerificación que se cumplen determinados estándares). Es contínuo porque cambiarn las
	  personas, hay nuevas vulnerabilidades siempre, etc.
	- Gasto de inversión: antes se veía como un gasto, ahora como una inversión. Porque se puede tener un estimado de lo
	  costoso que puede ser que se vulnere un activo. Se vio con el tiepmo que se ahorra mucha más plata haciendo estos
	  controloes de seguridad. Se hace algo preventivo a asumir el riesgo.
	  ISO 27001 es de la seguridad de la información.
	- Aspectos a considerar: En la filmina
	- Documentos - normas:
	  	* Privacidad: expectativas razonables de privacidad.
		* Norma de acceso: Define derechos y privilegios de acceso para resguardar recursos.

	(Se puso a debatir demasiado tiempo y dejé de escribir).

	- Trabajo Práctico (dos semanas para hacerlo).
	  	* Lo que se hace es simular las políticas de Administración de usuario, y plantear una normativa de adminsitrción
		  de usuario para el TP.
