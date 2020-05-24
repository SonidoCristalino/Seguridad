# Clase nº 5: 13/05/2020


Clase 2 : análisis de vulnerabilidades.

Proceso que cuando se comienza en la etapa de análisis, se segurización de un lugar. Se identifica los puntos débiles de la
organización.
Está el reporte cuáles son las incidencias en cada uno de los años, esto es lo que está reportado, por lo que se estima que hay
mucho más de lo que muestran. A muchas empresas no se le hacen un seguimiento delas vulnerabilidades,por lo que no se peude
representar tan de forma fidedigna.

Se hace una clasificación de los activios, uno tiene que decir qué información es importante (el empleado también es un
activo). A partir de esa clasificiación algunos antivirus lo que hacen es clasificar los tipos de archivos pueden circular
mediante niveles, por ejemplo que no salgan de la organización mediante mail o que se publique en otros niveles no
autorizados.

¿Para qué realizar este análisis?
	- Caja negra: se nos provee muy poca información para realizar el análisis para encontrar las vulnerabilidades.
	- Caja blanca: se nos da mucho más información para analizar.
	[Página 9 de una de las diapositivas]

Se hace el análisis para proponer medidas de segurizar. Es una contramedida de lo realizado.
Hay un tecnica comúnc que se denomina Test de penetración, que lo que intenta encontrar son los lugares por los cuales un extraño
peude ingresar a su organización, para alterar datos o causar daño en algúno de los activos.
Se hace un estudio de la red externa , todo sus puntos de contacto hacia internet, se realizan pruebas con todas las herramientas
que están en contacto con internet. Se prueban las debilidades de todas ellas.
	- Denegación de servicio: cuando el servicio colapsa y no puede atender peticiones externas. Se determina un umbral máximo
	  de peticiones que se puedan recibir.
	  Test de estreess: se prueba cuándo es el punto donde comienza a fallar la herramienta.

Cuando se tiene un ataque lo que se tiene que saber es qué hacer cuando se realiza el ataque. Lo que se tiene que sbaer es cómo
hacer para poder accionar, es bloquear esas IP que se generan de forma ___ para realizar el ataque mediante hackers.

Vulnerabilidades de redes: Lo pasa por encima porque es muy teórico.

Herramientas:
	- Escanéo de puertos: nmap lo que hace es buscar todos los equipos que tienen puertos abiertos. Lo que se tiene que hacer
	  es un análisis para saber que ese equipo realmente necesita seguridad. POr ejemplo que tengan puertos abiertos al pedo,
	  estos puertos deben ser cerrados, porqe se abren por defecto cuando se instalan determinados programas.
	  Esto es producto de la mala administración de los equipos, ya que cualquiera instala cualquier progrmaa que abre
	  puertos.

	- nmap: se puede hacer un barrido muy amplio delos servicios activos de la red y los que están publicados hacia afuera.

	- Analizador de protocolo: más profundo y más trabajoso, se necesito mas conocimiento de cada uno de los protocolos.

	- Passworcrackets: es para testear las contraseñas, la idea es que las empresas, sea del tamaño que sea, se tenga una
	  política global de administrador de contraseñas fuertes. Algunas empresas utilizan los que se denomina una doble
	  llave de seguridad.

	- Controladores de dominio: necesitan caracteres especiales, caracteres especiales, etc.
	  También se tiene una política de seguridad que a partir de los 3 o 5 intentos la contraseña se bloquea. Se tiene que
	  cambiar la contraseña cada x cantidad. No se puede repetir las contraseñas del último año.

	- Ingeniería social: esto busca tratar de determinar medianta una técnica (confianza de las personas( para obtener cierta
	  informaciónd e la organización. Muchas veces se mitiga es mucha cacpacitación al personal,permanentemente, lo que se
	  hace es evitar que otro de afuera obtenga información.

	- Trashing: a partir de los residuos se comienza a recopilar la información a partir de la basura. Hay empresas chicas que
	  tiran papeles importantes sin pasar por un picapapeles. Se inspecciona qué es lo que se está tirando la organización, si
	  esta no tiene una picadora de papel, entonces ahí hay una vulnerabilidad. Si no tiene un procedimiento de "escritorio
	  limpio" también se está teniendo una vulnerabilidad. Herramienta muy poderosa para obtener información.

[Se perdió 10 minutos de clase por problemas en zoom]

Está hablando sobre la actividad de laboratorio. La idea es levantar una máquina virtualizada e instalar un cracker de password.
La idea es

	La idea es que modificar el nombre del usuario que viene por defecto.
	Se tienen distintos formatos, la idea es probar el Password Cracker (brutus). Hay que trabajarlo mediante virtualización,
	no sobre la máquina física de uno.

# Organismos de consulta:

Organismos de seguridad a nivel internacional, son de consulta, lo que hacen es clasificar y publicar las probelmáticas sobre la
información que

# Metodología de análisis:
Lo siguiente se puede encontrar en la siguiente clase: [clase2 md](clase2.md)

	- Acuerdo de confidencialidad: es un marco legal,
	- Reglas de juego: se establece cuánto tiempo, a quién se le hace, cuáles son los límites que se deben respetar, etc.
	- Reunir información: se evalúa cada uno de los empleados por medio de redes sociales
	- Test interior: información que se trata de reuniir de forma interna, dentro de la organización
	- Test exterior: información que se trata de reuniir de forma externa, redes sociales, buscar información valiosa por
	  fuera de la organización, que haya sido encontrada por fuera de la organización.

