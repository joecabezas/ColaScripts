Si este archivo se ve mal en Bloc de Notas (Notepad), deja de usarlo y consigue "Sublime Text 2"
o ve este documento on-line en: http://github.com/joecabezas/ColaScripts/raw/master/LEEME.txt

====================================================================
ColaScripts README

Autor:	Joe Cabezas <joe.cabezas@gmail.com>
web:	http://github.com/joecabezas/ColaScripts
====================================================================

Descripción

	ColaScripts es un conjunto de scripts que facilita los controles, entre otras ventajas,
	para el juego Team Fortress 2

Glosario

	<usuario>:	Este es el nombre de usuario (SteamID) con el que haces login en Steam

	<tf>:		Carpeta "tf/" del juego, normalmente está ubicada en:
					Windows:
						C:\Program Files\Steam\steamapps\<usuario>\team fortress 2\tf\
					Mac:
						/Users/<usuario>/Library/Application Support/Steam/SteamApps/common/Team Fortress 2/tf/

Instalación

	paso 0 (opcional)
		Respaldar la carpeta <tf>/cfg

	paso 1
		Copiar la carpeta "cfg/" a la carpeta <tf> y reemplazar todo

Opciones de lanzamiento:

	-console -novid -window -w 1920 -h 1080 -noborder -high -autoconfig

	-console:	activa consola
	-novid	:	desactiva video de inicio
	-window	:	activa modo ventana
	-w <n>	:	hace que el juego se abra con un ancho de <n> pixeles
	-h <m>	:	hace que el juego se abra con un alto de <m> pixeles
	-noborder:	hace que en modo ventana, no tenga bordes
	-high	:	aumenta prioridad en el sistema operativo
	-autoconfig:	resetea opciones de video (ideal si ocupas configs de video)

