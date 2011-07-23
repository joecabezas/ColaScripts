Si este archivo se ve mal en Bloc de Notas (Notepad), deja de usarlo y consigue Notepad++
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
						C:\Program Files\Steam\steamapps\<usuario>\team fortress 2\tf\cfg

Instalación

	paso 0 (opcional)
		Respaldar la carpeta <tf>/cfg

	paso 1
		Copiar la carpeta "cfg/" a la carpeta <tf> y reemplazar todo

Changelog

	version 23 07 2011 (2)
		*Se agregaron 2 sets de configs de video para aumentar la calidad y/o los FPS (frames per second)
			*ChrisConfig:	http://www.fakkelbrigade.eu/chris/configs/
			*ColaGraphics:	Creados por usuario "ElChorizo" //http://steamcommunity.com/id/mascool7/

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