Changelog

	version 27 08 2011
		*TF2_binds:
			*se agregaron opciones nuevas para las net_graph ahora no debieran mostrarse
			encima del contador de munición, y tambien se ve mas pequeño
			
		*engineer.cfg:
			*Se agrego nueva funcion: "QUICK GUNSLINGER SENTRY", bindeada a la tecla "f"
				al presionar y mantener presionada la tecla "f", el engy construirá una sentry
				al soltar la tecla "f", el engy volverá al arma anterior (primaria o secundaria)
		
	version 26 08 2011
		*Mayor Update:
			*Ahora Colascripts es compatible con configuraciones de mouse personalizadas
			
			*Si quieren usar su propia config de mouse, deben crear este archivo config:
				cfg/mouse_configs/mouse.cfg
			
			*Colascripts NO VIENE con un archivo "mouse.cfg", para asi hacer mas facil la actualziacion de colascripts
			de esta manera sus configuraciones de mouse no se pierden al actualizar colascripts
			
			*Sugerencia: Pueden ocupar las plantillas para mouse de 3 y 5 botones que vienen en la carpeta:
				cfg/mouse_configs/
			
			*Para usar una plantilla, simplemente deben elegir la que ams les acomode, modificarla a su gusto y luego
			renombrarla a "mouse.cfg"
			
			*Creditos: GrUnTs por hacer el archivo plantilla "mouse_3_botones.cfg"
			
		*spy.cfg:
			* Ahora el spy tiene el autoreload desactivado por defecto, ya que molesta mucho con el arma
			* el Spy recarga arma con la tecla "r"
	
	version 25 08 2011
		*Arreglado bug detectado por GrUnTs, al desactivar auto reload en el soldier

	version 27 07 2011
		*La update de hoy es para corregir algunos bugs en soldier, engineer, y medic que detectó el usuario "Shark" http://steamcommunity.com/profiles/76561198040769814/
		
		*Corregidos bugs en el "Cola Quick Voice Commands", de soldier, engineer, y medic, y además pyro que no habia
		sido detectado.
		
		*se removio archivo sobrante: "cola_ultra_graphics.cfg", ya que esta duplicado en la carpeta "cola_graphics/"
	
	version 26 07 2011
		*La update de hoy, son cambios sugeridos por usuario "Babilonia.!" http://steamcommunity.com/id/UnrealZero/:
		
		*TF2_binds:
			*Se agregó tecla "n" que viene con el juego para abrir mochila
			*Se agrego un bind nuevo, "TECLA SPECIAL para uso en alguna clases":
				*bind "shift"	"colascripts_special"
		
		*Esta nueva TECLA SPECIAL sera usada por distintas clases para hacer una habilidad especial
		que actualmente estaba siendo activada con la tecla SHIFT.
			Pero ahora, se ha normalizado todo para que sea mas facil usar la tecla SHIFT para otras
		cosas, ya que algunos usuarios preguntaban	como hacer para poder agacharse con la tecla SHIFT,
		haciendo muy dificil editar las scritps para lograr eso.
			Ahora es mas simple, solo deben editar 1 archivo (TF2_binds.cfg) donde dice:
				bind "shift"	"colascripts_special"
		Con eso podran bindear la TECLA SPECIAL a cualquier otra, y usar el SHIFT para cualquier otra cosa,	como agacharse.

		*demoman.cfg:
			*Se elimino habilidad "Turn Charge", estaba comentada de todos modos, ya no es necesaria
		
		*engineer.cfg:
			*adaptacion a TECLA SPECIAL
			*TECLA SPECIAL = activar "construccion rapida"

		*medic.cfg:
			*adaptacion a TECLA SPECIAL
			*TECLA SPECIAL = activar "medic radar"

		*pyro.cfg
			*adaptacion a TECLA SPECIAL
			*TECLA SPECIAL = activar "boton de panico"

		*scout.cfg:
			*adaptacion a TECLA SPECIAL
			*se elimino modo para activar FANJUMP, ahora se hace con la TECLA SPECIAL
			*TECLA SPECIAL = ejecutar un "FANJUMP"

		*soldier.cfg:
			*adaptacion a TECLA SPECIAL
			*nueva distribucion de teclas, para adaptarse a la TECLA SPECIAL:
				*mouse2 = rocket jump
				*TECLA SPECIAL (shift por defecto) = disparo cargado con la "Cow Mangler 5000"

	version 25 07 2011
		*Cambios al Sniper (sniper.cfg) sugerencia de usuario "Babilonia.!" http://steamcommunity.com/id/UnrealZero/:
			*Sensibilidad con zoom cambiada de 50% a 80%
			*Se reestablecion comportamiento normal de la tecla "Q" (weapon switch) para permitir jugar con razorback (escudo)

	version 23 07 2011 (2)
		*Se agregaron 2 sets de configs de video para aumentar la calidad y/o los FPS (frames per second)
			*ChrisConfig:	http://www.fakkelbrigade.eu/chris/configs/
			*ColaGraphics:	Creados por usuario "ElChorizo"
		
		*Agradecimientos a "ElChorizo" por prestarme el arma y despues probar las scripts
			http://steamcommunity.com/id/mascool7/

	version 23 07 2011
		*Se agregó hud_combattext 1 (muestra cantidad de daño hecho sobre el enemigo)

		*Se agregó hitsound (dingaling) tf_dingalingaling 1 (reproduce un sonido al hacer daño)
			*Además se dejo comentado los comandos necesarios para cambiar el pitch (tono)
			pero quedó comentado para que lo modifiquen los usuarios avanzados que lo quieran (cfg/TF2_binds.cfg)

	version 20 07 2011(2)
		*Se arreglo bug de incompatibilidad con rocketjump:
			ahora las teclas son:
				mouse2:			rocketjump
				shift + mouse2:	charged fire (para arma nueva, Cow Mangler 5000)
				
		*Agradecimientos a "GrUnTs" por prestarme el arma y despues probar las scripts
			http://steamcommunity.com/profiles/76561197978410408/

	version 20 07 2011
		*Actualizacion para compatibilidad con la nueva arma de Soldier, "Cow Mangler 5000"
			(http://wiki.teamfortress.com/wiki/Cow_Mangler_5000)

		*Se agrego configuraciones para red, para resolver problemas de lag en algunos servidores

	version 19 07 2011
		*Pequeños cambios en la estructura de TF2 binds, para mouse de 5 botones

		*Actualizado README.txt

		*Se comento toda la seccion de PREC (POV RECORD), el que tenga el plugin que lo descomente si quiere

	version 18 07 2011
		Nueva reestructuracion de botones para el pyro, y nueva habilidad del medic: Medic Radar

		*Pyro:
			mouse3: ahora es Automelee
			shift: Panic Button
		*Medic:
			shift: Medic Radar

			Medic Radar: presionando shift aumenta el porcentaje minimo para auto llamar medic a 150% (maxima salud posible)
			haciendo que todos los aliados cercanos llamen medico automaticamente, permitiendo al medico
			ver donde hay gente cerca para cuando se quede solo.

	version 02 07 2011
		*Engineer: modo por defecto ahora es Switch Mode
		*Demoman: deprecado habilidad de girar con targe
		*Heavy: removido comando para botar sandwich

	version 06 05 2011
		*Se agregaron teclas por defecto para estar al dia con el "Replay Update":
			Nuevas teclas por defecto:
				- F6 = grabar replay
				- H = Item Slot, para usar taunts alternativos o items


	version 24 04 2011
		*MEDIC: Ahora anuncia las uber falsas por chat de equipo

		*MEDIC: Ahora cuando mutea una uber anuncia que la uber esta cargada por chat de equipo

		*pequeños cambios en todos los cfg para que las config sean mas livianas, se hizo mejoras en indentación

	version 23 04 2011
		*Cambio de nombre archivo README.txt, ahora se llama LEEME.txt, planeo hacer una version
		en ingles

		*Actualizado README.txt

		*TF2_binds.txt: acusar SPY con la tecla V, ahora viene desactivado (comentado) )ya que
		sobreescribia el valor por defecto de chat de voz con la misma tecla

	version 10 01 2011
		*Primera version del changelog (aca se escribiran los cambios en cada version)

		*MEDIC: arma por defecto cambiada a slot2 (medicgun)
